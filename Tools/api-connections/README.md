# API napojení

Konfigurace a příklady napojení na externí služby.

## Dostupná napojení

| Služba | Soubor | Status |
|--------|--------|--------|
| _(zatím žádné)_ | — | — |

## Bezpečnost

**Nikdy** neukládej API klíče přímo do souborů. Používej:
- `.env` soubory (přidej `.env` do `.gitignore`)
- Správce hesel (1Password, Bitwarden)
- Environment variables v CI/CD

## Šablona pro nové napojení

```markdown
# [Název služby] API

## Endpoint
https://api.sluzba.com/v1

## Autentizace
- Typ: Bearer token / API key / OAuth
- Kde získat: [odkaz na dokumentaci]

## Příklad volání
[ukázkový kód]

## Rate limits
[limity API]
```
