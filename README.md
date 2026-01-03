### ⚙️ DRIVETRAIN CALC

Precyzyjny analizator dynamiki napędu rowerowego.

Drivetrain Calc to zaawansowane, a jednocześnie lekkie narzędzie webowe stworzone dla pasjonatów mechaniki, serwisantów i konstruktorów rowerów customowych. Pozwala na błyskawiczne przeliczenie parametrów napędu z dokładnością, której brakuje standardowym kalkulatorom.

### Dlaczego warto go używać?
 - Pełna obsługa Mullet Setup: Niezależna konfiguracja przedniego i tylnego koła (np. 29" przód i 27.5" tył).
 - Profilowanie Opony (Aspect Ratio): Jako jeden z niewielu, skrypt uwzględnia wysokość profilu opony, co daje realny obwód toczny, a nie tylko teoretyczną wartość z rozmiaru obręczy.
 - Kadencja vs Prędkość: Dynamicznie wylicza wymaganą kadencję (RPM) dla zadanej prędkości (km/h) na Twoim konkretnym setupie.
 - Obroty Kół (Wheel Revs): Pokazuje dokładnie, ile razy obróci się każde z kół przy jednym pełnym obrocie korby – kluczowe dla analizy pracy napędu.

### Cechy techniczne:
 - Zero Dependencies: Jeden plik HTML, żadnych zewnętrznych bibliotek.
 - Grafika nagłówka i Favicon w Base64: Grafiki zaszyta bezpośrednio w kodzie.
 - Responsive Dark UI: Nowoczesny wygląd zoptymalizowany pod urządzenia mobilne.
 - Działa offline. Samodzielnie na urządzeniu.

### Jak używać:

Otwórz plik index.html w przeglądarce lub odwiedź wersję online: https://sobidoz.github.io/Drivetrain-Calc/

### Decyzja projektowa: rozmiar kół tylko w calach

Kalkulator używa cali (np. 28", 27.5", 26") zamiast standardów ETRTO/ISO i innz następujących powodów:

- Prostota i przyjazność dla użytkownika – większość rowerzystów myśli w calach przy wyborze kół/opon.
- Uniknięcie zamieszania spowodowanego wieloma nakładającymi się standardami (francuski, europejski, amerykański, marketingowe zaokrąglenia).
- Różni producenci mierzą średnicę koła inaczej (sama obręcz vs obręcz + opona, odkształcenie opony pod obciążeniem).
  

### Licencja:

CC BY-NC 4.0 – dozwolone użycie prywatne, edukacyjne, niekomercyjne.
Zabronione użycie komercyjne, sprzedaż, monetyzacja.
Autor: Sebastian Czaplinski & Gemini Google • wersja 2.01012026
_________________________________________
English Version (ANG)

### ⚙️ DRIVETRAIN CALC

High-precision bicycle drivetrain and wheel dynamics analyzer.

Drivetrain Calc is a professional-grade, lightweight web tool designed for bike builders, mechanics, and enthusiasts who need more than just a basic gear ratio calculator. It provides a real-world simulation of how your drivetrain interacts with different wheel and tire configurations.


### Key Features:
 - Mullet & Custom Setup Support: Configure front and rear wheels independently to see how they behave relative to each other.
 - Tire Aspect Ratio Logic: Achieve higher precision by including tire height profiles, ensuring results reflect the true rolling circumference.
 - Speed-to-Cadence Mapping: Instantly calculate the exact pedal RPM required to maintain a target speed (km/h).
 - Rotation Dynamics: See how many revolutions each wheel completes per single crank rotation.

### Technical Highlights:
 - Single-File App: Everything is packed into one lightweight HTML file (SPA).
 - Embedded Assets: Header pic and Favicon are encoded in Base64 for instant loading and offline support.
 - Mobile-First Design: A sleek, technical Dark Mode interface that works anywhere.
 - Works offline.

### How to use:

Open index.html in browser or visit online version: https://sobidoz.github.io/Drivetrain-Calc/

### Design decision: Wheel size in inches only

The calculator uses inches (e.g. 28", 27.5", 26") instead of ETRTO/ISO & other standards for the following reasons:

- Simplicity and user-friendliness – most cyclists think in inches when choosing wheels/tires.
- Avoids confusion caused by multiple overlapping standards (French, European, American, marketing approximations).
- Different manufacturers measure wheel diameter differently (rim only vs rim + tire, tire deformation under load).


### Licence:

CC BY-NC 4.0 – private, educational, non-commercial use allowed.
Commercial use, sale, monetization prohibited.
Author: Sebastian Czaplinski & Gemini Google • version 2.01012026
