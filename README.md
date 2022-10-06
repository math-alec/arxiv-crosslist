# arxiv-crosslist

I use this script to help me find new papers on the ArXiv that are cross-listed in the categories relevant to my research. Maybe this will be useful to someone else.

The script prompts the user for a "base category" and at least one "cross-listed category". The user will also be prompted to enter the number of submissions in the base category that they want to search through. The script uses the ArXiv API to check these categories and will output (and open) an HTML file with titles, abstracts, and links to the relevant PDFs on the ArXiv.

**Example:** My main area of focus is operator algebras. But I'm generally only interested in papers that are cross-listed in mathematical physics and/or quantum physics and/or quantum algebra, etc. When prompted for the base category, I enter **math.OA**. For the cross-listed categories, I enter **math.MP**, **quant-ph**, and **math.QA**. If I want to find the absolute most recent submissions, I might enter something like 25 when prompted. The script writes an HTML file which includes the subset of the 25 most recent submissions to **math.OA** which are also cross-listed in at least one of the other categories.

The script should work immediately, provided you change the url to the appropriate location on your computer.

You can find the list of ArXiV categories [here](https://arxiv.org/category_taxonomy). 
