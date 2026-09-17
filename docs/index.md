# Testovací dokumentace

Vítejte v testovací dokumentaci vytvořené pomocí GitHub Pages a Material for MkDocs.

## O dokumentaci

Tato testovací dokumentace ukazuje možnosti moderního dokumentačního webu:

- fulltextové vyhledávání,
- levé navigační menu,
- obsah stránky na pravé straně,
- tmavý vzhled,
- responzivní zobrazení,
- zvýrazňování zdrojového kódu.

## Rychlý začátek

Pokračujte na stránku [Instalace](instalace.md).

## Ukázka kódu

```powershell
Write-Host "Dokumentace funguje"
```

Nadpisy `##` a `###` automaticky vytvoří pravý panel „Obsah stránky“.

## 4. Upravte `docs/instalace.md`

# Instalace

Tato stránka slouží jako ukázka instalační dokumentace.

## Požadavky

Před zahájením budete potřebovat:

- účet na GitHubu,
- veřejný repozitář,
- povolené GitHub Actions,
- zapnuté GitHub Pages.

## Vytvoření repozitáře

Vytvořte veřejný repozitář pojmenovaný:

```text
ksefcik.github.io
```

## Přidání dokumentace

Dokumentační stránky ukládejte do složky docs.
Každá stránka je běžný Markdown soubor:

```text
docs/
├── index.md
└── instalace.md
```
## Nasazení

Po odeslání změn do větve main se automaticky spustí GitHub Actions a nová verze dokumentace se publikuje.


