# Importron support

Public support and privacy pages for Importron. The app source repository is separate.

[Support and privacy website](https://astrojams1.github.io/importron-support/) · [Open a support issue](https://github.com/astrojams1/importron-support/issues/new?template=support.yml)

Do not post lab PDFs, patient details or other medical information in public issues. Each sample PDF is wholly synthetic and intended only for testing.

## Synthetic lab report fixtures

These seven text-based reports contain invented results for SAMPLE, PERSON. Use a dedicated test device for import tests. The files exercise report parsing and duplicate handling. Importron transcribes results and does not interpret them.

[Run the first sample in the browser checker](https://astrojams-apps.vercel.app/lab-pdf-check/?utm_source=importron-fixture-readme#samples) to see its page count, text coverage and layout markers. Choose **Check the sample PDF**. The first report has six pages, selectable text on all six and the Health Gorilla marker.

| File | Test case |
| --- | --- |
| [First report](https://astrojams1.github.io/importron-support/synthetic-sample.pdf) | Start with 119 invented results. |
| [Second collection date](https://astrojams1.github.io/importron-support/synthetic-next.pdf) | Compare reports from different collection dates. |
| [118-result seed](https://astrojams1.github.io/importron-support/incremental-seed.pdf) | Start a partial-overlap test with this report. |
| [119-result overlap](https://astrojams1.github.io/importron-support/incremental-full.pdf) | Compare with the seed to find one additional result. |
| [121-result report](https://astrojams1.github.io/importron-support/incremental-extra.pdf) | Compare with the seed to find three additional results. |
| [Correction only](https://astrojams1.github.io/importron-support/incremental-conflict-only.pdf) | Check how a conflicting value is handled. |
| [Correction and new results](https://astrojams1.github.io/importron-support/incremental-corrected.pdf) | Distinguish a changed value from new results. |

Terminology notice: see LOINC_short_license.txt.
