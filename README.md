# Peter Winnberg

Hallå hallå 👋, jag heter Peter, jag bor i Piteå och jag fokuserar på två spår. Det ena handlar om kompetensförsörjning och ledarskap. Det kan vara frågor kopplade till rekrytering, kompetensutveckling och mentorskap. Det andra spåret handlar om att hjälpa andra organisationer i roller som t.ex. lösningsarkitekt.

Har en bakgrund som utvecklare 👨‍💻, började utveckla i slutet på 90-talet. Frontend-utveckling (HTML, CSS och Javascript) i webbläsarna Netscape Communicator 4 och Internet Explorer 4 kombinerat med CGI-script skrivna i Perl 🐪. Under åren har också blivit en del PHP 🐘. När det blir att utveckla något nu för tiden så tenderar det alltid att handla om Java ☕.

Här är några av mina favoriter i kategorin programmeringshumor:

* [Vim](https://twitter.com/iamdevloper/status/435555976687923200)
* [Threads](https://twitter.com/davidlohr/status/288786300067270656)
* [goto](https://xkcd.com/292/)
* [Exploits of a Mom](https://xkcd.com/327/)
* [Wat](https://www.destroyallsoftware.com/talks/wat)

Gillar att använda programmeringsuppgifter från t.ex. [Kattis](https://open.kattis.com/) eller [Advent of Code](https://adventofcode.com/) som en grund för att skapa gemenskap och diskussioner runt t.ex. refaktorering och skillnader mellan olika programmeringsspråk. Definitionen på lycka är väl när man lyckats hitta ett bra tillfälle att använda regular expressions som i Java-lösningen på Kattis-uppgiften [SMIL](https://open.kattis.com/problems/smil) nedan:

```java
import java.util.Scanner;
import java.util.regex.Pattern;

public class Smil {
    public static void main(String[] args) {
        try (Scanner in = new Scanner(System.in)) {
            Pattern.compile("[:;]-?\\)")
                    .matcher(in.nextLine())
                    .results()
                    .forEach(r -> System.out.println(r.start()));
        }
    }
}
```

Eller? 😎 Ta gärna kontakt på [LinkedIn](https://www.linkedin.com/in/peterwinnberg/) så diskuterar vi det. Eller varför inte diskutera allt intressant som händer i Java-världen runt t.ex. [Spring Boot](https://spring.io/) och [Quarkus](https://quarkus.io/) och hur det kopplar till container-teknik som [Docker](https://www.docker.com/) och [Kubernetes](https://kubernetes.io/).
