# context-search-userscript
The intent of the included code is to display a search link when arbitrary text is selected on a webpage.

![The code in action](/example/screenshots/in_action.png)

When a passage of text is selected, the script will create a small `div` below the selection. This div will display the selected text and a link labeled 'Go'. 
The 'Go' link is customisable and follows the following pattern:

`{domain}/{searchStub}?{queryKey}={selectedText}`

The parameters `searchStub` and `queryKey` can be set in selectSearchScript.js.

The script is intended to be used as a part of a userscript, an example will come in the near future.

[Example Link](https://mcat-ee.github.io/context-search-example/), with the first chapter of Cat's Cradle, by Kurt Vonnegut as the corpus
# Running the example

1. Clone the repo
2. cd into the '_example_' directory and serve the directory with the platform of your choice. If you have python installed, use `python -m SimpleHTTPServer`

## Screenshots
![Just select some text, and press Go!](/example/screenshots/1.png)
Just select some text, and press Go!


![The query string will be shown above the text corpus](/example/screenshots/2.png)
The query string will be shown above the text corpus
