# POLITYKA PRYWATNOŚCI I WARUNKI KORZYSTANIA
## ArinBot - Bot Discord
**Data wejścia w życie:** 01.01.2026  
**Wersja:** 2.0  
**Ostatnia aktualizacja:** 30.12.2025

---

## SPIS TREŚCI

### 1. POLITYKA PRYWATNOŚCI
- 1.1 Informacje wstępne
- 1.2 Jakie dane gromadzimy
- 1.3 Cel przetwarzania danych
- 1.4 Podstawa prawna
- 1.5 Jak długo przechowujemy dane
- 1.6 Udostępnianie danych
- 1.7 Zabezpieczenie danych
- 1.8 Prawa użytkownika (RODO)
- 1.9 Machine Learning i Automatyczne Decyzje
- 1.10 Międzynarodowe transfery danych

### 2. WARUNKI KORZYSTANIA
- 2.1 Ogólne warunki
- 2.2 Konto użytkownika
- 2.3 Zakazane działania
- 2.4 Odpowiedzialność użytkownika
- 2.5 Odpowiedzialność właściciela bota
- 2.6 Zmiany warunków
- 2.7 Wygaśnięcie dostępu
- 2.8 Postanowienia końcowe

### 3. DODATKOWE KLAUZULE
- 3.1 Ochrona przed atakami i spam
- 3.2 Moderacja treści
- 3.3 Zgodność z Discord Terms of Service
- 3.4 Machine Learning i Automatyczne Decyzje
- 3.5 System Punktów i Ekonomia
- 3.6 System Partnerstw i Auto-Matching
- 3.7 Monitoring Botów (SafeCheck)

---

# 1. POLITYKA PRYWATNOŚCI

## 1.1 Informacje wstępne

Niniejsza Polityka Prywatności określa, w jaki sposób ArinBot ("Bot", "my", "nasz/nasza") zbiera, przetwarza, przechowuje i chroni dane osobowe użytkowników ("użytkownik", "ty", "twój/twoja") za pośrednictwem platformy Discord.

**Administrator danych osobowych:**  
Właściciel ArinBot  
Kontakt: jangcy_ / strefareklamdiscord@gmail.com
Serwer wsparcia: https://discord.gg/vXR3TrM5V2

Użytkownik ma prawo do informacji o sposobie przetwarzania jego danych osobowych zgodnie z Rozporządzeniem Parlamentu Europejskiego i Rady (UE) 2016/679 z dnia 27 kwietnia 2016 r. (RODO).

## 1.2 Jakie dane gromadzimy

Bot zbiera i przetwarza następujące kategorie danych:

### A. Dane identyfikacyjne
- **ID Discord użytkownika** (unikalny identyfikator)
- **Nazwa użytkownika** (username, display name)
- **Awatar użytkownika** (URL zdjęcia profilowego)
- **ID serwera** (guild ID)
- **Nazwa serwera**
- **ID kanału** i nazwy kanałów

### B. Dane interakcji i komunikacji
- **Historia komend** wykonywanych przez użytkownika (komendy slash `/`)
- **Znaczniki czasowe** wszystkich działań
- **Zawartość wiadomości** (przetwarzana do celów opisanych w pkt. 1.3):
  - Tekst wiadomości (do analizy raidów, moderacji, naliczania punktów)
  - Linki w wiadomościach (detekcja phishingu)
  - Długość wiadomości (do systemu punktów)
  - Częstotliwość wysyłania wiadomości (detekcja spamu)
  - Podobieństwo wiadomości (machine learning raid detection)
- **Reakcje** na wiadomości (emoji)
- **Głosy** w systemie sugestii (upvote/downvote)

### C. Dane konfiguracyjne serwera
- **Ustawienia systemu powitalnego:**
  - Kanał powitalny
  - Rola powitalna
  - Wiadomości powitalne i pożegnalne (niestandardowe)
- **Ustawienia weryfikacji:**
  - Typ weryfikacji (matematyczna/CAPTCHA/przycisk)
  - Kanał weryfikacji
  - Rola zweryfikowana/niezweryfikowana
  - Dostępne kanały dla niezweryfikowanych
- **Ustawienia ticketów:**
  - Kategorie ticketów (Pomoc, Rekrutacja, Bug Report, etc.)
  - Kanał panelu ticketów
  - Kategoria dla ticketów
  - Kanał logów ticketów
- **Ustawienia logów:**
  - Kanały dla różnych typów logów
  - Włączone/wyłączone typy logów
- **Ustawienia newsów:**
  - Kanał newsów
  - Status subskrypcji
- **Ustawienia partnerstw:**
  - Tagi serwera (3 wybrane kategorie)
  - Kanał partnerstw
  - Tekst reklamowy serwera
  - Status auto-matchingu (włączony/wyłączony)
  - Akceptowalne kanały dla partnerstw
- **Zaufani użytkownicy (trusted users):**
  - Lista użytkowników z immunitetem przed raid detection
- **Ignorowane kanały:**
  - Kanały wyłączone z moderacji automatycznej
- **Filtr słów:**
  - Niestandardowe filtrowane słowa/frazy

### D. Dane moderacji i bezpieczeństwa
- **Logi działań moderacyjnych:**
  - Ostrzeżenia
  - Wyciszenia (mute)
  - Wyrzucenia (kick)
  - Bany
  - Powody działań moderacyjnych
- **Raid Detection Logs:**
  - Wykryte raidy (raid_nr)
  - Lista raiderów (user_id, detected_at)
  - Wyniki detekcji Stage 1 (Global Scan) - JSON
  - Wyniki detekcji Stage 2 (Precise Analysis) - JSON
  - Confidence Score (0-100%)
  - Znaczniki czasowe detekcji
  - Decyzje właściciela serwera (ban/kick/unmute)
- **Auto-Mute Records:**
  - Automatyczne wyciszenia (48 godzin)
  - Czas rozpoczęcia i zakończenia mute
  - Powód (raid detection)
- **Auto-Delete Logs:**
  - Usunięte wiadomości raiderów
  - Liczba usuniętych wiadomości
  - Znaczniki czasowe
- **Raid Cooldowns:**
  - Ostatnia detekcja raidu (timestamp)
  - Status cooldownu (3.5 minuty między detekcjami)
- **Filter Violations:**
  - Naruszone słowa/frazy
  - Liczba naruszeń
- **Bot Trust Data (SafeCheck):**
  - Lista trusted/untrusted botów
  - Monitoring dołączania botów
  - Analiza uprawnień botów

### E. Dane ekonomiczne (System Punktów ARIN_POINTS)
- **Saldo punktów** użytkownika
- **Total earned** (łączna suma zarobionych punktów)
- **Ostatnia aktywność zarobkowa** (timestamp)
- **Historia transakcji punktowych:**
  - Typ transakcji (earn/spend/admin_add/admin_remove)
  - Kwota transakcji
  - Powód transakcji
  - ID serwera
  - Znacznik czasowy
- **Daily Limits Tracking:**
  - Punkty zarobione dzisiaj
  - Ostatnie resetowanie limitu
- **Zakupy w sklepie profilowym:**
  - Zakupione przedmioty
  - Karty profilowe
  - Cena zakupu
  - Data zakupu
- **Posiadane przedmioty:**
  - Aktywna karta profilowa
  - Kolekcja przedmiotów

### F. Dane partnerstw i matchingu
- **Tagi serwera** (3 wybrane kategorie opisujące serwer)
- **Partnership History:**
  - Z kim nawiązano partnerstwo
  - Kiedy (timestamp)
  - Match Score (0-100 punktów kompatybilności)
  - Status (success/failed)
  - Typ (manual/auto-matching)
- **Tekst reklamowy** serwera (do 1000 znaków)
- **Kanał partnerstw** (gdzie wysyłane są reklamy)
- **Akceptowalne kanały** (gdzie bot może wysyłać)
- **Liczba członków** serwera (do matchingu)
- **Match Compatibility Data:**
  - Scores dla różnych aspektów (tags, members, activity)
  - Final match score
  - Powody odrzucenia matchów

### G. Dane ticketów i wsparcia
- **Otwarte tickety:**
  - ID ticketu
  - Właściciel (user_id)
  - Kategoria
  - Status (open/closed)
  - Czas utworzenia i zamknięcia
- **Transkrypcje ticketów:**
  - Pełna treść konwersacji
  - Wiadomości wszystkich uczestników
  - Załączniki (linki, metadane)
  - Przechowywane przez 60 dni po zamknięciu
- **Ticket Logs:**
  - Kto utworzył/zamknął ticket
  - Powód zamknięcia
  - Uczestniczący moderatorzy

### H. Dane weryfikacji
- **Status weryfikacji** (zweryfikowany/niezweryfikowany)
- **Typ wykonanej weryfikacji** (math/captcha/button)
- **Timestamp weryfikacji**
- **Liczba prób** weryfikacji (failed attempts)

### I. Dane sugestii użytkowników
- **Treść sugestii**
- **Autor sugestii** (user_id)
- **Liczba głosów** (upvotes/downvotes)
- **Status sugestii** (pending/accepted/rejected)
- **Komentarz administracji**
- **Timestamp utworzenia i aktualizacji**

### J. Dane analityczne i statystyczne
- **Server Activity Stats:**
  - Liczba aktywnych użytkowników
  - Wzrost/spadek liczby członków
  - Aktywność w czasie
- **Bot Performance Metrics:**
  - Czas działania (uptime)
  - Liczba przetworzonych komend
  - Opóźnienie (latency)
- **Activity Calculator Data:**
  - Ranking aktywności użytkowników
  - Punktacja aktywności serwera

### K. Dane techniczne
- **Adresy IP** (pośrednio poprzez serwery Discord)
- **Informacje o urządzeniu** (pośrednio poprzez Discord API)
- **Metadane działań:**
  - User agent (poprzez Discord)
  - Lokalizacja czasowa (timezone)
  - Język interfejsu

### L. Dane Machine Learning
- **Confidence Scores** (0-100%) dla detekcji raidów
- **Feature Vectors** (wektory cech wiadomości):
  - Link presence score
  - Banned phrase score
  - Message similarity score
- **Training Data** (zanonimizowane dane historyczne do uczenia modeli)
- **Detection Metadata:**
  - Stage 1 Global Scan results
  - Stage 2 Precise Analysis results
  - False positive/negative rates

## 1.3 Cel przetwarzania danych

Dane są przetwarzane w następujących celach:

### A. Świadczenie podstawowych usług
- Funkcjonowanie Bota i jego komend
- Komunikacja z użytkownikami
- Personalizacja doświadczenia

### B. Systemy moderacji i bezpieczeństwa
- **Automatyczne przyznawanie ról** powitalnych nowym członkom
- **Weryfikacja tożsamości** użytkowników (anti-bot, anti-raid)
- **Zarządzanie systemem ticketów** i wsparcia technicznego
- **Prowadzenie logów aktywności** na serwerze
- **Moderacja treści** (filter słów, spam detection)

### C. Ochrona przed atakami (Raid Protection)
- **Automatyczna detekcja raidów** z użyciem Machine Learning
- **Analiza podobieństwa wiadomości** (spam detection)
- **Wykrywanie phishingu** i złośliwych linków
- **Scoring system** do oceny zagrożeń (0-100% confidence)
- **Automatyczne podejmowanie decyzji:**
  - Auto-mute raiderów (48 godzin)
  - Auto-delete wiadomości raiderów
  - Powiadomienia właściciela serwera
- **Trenowanie modeli** Machine Learning na danych historycznych
- **Zapobieganie fałszywym pozytywom** (trusted users, immunitet)

### D. System ekonomiczny (ARIN_POINTS)
- **Naliczanie punktów** za aktywność użytkowników
- **Zarządzanie systemem nagród** i rankingów
- **Tracking daily limits** (50 punktów/dzień)
- **Obsługa sklepu profilowego** (zakupy, przedmioty, karty)
- **Historia transakcji** i audyt

### E. System partnerstw (AutoPartnership)
- **Automatyczne dopasowywanie serwerów** partnerstw
- **Analiza kompatybilności** na podstawie:
  - Tagów serwera (3 kategorie)
  - Liczby członków
  - Aktywności serwera
- **Scoring algorithm** (0-100 punktów matchingu)
- **Automatyczne wysyłanie** wiadomości partnerstw
- **Tracking historii** matchingów (success/failure)
- **Optymalizacja matchingu** na podstawie danych historycznych

### F. Monitoring botów (SafeCheck)
- **Ochrona przed złośliwymi botami**
- **Monitoring dołączania** nowych botów
- **Analiza uprawnień** botów na serwerze
- **Trust levels** (trusted/untrusted bots)
- **Automatyczne ostrzeżenia** o podejrzanych botach

### G. Komunikacja i powiadomienia
- System newsów i ogłoszeń
- System sugestii społeczności
- Powiadomienia o ważnych wydarzeniach

### H. Analiza i optymalizacja
- **Poprawa wydajności i stabilności** Bota
- **Statystyki użycia** funkcji
- **Wykrywanie i naprawa błędów**
- **Optymalizacja algorytmów** ML

### I. Zgodność prawna
- **Zapobieganie oszustwom i nadużyciom**
- **Zgodność z wymogami prawnymi** (RODO, Discord ToS)
- **Audyt bezpieczeństwa**
- **Postępowania prawne** (jeśli wymagane)

## 1.4 Podstawa prawna

Przetwarzanie danych osobowych odbywa się na podstawie:

**Art. 6 ust. 1 lit. a RODO** - Zgoda użytkownika
- Dodanie bota do serwera oznacza zgodę na przetwarzanie danych
- Korzystanie z komend bota oznacza zgodę na przetwarzanie

**Art. 6 ust. 1 lit. b RODO** - Wykonanie umowy
- Niezbędność do świadczenia usług bota
- Warunki korzystania stanowią umowę między użytkownikiem a właścicielem

**Art. 6 ust. 1 lit. c RODO** - Obowiązek prawny
- Zgodność z Discord Terms of Service
- Zgodność z przepisami prawa polskiego i UE

**Art. 6 ust. 1 lit. f RODO** - Uzasadniony interes administratora
- Bezpieczeństwo serwera (raid protection, spam detection)
- Zapobieganie oszustwom
- Poprawa jakości usług

**Art. 22 RODO** - Automatyczne podejmowanie decyzji
- Użytkownik ma prawo nie podlegać decyzjom opartym wyłącznie na zautomatyzowanym przetwarzaniu (ML)
- Bot stosuje automatyczne decyzje (auto-mute, auto-delete) w celach bezpieczeństwa
- Użytkownik może odwołać się od automatycznych decyzji (trusted users, kontakt z ownerem)

## 1.5 Jak długo przechowujemy dane

Okres przechowywania danych jest zróżnicowany w zależności od typu:

| Typ danych | Okres przechowywania | Uwagi |
|------------|---------------------|-------|
| **Dane konfiguracyjne serwera** | Dopóki bot jest na serwerze + 30 dni | Po usunięciu bota dane są archiwizowane przez 30 dni |
| **Dane identyfikacyjne** | Dopóki użytkownik korzysta z bota | ID, nazwa, awatar |
| **Historia komend** | 30 dni | Rolling window |
| **Zawartość wiadomości** | Przetwarzane w czasie rzeczywistym, nie przechowywane | Wyjątek: raid detection logs (90 dni) |
| **Logi moderacji** | 90 dni | Ostrzeżenia, bany, kicki, mutes |
| **Raid Detection Logs** | 90 dni | Stage1, Stage2, confidence scores |
| **Raiders Database** | 90 dni | Lista wykrytych raiderów |
| **Auto-Mute Records** | 48h (aktywne) + 30 dni (archiwum) | Aktywne mute 48h, potem log 30 dni |
| **Auto-Delete Logs** | 90 dni | Logi usuniętych wiadomości |
| **Raid Cooldowns** | 3.5 minuty | W pamięci, nie w bazie |
| **Punkty użytkownika** | Dopóki użytkownik używa bota | Points, total_earned, saldo |
| **Historia transakcji punktów** | 180 dni | user_points_history |
| **Zakupy w sklepie** | Permanentnie | Zakupione przedmioty pozostają |
| **Partnership History** | 365 dni | Historia matchingów |
| **Match Scores** | 90 dni | Compatibility data |
| **Bot Trust Data** | Dopóki bot jest na serwerze | Trusted/untrusted bots list |
| **Filter Violations** | 60 dni | Naruszone słowa |
| **Tickety - otwarte** | Dopóki nie są zamknięte | Aktywne tickety |
| **Transkrypcje ticketów** | 60 dni po zamknięciu | Pełna treść konwersacji |
| **Ticket Logs** | 90 dni | Kto utworzył/zamknął |
| **Dane weryfikacji** | Dopóki użytkownik jest członkiem serwera | Status verified |
| **Sugestie użytkowników** | 365 dni | Głosy, statusy, komentarze |
| **Server Activity Stats** | 90 dni | Rolling analytics |
| **Bot Performance Metrics** | 30 dni | Uptime, latency, commands |
| **ML Training Data** | Zanonimizowane - permanentnie | Do uczenia modeli |
| **News Settings** | Dopóki bot jest na serwerze | Subskrypcje newsów |
| **Logs Settings** | Dopóki bot jest na serwerze | Konfiguracja logów |

**Po upływie okresu przechowywania:**
- Dane są automatycznie usuwane z bazy danych
- Dane zanonimizowane do celów ML mogą być zachowane permanentnie
- Użytkownik może zażądać wcześniejszego usunięcia (patrz: Prawa użytkownika)

## 1.6 Udostępnianie danych

Bot **NIE udostępnia** danych osobowych stronom trzecim, z wyjątkiem:

### A. Usługi niezbędne do działania
- **Discord Inc.** - Wszystkie dane są przetwarzane przez Discord API
- **Supabase** - Baza danych w chmurze (Frankfurt, Niemcy, EU)
  - Dane przechowywane w regionie EU (zgodność z RODO)
  - Szyfrowanie end-to-end
  - Dostęp tylko dla autoryzowanych administratorów
- **Hetzner Cloud** - Hosting VPS (Falkenstein, Niemcy, EU)
  - Serwer fizycznie w Unii Europejskiej
  - Zgodność z RODO i prawem UE

### B. Machine Learning i AI
- **Modele ML są trenowane lokalnie** na serwerze bota
- Dane do trenowania są **zanonimizowane** (usunięte user_id)
- **Brak udostępniania** danych do zewnętrznych usług AI/ML
- Modele działają **on-premise** (na własnej infrastrukturze)

### C. Wymagania prawne
- **Organy ścigania** - gdy jest to wymagane przez prawo
- **Postępowania sądowe** - na mocy wyroku sądu
- **Ochrona praw** - obrona przed roszczeniami prawnymi

### D. Zgoda użytkownika
- Dane mogą być udostępnione za **wyraźną zgodą** użytkownika
- Np. eksport danych na życzenie użytkownika

### E. Administratorzy serwerów Discord
- **Właściciele serwerów** mają dostęp do:
  - Logów moderacji na swoim serwerze
  - Ustawień konfiguracyjnych
  - Raid detection alerts
  - Ticket logs
- Administratorzy **NIE mają dostępu** do:
  - Danych z innych serwerów
  - Globalnych statystyk użytkownika
  - Danych punktów ARIN (cross-server)

**WAŻNE:** Dane nigdy nie są sprzedawane ani udostępniane do celów marketingowych.

## 1.7 Zabezpieczenie danych

Stosujemy profesjonalne środki bezpieczeństwa zgodnie z RODO:

### A. Zabezpieczenia techniczne
- ✅ **Szyfrowanie podczas transmisji:** HTTPS/TLS 1.3
- ✅ **Szyfrowanie bazy danych:** AES-256
- ✅ **Bezpieczne hasła:** Argon2id hashing
- ✅ **Firewall:** Ochrona na poziomie serwera
- ✅ **Rate limiting:** Ochrona przed DDoS i brute-force
- ✅ **Token security:** Discord bot token w zmiennych środowiskowych
- ✅ **API keys:** Zabezpieczone w secrets management

### B. Zabezpieczenia organizacyjne
- ✅ **Kontrola dostępu:** Tylko autoryzowani administratorzy
- ✅ **Audyt logów:** Monitoring dostępu do danych
- ✅ **Backup system:** Regularne kopie zapasowe (daily)
- ✅ **Disaster recovery:** Plan odzyskiwania danych
- ✅ **Security updates:** Regularne aktualizacje systemu
- ✅ **Minimalizacja danych:** Zbieramy tylko niezbędne dane

### C. Monitoring bezpieczeństwa
- 🔍 **Logi bezpieczeństwa:** Monitoring prób nieautoryzowanego dostępu
- 🔍 **Intrusion detection:** Wykrywanie podejrzanej aktywności
- 🔍 **Vulnerability scanning:** Regularne skanowanie bezpieczeństwa
- 🔍 **Incident response:** Plan reagowania na incydenty

### D. Polityki i procedury
- 📋 **Privacy by design:** Bezpieczeństwo od projektu
- 📋 **Data retention policy:** Automatyczne usuwanie starych danych
- 📋 **Access control policy:** Kto ma dostęp do jakich danych
- 📋 **Breach notification:** Procedura powiadamiania o wyciekach

**⚠️ UWAGA:** Mimo naszych starań, żadne metody transmisji przez Internet nie są w 100% bezpieczne. Nie możemy zagwarantować absolutnego bezpieczeństwa danych.

## 1.8 Prawa użytkownika (RODO)

Zgodnie z RODO, każdy użytkownik ma następujące prawa:

### 🔍 Prawo dostępu (Art. 15 RODO)
- Prawo do informacji, jakie dane są przetwarzane
- Prawo do kopii swoich danych
- **Jak skorzystać:** Komenda `/moje-dane` lub kontakt z administratorem

### ✏️ Prawo do sprostowania (Art. 16 RODO)
- Prawo do poprawy nieprawidłowych danych
- Prawo do uzupełnienia niekompletnych danych
- **Jak skorzystać:** Kontakt z administratorem + weryfikacja tożsamości

### 🗑️ Prawo do usunięcia "prawo do bycia zapomnianym" (Art. 17 RODO)
- Prawo do usunięcia danych osobowych
- **Wyjątki (dane mogą być zachowane):**
  - Logi moderacji (bezpieczeństwo serwera) - 90 dni
  - Raid detection logs (ochrona społeczności) - 90 dni
  - Dane wymagane przez prawo
- **Jak skorzystać:** Komenda `/usuń-dane` lub kontakt z administratorem

### 🔒 Prawo do ograniczenia przetwarzania (Art. 18 RODO)
- Prawo do wstrzymania przetwarzania danych
- Dane są przechowywane, ale nie przetwarzane
- **Jak skorzystać:** Kontakt z administratorem

### 📦 Prawo do przenoszenia danych (Art. 20 RODO)
- Prawo do otrzymania danych w formacie JSON
- Prawo do przesłania danych innemu administratorowi
- **Jak skorzystać:** Komenda `/eksport-danych`

### ⛔ Prawo do sprzeciwu (Art. 21 RODO)
- Prawo do sprzeciwu wobec przetwarzania
- Dotyczy przetwarzania na podstawie uzasadnionego interesu
- **Konsekwencje:** Bot może przestać działać poprawnie
- **Jak skorzystać:** Kontakt z administratorem

### 🔄 Prawo do wycofania zgody (Art. 7 RODO)
- Prawo do wycofania zgody w dowolnym momencie
- Nie wpływa na legalność przetwarzania przed wycofaniem
- **Jak skorzystać:** Usunięcie bota z serwera

### 🤖 Prawo do niepodlegania automatycznym decyzjom (Art. 22 RODO)
- Prawo do odwołania się od decyzji AI/ML
- Dotyczy: auto-mute, auto-delete, raid detection
- **Opcje odwołania:**
  - Dodanie do **trusted users** (immunitet)
  - Ręczne unmute przez właściciela serwera
  - Przegląd detection logs (confidence score, powody)
- **Jak skorzystać:** Kontakt z właścicielem serwera

### 📝 Prawo do skargi (Art. 77 RODO)
- Prawo do złożenia skargi do organu nadzorczego
- **Polska:** Urząd Ochrony Danych Osobowych (UODO)
- **Adres:** ul. Stawki 2, 00-193 Warszawa
- **Website:** https://uodo.gov.pl

**Czas odpowiedzi:** Odpowiadamy na żądania w ciągu **30 dni** od otrzymania.

**Weryfikacja tożsamości:** Możemy poprosić o weryfikację tożsamości przed realizacją żądań (ochrona przed oszustwami).

## 1.9 Machine Learning i Automatyczne Decyzje

### A. Jak działa nasz system ML

Bot wykorzystuje **Machine Learning** do automatycznej detekcji raidów i ochrony serwerów.

**Model detekcji składa się z dwóch etapów:**

**🔍 Stage 1: Global Scan (Szybkie skanowanie)**
- Analiza wszystkich wiadomości z ostatnich 2 minut
- Wykrywanie linków (link_score)
- Wykrywanie zakazanych fraz (phrase_score)
- Analiza podobieństwa wiadomości (similarity_score)
- **Próg globalny:** 30-40% (konfigurowalne)

**🎯 Stage 2: Precise Analysis (Precyzyjna analiza)**
- Głębsza analiza podejrzanych użytkowników ze Stage 1
- Filtrowanie false positives
- Uwzględnienie trusted users (immunitet)
- **Final Confidence Score:** 0-100%
- **Próg akcji:** 40%+ (konfigurowalne)

### B. Automatyczne akcje podejmowane przez AI

Gdy **confidence score ≥ 40%**, bot automatycznie:

1. **Auto-Mute (48 godzin):**
   - Wycisza wykrytych raiderów na 48h
   - Można ręcznie odmutować (właściciel serwera)
   - Trusted users są ZAWSZE pomijani

2. **Auto-Delete:**
   - Usuwa wiadomości wykrytych raiderów
   - Limit: wiadomości z ostatnich 5 minut
   - Zapisuje logi (co zostało usunięte)

3. **Alert dla właściciela:**
   - Powiadomienie DM do właściciela serwera
   - Informacje o wykrytym raidzie
   - Przyciski do dodatkowych akcji (Ban/Kick/Unmute)

### C. Dokładność systemu

- **Claimed accuracy:** 98.2% (marketing claim - nie zweryfikowane naukowo)
- **False positive rate:** < 2% (szacunkowo)
- **False negative rate:** Nieznany (brak kompletnych danych testowych)

**⚠️ WAŻNE:** System ML **nie jest doskonały** i może popełniać błędy. Dlatego oferujemy mechanizmy odwołania.

### D. Dane używane do uczenia modeli

- **Training data:** Zanonimizowane dane historyczne z raidów
- **Features:** Link presence, banned phrases, message similarity
- **Brak danych osobowych:** User ID są usuwane przed trenowaniem
- **Aktualizacja modeli:** Co 3-6 miesięcy (ręcznie)

### E. Twoje prawa wobec automatycznych decyzji

✅ **Możesz:**
- Poprosić o dodanie do **trusted users** (immunitet przed ML)
- Przejrzeć **detection logs** (powody, confidence score)
- Odmutować siebie poprzez właściciela serwera
- Wyłączyć raid detection dla swojego serwera (właściciel)

❌ **Nie możesz:**
- Zmienić parametrów modelu ML
- Usunąć swoich danych z training data (zanonimizowane)
- Zablokować przetwarzania danych do raid detection (podstawa prawna: bezpieczeństwo)

### F. Transparentność i odpowiedzialność

- 📊 **Detection logs są zapisywane** (90 dni) - możesz je przejrzeć
- 🔍 **Confidence score jest jawny** - wiesz dlaczego zostałeś uznany za raidera
- ⚖️ **Możliwość odwołania** - trusted users, kontakt z ownerem
- 🛡️ **Ochrona przed false positives** - trusted users są ZAWSZE bezpieczni

## 1.10 Międzynarodowe transfery danych

### A. Lokalizacja danych

**Wszystkie dane są przechowywane w Unii Europejskiej:**
- 🇩🇪 **Supabase Frankfurt** (baza danych) - Niemcy
- 🇩🇪 **Hetzner Falkenstein** (VPS hosting) - Niemcy
- 🇺🇸 **Discord Inc.** (API, pośrednio) - USA z Standard Contractual Clauses (SCC)

### B. Zgodność z RODO

- ✅ Dane w EU są **w pełni zgodne z RODO**
- ✅ Discord Inc. stosuje **Standard Contractual Clauses** (SCC)
- ✅ **Nie sprzedajemy** danych poza EU
- ✅ **Nie przesyłamy** danych do krajów bez odpowiedniego poziomu ochrony

### C. Discord Inc. i USA

Discord Inc. przetwarza dane w USA, ale stosuje zabezpieczenia:
- Standard Contractual Clauses (SCC) zgodne z RODO
- Privacy Shield (choć nieważny, Discord stosuje podobne standardy)
- Użytkownicy UE mają pełne prawa RODO

**Więcej:** https://discord.com/privacy

---

# 2. WARUNKI KORZYSTANIA

## 2.1 Ogólne warunki

Dodając ArinBot do swojego serwera Discord, użytkownik **akceptuje niniejsze Warunki Korzystania** oraz Politykę Prywatności.

Bot jest udostępniany **"w stanie, w jakim się znajduje"** (as-is) i może być modyfikowany bez wcześniejszego powiadomienia.

### Kogo dotyczą Warunki:
- ✅ Użytkowników korzystających z Bota na serwerach Discord
- ✅ Administratorów serwerów Discord, którzy dodają Bota
- ✅ Moderatorów i osób z uprawnieniami do konfiguracji Bota

### Akceptacja Warunków:
- Dodanie bota do serwera = akceptacja Warunków
- Użycie komendy bota = akceptacja Warunków
- Kontynuacja korzystania po zmianach = akceptacja nowych Warunków

## 2.2 Konto użytkownika

Użytkownik jest odpowiedzialny za:

✅ **Utrzymywanie poufności** swoich poświadczeń Discord  
✅ **Wszystkie działania** wykonane na swoim koncie  
✅ **Bezzwłoczne powiadomienie** o nieuprawniony dostępie  
✅ **Zgodę na przetwarzanie** swoich danych osobowych  
✅ **Przestrzeganie** Discord Terms of Service  

**⚠️ UWAGA:** Bot nie ma dostępu do Twoich danych logowania Discord. Autentykacja odbywa się przez Discord OAuth2.

## 2.3 Zakazane działania

Użytkownik **ZOBOWIĄZUJE SIĘ NIE:**

### A. Nadużycia techniczne
❌ Nadużywać Bota do spamu, ataków lub uszkodzenia serwera  
❌ Próbować hakować, zainfekować lub uzyskać nieuprawniony dostęp do Bota  
❌ Dystrybować złośliwego oprogramowania za pośrednictwem Bota  
❌ Wykonywać reverse engineering kodu Bota  
❌ Exploitować błędy dla osobistych korzyści  
❌ Przeciążać Bot (DoS, DDoS)  

### B. Nadużycia funkcji
❌ **Manipulować systemem punktów** lub sklepem:
  - Farming punktów przez boty
  - Eksploitowanie bugów do zdobywania punktów
  - Tworzenie wielu kont dla punktów (multi-accounting)
❌ **Obchodzić raid detection:**
  - Skoordynowane ataki mające na celu oszukanie ML
  - Manipulowanie trusted users listą
❌ **Nadużywać systemu partnerstw:**
  - Spam invites do partnerstwa
  - Fałszywe tagi serwera
  - Manipulowanie match scoringiem
❌ **Oszukiwać systemu weryfikacji**
❌ **Spamować tickety** lub sugestie

### C. Naruszenia prawne i etyczne
❌ Naruszać **regulamin Discord Inc.**  
❌ Tworzyć **wiele kont** do obejścia blokad  
❌ Wykorzystywać Bota do **phishingu** lub inżynierii społecznej  
❌ Publikować **zawartość niezgodną z prawem:**
  - Pornografia dziecięca (CSAM)
  - Nielegalne treści (terroryzm, narkotyki, etc.)
  - Naruszenie praw autorskich
❌ **Dyskryminować, molestować** lub zagrażać innym użytkownikom  
❌ **Doxxing** (publikowanie danych osobowych bez zgody)  
❌ **Manipulować ML/AI** detection systems poprzez adversarial attacks  

### D. Nadużycia komercyjne
❌ Odsprzedawać funkcje Bota bez zgody  
❌ Wykorzystywać Bota do działalności komercyjnej bez zgody  
❌ Kopiować funkcje Bota do własnych projektów (naruszenie copyright)  

**⚠️ Konsekwencje:** Naruszenie tych zasad może skutkować **banem** (permament blacklist) z używania Bota.

## 2.4 Odpowiedzialność użytkownika

Użytkownik ponosi **pełną odpowiedzialność** za:

✅ Wybranie odpowiednich **uprawnień** dla Bota na swoim serwerze  
✅ Konfigurację **bezpieczeństwa** serwera  
✅ Działania podjęte przez Bota w rezultacie **poleceń użytkownika**  
✅ Zgodność z **regulaminem i polityką Discord**  
✅ Treści publikowane przez **członków swojego serwera**  
✅ Prawidłowe skonfigurowanie **trusted users** (jeśli używane)  
✅ Przegląd **raid detection alerts** i podejmowanie odpowiednich działań  

**Przykład:** Jeśli administrator serwera nadał Botowi uprawnienia "Administrator", ponosi odpowiedzialność za potencjalne skutki tych uprawnień.

## 2.5 Odpowiedzialność właściciela Bota

Właściciel Bota **NIE PONOSI ODPOWIEDZIALNOŚCI** za:

### A. Kwestie techniczne
❌ Utratę danych spowodowaną **awarią bazy danych**  
❌ **Przestoje lub niedostępność** Bota (downtime)  
❌ **Błędy w działaniu** Bota (bugs, glitches)  
❌ **False positives** raid detection (błędne wykrycia)  
❌ **Utratę punktów** ARIN_POINTS z powodów technicznych  
❌ **Nieudane matchingi** partnerstw  

### B. Straty i szkody
❌ **Straty finansowe lub majątkowe** użytkownika  
❌ **Szkody pośrednie** wynikające z używania Bota  
❌ **Utratę reputacji** serwera  
❌ **Konflikt między użytkownikami** spowodowany działaniem Bota  

### C. Treści i działania użytkowników
❌ **Treści publikowane** przez użytkowników na serwerach  
❌ **Nadużycia** dokonane przez administratorów serwerów  
❌ **Naruszenia Discord ToS** przez użytkowników  

### D. Zmiany zewnętrzne
❌ **Działania Discord Inc.** lub zmiany w API Discord  
❌ **Zmiany w przepisach prawa**  
❌ **Działania osób trzecich** (hakerzy, ataki DDoS)  

**⚠️ ZASTRZEŻENIE ODPOWIEDZIALNOŚCI:**

Bot jest świadczony **NIEODPŁATNIE** i **"w stanie, w jakim się znajduje"** (as-is, as available).

Właściciel **NIE DAJE ŻADNYCH GWARANCJI** dotyczących:
- Dostępności (uptime)
- Bezpieczeństwa (security)
- Dokładności (accuracy)
- Przydatności do określonego celu (fitness for purpose)

**Maksymalna odpowiedzialność** właściciela jest ograniczona do **0 PLN** (bot jest darmowy).

## 2.6 Zmiany warunków

Właściciel Bota **zastrzega sobie prawo** do zmiany niniejszych Warunków w dowolnym momencie.

### Jak działają zmiany:
1. **Publikacja zmian** - na serwerze wsparcia / stronie www
2. **Wejście w życie** - po 30 dniach od publikacji
3. **Znaczące zmiany** - powiadomienie DM (jeśli możliwe)
4. **Kontynuacja korzystania** = akceptacja zmian

### Powiadomienia o zmianach:
- 📧 **Wiadomości bezpośrednie** (DM) do właścicieli serwerów (jeśli włączone)
- 📢 **Powiadomienia w kanale bota** (jeśli skonfigurowany)
- 🌐 **Aktualizacje na oficjalnym serwerze wsparcia**
- 📄 **Aktualizacje na stronie www** (jeśli istnieje)

### Twoje opcje:
✅ **Akceptujesz zmiany** - kontynuujesz korzystanie  
❌ **Nie akceptujesz zmian** - usuń Bota z serwera przed wejściem w życie  

**Data ostatniej zmiany** znajduje się na górze tego dokumentu.

## 2.7 Wygaśnięcie dostępu

Właściciel Bota **zastrzega sobie prawo** do:

### A. Działania wobec serwerów
🔴 **Usunięcia Bota z serwera** bez podania przyczyny  
🔴 **Blacklist serwera** (permanentna blokada)  
🔴 **Wyłączenia funkcji** dla konkretnego serwera  
🔴 **Ograniczenia limitów** (np. raid detection cooldown)  

### B. Działania wobec użytkowników
🔴 **Zablokowania użytkownika** przed korzystaniem z Bota (global ban)  
🔴 **Usunięcia danych użytkownika** ze względów bezpieczeństwa  
🔴 **Zawieszenia konta punktów** ARIN_POINTS  
🔴 **Cofnięcia zakupów** w sklepie (w przypadku oszustwa)  

### C. Działania wobec Bota
🔴 **Zawieszenia Bota** lub jego funkcji (maintenance)  
🔴 **Całkowitego wyłączenia Bota** (end-of-life)  
🔴 **Migracji na nową wersję** Bota  

### Powody możliwego wygaśnięcia:
- Naruszenie Warunków Korzystania (sekcja 2.3)
- Nadużycia techniczne lub funkcji
- Działania niezgodne z Discord ToS
- Ataki na Bota lub infrastrukturę
- Decyzja biznesowa właściciela
- Wymogi prawne

**⚠️ UWAGA:** Wygaśnięcie dostępu zazwyczaj jest poprzedzone ostrzeżeniem (z wyjątkiem poważnych naruszeń).

## 2.8 Postanowienia końcowe

### A. Całość umowy
Niniejsze **Warunki Korzystania** i **Polityka Prywatności** stanowią **całość umowy** między użytkownikiem a właścicielem Bota.

Zastępują one wszystkie wcześniejsze umowy, komunikaty i ustalenia.

### B. Prawo właściwe
Niniejsze Warunki podlegają **prawu Rzeczypospolitej Polskiej**.

Wszelkie spory będą rozstrzygane zgodnie z **polskim kodeksem postępowania cywilnego**.

**Właściwość sądów:**
- Dla sporów z konsumentami: sąd właściwy według przepisów o ochronie konsumentów
- Dla sporów z przedsiębiorcami: Sąd właściwy dla siedziby właściciela Bota

### C. Separatywność (severability)
Jeśli jakakolwiek część niniejszych Warunków będzie uznana za **niezgodną z prawem lub niewykonalną**, pozostałe postanowienia będą **nadal obowiązujące**.

Nieważne postanowienie zostanie zastąpione przez najbliższe prawnie dopuszczalne postanowienie.

### D. Zrzeczenie się praw (waiver)
Brak egzekucji któregokolwiek z postanowień **NIE oznacza rezygnacji** z tego prawa.

Właściciel może egzekwować prawa w dowolnym momencie.

### E. Cesja (assignment)
Użytkownik **NIE może przenieść** swoich praw i obowiązków wynikających z niniejszych Warunków na osoby trzecie bez zgody właściciela.

Właściciel **może przenieść** swoje prawa i obowiązki (np. w przypadku sprzedaży Bota).

### F. Języki
Niniejszy dokument jest dostępny w języku **polskim** (wersja oryginalna).

Tłumaczenia na inne języki służą wyłącznie celom informacyjnym. W przypadku sprzeczności, **wersja polska** jest wiążąca.

### G. Kontakt
W przypadku pytań lub zastrzeżeń dotyczących Warunków Korzystania lub Polityki Prywatności, prosimy o kontakt:

📧 **Email:** [Twój email]  
💬 **Discord:** [Twoja nazwa użytkownika]  
🌐 **Serwer wsparcia:** [Link do serwera Discord]  
📱 **Website:** [Jeśli istnieje]  

**Czas odpowiedzi:** Staramy się odpowiadać w ciągu **48-72 godzin** (dni robocze).

---

# 3. DODATKOWE KLAUZULE

## 3.1 Ochrona przed atakami i spam

Bot zawiera wbudowane mechanizmy ochrony serwerów przed atakami DDoS, raidami i spamem.

### A. Raid Protection System
- ✅ Dwuetapowa detekcja (Global Scan + Precise Analysis)
- ✅ Machine Learning scoring (confidence 0-100%)
- ✅ Automatyczne akcje (auto-mute 48h, auto-delete)
- ✅ Trusted users (immunitet przed detekcją)
- ✅ Cooldown system (3.5 min między detekcjami)

### B. Spam Protection
- ✅ Rate limiting na komendy (max 5/min per user)
- ✅ Filter słów (customizowalne)
- ✅ Duplicate message detection
- ✅ Link spam detection

### C. Monitoring i logowanie
Bot może:
- 📊 Monitorować częstotliwość poleceń użytkownika
- 🚫 Tymczasowo blokować użytkowników podejrzanych o spam
- 🗑️ Automatycznie usuwać spamowe wiadomości
- 💾 Przechowywać dane o podejrzanych aktywności (90 dni)

**Administrator serwera** jest odpowiedzialny za konfigurację odpowiedniego poziomu ochrony.

## 3.2 Moderacja treści

Bot może automatycznie moderować treść zgodnie z ustawieniami serwera.

### Funkcje moderacji:
- 🔍 **Filter słów** - automatyczne usuwanie wulgaryzmów
- 🔗 **Link filtering** - blokowanie phishingu
- 📝 **Content analysis** - wykrywanie spam/raid
- 🤖 **Auto-mute** - automatyczne wyciszenie (raid detection)
- 🗑️ **Auto-delete** - automatyczne usuwanie wiadomości

**Administrator serwera** jest odpowiedzialny za:
- Skonfigurowanie poziomu moderacji
- Wybór filtrowanych słów
- Trusted users list
- Oversig działania auto-moderacji

**⚠️ UWAGA:** Bot nie odpowiada za treści, które nie zostały wykryte przez system moderacji.

## 3.3 Zgodność z Discord Terms of Service

Bot jest **całkowicie zgodny** z Warunkami Usługi Discord (Discord Terms of Service, Discord Developer Terms, Discord Developer Policy).

### Użytkownik zgadza się, że:
- Naruszenie **Discord ToS** jest naruszeniem także **niniejszych Warunków**
- Bot stosuje się do **Discord API Terms** i **Rate Limits**
- Użytkownik **nie będzie wykorzystywał** Bota do działań zabronionych przez Discord
- Discord Inc. **ma prawo zablokować** Bota w dowolnym momencie

### Linki do dokumentów Discord:
- 📄 **Discord Terms of Service:** https://discord.com/terms
- 📄 **Discord Privacy Policy:** https://discord.com/privacy
- 📄 **Discord Community Guidelines:** https://discord.com/guidelines
- 📄 **Discord Developer Terms:** https://discord.com/developers/docs/policies-and-agreements/developer-terms-of-service
- 📄 **Discord Developer Policy:** https://discord.com/developers/docs/policies-and-agreements/developer-policy

**⚠️ Każdy użytkownik Bota jest zobowiązany do przestrzegania powyższych regulaminów Discord Inc.**

## 3.4 Machine Learning i Automatyczne Decyzje

### A. Wykorzystanie AI/ML
Bot wykorzystuje **Machine Learning** do następujących celów:

1. **Raid Detection** (98.2% claimed accuracy)
   - Analiza podobieństwa wiadomości
   - Link detection
   - Banned phrase detection
   - Scoring algorithm (0-100%)

2. **Spam Detection**
   - Duplicate message detection
   - Frequency analysis
   - Pattern recognition

3. **Partnership Matching** (Scoring 0-100)
   - Compatibility analysis na podstawie tagów
   - Member count matching
   - Activity level matching

### B. Automatyczne podejmowanie decyzji
System **automatycznie podejmuje decyzje** gdy:

| Warunek | Akcja | Możliwość odwołania |
|---------|-------|---------------------|
| Confidence score ≥ 40% (raid) | Auto-mute 48h | ✅ Trusted users, ręczne unmute |
| Confidence score ≥ 40% (raid) | Auto-delete wiadomości | ❌ Nie można przywrócić |
| Filter match | Delete wiadomości | ❌ Nie można przywrócić |
| Match score ≥ 60 (partnership) | Auto-send invite | ✅ Manual block |

### C. Prawa użytkownika wobec AI/ML

**Zgodnie z Art. 22 RODO**, użytkownik ma prawo:

✅ **Nie podlegać** wyłącznie automatycznym decyzjom  
✅ **Zażądać interwencji człowieka** (owner review)  
✅ **Wyrazić swoje stanowisko** (appeal)  
✅ **Zakwestionować decyzję** (dispute)  

**Jak skorzystać z praw:**
1. **Trusted users** - dodanie do listy (immunitet przed ML)
2. **Appeal** - kontakt z właścicielem serwera
3. **Review detection logs** - przegląd confidence score i powodów
4. **Manual unmute** - właściciel może ręcznie odmutować

**Ograniczenia:**
- Trusted users mogą być **cofnięci** przez właściciela
- Appeal może być **odrzucony** jeśli dowody są jednoznaczne
- System ML **nie może być całkowicie wyłączony** (podstawa bezpieczeństwa)

### D. Transparentność ML
Zapewniamy:
- 📊 **Detection logs** - pełne dane o detekcji (90 dni)
- 🎯 **Confidence score** - jawny scoring (0-100%)
- 📝 **Powody** - dlaczego użytkownik został uznany za raidera
- 🔍 **Stage 1 i Stage 2** - pełne wyniki obu etapów

**⚠️ UWAGA:** Model ML **nie jest doskonały**. False positive rate < 2% jest możliwy.

## 3.5 System Punktów i Ekonomia

### A. Opis systemu ARIN_POINTS
Bot zawiera **darmowy system punktów** do celów rozrywkowych:

- 💰 **Punkty** są przyznawane za aktywność (wysyłanie wiadomości)
- 📈 **Naliczanie:** 0.5-2.0 pkt per wiadomość (zależnie od długości)
- 🚫 **Daily limit:** maksymalnie **50 punktów dziennie** na użytkownika
- 🛒 **Sklep:** punkty można wydawać na **karty profilowe** i przedmioty
- 🏆 **Ranking:** leaderboard najaktywniejszych użytkowników

### B. Wartość punktów
**⚠️ WAŻNE:** Punkty ARIN **NIE MAJĄ** wartości pieniężnej:
- ❌ Nie można ich wymienić na prawdziwe pieniądze
- ❌ Nie można ich transferować między użytkownikami
- ❌ Nie mają wartości realnej
- ✅ Służą wyłącznie **celom rozrywkowym**

### C. Reguły systemu punktów
**Zabrania się:**
- ❌ Farming punktów przez boty/automated scripts
- ❌ Multi-accounting (wiele kont dla punktów)
- ❌ Exploitowanie bugów do zdobywania punktów
- ❌ Manipulowania daily limits
- ❌ Spamowania wiadomości dla punktów

**Konsekwencje:**
- 🚫 Reset punktów do 0
- 🚫 Ban z systemu punktów (permanentny)
- 🚫 Global blacklist z bota

### D. Utrata punktów
Administrator **NIE PONOSI ODPOWIEDZIALNOŚCI** za utratę punktów z powodu:
- 💥 Bugów w systemie
- 💥 Awarii bazy danych
- 💥 Rollbacków po exploitach
- 💥 Zmian w systemie punktowym
- 💥 Usunięcia konta użytkownika

**Brak zwrotów:** Punkty wydane w sklepie **nie podlegają zwrotowi**.

### E. Zmiany w systemie
Właściciel **zastrzega sobie prawo** do:
- Zmiany sposobu naliczania punktów
- Zmiany daily limits
- Dodania/usunięcia przedmiotów w sklepie
- Zmiany cen w sklepie
- Resetu punktów (w wyjątkowych przypadkach)

**Powiadomienia:** Użytkownicy zostaną powiadomieni o zmianach z 7-dniowym wyprzedzeniem (jeśli możliwe).

## 3.6 System Partnerstw i Auto-Matching

### A. Opis systemu
Bot oferuje **automatyczne dopasowywanie partnerstw** (AutoPartnership):

- 🤝 **Auto-matching** - bot automatycznie znajduje partnerów
- 🏷️ **Tag-based** - dopasowanie na podstawie 3 tagów serwera
- 📊 **Scoring** - algorytm oceny kompatybilności (0-100)
- 📤 **Auto-send** - automatyczne wysyłanie zaproszeń
- 📜 **History** - śledzenie historii partnerstw

### B. Jak działa matching
Algorytm ocenia kompatybilność na podstawie:

1. **Tags Match** (50% wagi)
   - Liczba wspólnych tagów (0-3)
   - Dokładne dopasowanie kategorii

2. **Member Count** (30% wagi)
   - Podobna liczba członków (+/- 50%)
   - Preferencja serwerów podobnej wielkości

3. **Activity Level** (20% wagi)
   - Aktywność serwera
   - Growth rate

**Match threshold:** Minimum **60 punktów** do auto-sendu.

### C. Reguły partnerstw
**Zabrania się:**
- ❌ Spam invites (więcej niż 5/dzień)
- ❌ Fałszywych tagów (tags non-representative)
- ❌ Manipulowania member countem
- ❌ Botów zamiast prawdziwych członków
- ❌ NSFW serwerów w SFW tagach

**Konsekwencje:**
- 🚫 Wyłączenie auto-matchingu
- 🚫 Blacklist z systemu partnerstw
- 🚫 Usunięcie wszystkich partnerstw

### D. Prywatność w systemie partnerstw
- ✅ **Dane publiczne:** Tagi, member count, nazwa serwera
- ✅ **Dane prywatne:** Lista członków, invite codes
- ✅ **Udostępnianie:** Dane są udostępniane tylko potencjalnym partnerom

**⚠️ UWAGA:** Włączając auto-matching, zgadzasz się na udostępnianie podstawowych informacji o serwerze (tagi, nazwa, liczba członków) innym serwerom w systemie.

### E. Opt-out z systemu
Możesz **wyłączyć** auto-matching w dowolnym momencie:
- Komenda `/autopartner_stop`
- Twoje dane pozostają w bazie przez 365 dni (history)
- Możesz zażądać usunięcia danych (RODO)

## 3.7 Monitoring Botów (SafeCheck)

### A. Opis systemu
Bot monitoruje **inne boty** na serwerze dla bezpieczeństwa:

- 🔍 **Bot Join Monitor** - śledzenie dołączania botów
- 🛡️ **Trust Levels** - trusted/untrusted bots
- ⚠️ **Alerts** - powiadomienia o podejrzanych botach
- 🔐 **Permission Analysis** - analiza uprawnień botów

### B. Cel monitoringu
SafeCheck chroni przed:
- 🚨 Złośliwymi botami (nukers, raiders)
- 🚨 Botami z nadmiernymi uprawnieniami
- 🚨 Podejrzanymi botami bez weryfikacji
- 🚨 Spamujący botami

### C. Dane zbierane o botach
- Bot ID
- Bot name
- Join timestamp
- Permissions (uprawnienia)
- Trust level (trusted/untrusted)

**⚠️ UWAGA:** Bot **NIE monitoruje** aktywności innych botów - tylko join event i permissions.

### D. Privacy innych botów
- Dane dotyczą **tylko botów** (nie użytkowników)
- Dane są **publiczne** (dostępne przez Discord API)
- **Nie monitorujemy** wiadomości innych botów
- **Nie ingerujemy** w działanie innych botów

### E. Opt-out
Administrator serwera może:
- Wyłączyć SafeCheck (`/ustawienia`)
- Dodać bota do trusted list (nie będzie monitorowany)
- Całkowicie wyłączyć monitoring botów

---

# POSTANOWIENIA KOŃCOWE

## Akceptacja Warunków

Korzystając z ArinBot, **potwierdzasz**, że:

✅ Przeczytałeś i zrozumiałeś niniejszą Politykę Prywatności i Warunki Korzystania  
✅ Zgadzasz się na przetwarzanie Twoich danych zgodnie z niniejszym dokumentem  
✅ Akceptujesz wszystkie postanowienia i warunki  
✅ Jesteś świadomy wykorzystania Machine Learning i automatycznych decyzji  
✅ Rozumiesz, że Bot jest dostarczany "as-is" bez gwarancji  

## Data wejścia w życie

Niniejszy dokument wchodzi w życie **01.01.2026** i zastępuje wszystkie poprzednie wersje Polityki Prywatności i Warunków Korzystania.

## Kontakt

W przypadku pytań lub wątpliwości, skontaktuj się z nami:

📧 **Email:** [Twój email]  
💬 **Discord:** [Twoja nazwa użytkownika + tag]  
🌐 **Serwer wsparcia:** [Link do serwera Discord]  
📱 **Website:** [Jeśli istnieje]  

**Godziny wsparcia:** Odpowiadamy w ciągu 48-72 godzin (dni robocze)

---

## Załączniki

### Załącznik A: Definicje
- **RODO** - Rozporządzenie Parlamentu Europejskiego i Rady (UE) 2016/679 (GDPR)
- **Bot** - ArinBot, bot Discord
- **Użytkownik** - osoba fizyczna korzystająca z Bota
- **Administrator** - właściciel serwera Discord
- **ML** - Machine Learning (uczenie maszynowe)
- **AI** - Artificial Intelligence (sztuczna inteligencja)
- **Raid** - skoordynowany atak na serwer Discord (spam, trolling)
- **Confidence Score** - ocena pewności detekcji (0-100%)
- **Trusted Users** - użytkownicy z immunitetem przed automatyczną detekcją

### Załącznik B: Linki do dokumentów prawnych
- RODO (pełny tekst): https://eur-lex.europa.eu/legal-content/PL/TXT/?uri=CELEX:32016R0679
- Discord Terms of Service: https://discord.com/terms
- Discord Privacy Policy: https://discord.com/privacy
- Discord Developer Terms: https://discord.com/developers/docs/policies-and-agreements/developer-terms-of-service
- UODO (Urząd Ochrony Danych Osobowych): https://uodo.gov.pl

### Załącznik C: Historia zmian
| Wersja | Data | Główne zmiany |
|--------|------|---------------|
| 1.0 | 31.10.2025 | Pierwsza wersja polityki |
| 2.0 | 01.01.2026 | Dodano: ML/AI, ARIN_POINTS, AutoPartnership, SafeCheck, pełne RODO compliance |

---

**© 2025 ArinBot. Wszelkie prawa zastrzeżone.**

Niniejszy dokument jest prawnie wiążący. Przeczytaj go uważnie przed korzystaniem z Bota.

**Ostatnia aktualizacja:** 30.12.2025  
**Wersja dokumentu:** 2.0  
**Status:** FINALNY - GOTOWY DO WERYFIKACJI DISCORD
