# Sample Notebook for Extracting Data from OCRed PDFs Using Regex and LLMs

One can use the [notebook provided here](https://github.com/SuffolkLITLab/entity_extraction/blob/main/PDF%20Entity%20Extraction%20with%20Regex%20and%20LLMs.ipynb) to build a pipeline to parse and extract data from OCRed PDF files. _**Warning:** When using LLMs for entity extraction, be sure to perform extensive quality control. They are very susceptible to distracting language (latching on to text that sounds "kind of like" what you're looking for) and missing language (making up content to fill any holes), and importantly, they do **NOT** provide any hints to when they may be erroring. You need to make sure random audits are part of your workflow!_ In the notebook we've worked out a workflow using regular expressions and LLMs to parse data from zoning board orders, but the process is generalizable.

1. Collect a set of PDFs
2. Place OCRed PDFs into the data folder
3. Write regexes to pull out data
4. Write LLM prompts to pull out data
5. Test on random sample
6. Iterate & improve


