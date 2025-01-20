# bible-batch-search
*bible-batch-search* is a simple web application which can be run on a browser to search bible verses as a batch and export it as a PDF.
This works now only for Malayalam language.

## Running the search
Clone (or download) the repository and double-click  and open `bible-batch-search.html` file in your preferred browser.
Please note that data folder is not needed.

Enter the verses you need to search in the text area and click `Search` button.

## Try it

1. [https://www.obeyingchur.ch/malayalam-bible-search/](https://www.obeyingchur.ch/malayalam-bible-search/)
2. [https://samraj-dev.github.io/bible-batch-search](https://samraj-dev.github.io/bible-batch-search)

## Demo

Short Demo: [https://www.youtube.com/shorts/YmbxhX4A3mc](https://www.youtube.com/shorts/YmbxhX4A3mc)

## Data
Following link has the malayalam bible as JSON format which is used for this application [bible.json](https://github.com/godlytalias/Bible-Database/blob/master/Malayalam/bible.json)

## Export as PDF
Exporting as PDF is implemented using `pdfmake` library.
The steps in [https://pdfmake.github.io/docs/0.1/fonts/custom-fonts-client-side/vfs/](https://pdfmake.github.io/docs/0.1/fonts/custom-fonts-client-side/vfs/) were followed to add Nirmala UI font.
