# Narzędzie wspomagające audyt zgodności z normą EN 301 549

Jest to **wczesna wersja narzędzia** mającego pomóc w audycie produktów i usług pod kątem ich zgodności z normą EN 301 549.

Starałem się odwzorować w nim strukturę i testy z aneksu C wspomnianej normy. Mam nadzieję, że się to udało.  
Udostępniam je na licencji Creative Commons, licząc na to, że stanie się zalążkiem czegoś przydatnego.

## Jak korzystać z narzędzia?

### Wersja online

Narzędzie znajdziesz na Github Pages pod tym linkiem:
[Narzędzie wspomagające audytu zgodności z EN 301 549](https://ka-er-zet.github.io/audyt-eaa/)

### Wersja offline

1. Możesz pobrać archiwum .zip z kodem klikając powyżej w "Code", a następnie "Download Zip".
2. Następnie rozpakuj archiwum .zip i wejdź do rozpakowanego folderu.
3. Kliknij otwórz plik `index.html` za pomocą ulubionej przeglądarki.

## Co narzędzie potrafi?

- Można w nim wybrać jedną lub więcej klauzul do wykonania badania.
- Można ocenić zgodność produktu/usługi z założeniami każdego z testów i dodać notatkę.
- Narzędzie podsumowuje wyniki testowania i generuje wynik oparty o prostą punktację:
  - **Test zaliczony:** `1 punkt`
  - **Test niezaliczony:** `-1 punkt`
  - **Nie dotyczy/nie testowalne:** `0 punktów`
- Wyniki badania można wyeksportować do plików w formatach **JSON, ODT i CSV**.
- Narzędzie działa także jako **PWA** (Progressive Web App).

## Co warto mieć na uwadze?

- Jak już wspomniałem – to bardzo wczesna wersja, coś może nie działać jak powinno.
- Tłumaczenie jest tłumaczeniem maszynowym (Gemini 2.5 Pro), więc nie należy go traktować jako oficjalnego.
- Język normy jest jaki jest, czyli delikatnie mówiąc hermetyczny i pewnie warto by nad nim popracować.
- Starałem się weryfikować pracę AI, ale przy tej objętości tekstu i strukturze coś mogło umknąć mojej uwadze – krótko mówiąc, mogą pojawiać się błędy, przeinaczenia w stosunku do treści EN 301 549, dlatego warto konsultować się z pełną treścią normy.

## Co dalej?

Super by było, jakby narzędzie zaczęło żyć, dlatego:

- Jeśli widzisz jakiś błąd, nie bój się do mnie odezwać (kontakt poniżej) albo kontrybuować do tego repozytorium.
- Czegoś Ci brakuje? Jak wyżej...
- Masz pomysł na funkcjonalność? Jak wyżej...

Jak patrzę na szereg opisów testów, dobrze by było zrobić formularze "sprytniejszymi". Np. nie jest spełniony warunek wstępny - niech ustawi się od razu odpowiednia odpowiedź, itd. Chciałbym też umożliwić korzystającym szybki dostęp do opisów klauzul i wymagań, tak by przy prowadzeniu testów nie trzeba było „skakać” pomiędzy narzędziem a treścią normy. To też pewnie będzie wymagało przejścia na inną strukturę całości, tak by łatwiej edytować treści. Wstępny pomysł to statyczna strona oparta np. o **HUGO**.  
Więc jak to mawiają „stay tuned”, bo są przewidywane zmiany.

No i daj znać, jeśli na coś Ci się to przydało!

---

**Kontakt:** [Marcin Krzanicki na LinkedIn](https://www.linkedin.com/in/marcinkrzanicki/)

---

**Licencja:**  
Narzędzie objęte jest licencją [Creative Commons Uznanie autorstwa – Na tych samych warunkach 4.0 Międzynarodowa (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/deed.pl)

---

**Narzędzie**
[Narzędzie wspomagające audytu zgodności z EN 301 549](https://ka-er-zet.github.io/audyt-eaa/)
