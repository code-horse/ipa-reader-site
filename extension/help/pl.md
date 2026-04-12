---
layout: bare
title: Rozszerzenie IPA Reader — Przewodnik użytkownika
lang: pl
---

# IPA Reader — Przewodnik użytkownika

> Wersja: v1.4.3

## Wprowadzenie

IPA Reader to rozszerzenie przeglądarki stworzone dla osób uczących się języka angielskiego. Dodaje adnotacje wymowy IPA (Międzynarodowy Alfabet Fonetyczny) do angielskich słów na stronach internetowych i w plikach PDF, obsługując zarówno akcent amerykański, jak i brytyjski. Zawiera też wbudowany słownik angielski, zamianę tekstu na mowę oraz funkcje tłumaczenia — ułatwiając naukę angielskiej wymowy.

---

## Główne funkcje

- **Tryb IPA na całej stronie** — Dodaj adnotacje IPA do wszystkich angielskich słów na stronie jednym kliknięciem; symbole IPA są kolorowo oznaczone według typu (samogłoski, spółgłoski, akcenty) dla łatwiejszego czytania
- **Słownik po najechaniu** — Najedź na słowo, aby zobaczyć definicje po angielsku (82 tys.+ wyrazów z WordNet), IPA z kolorowymi symbolami i przyciski wymowy; wybierz tryb Słownik, Dymek lub Wyłączone
- **Czytnik PDF** — Wbudowany czytnik PDF z adnotacjami IPA, słownikiem, mową i tłumaczeniem; obsługa przeciągnij i upuść, wczytywanie z adresu URL oraz automatyczne wykrywanie PDF z inteligentnym przekierowaniem
- **Formy słabe/mocne** — Automatyczne wyświetlanie słabych i mocnych wariantów wymowy wyrazów funkcyjnych (np. „the”, „to”, „can”) do opanowania naturalnej mowy
- **Akcent amerykański i brytyjski** — Przełączaj między IPA angielskiego amerykańskiego (en-US) i brytyjskiego (en-GB)
- **Text-to-Speech** — Kliknij przycisk głośnika, aby usłyszeć wymowę dopasowaną do wybranego akcentu
- **Mówienie zaznaczenia z efektem karaoke** — Zaznacz dowolny angielski tekst: pojawi się kompaktowy pasek z przyciskami odczytu i tłumaczenia; mowa jest odtwarzana z podświetlaniem słów w czasie rzeczywistym (efekt karaoke), zsynchronizowanym z dźwiękiem
- **Tłumaczenie zaznaczenia** — Zaznacz dowolny tekst, kliknij przycisk tłumaczenia na pasku — natychmiastowe tłumaczenie przez Bing lub Google Translate w dymku pod paskiem
- **Rozpoznawanie homografów** — Automatyczna identyfikacja wyrazów o wielu wymowach (np. read, live) i wybór właściwej na podstawie kontekstu
- **Skróty klawiszowe** — Szybki dostęp do głównych funkcji dzięki konfigurowalnym skrótom
- **Wielojęzyczny interfejs** — Obsługuje 41 języków interfejsu

---

## Jak używać

### Krok 1: Zainstaluj rozszerzenie

Zainstaluj **IPA Reader** ze [Chrome Web Store](https://chromewebstore.google.com/) lub załaduj je lokalnie w trybie deweloperskim.

### Krok 2: Otwórz dowolną stronę internetową

Odwiedź dowolną stronę internetową z angielską treścią.

### Krok 3: Włącz IPA

Kliknij ikonę rozszerzenia na pasku narzędzi przeglądarki. Włącz „Włącz IPA”, następnie „IPA na całej stronie”, aby adnotować wszystkie słowa na stronie. Możesz też użyć pływającego przycisku w prawym dolnym rogu.

### Krok 4: Wyświetlanie IPA

Najedź kursorem na słowa, aby zobaczyć dymki IPA z kolorowymi symbolami fonetycznymi. Kliknij ikonę głośnika, aby usłyszeć wymowę. Dla słów ze słabymi/mocnymi formami w dymku pokazane są oba warianty.

### Krok 5: Mówienie i tłumaczenie zaznaczonego tekstu

Zaznacz dowolny angielski tekst myszą. Obok zaznaczenia pojawi się kompaktowy pasek z dwoma przyciskami:
- **🔊 Mów** — odtwarza zaznaczony tekst z podświetlaniem słów w stylu karaoke
- **🌐 Tłumacz** — pokazuje dymek z tłumaczeniem pod paskiem

Możesz też kliknąć prawym przyciskiem i wybrać „IPA Reader > Speak Selection” lub „IPA Reader > Translate Selection”.

> **Wskazówka:** Kliknij ikonę rozszerzenia na pasku narzędzi, aby otworzyć ustawienia: typ akcentu, szybkość mowy, tryb po najechaniu, silnik tłumaczenia i więcej.

---

## Tryb IPA na całej stronie

Gdy włączony jest tryb IPA na całej stronie, nad każdym angielskim słowem wyświetlana jest adnotacja IPA w postaci tekstu ruby. Symbole IPA są kolorowo oznaczone:

- **Samogłoski** — na niebiesko
- **Spółgłoski** — na szaro
- **Znaki akcentu** (ˈ ˌ) — na czerwono
- **Znaki długości** (ː) — na fioletowo

Rozszerzenie automatycznie dostosowuje interlinię, aby adnotacje nie nachodziły na tekst, i skaluje rozmiar czcionki IPA w zależności od długości słowa.

---

## Słownik po najechaniu

Rozszerzenie zawiera wbudowany słownik angielski oparty na WordNet (ponad 82 000 wyrazów). W ustawieniach możesz wybrać jeden z trybów po najechaniu:

| Tryb | Zachowanie |
|------|------------|
| **Słownik** | Po najechaniu: IPA + definicja po angielsku + przycisk wymowy |
| **Dymek** | Po najechaniu: IPA + przycisk wymowy (bez definicji) |
| **Wyłączone** | Brak efektu po najechaniu |

W **trybie Słownik** dymek pokazuje:
- Słowo i transkrypcję IPA
- Przycisk wymowy (kliknij, aby odsłuchać)
- Definicje po angielsku z WordNet

> **Wskazówka:** Dane słownika są wczytywane na żądanie, gdy włączony jest tryb Słownik, i zwalniane po przełączeniu na inne tryby — oszczędność pamięci.

---

## Czytnik PDF

IPA Reader zawiera wbudowany czytnik PDF, dzięki któremu czytasz dokumenty z adnotacjami IPA, słownikiem, mową i tłumaczeniem — te same funkcje co na stronach WWW, teraz także dla plików PDF.

### Otwieranie pliku PDF

**Metoda 1: Z wyskakującego okna**  
Kliknij ikonę rozszerzenia, potem „Open PDF Reader”. Przeciągnij i upuść plik PDF lub kliknij „Choose File”, aby otworzyć plik lokalny. Możesz też wkleić adres URL pliku PDF.

**Metoda 2: Menu kontekstowe**  
Kliknij prawym przyciskiem dowolny link `.pdf` na stronie i wybierz „Open PDF with IPA Reader”.

**Metoda 3: Automatyczne wykrywanie**  
Gdy w ustawieniach włączone jest „PDF Smart Detection”, rozszerzenie automatycznie przekierowuje adresy URL kończące się na `.pdf` do wbudowanego czytnika. Gdy PDF zostanie wykryty, ale nie przekierowany (np. w wbudowanej przeglądarce Chrome), zobaczysz powiadomienia i zachętę do otwarcia w IPA Reader.

### Funkcje czytnika PDF

- **Adnotacje IPA** — Wszystkie funkcje IPA działają na tekście PDF, w tym tryb całej strony i dymki po najechaniu
- **Słownik po kliknięciu** — Kliknij dowolne słowo, aby zobaczyć definicję (w PDF zamiast najechania używane jest kliknięcie — wygodniejsze czytanie)
- **Pasek zaznaczenia** — Zaznacz tekst, aby mówić, tłumaczyć lub kopiować
- **Panel boczny** — Spis treści i miniatury stron
- **Wyszukiwanie** — Szukanie tekstu w PDF
- **Motywy** — Ciemny, jasny i sepia do czytania
- **Powiększenie** — Wiele poziomów, m.in. Auto, Dopasuj stronę, Szerokość strony
- **Skróty klawiszowe** — Strzałki do nawigacji, +/- do powiększenia, Ctrl/Cmd+F do wyszukiwania

---

## Formy słabe/mocne

Wiele popularnych wyrazów funkcyjnych ma dwie wymowy:

- **Forma słaba** — zredukowana wymowa w płynnej mowie (np. „the” → /ðə/)
- **Forma mocna** — pełna wymowa przy akcentowaniu lub w izolacji (np. „the” → /ðiː/)

Gdy włączone jest „Pokaż formy słabe/mocne”, po najechaniu na takie słowa w dymku widać oba warianty z etykietami „WEAK” i „STRONG”. Pomaga to zrozumieć zmiany wymowy w naturalnej mowie.

Obejmują m.in.: przedimki (the, a, an), przyimki (to, for, of, from, at, as, than), spójniki (and, or, but), zaimki (you, your, her, him, his, them, us, our, there), czasowniki posiłkowe (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had) i inne.

---

## Mówienie zaznaczenia i karaoke

Funkcja mówienia zaznaczenia pozwala zaznaczyć dowolny angielski tekst i odczytać go na głos jednym kliknięciem — idealnie do nauki wymowy zdań i ćwiczenia czytania.

**Metoda 1: Pasek zaznaczenia**  
Zaznacz angielski tekst myszą. Obok zaznaczenia pojawi się kompaktowy pasek z przyciskiem 🔊 mów i 🌐 tłumacz. Kliknij mów, aby odtworzyć. Podczas czytania każde słowo jest podświetlane w czasie rzeczywistym (efekt karaoke).

**Metoda 2: Menu kontekstowe**  
Po zaznaczeniu angielskiego tekstu kliknij prawym przyciskiem i wybierz „IPA Reader > Speak Selection”.

**Metoda 3: Skrót klawiszowy**  
Zaznacz tekst i naciśnij `Alt+Shift+S` (na Mac: `Ctrl+Shift+S`), aby mówić.

> **Wskazówka:** Podświetlanie karaoke działa najlepiej, gdy przeglądarka obsługuje zdarzenia granic słów TTS. W przeciwnym razie rozszerzenie używa zapasowego mechanizmu czasowego dla płynnego podświetlania.

---

## Tłumaczenie

Zaznacz dowolny tekst na stronie i skorzystaj z tłumaczenia, aby uzyskać natychmiastowy wynik.

**Metoda 1: Pasek zaznaczenia**  
Zaznacz tekst, potem kliknij przycisk 🌐 tłumacz na pasku. Poniżej pojawi się dymek z wynikiem i przyciskiem kopiowania.

**Metoda 2: Menu kontekstowe**  
Zaznacz tekst, kliknij prawym przyciskiem i wybierz „IPA Reader > Translate Selection”.

**Metoda 3: Skrót klawiszowy**  
Zaznacz tekst i naciśnij `Alt+Shift+T` (na Mac: `Ctrl+Shift+T`), aby przetłumaczyć.

**Silniki tłumaczenia:**
- **Bing Translate** (domyślnie) — Microsoft Translator
- **Google Translate** — Google

Oba silniki obsługują **108 języków docelowych**.

Silnik i język docelowy można zmienić w ustawieniach rozszerzenia. Język docelowy jest domyślnie wykrywany z języka przeglądarki.

> **Wskazówka:** Kliknij poza paskiem lub dymkiem, aby je zamknąć.

---

## Skróty klawiszowe

| Skrót | Mac | Działanie |
|-------|-----|-----------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Włącz/wyłącz adnotacje IPA |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Mów zaznaczony tekst |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Tłumacz zaznaczony tekst |

> **Wskazówka:** Skróty można dostosować w Chrome pod adresem `chrome://extensions/shortcuts`.

---

## Przewodnik ustawień

| Ustawienie | Opis |
|---------|-------------|
| **Włącz IPA** | Główny przełącznik do włączania lub wyłączania funkcji adnotacji IPA |
| **IPA na całej stronie** | Po włączeniu wyświetla kolorowe IPA dla wszystkich angielskich słów nad tekstem |
| **Styl IPA** | Wybór między amerykańskim i brytyjskim angielskim IPA oraz wymową |
| **Tryb po najechaniu** | Zachowanie po najechaniu: Słownik (IPA + definicje + audio), Dymek (IPA + audio) lub Wyłączone |
| **Pokaż formy słabe/mocne** | Słabe i mocne warianty wymowy wyrazów funkcyjnych |
| **Szybkość mówienia zdań** | Szybkość odczytu zdań (pojedyncze słowa bez zmian) |
| **Silnik tłumaczenia** | Wybór między Bing Translate a Google Translate |
| **Język docelowy** | Język tłumaczenia (domyślnie wykrywany z języka przeglądarki) |
| **PDF Smart Detection** | Po włączeniu automatycznie przekierowuje adresy PDF do wbudowanego czytnika i pokazuje powiadomienia przy wykrytych plikach PDF |

---

## FAQ

**P: Dlaczego nie działa na niektórych stronach?**  
O: Ze względów bezpieczeństwa rozszerzenia przeglądarki nie mogą działać na specjalnych stronach, takich jak `chrome://`, ustawienia przeglądarki lub Chrome Web Store.

**P: Co zrobić, jeśli brakuje IPA dla niektórych słów?**  
O: Słownik IPA obejmuje ponad 134 000 słów w amerykańskim angielskim i ponad 67 000 w brytyjskim. Dla słów spoza słownika rozszerzenie generuje przybliżone IPA przez lematyzację i G2P oparte na regułach; w dymku oznaczone to jest ≈ lub ~.

**P: Brak dźwięku z text-to-speech?**  
O: Sprawdź głośność systemu i pakiety głosowe angielskie. Obsługa mowy różni się w zależności od przeglądarki i systemu.

**P: Tryb całej strony wpływa na układ?**  
O: Adnotacje IPA wymagają dodatkowego miejsca. Rozszerzenie dostosowuje interlinię, aby ograniczyć wpływ. Jeśli nadal przeszkadza, wyłącz tryb całej strony i używaj dymków po najechaniu.

**P: Co oznaczają symbole ~ i ≈ w dymkach?**  
O: ~ oznacza IPA wygenerowane regułami (G2P), a nie ze słownika. ≈ — że IPA pochodzi z pokrewnego wyrazu podstawowego przez lematyzację. Mogą być mniej dokładne niż wpisy słownikowe.

**P: Tłumaczenie nie działa?**  
O: Tłumaczenie wymaga połączenia z internetem. Jeśli Bing Translate nie odpowiada, spróbuj przełączyć na Google Translate w ustawieniach. W niektórych sieciach dostęp do usług tłumaczenia może być zablokowany.

**P: Jak otworzyć PDF w IPA Reader?**  
O: Możesz na kilka sposobów: kliknij „Open PDF Reader” w wyskakującym oknie, kliknij prawym przyciskiem link do PDF i wybierz „Open PDF with IPA Reader”, albo włącz „PDF Smart Detection” w ustawieniach, aby adresy PDF były automatycznie przekierowywane do wbudowanego czytnika.

**P: Włączone jest PDF Smart Detection, ale część PDF-ów się nie przekierowuje?**  
O: Automatyczne przekierowanie działa dla adresów URL kończących się na `.pdf`. Dla plików PDF serwowanych bez rozszerzenia `.pdf` lub otwieranych w wbudowanej przeglądarce Chrome pojawi się powiadomienie i znacznik zachęcający do otwarcia w IPA Reader.

**P: Czy słownik działa offline?**  
O: Tak. Słownik WordNet (ponad 82 000 wyrazów) jest w całości dołączony do rozszerzenia. Wszystkie wyszukiwania odbywają się lokalnie, bez połączenia sieciowego.

---

## Powiązane linki

- [Privacy Policy](../privacy-policy)
- [Support & Feedback](../support)

---
