---
title: "Foundations"
teaching: 45
exercises: 0
questions:
- What best practices and generic skills can be used to successfully use and create library related programs?
objectives:
- Identify best practices in using software and data.
- Identify best practices in saving files.
- Identify best practices in naming files.
keypoints:
- Data structures should be consistent and predictable.
- Consider using semantic elements or data identifiers to data directories.
- Fit and adapt your data structure to your work.
- Apply naming conventions to directories and file names to identify them, to create associations between data elements, and to assist with the long term readability and comprehension of your data structures.
---

### Plain text formats are your friend

Why? Because computers can process them!

If you want computers to be able to process your stuff, try to get in the habit where possible of using platform-agnostic formats such as `.txt` for notes and `.csv` (comma-separated values) or `.tsv` (tab-separated values) for tabular data. TSV and CSV files are both spreadsheet formats. These plain text formats are preferable to the proprietary formats (e.g., Microsoft Word)  because they can be opened by many software packages and have a strong chance of remaining viewable and editable in the future. Most standard office suites include the option to save files in `.txt`, `.csv`, and `.tsv` formats, meaning you can continue to work with familiar software and save your files in the more perennial formats. Compared to `.doc` or `.xls`, these formats have the additional benefit of containing only machine-readable elements. 

When working with files for automation or computational purposes, it is more important to focus on meaningful transmission of data as opposed to fancy formatting. Whilst using bold, italics, and colouring to signify headings or to make a visual connection between data elements is common practice, these display-orientated annotations are not (easily) machine-readable and hence can neither be queried and searched nor are appropriate for large quantities of information. One rule of thumb is if you can't find it by <kbd>Ctrl</kbd>+<kbd>F</kbd>/<kbd>Command</kbd>+<kbd>F</kbd> it isn't machine readable. Preferable are simple notation schemes such as using a double-asterisk or three hashes to represent a data feature: for example, we could use three question marks to indicate something that needs follow up, chosen because `???` can easily be found with a <kbd>Ctrl</kbd>+<kbd>F</kbd>/<kbd>Command</kbd>+<kbd>F</kbd> search.

### Use machine readable plain text notation for formatting
There are some simple notation schemes that are also plain text and machine readable, but can be used to render simple formatting. One such scheme is called Markdown, a lightweight markup language. A markup language is a metadata language that uses notation to distinguish between the content and the formatting of the content. Markdown files, which use the file extension `.md`, are machine and human readable. Markdown applications can be disparate, from simple to-do lists, to extensive manual pages. For example, GitHub renders text via Markdown.  

For those who wish to follow – or adapt – this existing schema, you can try Markdown formatting interactively by following [CommonMark's guide](https://commonmark.org/help/), or using [TailorDev's Monod editor](https://github.com/TailorDev/monod). An excellent [Markdown cheat sheet is available on GitHub](https://github.com/adam-p/markdown-here).  

### Applications for writing, reading and outputting plain text files

We've already discussed why plain text formats are needed for working with data, and it's also important to understand that you need different tools to work with these formats. Word processors like Microsoft Word, LibreOffice Writer, and Google Docs will explicitly _not_ work for this purpose -- those tools are meant to optimize how documents appear to humans, not to computers. They add many hidden characters and generally are unsuitable for working with plain text files. The category of tool you'll want to use for data is called a _text editor_. Text editors save only the text that you type -- there is no hidden formatting or metadata. What you see in a text editor is what a computer will see when it tries to process that data.       

Two free, cross-platform editors that work well for handling plain text files are [Visual Studio Code](https://code.visualstudio.com/) and [Atom](https://atom.io/). For Windows users, [Notepad++](http://notepad-plus-plus.org/) is recommended. Mac or Unix users may find [Komodo Edit](https://www.activestate.com/products/komodo-ide/downloads/edit/), [Kate](https://kate-editor.org/) or [Gedit](https://wiki.gnome.org/Apps/Gedit) useful.
Combined with [pandoc](http://pandoc.org/), a Markdown file can be exported to PDF, HTML, a formatted Word document, LaTeX or other formats, so it is a great way to create machine-readable, easily searchable documents that can be repurposed in many ways. This [Programming Historian](https://programminghistorian.org/) [tutorial](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown) spells out what to do.
