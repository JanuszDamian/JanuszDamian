# 'O mnie'
  Cześć, 
  Z wykształcenia jestem mgr. inż. Automatyki i Robotyki. Początek mojej zawodowej kariery związany jest z branżą produkcyjną gdzie pracowałem jako inżynier procesu i inżynier jakości.
  Od początku 2022 roku zmieniłem branżę na IT. Obecnie pracuje na stanowisku Specjalista ds. jakości oprogramowania. Pracuję głównie przy projektach wdrożeniowych systemu CRM, gdzie wykonuje testy funkcjonalne, integracyjne i regresyjne. W ostatnim projekcie stworzyłem testy automatyczne ścieżek E2E z wykorzystaniem playwright/typeScript. W wolnych chwilach rozwijam swoje umiejętności w kierunku automatyzacji testów.
  <br> Skontaktuj się ze mną[<img align="left" alt="linked-in" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/janusz-dobro%C5%84ski-100a04186/)
# Narzędzia na których pracuje
* **Języki programowania**: java, C#, type script
* **Bazy danych**: MS SQL
* **System operacyjny**: Windows
* **System kontroli wersji**: Git
* **Narzędzia do zarządzania testowaniem**: Redmine, Jira, ADO
* **Narzędzia do automatyzacji testów**: Playwright, Cypress
# Kursy
* **'Kurs Selenium Java od podstaw'**
* **'Postman testowanie Rest API'**
* **'Automated software testing with playwright'**
* **'Cypress od podstaw - automatyzacja testów'** - w trakcie
# Techniczne ksiązki
* **'Podróżowanie przez świat testowania'** Karolina Pawłowska & Natalia Pawlak
# Przykładowy proces automatyzacji testów w playwright
**1. Opis projektu:**
Jestem w trakcie realizowania projektu automatyzacji testów strony testerskiej [https://www.saucedemo.com/](https://www.saucedemo.com/).
Weryfikuje funkcjonalności logowania, sortowania produktów na stronie oraz kilka testów E2E.

**2. Technologie:**
- TypeScript – język testów
- Playwright – automatyzacja testów E2E
- Node.js – środowisko uruchomieniowe
- Playwright Test Runner
- Chromium / Firefox – przeglądarki testowe
- HTML Reporter – raportowanie wyników testów
- Prettier – formatowanie kodu

**3. Struktura projektu:**

src<br>
├── data<br>
 │    ├── types<br>
 │    └── json<br>
├── pages<br>
└── tests<br>
     
gdzie:
- data - folder z danymi testowymi
- types - folder z klasami za pomocą których dane testowe z plików json przenoszone są do klas testowych
- pages - Page Object Model
- tests - folder z klasami testowymi

**4. Wymagania:**
- Node.js 18 lub nowszy
- Git
- Edytor kodu (np Visual Studio Code)
- Dostęp do internetu

**5. Instalacja:**
* W wybranym lokalnie folderze należy za pomocą git sklonować repozytorium:
git clone [https://github.com/twoj-login/nazwa-repo.git](https://github.com/JanuszDamian/SauceDemo-playwright.git)
* Zainstalować moduł playwright do testów automatycznych: npm install @playwright/test
* Zainstalować przeglądarki do testowania, korzytając z komendy: npx playwright install

Uruchomienie wszystkich testów w przeglądarce:
- chrome: npm run tests:chrome
- firfox: npm run tests:firefox

Uruchomienie danego typu testów (używane są: @Sorting, @E2E, @Login):
- npm run tests:chrome -- --grep "@E2E"
  
**6. Raporty z testów:**

Jeżeli test zakończy się błędem, w formacie HTML zostaje wyświetlony raport zawierający screen, nagranie z przebiegu procesu, przyczynę wystąpienia błędu oraz w załączniku logi.
Jeżeli wszystkie testy zakończyły się pozytywnie, raport można uruchomić korzystając z komendy: npx playwright show-report.



* link do repozytorium: https://github.com/JanuszDamian/SauceDemo-playwright

**Chętnie przyjmę feedback od innych QA / Automation Engineers 🚀**

<!---
JanuszDamian/JanuszDamian is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
