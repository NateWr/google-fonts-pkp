# Google Fonts

This a plugin for [OJS](https://pkp.sfu.ca/software/ojs), [OMP](https://pkp.sfu.ca/software/omp), and [OPS](https://pkp.sfu.ca/software/ops) that provides Google Font files for use in custom themes.

## Update Fonts

The fonts can be updated by running the [node](https://nodejs.org/en) script.

Install the dependencies.

```bash
npm install
```

Run the script.

```bash
node ./scripts/get-fonts.js
```

Only the fonts that Google has updated since last run will be downloaded.