# Google Fonts

This a plugin for [OJS](https://pkp.sfu.ca/software/ojs), [OMP](https://pkp.sfu.ca/software/omp), and [OPS](https://pkp.sfu.ca/software/ops) that provides Google Font files for use in custom themes.

## Update Fonts

The fonts can be updated by running the [node](https://nodejs.org/en) script.

Install the dependencies.

```bash
npm install
```

Get a [Google Fonts API Key](https://developers.google.com/fonts/docs/developer_api) and create a `.env` file.

```
GOOGLE_FONTS_API_KEY="AIza...sJkk"
```

Run the script.

```bash
node ./scripts/get-fonts.js
```

Only the fonts that Google has updated since last run will be downloaded.