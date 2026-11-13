# MCA Consolidated Grade Report — Version 6

## Fixes in this version
- Fixed the JavaScript error caused by the SGPA table cell ID not matching the calculation code.
- Semester SGPA now appears in a merged SGPA column cell for each semester.
- Passing month/year is prefilled for all subjects in each semester:
  - Semester I: APR, 2025
  - Semester II: NOV, 2025
  - Semester III: APR, 2026
  - Semester IV: OCT, 2026
- Save as PDF and Share result are always enabled.
- Save as PDF automatically calculates first, then opens the browser print dialog. Choose **Save as PDF**.
- Share result calculates first and uses the browser share sheet, clipboard, or a copy prompt fallback.
- No external PDF library or CDN dependency.

## Run
Open with VS Code Live Server or any modern browser. No internet connection is needed for calculation or printing.

## Calculation
S=10, A=9, B=8, C=7, D=6, E=5. F is counted as a fail but excluded from the GPA numerator and denominator. Blank grades are ignored.

## Disclaimer
This is an unofficial student-generated academic summary, not an official university-issued marks memo, transcript or provisional certificate.
