# Ukázky e-mailů

Skutečné nebo upravené e-maily jako reference pro AI — aby výstup zněl jako Hana.

## Jak přidat ukázku
1. Zkopíruj e-mail do nového souboru: `situace-popis.md`
2. Anonymizuj citlivá jména/data (pacienti, interní čísla)
3. Přidej záznam do tabulky níže

## Ukázky

| Soubor | Situace | Kanál | Tón |
|--------|---------|-------|-----|
| `hcp-gastro-uvodni.md` | Úvodní email pro gastroenterology | SFMC / HCP email | Profesionální, respektující |
| `workshop-pozvanka.md` | Pozvánka na OCE workshop | Interní email | Přátelský, akční |

## Charakteristiky Haniných e-mailů

### HCP komunikace (lékaři)
- Respektující, na úrovni kolegy — ne paternalistický
- Medicínsky relevantní — konkrétní data, SmPC reference
- Compliance-first — MLR schválený jazyk
- Jasné CTA — co má HCP udělat dál
- Žádný zbytečný marketing-speak

### Interní komunikace
- Přímá, přátelská
- Akční — co potřebuji, do kdy, od koho
- Strukturovaná — odrážky nebo číslovaný seznam pokud více bodů
- Minimální formalita — "Ahoj" ne "Vážený kolego"

## Jak použít v promptu

```
Napiš email v mém stylu. Tady jsou příklady jak píšu:

---
[obsah z ukázkového souboru]
---

Kontext: [popis situace]
Příjemce: [kdo to dostane]
Cíl emailu: [co má příjemce udělat]
Délka: max [X] slov
```
