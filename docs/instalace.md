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

Dokumentační stránky ukládejte do složky `docs`.

Každá stránka je běžný Markdown soubor:

```text
docs/
├── index.md
└── instalace.md
```

## Nasazení

Po odeslání změn do větve `main` se automaticky spustí GitHub Actions a nová verze dokumentace se publikuje.
