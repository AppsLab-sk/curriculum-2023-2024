# Týždeň 1: Nastavenie prostredia

## 1. Úvod

### Prehľad lekcie

Táto lekcia je venovaná základom Angularu a ASP.NET Core a ich nastaveniu v lokálnom vývojovom prostredí. Tieto technológie sú dôležité pre vývoj webových aplikácií.

### Cieľ lekcie

- Porozumieť základom Angularu a ASP.NET Core
- Nastaviť lokálne vývojové prostredie pre Angular a ASP.NET Core
- Vedieť vytvárať nové projekty s pomocou Angular CLI a .NET CLI
- Vedieť použiť existujúcu šablónu pre vytváranie webovej aplikácie s Angularom a ASP.NET Core v Visual Studio 2022

## 2. Popis lekcie

### Front-end (Angular)

#### Čo je Angular?

- Angular je open-source framework pre vývoj webových aplikácií, ktorý bol vytvorený a je udržiavaný spoločnosťou Google. Je postavený na jazyku TypeScript od Microsoftu, ktorý je staticky typovaný nadstavbou JavaScriptu, čo pridáva dodatočnú bezpečnosť a efektívnosť vývoja.

#### Komponenty v Angulare

- Jedinou základnou stavebnou jednotkou v Angulare sú komponenty. Komponenty sú nezávislé a opakovateľné časti kódu, ktoré zoskupujú HTML šablónu, CSS štýly a logiku do jedného celku, čo nám umožňuje budovať komplexné aplikácie ako súbor samostatných, opakovateľných a izolovaných komponentov.

#### Nastavenie prostredia

- Predtým, než môžeme začať vytvárať aplikácie v Angulare, je potrebné nastaviť vývojové prostredie. Na to potrebujeme nainštalovať Node.js a npm (Node Package Manager). Node.js nám poskytuje serverovú platformu pre spustenie JavaScriptu a npm je balíčkovací systém, ktorý nám umožňuje inštalovať a spravovať balíčky JavaScriptu, na ktorých sa Angular a naše aplikácie spoliehajú.

#### Angular CLI

- Po inštalácii Node.js a npm môžeme nainštalovať Angular CLI (Command Line Interface). Angular CLI je výkonný nástroj, ktorý nám uľahčuje vývoj aplikácií v Angulare. Umožňuje nám vytvárať nové projekty, generovať rôzne časti kódu (napr. komponenty, služby, moduly atď.), spúšťať testy, buildovať našu aplikáciu pre produkciu a spúšťať lokálny vývojový server, ktorý nám umožňuje vidieť naše zmeny v reálnom čase.

### Back-end (ASP.NET Core)

#### Čo je ASP.NET Core?

- ASP.NET Core je open-source a multiplatformový framework pre vývoj moderných webových aplikácií. Je vytvorený a udržiavaný spoločnosťou Microsoft. Tento framework je navrhnutý pre vytváranie moderných internetových aplikácií, vrátane webových aplikácií a služieb API.

#### Testovateľnosť a podpora moderných vývojových prístupov

- ASP.NET Core je navrhnutý tak, aby bol ľahko testovateľný. Umožňuje vytváranie jednotkových testov pre logické časti kódu, čo zvyšuje kvalitu výslednej aplikácie a uľahčuje jej údržbu. Taktiež podporuje moderné vývojové prístupy, ako je napríklad dependency injection. Toto je technika, ktorá znižuje závislosť medzi jednotlivými časťami kódu a zjednodušuje ich testovanie.

#### Multiplatformovosť

- ASP.NET Core aplikácie je možné vytvárať a spúšťať na rôznych platformách. Podporuje Windows, macOS aj Linux. To umožňuje vývojárom pracovať na platforme, na ktorej sú najproduktívnejší.

#### .NET Core SDK a .NET CLI

- Kľúčovým prvkom pre prácu s ASP.NET Core je .NET Core SDK (Software Development Kit). Tento balík obsahuje všetky nástroje potrebné pre vývoj ASP.NET Core aplikácií. Medzi tieto nástroje patrí napríklad .NET CLI (Command Line Interface), ktorý umožňuje riadenie projektu a balíčkov.

#### Jazyk `C#`

- Kód ASP.NET Core aplikácií sa obvykle píše v jazyku C#, ktorý je moderný, typovo bezpečný, objektovo orientovaný programovací jazyk od spoločnosti Microsoft. C# má silnú podporu pre moderné programovacie koncepty ako sú asynchrónne operácie, LINQ, tuples, pattern matching a iné.

### Kombinácia

- Visual Studio 2022 ponúka šablóny pre vytvorenie webovej aplikácie, ktorá využíva Angular na front-ende a ASP.NET Core na back-ende. Tieto šablóny poskytujú už predpripravený základ pre rýchlejší štart vývoja. V tomto kurze si ukážeme, ako použiť túto šablónu pre vytvorenie nového projektu.

### Google Search

**Front-end (Angular):** "Angular basics", "Setting up Angular environment", "Working with Angular CLI"

**Back-end (ASP.NET Core):** "ASP.NET Core basics", "Setting up ASP.NET Core environment", "Working with .NET CLI"

**Kombinácia:** "Creating web application with Angular and ASP.NET Core using Visual Studio 2022 template"

### ChatGPT

**Front-end (Angular):** "Explain the basics of Angular", "How to set up an Angular development environment?", "How to work with Angular CLI?"

**Back-end (ASP.NET Core):** "Explain the basics of ASP.NET Core", "How to set up an ASP.NET Core development environment?", "How to work with .NET CLI?"

**Kombinácia:** "How to create a web application using Angular and ASP.NET Core with Visual Studio 2022?"

## 3. Cvičenie

### Popis cvičenia

**Front-end (Angular):** Inštalácia Node.js a npm, vytvorenie nového Angular projektu s pomocou Angular CLI.

**Back-end (ASP.NET Core):** Inštalácia .NET Core SDK, vytvorenie nového ASP.NET Core projektu s pomocou .NET CLI.

**Kombinácia:** Vytvorenie webovej aplikácie s použitím Angularu a ASP.NET Core vo Visual Studio 2022 s pomocou existujúcej šablóny.

### Očakávané výsledky

- Angular a ASP.NET Core prostredia sú nastavené a pripravené na vývoj.
- Ste schopní vytvárať nové projekty.

### Pomôcky

- Postupujte podľa krokov uvedených v sekcii "Teória".
- Pri problémoch využite Google Search a ChatGPT návrhy pre samostatné riešenie problémov.

## 4. Zhrnutie

V tejto lekcii sme sa oboznámili so základmi Angularu a ASP.NET Core, nastavili sme si lokálne vývojové prostredie a naučili sme sa vytvárať nové projekty s pomocou Angular CLI a .NET CLI. Taktiež sme sa naučili využívať šablónu vo Visual Studio 2022 pre vytvorenie webovej aplikácie.

## 5. Ďalšie kroky

Preskúmajte vytvorené projekty a oboznámte sa s ich štruktúrou. Pripravte sa na ďalšiu lekciu, kde sa budeme zaoberať podrobnejším kódom a funkcionalitou.

## 6. Ďalšie štúdium

- [Oficiálna dokumentácia pre Angular](https://angular.io/docs)
- [Oficiálna dokumentácia pre ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-5.0)
