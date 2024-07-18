<h1>Internal linking opportunities</h1>
<p> Given you have a Sitebulb scrape of the content of every relevant webpage and a csv with the keywords you have assigned to landing pages, you can use this simple scripts to find out internal linking opportunities.</p>

<H2>Scrape content with Sitebulb</H2>
<p>In Sitebulb, go to Audit settings, Saving Crawl Data and toggle on "Webpage Text". There you add the CSS selector of the body content and exclude any navigational features and headings that should not be linked or is already a link item. Then after crawl, you go to Bulk Export and export Website Text, which is a csv file you can rename to crawl.csv</p>

<h2>Prepare Keyword, URL data</h2>
<p>Next you need is a csv called "kw-targeting.csv" with the headings: Keyword,URL. This is a list of keywords you want to have linked to the assigned URL.</p>

<h2>Execute the Script</h2>
<p>Make sure internal_linking_opportunities.ipynb is downloaded and in the same folder as the two csv files and run the notebook. You can use anaconda.com/download and open the file in Jupyter, or any other program that can execute this file type such as Visual Studio Code.</p>

<H2>Open in Excel and finish your analysis</H2>
<p>Now you have an Excel output. Add pivot tables to show how many potential links your target_urls can get and how many instances on what keywords crawl_url can link out.</p>

<H2>Latest update</H2>
<p>The latest update is due to Sitebulb exports now having its content scrape renamed from "content" to "Text".</p>
