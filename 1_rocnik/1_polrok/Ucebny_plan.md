# Programovací jazyk `C#`

- 1. polrok (16 týždnov, 80 školských hodín)

## Zhrnutie

- Tento súhrn učebných osnov pokrýva rozsiahle študijné materiály zamerané na výuku programovania v jazyku C#.
- Kurz začína úvodom do OpenLabu, kde študenti spoznajú Lab Mastra, princípy OpenLabu, hodnotenie a kódex študenta, ako aj praktické aspekty a majú príležitosť položiť otázky.
- Ďalšia časť sa venuje základom programovania, predstavuje koncepty ako .NET a C#, IDE, Git a GitHub, a následne prechádza k základným programovacím konceptom v C#, vrátane premenných, operátorov, cyklov, podmienok a viac.
- Nasledujúci blok lekcií sa zaoberá pokročilejšími témami v C# vrátane metód, tried a objektovo orientovaného programovania (OOP). Študenti sa naučia o parametroch, návratových hodnotách, preťažení metód, triedach, dedičnosti, polymorfizme, abstrakcii a mnohých ďalších témach.
- Ak to Lab Master zhodnotí ako vhodné, môže pokračovať bonusovými časťami učebných osnov, ktoré sa týkajú pokročilých tém v C# vrátane delegátov, udalostí, generických typov, atribútov, multithreadingu a ďalších súvisiacich konceptov ako sú JSON, XML, databázy a SQL.
- Študenti tiež dostanú možnosť naučiť sa o základoch softvérového inžinierstva, princípoch SOLID, testovaní, dokumentácii kódu a kontinuálnej integrácii.
- Kurz končí projektovou časťou, kde študenti vytvoria svoju vlastnú konzolovú aplikáciu, od návrhu a plánovania až po implementáciu a prezentáciu.
- Na záver kurzu prebehne záverečné hodnotenie a retrospektíva.

## Lekcie

### 1. týždeň: Úvod do OpenLabu

- Prezentácia - [Úvod do OpenLabu](/Prezentacie/1.%20Intro%20do%20OpenLabu.pptx)
  - Predstavenie Lab Mastra (Lab Mastrov)
  - Princípy OpenLabu
  - Hodnotenie
  - Kódex študenta
  - Praktické veci
  - Otázky a odpovede

### 2. týždeň: Úvod do programovania

- [Čo je programovanie?](lekcie/Co%20je%20programovanie.md)
- [Code Game](https://www.w3schools.com/codegame/index.html)

### 3. týždeň: IDE, Git, GitHub

- [CSharp repozitár](https://github.com/AppsLab-sk/csharp)
- [Čo je .NET a C#?](lekcie/Co%20je%20.NET%20a%20CSharp.md)
- Čo je IDE?
  - Teória: Prehľad Visual Studio 2022
  - Prax: Kontrola prostredia, verzie Visual Studio 2022
- Čo je Git?
  - Teória: Dôležitosť a úloha Source Control pri vývoji softvéru
- Čo je GitHub?
  - Teória: Možnosti a funkcie GitHubu
  - Prax: Vytvorenie účtu
  - Prax: Predstavenie repositára s cvičeniami
  - Prax: Predstavenie spôsobu práce s repozitárom - fork, commit, pull-request
  - Prax: Predstavenie automatického testovania riešení pre cvičenia pomocou GitHub Actions
- Console.WriteLine
  - [AppsLab-002-Console.WriteLine - Ako používať Console.WriteLine v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-002-ConsoleWriteLine.md)
- Komentáre (Comments)
  - [AppsLab-003-Comments - Práca s komentármi](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-003-Comments.md)
- Premenné, dátové typy a konštanty (Variables, Data Types, Constants)
  - [Premenné v jazyku C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-004-Variables.md)
  - [Úvod do dátových typov v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-005-DataTypes.md)
  - [Konštanty v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-006-Constants.md)

### 4. týždeň: C# Základy (C# Fundamentals) I

- Implicitné a explicitné pretypovanie (Implicit and Explicit Casting)
  - [Implicitné a explicitné pretypovanie v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-007-Casting.md)
- Console.ReadLine
  - [Používanie metódy Console.ReadLine v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-008-ConsoleReadLine.md)
- Operátory (Operators)
  - [Operátory v jazyku C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-009-Operators.md)
- Math
  - [Matematická trieda v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-010-Math.md)
- Reťazce a špeciálne znaky (Strings and special characters)
  - [Reťazce a špeciálne znaky v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-011-Strings.md)

### 5. týždeň: C# Základy (C# Fundamentals) II

- Boolean
  - [Boolean v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-012-Boolean.md)
- Podmienky `if`, `else` (Conditions)
  - [Podmienky if, else v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-013-Conditions.md)
- `switch`
  - [Switch v jazyku C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-014-Switch.md)

### 6. týždeň: Polia, Cykly (Arrays, Loops)

- Polia (Arrays)
  - [Polia (Arrays)](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-015-Arrays.md)
- Cykly - `while`, `for`, `foreach` (Loops)
  - `break`, `continue`
  - [Cykly v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-016-Loops.md)
- `List<T>`
  - [Práca s List](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-017-List.md)

### 7. týždeň: C# Metódy (C# Methods)

- Metódy (Methods)
  - Návratové hodnoty (Return Values)
  - Parametre a argumenty (Parameters and Arguments)
  - [Metódy v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-018-Methods.md)
- Preťaženie metód (Method Overloading)
  - [Preťaženie metód v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-019-MethodsOverloading.md)

### 8. týždeň: C# Triedy (C# Classes)

- Čo je OOP?
  - Triedy a objekty (Classes and Objects)
  - Viac tried a objektov (Multiple Classes and Objects)
  - Členovia triedy (Class Members)
  - Konštruktor (Constructor)
  - Modifikátory prístupu (Access Modifiers)
  - Vlastnosti (Properties)
  - Dedičnosť (Inheritance)
  - Polymorfizmus (Polymorphism)
  - Abstrakcia (Abstraction)
  - [Objektovo orientované programovanie (OOP)](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-020-OOP.md)
- Rozhranie (Interface)
  - [Úvod do rozhraní (Interfaces) v jazyku C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-021-Interfaces.md)
- Súbory (Files)
  - [Práca so súbormi v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-022-Files.md)
- Výnimky (Exceptions)
  - [Výnimky (Exceptions) v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-023-Exceptions.md)

> V tomto bode Lab Master zváži úroveň a progres študentov a rozhodne, či bude pokračovať s bonusovými časťami učebných osnov, alebo prejde rovno na projektovú časť.

### 9. týždeň: Pokročilý C# (Advanced C#) (BONUS)

- Udalosti (Events)
  - [Udalosti (Events) v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-024-Events.md)
- Lambda výrazy (Lambda Expressions)
  - [Lambda výrazy (Lambda Expressions) v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-025-Lambda.md)
- LINQ
  - [LINQ v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-026-LINQ.md)
- Generické typy (Generics)
  - [Generické typy (Generic types) v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-027-Generics.md)
- Indexátori (Indexers)
  - [Indexátori (Indexers) v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-028-Indexers.md)

### 10. týždeň: C# Multithreading (BONUS)

- Úvod do multithreadingu (Introduction to Multithreading)
- Task trieda (Task class)
- Async a Await
- [Asynchrónne programovanie (Async Programming) v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-029-Async.md)

### 11. týždeň: C# Súvisiace koncepty (Related Concepts) (BONUS)

- JSON
  - [C# Súvisiace koncepty (Related Concepts) - JSON](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-030-JSON.md)
- XML
  - [C# Súvisiace koncepty (Related Concepts) - XML](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-031-XML.md)
- Databázy a SQL
  - [C# Súvisiace koncepty (Related Concepts) - Databázy a SQL](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-032-SQL.md)
- .NET knižnice a NuGet balíčky (.NET libraries and NuGet packages)
  - [.NET knižnice a NuGet balíčky (.NET libraries and NuGet packages)](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-033-NuGet.md)
- Debugovanie a testovanie (Debugging and testing)
  - [Debugovanie a testovanie (Debugging and testing) v C#](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-034-Debug.md)

### 12. týždeň: Softvérové inžinierstvo (Software Engineering) (BONUS)

- Základy softvérového inžinierstva
  - [Základy softvérového inžinierstva](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-035-SoftwareEngineering.md)
- Zásady SOLID (SOLID Principles)
  - [Zásady SOLID (SOLID Principles)](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-036-SOLID.md)
- Kontinuálna integrácia (CI) (Continuous Integration (CI))
  - [Kontinuálna integrácia (Continuous Integration) (CI)](https://github.com/AppsLab-sk/csharp/blob/main/lekcie/AppsLab-037-CI.md)

### 13-15. týždeň: Projekt pre konzolovú aplikáciu (Project for Console App)

- Návrh projektu (Project Design)
- Plánovanie projektu (Project Planning)
- Implementácia projektu (Project Implementation)
- Prezentácia projektu (Project Presentation)

### 16. týždeň: Záverečné hodnotenie (Final Evaluation)

- Záverečné hodnotenie a prehľad (Final Evaluation and Summary)
- Retrospektíva (Retrospective)
