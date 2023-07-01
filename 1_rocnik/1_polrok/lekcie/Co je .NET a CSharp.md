# Lekcia: Čo je .NET a C#?

Odhadovaný čas lekcie: 45 minút

## Cieľ

Na konci tejto lekcie budú študenti rozumieť tomu, čo sú .NET a C# a ako sa používajú v programovaní a napíšu svoj prvý program v C#.

## Štruktúra

### 1. Úvod (5 minút)

- Predstavenie témy: Čo je .NET a C#?
- Cieľ lekcie: Porozumieť, čo je .NET a C#, a aký je ich význam v oblasti vývoja softvéru.

### 2. Čo je .NET? (5 minút)

- Predstavenie .NET: .NET je všeobecná platforma pre vývoj softvéru, ktorú udržiava Microsoft. Funguje na rôznych platformách a bol vytvorený tak, aby bol rýchly, flexibilný a moderný. Vývojári môžu teraz vytvárať aplikácie pre Android, iOS, Linux, Mac a Windows s .NET.
- Diskusia o výhodách a použití .NET.

### 3. Čo je C#? (5 minút)

- Predstavenie C#: C# (C-Sharp, sí-šarp) je programovací jazyk vyvinutý spoločnosťou Microsoft, ktorý beží na .NET. C# sa používa na vývoj webových aplikácií, desktopových aplikácií, mobilných aplikácií, hier atp.
- Diskusia o výhodách a použití C#.

### 4. Cvičenie: Hello World! (15 minút)

- [W3Schools](https://www.w3schools.com/cs/trycs.php?filename=demo_helloworld)
- [DotNet](https://dotnet.microsoft.com/en-us/learn/dotnet/in-browser-tutorial/1)
- Zdieľať na prezentéri
- Jednoduchá ukážka kódu v C# s vysvetlením, a to "Hello World!" program:

```C#
using System;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");    
    }
  }
}
```

- Vysvetlenie každej časti kódu jednoduchými slovami:
  - `using System;` - Toto je príkaz, ktorý nám hovorí, že chceme použiť "System" knižnicu, ktorá obsahuje základné funkcie, ako je výpis textu na obrazovku.
  - `namespace HelloWorld` - Menný priestor (namespace) je spôsob, ako organizovať náš kód. V našom prípade sme vytvorili menný priestor s názvom "HelloWorld".
  - `class Program` - Trieda (class) je základným stavebným kameňom v C#. V našom prípade sme vytvorili triedu s názvom "Program".
  - `static void Main(string[] args)` - Toto je hlavná funkcia programu, ktorá sa automaticky spustí, keď spustíme náš program. Táto funkcia môže prijímať argumenty (args), ale v tomto prípade ich nepoužívame.
  - `Console.WriteLine("Hello World!");` - Toto je príkaz, ktorý vypíše text "Hello World!" na obrazovku.
- Ukázať, ako sa kód spustí a aký výstup vytvára.

### 5. Zhrnutie a otázky (5 minút)

- Stručné zhrnutie hlavných bodov lekcie.
- Čas na otázky a odpovede.

### 6. Quiz (10 minúť)

- [Kahoot](https://create.kahoot.it/details/8a9e8422-6c2f-4563-a586-91512d34f52c)
  - Zdieľať na prezentéri
  - Start > Classic mode
  - Počkať kým sa študenti pripoja - pod svojim celým menom (meno a priezvisko)
  - Štart
  - Vyhodnotenie
  - Obodovanie študentov (po hodine)
    - Študenti získajú body v opačnom poradí ako boli umiestnení (prvý získa najviac bodov - počet súťažiacich, posledný študent získava 1 bod)
    - Zapísanie bodov do tabuľky študentov

## Skúsenosti od Lab Mastra po lekcii

- Lab Master sem napíše svoje skúsenosti po hodine, s návrhami na zlepšenie a dátumom lekcie.
