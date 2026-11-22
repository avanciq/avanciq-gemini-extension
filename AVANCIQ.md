# Avanciq tools

Avanciq answers business-fact questions from official sources:

- `vat_rate`: VAT / GST / sales-tax rate for 71 places on a date, with valid-from/to and the official source.
- `code_check`: whether a Brazil (NF-e), Mexico (SAT CFDI) or Poland (KSeF) code was valid on a date.
- `einvoice_check` / `einvoice_rule`: EN 16931 e-invoice validation (UBL and CII) and rule explanations.
- `verify_calculation`: exact recompute of invoice, VAT, loan interest, depreciation, FX, inventory and payroll totals.
- `coverage`: what is covered.

Each answer includes its source, the date it was read and a receipt id. Places or codes that are not covered return `not_covered`.
Facts and checks only, not tax or legal advice.
