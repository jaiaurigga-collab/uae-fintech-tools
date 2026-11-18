# UAE & GCC Fintech Utilities (Client-Side)

A curated collection of browser-native, client-side developer tools built for core banking engineers, payroll operations teams, and fintech builders across the UAE and GCC. 

## Live Web Tools (100% Client-Side)
No server-side processing or data transmission—all utilities run locally in your browser:

* **[UAE WPS SIF Generator & Validator](https://aurigga.com/tools/wps-sif-generator.php)** — Generate and validate Salary Information Files (SIF) for the UAE Wages Protection System (EDR, EVP, and SCR records).
* **[MX-to-MT Converter](https://aurigga.com/tools/mx-to-mt-converter.php)** — Map ISO 20022 `pacs.008` payment messages to legacy SWIFT MT103 formats.
* **[SWIFT MT Message Parser](https://aurigga.com/tools/swift-mt-parser.php)** — Parse raw SWIFT MT103/MT202 messages into human-readable field breakdowns (`:20:`, `:32A:`, `:50K:`, `:59:`).
* **[ISO 20022 XML Message Validator](https://aurigga.com/tools/iso20022-validator.php)** — Structural checker for `pacs.008`, `pain.001`, and `camt.053` with UAE IBAN MOD-97 checksum validation.
* **[UAE IBAN & SWIFT/BIC Validator](https://aurigga.com/tools/uae-iban-validator.php)** — Verify 23-character UAE IBANs, check MOD-97 checksums, and generate QA test IBANs.

📂 Sample Payloads
Use these sample files to test the tools locally or within your own QA environments:
*   [pacs.008 Sample (XML)](./samples/pacs008-sample.xml) — Test with the [ISO 20022 Validator](https://aurigga.com/tools/iso20022-validator.php) or [MX-to-MT Converter](https://aurigga.com/tools/mx-to-mt-converter.php).
*   [MT103 Sample (TXT)](./samples/mt103-sample.txt) — Test with the [SWIFT MT Parser](https://aurigga.com/tools/swift-mt-parser.php).
*   [WPS SIF Sample (TXT)](./samples/wps-sif-sample.txt) — Test with the [UAE WPS SIF Validator](https://aurigga.com/tools/wps-sif-generator.php).

## License
Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
