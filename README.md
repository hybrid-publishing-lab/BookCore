# BookCore
BookCore Plugin for Omeka adding a custom metadata set tailored for books

##General Description
The BookCore Plugin adds an element set "Book" to Omeka (<http://omeka.org/>) tailored for book publications and maps entries in the Book element set to the Dublin Core element set.

The plugin has been developed for and tested with Omeka 2.3.

##Install
1) Download and unzip the plugin
2) Copy the folder to the folder "plugins" in your Omeka installation on your web server.
3) Login to Omeka and activate **BookCore**

##How to Use
Once installed the **Book** element set is added to **Edit Items**. If any content is entered in any field of the Book element set all previously entered values in the Dublin Core fields are erased when saved.

The **Book** element set contains the following fields:

Title

Subtitle        => Title and Subtitle are mapped onto dc:title separated by ' : '	  

                
Author/Editor 	=> dc:creator

Publisher 			=> dc:publisher

Year Published	=> dc:date

Blurb					=> dc:description

Series			=> dc:description

Keywords			=> dc:subject

ISBN Print			=> dc:identifier amended by 'ISBN Print: '

ISBN PDF			=> dc:identifier amended by 'ISBN PDF: '

ISBN EPUB			=> dc:identifier amended by 'ISBN EPUB: '

DOI						=> dc:identifier amended by 'DOI: '

Rights					=> dc:rights

Language			=> dc:language

Type					=> dc:type

Format				=> dc:format


##License
This plugin is licensed under Apache License Version 2.0, http://www.apache.org/licenses/LICENSE-2.0.html
