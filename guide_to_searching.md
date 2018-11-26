# Guide to searching BnF Ms Fr 640

## Source Data

### XML

* As single files:
  * [Diplomatic Transcription](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/allFolios_xml/all_tc.xml)
  * [Normalized Transcription](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/allFolios_xml/all_tcn.xml)
  * [English Translation](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/txt/allFolios_xml_tl.xml)
* [Indiviudal folios](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/ms-xml.zip)
 
### "Raw" text files

* As single files:
  * [Diplomatic Transcription](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/allFolio_txt/all_tc.txt)
  * [Normalized Transcription](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/allFolio_txt/all_tcn.txt)
  * [English Translation](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/allFolio_txt/all_tl.txt)
* [Indiviudal folios](https://raw.githubusercontent.com/cu-mkp/ms-text-analysis/master/ms-xml.zip)

## Searching

### Basic: In web browser

* open any of the single file source files in web browser
* control-f to search

### Using Atom text editor

* download and install Atom text editor:
   * Download:
     * Mac: https://github.com/atom/atom/releases/download/v1.33.0-beta3/atom-mac.zip
     * Windows: https://github.com/atom/atom/releases/download/v1.33.0-beta3/AtomSetup.exe
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

### Advanced: Using Voyant Text Analysis Tools

#### Term frequency (English Translation)



<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->

<iframe style='width: 446px; height: 285px;' src='//voyant-tools.org/tool/CorpusTerms/?corpus=d7eadde0616c2a8fd8863f7a3a7ff290'></iframe>

####  Concordance (English Translation)


<!--	Exported from Voyant Tools (voyant-tools.org).
The iframe src attribute below uses a relative protocol to better function with both
http and https sites, but if you're embedding this into a local web page (file protocol)
you should add an explicit protocol (https if you're using voyant-tools.org, otherwise
it depends on this server.
Feel free to change the height and width values or other styling below: -->

<iframe style='width: 672px; height: 447px;' src='//voyant-tools.org/tool/Contexts/?query=make&corpus=d7eadde0616c2a8fd8863f7a3a7ff290'></iframe>
