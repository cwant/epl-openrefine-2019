---
title: "Getting data into OpenRefine"
teaching: 5
exercises: 0
questions:
- "How can we bring our data into OpenRefine?"
objectives:
- "Create a new OpenRefine project from a CSV file."
- "Understand potential problems with file headers."
keypoints:
- "OpenRefine can import a variety of file types."
---

# Lesson

## Creating a new OpenRefine project

In Windows, you can start the OpenRefine program by double-clicking on the openrefine.exe file. Java services will start automatically on your machine, and OpenRefine will open in your browser. On a Mac, OpenRefine can be launched from your Applications folder. If you are using Linux, you will need to navigate to your OpenRefine directory in the command line and run `./refine`.

OpenRefine can import a variety of file types, including tab separated (`tsv`), comma separated (`csv`), Excel (`xls`, `xlsx`), JSON, XML, RDF as XML, Google Spreadsheets. See the [OpenRefine Importers page](https://github.com/OpenRefine/OpenRefine/wiki/Importers) for more information.

In this first step, we'll browse our computer to the sample data file for this lesson.
In this case, we will be using data on the top requested books from the Edmonton Public Library. Instructions on downloading the data are available
[here]({{site.baseurl}}/setup.html).

Once OpenRefine is launched in your browser, the left margin has options to `Create Project`, `Open Project`, or `Import Project`. Here we will create a new project:

1. Click `Create Project` and select `Get data from` `This Computer`.
2. Click `Choose Files` and select the file `Most_Popular_Books_by_Branch___Edmonton_Public_Library.csv`. Click `Open` or double-click on the filename.
3. Click `Next>>` under the browse button to upload the data into OpenRefine.
4. OpenRefine gives you a preview - a chance to show you it understood the file. If, for example, your file was really tab-delimited, the preview might look strange, you would choose the correct separator in the box shown and click `Update Preview` (bottom left). If this is the wrong file, click `<<Start Over` (upper left).  There are also options to indicate whether the dataset has column headers included and whether OpenRefine should skip a number of rows before reading the data.
  ![Parse Options](../fig/OR_01_parse_options.png)
5. If all looks well, click `Create Project>>` (upper right).

Note that at step 1, you could upload data in a standard form from a web address by selecting `Get data from` `Web Addresses (URLs)`. However, this won't work for all URLs.

{% include links.md %}
