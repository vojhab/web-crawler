# Web Crawler

Web crawler napsaný v Node.js, který prochází webové stránky a získává o nich různá data. Tato data jsou poté uložena do databáze.

## Cíl

Cílem je vytvořit kompletní řešení, které bude schopno automaticky procházet webové stránky, získávat o nich data a ukládat je do databáze. Tento web crawler může být využit například k vytvoření nového vyhledávače nebo k analýze různých dat na webových stránkách.

## Použité balíčky

- **Firebase Admin** pro přístup k Firestore databázi pro ukládání dat
- **Cheerio** pro zpracování HTML stránek
- **Axios** pro HTTP požadavky
- **Dotenv** pro načítání proměnných z .env souboru

## Instalace

Nainstalujte:

- Node.js

Naklonujte tento repozitář:

```bash
  git clone https://github.com/vojhab/web-crawler.git
```

Otevřete terminál v adresáři s repozitářem nainstalujte všechny potřebné balíčky:

```bash
  npm install
```

Vytvořte soubor .env a vložte do něj toto a upravte si hodnoty dle svých potřeb:

```
USER_AGENT=
QUEUE_COLLECTION_NAME=
CRAWLED_COLLECTION_NAME=
SAVE_LINKS=
SAVE_HEADINGS=
```

Vytvořte nový projekt na Firebase console a aktivujte Firestore databázi.

Přes Firebase console vytvořte nový private key a soubor přejmenujte na "serviceAccountKey.json". Soubor pak vložte do adresáře se staženým repozitářem.

## Tvůrce

[Vojtěch Habeš](https://www.github.com/vojhab)

habes.vo.2022@ssps.cz
