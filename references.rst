14. References
--------------
Rererences checks are quite complex due to high number of possible variations. Therfore we have split reference checks into two parts:

| Author list
| Citation data - in-house journals
| Citation data - other journals
| Garbage

14.1. Author List
=================

Author list is a list of authors in the reference. Author list should always end with period (.).

14.1.1. Check the format of author names in the autor list:

	| Lastname INIT (where INIT is initials of the author, no more than 4 letters)
	|
	| `Examples:`
	| Rini B
	| Escudier BI
	| Loo SCJ
	| Wang KHCN

	| Please note that last names can be compound, can have prepositions, suffixes, prefixes or be mononyms. For example:
	|
	| Compound last names: Garcia-Closas, Gomez Jimenez
	| Last name related prepositions: Van den Brandt, van der Ent
	| Suffixes: Williams 3rd, Rowland Jr
	| Prefixes: McCann, O'Kelly
	| Mononym: Govindjee


	- Check that initials have no more than 4 letters and have **no** hyphens (-) or spaces in-between.

	- Check that mononym (names which have no initials) is “true” mononym, rather being Lasname with missed initials. Check PubMed site, if in doubt.

14.1.2. Check the format of author list. The following options are acceptable:

	| exactly 13 authors, et al.
	|
	| exactly 13 authors, et al, Group Authorship 
	|	(comma as a separator between et al and Group Authorship)
	| exactly 13 authors, et al; Group Authorship 
	|	(semicolon as a separator between et al and Group Authorship)


	.. image:: /_static/html_author_number.png
		:alt: Number of authors

	.. image:: /_static/html_group_authorship1.png
		:alt: Group Authorship

	.. image:: /_static/html_group_authorship3.png
		:alt: Group Authorship

	| OR
	|
	| less or equal to 14 authors.
	|
	| less or equal to 14 authors, Group Authorship
	|	(comma as a separator between author list and Group Authorship) 
	| less or equal to 14 authors; Group Authorship 
	|	(semicolon as a separator between author list and Group Authorship)


	.. image:: /_static/html_author_etal_number.png
		:alt: Number of authors

	.. image:: /_static/html_group_authorship2.png
		:alt: Group Authorship


	.. image:: /_static/html_group_authorship4.png
		:alt: Group Authorship


	There can be "and" before Group Authorship. Check that there is a separator (comma or semicolon) before "and".


	- Check that Group Authorship is positioned at the end of author list. Other positions are not allowed.

	- Check that there is a period (.) either after the last author name (if there are less or equal to 14 authors), or after et al (if there are exactly 13 authors + et al), or after Group Authorship (if present).

	- Author list should be formated as plain text.


14.2. Citation Data (in-house)
=============================

.. ATTENTION::
	
	This section is applicable ONLY to in-house journals: **Oncotarget, Oncoscience, Aging (Albany NY), Genes Cancer**.

Citation data is a part of a reference, which contains Jounal Title, year, volume, pages and doi.


14.2.1. Check that citation data has correct journal title. The following titles are allowed:

	| Oncotarget
	| Oncoscience 
	| Aging (Albany NY)
	| Genes Cancer

	This is the only acceptable spelling. No variations are allowed.

14.2.2. Check that citation data has the following elements in the following order:

	| Journal Title. year; volume: page numbers. doi.
	|
	| `Example`
	|
	| Oncotarget. 2017; 8:4218–27. http://doi.org/10.18632/oncotarget.13906.
	| Aging (Albany NY). 2015; 7:609-10. doi: 10.18632/aging.100804.
	| Genes Cancer. 2010; 1:1100-14. doi: 10.1177/1947601910396213.
	| Oncoscience. 2016; 3:58-70. https://doi.org/10.18632/oncoscience.292.

	- Check the format of each element:

		+ Journal title should be followed by period (.). There should be a space after period.

		+ Year shoudl be presented in full (4 digits) and should be followed by semicolon (;). There can be a space after semicolon (but this is not mandatory).

		+ Volume should be one or more digits and should be followed by colon (:). There can be a space after colon (but this is not mandatory).

		+ Page numbers can be in either in short (12063-74) of full (12063-12074) format and should be followed by period (.). There should be a space after period.

		+ DOI should be present and it should not contain spaces. There are 2 allowed formats of doi:

			| https://doi.org/ ... (e.g. https://doi.org/10.18632/oncoscience.292.)
			| doi: ... (e.g. doi: 10.1177/1947601910396213.)

		+ DOI shoud should be hyperlinked if in https://doi.org/ format.

		+ DOI can be followed by period (but this is not mandatory).

		If doi is missing, then you should chose doi format for corrections based on the format of other doi present in the article. I.e. the format of doi should be consistent across all the references in the article.

		.. image:: /_static/html_citaiton_data.png
			:alt: Citation Data


14.2.3. Check for references to articles in Advance Publications. These references can be distinguished by having full date (2016 Jul 19) instead of just year and/or having [Epub ahead of print] note (see image below).


.. image:: /_static/html_cit_dat_ahead_of_print.png
	:alt: Ahead of Print



- Check whether those references were moved from Advance Publications section to specific issue and have full-citation data available:

| Go to corresponding article page on Oncotarget site and check whether article page contains full citation-data (year; volume: pages).

	.. image:: /_static/html_cit_dat_check.png
		:alt: Adavance Publications check

	+ If full citation data is present, then suggest correction to include full citation-data to the reference.

	.. image:: /_static/html_cit_dat_corrections.png
		:alt: Adavance Publications corrections

	**OR**


	.. image:: /_static/html_cit_dat_no_full_cit_data.png
		:alt: Full citation data

	+ If full citation data is not present on article page, then leave references as it is. No action is necessary.

	.. image:: /_static/html_cit_dat_ahead_of_print.png
		:alt: Ahead of Print