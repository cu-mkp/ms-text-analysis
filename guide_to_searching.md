# Guide to searching BnF Ms Fr 640

## Source Data

### XML

* As single files:
  * [Diplomatic Transcription](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/allFolios/xml/all_tc.xml)
  * [Normalized Transcription](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/allFolios/xml/all_tcn.xml)
  * [English Translation](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/allFolios/xml/all_tl.xml)
* [Indiviudal folios](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/ms-xml.zip)
 
### "Raw" text files

* As single files:
  * [Diplomatic Transcription](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/allFolios/txt/all_tc.txt)
  * [Normalized Transcription](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/allFolios/txt/all_tcn.txt)
  * [English Translation](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/allFolios/txt/all_tl.txt)
* [Indiviudal folios](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/ms-txt.zip)

## Searching

### Basic: In web browser

* open any of the single file source files in web browser
* control-f to search

### Using Atom text editor

* download and install Atom text editor:
   * Download:
     * [Mac](https://github.com/atom/atom/releases/download/v1.33.0-beta3/atom-mac.zip)
     * [Windows] (https://github.com/atom/atom/releases/download/v1.33.0-beta3/AtomSetup.exe)
  * Installation Instructions:
     * Mac: Click on downloaded file to extract and then drag the new Atom application into your "Applications" folder.
     * Windows: Click on AtomSetup.exe. This setup program will install Atom and create shortcuts on the desktop and in the start menu.
* add a new "project" to Atom
  * `File > Add Project Folder`
  * select downloaded `ms-xml` or `ms-txt` folder
  * folder and its contents will be open in the left pane of Atom
* search across directory of folio files
  * (mac) control-select or (win) right-click `tc`, `tcn`, or `tl` folder
  * select `Search in directory`
  * enter search term(s) in box in lower right area of Atom and click Find All
  * results snippets, grouped by folio file will appear above search box
* advanced search features
  * `.*` "Regex" (Regular Expression) search
    * `*` : zero or more of preceding term
    * `+` :  1 or more of preceding term
    * `.` : any character
    * `.*` : zero or more of any character
    * `.+` : 1 or more of any character
  * `Aa`: Match case
  * `["]` : Whole word
    * "red" will match "covered" if off; only "red" if on

## Advanced: Using Voyant Text Analysis Tools

Voyant is a set of web based analysis and visualization tools for study of digital texts.

 * Guides:
   * [Getting Started] https://voyant-tools.org/docs/#!/guide/start
   * [Tools] https://voyant-tools.org/docs/#!/guide/tools
 * [Normalized French Voyant Corpus] http://voyant-test.makingandknowing.org:8888/?corpus=05909ba272f5a74e056a69ca514bd550
 * [English Translation Voyant Corpus] http://voyant-test.makingandknowing.org:8888/?corpus=57cb722a686c789f8d404324d2e4181e
 
### Term frequency

 * displays each term in "corpus" (i.e., MS translation), the number of times it occurs, and a "trend line" graph visualizing its occurrences across the entire manuscript
 * terms are ordered by frequency
 * may sort by term or by frequency
 * entering search term will prompt matching term in exact or "expanded" (e.g., including plural) form
 

<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->


#### [English Translation] http://voyant-test.makingandknowing.org:8888/tool/CorpusTerms/?corpus=57cb722a686c789f8d404324d2e4181e

<iframe style='width: 446px; height: 285px;' src='https://voyant-test.makingandknowing.org:8888/tool/CorpusTerms/?corpus=557cb722a686c789f8d404324d2e4181e'></iframe>


<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->

#### [Normalized French] http://voyant-test.makingandknowing.org:8888/tool/CorpusTerms/?corpus=05909ba272f5a74e056a69ca514bd550

<iframe style='width: 445px; height: 309px;' src='https://voyant-test.makingandknowing.org:8888/tool/CorpusTerms/?corpus=05909ba272f5a74e056a69ca514bd550'></iframe>



###  Concordance (English Translation)
 
 * displays each occurence of term in MS by "document" (i.e., folio file), in context (default 5 words left and right) 
 * terms are ordered by document/folio
 * may sort by document/folio, left context string, term, and right context string
 * entering search term will prompt matching term in exact or "expanded" (e.g., including plural) form

<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->

#### [English Translation] http://voyant-test.makingandknowing.org:8888/tool/Contexts/?query=make&corpus=57cb722a686c789f8d404324d2e4181e

<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->



<iframe style='width: 672px; height: 447px;' src='http://voyant-test.makingandknowing.org:8888/tool/Contexts/?query=make&corpus=57cb722a686c789f8d404324d2e4181e'></iframe>


#### [Normalized French] http://voyant-test.makingandknowing.org:8888/tool/Contexts/?query=make&corpus=05909ba272f5a74e056a69ca514bd550

<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->


<iframe style='width: 681px; height: 390px;' src='http://voyant-test.makingandknowing.org:8888/tool/Contexts/?query=avecq&corpus=05909ba272f5a74e056a69ca514bd550'></iframe>
