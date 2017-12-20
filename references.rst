.. role:: und

.. role:: sample

.. role:: sampleb

.. role:: sampleu

.. _reference_checks:

14. References
--------------
References checks are quite complex due to high number of possible variations. Therefore, we have split reference checks into several parts:

| :ref:`Author list<reference_author_list>`
| :ref:`Citation data - in-house journals<eference_cd_house>`
| :ref:`Citation data - other journals<reference_cd_other>`
| :ref:`General checks<reference_general_check>`
| :ref:`Websites<reference_web>`
| :ref:`Books<reference_books>`

.. _reference_author_list:

14.1. Author List
=================

Author list is a list of authors in the reference. Author list should always end with period (.).

14.1.1. Check the format of author names in the author list:

	| :sample:`Lastname INIT` (where INIT is initials of the author, no more than 4 letters)
	|
	| `Examples:`
	| :sample:`Rini B`
	| :sample:`Escudier BI`
	| :sample:`Loo SCJ`
	| :sample:`Wang KHCN`

	| Please note that last names can be compound, can have prepositions, suffixes, prefixes or be mononyms. For example:
	|
	| Compound last names: :sample:`Garcia-Closas, Gomez Jimenez`
	| Last name related prepositions: :sample:`Van den Brandt, van der Ent`
	| Suffixes: :sample:`Williams 3rd, Rowland Jr`
	| Prefixes: :sample:`McCann, O'Kelly`
	| Mononym: :sample:`Govindjee`


	- Check that initials have no more than 4 letters and have **no** hyphens (-) or spaces in-between.

	- Check that mononym (names which have no initials) is “true” mononym, rather being Lastname with missed initials. Check PubMed site, if in doubt.

14.1.2. Check the format of author list. The following options are acceptable:

	| :sample:`from 1 to 14 authors`
	|
	| :sample:`from 1 to 14 authors, Group Authorship`
	|	(comma as a separator between author list and Group Authorship) 
	| :sample:`from 1 to 14 authors; Group Authorship`
	|	(semicolon as a separator between author list and Group Authorship)


	.. image:: /_static/html_author_etal_number.png
		:alt: Number of authors

	.. image:: /_static/html_group_authorship2.png
		:alt: Group Authorship

	.. image:: /_static/html_group_authorship4.png
		:alt: Group Authorship

	.. image:: /_static/html_group_authorship3.png
		:alt: Group Authorship

	| **OR**
	|
	| :sample:`exactly 13 authors, et al`
	|
	| :sample:`exactly 13 authors, et al, Group Authorship` 
	|	(comma as a separator between et al and Group Authorship)
	| :sample:`exactly 13 authors, et al; Group Authorship`
	|	(semicolon as a separator between et al and Group Authorship)


	.. image:: /_static/html_author_number.png
		:alt: Number of authors

	.. image:: /_static/html_group_authorship1.png
		:alt: Group Authorship

	|
	There can be "and" before :ref:`Group Authorship<group_authorship>`. Check that there is a separator (comma or semicolon) before "and".


	- Check that :ref:`Group Authorship<group_authorship>` is positioned at the end of author list. Other positions are not allowed.

	- Check that there is a period (.) either after the last author name (if there are less or equal to 14 authors), or after et al (if there are exactly 13 authors + et al), or after :ref:`Group Authorship<group_authorship>` (if present).

	- Author list should be formatted as plain text.

.. _reference_cd_house:

14.2. Citation Data (in-house)
=============================

.. ATTENTION::
	
	This section is applicable ONLY to in-house journals: |br|
	 **Oncotarget, Oncoscience, Aging (Albany NY), Genes Cancer**.

Citation data is a part of a reference, which contains Journal Title, year, volume, pages and doi.


14.2.1. Check that citation data has correct journal title. The following titles are allowed:

	| :sample:`Oncotarget`
	| :sample:`Oncoscience`
	| :sample:`Aging (Albany NY)`
	| :sample:`Genes Cancer`

	This is the only acceptable spelling. No variations are allowed.

14.2.2. Check that citation data has the following elements in the following order:

	| :sample:`Journal Title. year; volume: page numbers. doi.`
	|
	| `Example:`
	| Oncotarget. 2017; 8:4218–27. http://doi.org/10.18632/oncotarget.13906.
	| Aging (Albany NY). 2015; 7:609-10. doi: 10.18632/aging.100804.
	| Genes Cancer. 2010; 1:1100-14. doi: 10.1177/1947601910396213.
	| Oncoscience. 2016; 3:58-70. https://doi.org/10.18632/oncoscience.292.

14.2.3. Check the format of each element:

	+ Journal title should be followed by period (.). There should be a space after period.

	+ Year should be presented in full (4 digits) and should be followed by semicolon (;). There can be a space after semicolon (but this is not mandatory).

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


14.2.4. Check for references to articles in Advance Publications. These references can be distinguished by having full date (2016 Jul 19) instead of just year and/or having [Epub ahead of print] note (see image below).


.. image:: /_static/html_cit_dat_ahead_of_print.png
	:alt: Ahead of Print



- Check whether those references were moved from Advance Publications section to specific issue and have full-citation data available:

| Go to corresponding article page on Oncotarget site and check whether article page contains full citation-data (year; volume: pages).

	.. image:: /_static/html_cit_dat_check.png
		:alt: Advance Publications check

	|
	+ If full citation data is present, then suggest correction to include full citation-data to the reference.

	.. image:: /_static/html_cit_dat_corrections.png
		:alt: Advance Publications corrections

	**OR**


	.. image:: /_static/html_cit_dat_no_full_cit_data.png
		:alt: Full citation data

	|
	+ If full citation data is not present on article page, then leave references as it is. No action is necessary.

	.. image:: /_static/html_cit_dat_ahead_of_print.png
		:alt: Ahead of Print

.. _reference_cd_other:

14.3. Citation Data (other journals)
====================================

.. ATTENTION::
	
	This section is applicable to all journals **except for in-house journals**. 

Citation data is a part of a reference, which contains Journal Title, year, volume, pages and doi.

14.3.1. Check that citation data has the following elements in the following order:

	| :sample:`Journal Title. year; volume: page numbers. doi.` (note: doi is optional)
	|	
	| `Example:`
	| International Journal of Cancer. 2005; 115:503–510
	| Clin Microbiol Rev. 2003; 16:1-17. https://doi.org/10.1128/CMR.16.1.1-17.2003.
	| Quant Biol. 2013; 1: 115-30. doi: 10.1007/s40484-013-0012-4.

14.3.2. Check the format of each element:

	- Journal title can be abbreviated or written in full. If abbreviated, check that it is written the same way as on PubMed site. You can look up journal titles here: https://www.ncbi.nlm.nih.gov/nlmcatalog/journals

	- If both full and abbreviated title are present in the reference, then delete abbreviation and leave full title (you can spot such cases by presence of colon (:) in the title; e.g. Rapid Communications in Mass Spectrometry : RCM.)

	.. image:: /_static/html_full_journal_title.png
		:alt: Full Journal title
		:scale: 99%


	- Journal tile should be in a :ref:`title case<title_case>`.

	- Journal title should be followed by period (.). There should be a space after period.

	.. image:: /_static/html_cdo_journal_title.png
		:alt: Journal title
		:scale: 60%

	- Year shoudl be presented in full (4 digits) and should be followed by semicolon (;). There can be a space after semicolon (but this is not mandatory).

	.. image:: /_static/html_cdo_year.png
		:alt: Year
		:scale: 60%

	- Volume should be one or more digits (rarely can also contain letters) and should be followed by colon (:). There can be a space after colon (but this is not mandatory).

	.. image:: /_static/html_cdo_volume.png
		:alt: Volume
		:scale: 60%

	- Page numbers can be either in short (12063-74) of full (12063-12074) format and rarely can also contain letters. Page numbers should be followed by period (.). There should be a space after period.

	.. image:: /_static/html_cdo_pages.png
		:alt: Page numbers
		:scale: 60%

	- DOI should be present and it should not contain spaces. There are 2 allowed formats of doi:

		| https://doi.org/ ... (e.g. https://doi.org/10.18632/oncoscience.292.)
		| doi: ... (e.g. doi: 10.1177/1947601910396213.)

	- DOI should should be hyperlinked if in https://doi.org/ format.

	- DOI can be followed by period (but this is not mandatory).
	
	.. image:: /_static/html_cdo_doi.png
		:alt: DOI
		:scale: 60%

.. _reference_general_check:

14.4. General checks
====================

14.4.1. Check for duplicates in the reference list. 

If you find duplicate references, please contact the author asking to correct the reference list.

14.4.2. Check for references translated into English from other language (usually you can spot those by keywords: translation, translated from, in Chinese, in French etc). Those references should comply to the following format:

	| :sample:`Author list. [Title of the article]. [Article in Chinese]. Journal Name. 1072; 1: 1-2.` (doi is optional)
	|
	| `Example:`
	| 34. Yang XM, Yang H. [Expression of high mobility group box-1 in the lung tissue and serum of patients with pulmonary tuberculosis]. [Article in Chinese]. Zhonghua Jie He He Hu Xi Za Zhi. 2013; 36:497-500.


14.4.3. Check for references containing journal title in English and original language (e.g. "International journal of cancer" and "Journal international du cancer"). Remove title in original language and leave English version.

14.4.4. Check for extra information to the references (i.e. in addition to "standard" information). Remove all extra information.
	
	| `Example:`
	| ":official publication of the society of…"
	| "http://dx.doi.org/"

14.4.5. Remove any instances of “[Internet]”, "[pii]" and empty (blank) doi.

14.4.6. Remove “PMID” and “PMCID” details, if present in any reference.

.. _reference_web:

14.5. Websites
==============

14.5.1. There is no standard for website references. Authors are allowed to accompany a web link with any information they think appropriate. 

14.5.2. Check that website link is valid (i.e. it points to the referenced web resources, rather to error or other not relevant page).

If the link is not valid, please contact author to provide a working link.

.. _reference_books:

14.6. Books and reports
=======================

14.6.1. There is no standard for books and reports. However at least "Title, Year, (Author name for book references)" should be there. If there is any other extra information like valid links given for the same, it would be great.


.. |br| raw:: html

   <br />
