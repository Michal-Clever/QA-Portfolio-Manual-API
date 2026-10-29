# QA-Portfolio-Manual-API

![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Xray](https://img.shields.io/badge/Xray-172B4D?style=for-the-badge&logo=atlassian&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## 📌 O projekcie
Niniejsze repozytorium zawiera kompletny projekt testowy przygotowany dla aplikacji **[SauceDemo]** dostępnej pod adresem: `(https://sauce-demo.myshopify.com/)`.

Celem projektu jest zaprezentowanie pełnego cyklu testowania oprogramowania (STLC) – od analizy wymagań i przygotowania planu testów, przez egzekucję przypadków testowych w Jiry, aż po weryfikację interfejsów API w narzędziu Postman.

---

## 🛠️ Użyte narzędzia i technologie

* **Zarządzanie testami & Zgłaszanie błędów:** Jira Cloud + wtyczka Xray
* **Dokumentacja & System kontroli wersji:** GitHub (Markdown, Git)
* **Testowanie API:** Postman (Kolekcje, Zmienne, Asercje w JavaScript)
* **Analiza i Diagnostyka:** Chrome DevTools (Console, Network, Application)
* **Standardy:** ISTQB (metodologia, terminologia, dobra praktyka)

---

## 📂 Struktura repozytorium
```text
├── README.md                   <-- Główne podsumowanie projektu
├── docs/                       <-- Dokumentacja testowa w Markdown
│   ├── 01_Test_Plan.md         <-- Plan testów, zakres, środowiska, kryteria
│   ├── 02_Test_Cases.md        <-- Przypadki testowe (ścieżki pozytywne i negatywne)
│   ├── 03_Bug_Reports.md       <-- Zgłoszone błędy z krokami do odtworzenia
│   └── 04_RTM.md               <-- Matryca pokrycia wymagań (Requirement Traceability)
├── images/                     <-- Zrzuty ekranu z systemu Jira / Xray
│   ├── jira_test_case.png
│   ├── jira_execution_failed.png
│   └── jira_bug_report.png
└── api/                        <-- Testy API
    └── postman_collection.json <-- Wyeksportowana kolekcja Postman z asercjami
