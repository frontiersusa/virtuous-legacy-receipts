## Requirements

- Mac OS (untested on Windows)
- Node/NPM
- Git (optional)

## Things to know

- This is for Virtuous' _legacy_ templating system. There is no way to know when or if they will stop supporting this system.
- This system uses Handlebars for templating.
- There no public docs for what variables/data points are available at this point. Virtuous would need to be contacted to get an updated list.

## Install

1. Clone project by running `git clone git@github.com:frontiersusa/virtuous-legacy-receipts.git` or just download the .zip.
2. In new directory run `npm intall`.

## How to use

After installation, run `npm run serve` to launch preview. Choose receipt version.

In the preview there are two options: _Print Preview_ and _Copy Code_.

1. _Print Preview_ will remove all non-essental styles and provide a better view of what will actually export.
2. _Code Copy_ will copy the exact code needed to paste into Virtuous.

## How to edit

Edit .html files to update receipt templates.

In all receipts (except for general-v1), there is a section that notates what will export when the _Code Copy_ button is clicked:

```
<!-- Start of exportable code below -->
  ... the receipt template in between ...
<!-- End of exportable code -->
```

The code outside of those comments are not included in the export and are for local presentation purposes only.

## Design Files

There are additional design files, if ever needed, located in in `/design-files`.
