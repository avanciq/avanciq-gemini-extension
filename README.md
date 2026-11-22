# Avanciq extension for Gemini CLI

Official VAT/GST rates on a date, Brazil/Mexico/Poland tax-code validity, EN 16931 e-invoice checks and exact business sums, with sources and receipt ids.

## Install

```bash
gemini extensions install https://github.com/avanciq/avanciq-gemini-extension
```

Works without a key: 20 free calls a day. For more, get a free key (100 calls a month) at https://avanciq.com/api/keys/ and add it in `~/.gemini/extensions/avanciq/gemini-extension.json`:

```json
"headers": { "Authorization": "Bearer avq_..." }
```

## Tools

| Tool | What it does |
|---|---|
| `coverage` | Lists what is covered (free) |
| `vat_rate` | VAT/GST/sales-tax rate on a date, with source |
| `code_check` | Was a BR/MX/PL tax or e-invoice code valid on a date |
| `einvoice_check` | Validate a UBL/CII e-invoice against EN 16931 |
| `einvoice_rule` | Explain an EN 16931 rule (free) |
| `verify_calculation` | Recompute a business calculation to the cent |

All tools are read-only. Docs: https://avanciq.com/agents/ · Privacy: https://avanciq.com/privacy/ · Support: hello@avanciq.com

Facts and checks only, not tax or legal advice.

MIT licence.
