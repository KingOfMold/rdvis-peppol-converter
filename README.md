# RDVIS/eRiga XML → PEPPOL BIS Billing 3.0 konvertors

Šis ir statisks GitHub Pages rīks Rīgas domes / eRiga `InvoiceImport` XML failu pārveidošanai uz PEPPOL BIS Billing 3.0 / UBL Invoice XML formātu.

## Ātrākā publicēšana GitHub Pages

1. Izveido jaunu GitHub repozitoriju, piemēram, `rdvis-peppol-converter`.
2. Augšupielādē šos failus repozitorija saknē:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. Atver repozitoriju GitHub → **Settings** → **Pages**.
4. Pie **Build and deployment** izvēlies:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/root`
5. Saglabā. Pēc publicēšanas GitHub parādīs lapas URL, parasti:
   `https://TAVS-LIETOTAJVARDS.github.io/rdvis-peppol-converter/`

## Drošība

Konvertors darbojas lietotāja pārlūkā. XML fails netiek augšupielādēts uz serveri, ja vien pats nepapildini kodu ar servera nosūtīšanu.

Tomēr pati GitHub Pages lapa parasti ir publiski pieejama. Repozitorijā neliec īstus rēķinu XML piemērus ar uzņēmuma, bankas vai klienta datiem.

## Lietošana

1. Atver publicēto GitHub Pages lapu.
2. Izvēlies vienu vai vairākus Rīgas domes XML failus.
3. Spied **Konvertēt**.
4. Lejupielādē ģenerēto PEPPOL/UBL XML un iesniedz EDS.
