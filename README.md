# CSV Cleanroom — Day 04

Clean up everyday CSV files without sending them to a server. Paste data or open a local file, choose a few cleanup rules, preview the result, then download a cleaned CSV.

**[Open CSV Cleanroom](https://mhussain-codes.github.io/day-04-csv-cleanroom/)** · [View source](https://github.com/mhussain-codes/day-04-csv-cleanroom)

## What it does

- Reads comma, tab, or semicolon separated values, including quoted fields and escaped quotes.
- Trims whitespace in cells, removes fully blank rows, and removes duplicate data rows with independent toggles.
- Keeps the first row as the header and preserves the remaining column order.
- Shows a preview and cleanup counts before download; preview is capped for large files, while export includes all cleaned rows.
- Writes valid CSV quoting and downloads a local cleaned-data.csv file.

## Use it

1. Open the demo and paste CSV text or choose a .csv/.tsv file from your device.
2. Select **Load data**, review the preview, and adjust the cleanup options.
3. Select **Download cleaned CSV** when the result looks right.

## Privacy and limitations

Everything runs in your browser. Your file is read locally and is not uploaded, saved to an account, or stored by this project. Reloading clears the data. Duplicate rows are compared as whole rows after the selected trim option; this tool does not guess which columns are identifiers or change number/date formats. Review the preview before using the exported file.

## Built with

HTML, CSS, and vanilla JavaScript. No build step or external dependencies. MIT License.
