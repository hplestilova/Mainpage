# Druhý mozek — PACT systém

Osobní znalostní systém organizovaný podle struktury **PACT**.

```
PACT/
├── Projects/   → aktuální projekty a jejich kontexty
├── Agents/     → AI agenti, prompty, registr
├── Context/    → expertíza, cíle, tone of voice, příklady
└── Tools/      → skripty, API napojení, šablony
```

---

## Jak systém používat

| Složka | Kdy ji otevřu |
|--------|--------------|
| `Projects/` | Začínám nebo pokračuji v projektu |
| `Agents/` | Potřebuji prompt nebo vytvářím nového agenta |
| `Context/` | Potřebuji připomenout kdo jsem, co chci, jak komunikuji |
| `Tools/` | Hledám hotový skript nebo API napojení |

## Konvence

- Každý projekt dostane vlastní složku: `Projects/nazev-projektu/`
- Každý agent má soubor v `Agents/prompts/` a záznam v `Agents/registry.md`
- Soubory se pojmenovávají v lowercase s pomlčkami: `tone-of-voice.md`
