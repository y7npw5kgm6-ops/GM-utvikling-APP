# GM-utvikling-APP

Webapp for anleggsanalyse av vannbårne anlegg. Legg inn væskeprøve og observasjoner, og få vurdering mot veiledende grenseverdier (VDI 2035 / NS-EN 14868) med anbefalte tiltak og delstrømsfiltre fra Envatec AS.

## Bruk

Åpne `index.html` i en nettleser. Ingen installasjon eller byggesteg trengs.

## Tilpasning

Produktkatalogen (`PRODUCTS`) og grenseverdiene (`LIMITS`) ligger øverst i skriptet i `index.html`. Bekreft dimensjonering med Envatec AS (tlf. 400 07 550, post@envatec.no).

## Logo

Legg Envatec-logoen i roten av repoet som `envatec-logo.png`. Den vises da øverst i appen. Uten fil vises ingen logo.

## Send rapport

Knappen «Send rapport til Envatec» åpner kundens e-postprogram med ferdig utfylt rapport til `info@envatec.odoo.com`. Rapporten kopieres samtidig til utklippstavlen, i tilfelle e-postprogrammet kutter lange meldinger. Adressen endres i `ENVATEC_EMAIL` i `index.html`.
