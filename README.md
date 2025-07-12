### Project-1

# David Hockney, where everything has color: exploring the color system and palette throughout more than seven decades of creative work.

This work sought to find a way to analyze David Hockney's entire catalog of work. In the absence of a database containing all the information, we opted to use a sample of works available on the author's website. Among the available options, the focus was on paintings using traditional techniques and digital illustrations. A total of 412 pieces were found.


# Brief explanation:

**Scrape and analysis.ipynb** The codes used for scraping and visualization.

**csv**The resulting files from the analysis.

**Palettes** The folder with all the palettes created in Python. The code is also available.

**HTML and CSS** The html is in "index.html" and the respective css in "scrolly-style.css"


# Python libraries used

| Library  | Workflow             | Description                                                                                   |
|----------|----------------------|-----------------------------------------------------------------------------------------------|
| Pandas   | Scraping and Analysis| Essential for reading the created database and improving columns and the final analysis      |
| KMeans   | Visualization and Analysis | Used to identify and create color clusters                                              |
| Counter  | Analysis             | Used to count pixels per color cluster                                                       |
| Altair   | Visualization        | Used to improve the appearance of charts and make them easier to save as SVG for Illustrator |


**Illustrator** Illustrator was essential for creating images that later facilitated the transition effects in the template and for using the generated graphics in a more appealing way. 