Readme File for BioEdit v7.7.1.0

BioEdit is a graphical biological sequence editor that runs on
Windows 95, 98, NT, 2000, XP, 7, 8 and 10.  The purpose of this program is 
to provide a useful molecular biology tool which can be started 
up and used easily with as little effort required as possible to 
learn the program.

***** DISCLAIMER ******

** The author makes no guarantee as to the fitness or 
suitability of this software for any purpose.  BioEdit
is offered as is and no responsibility will befall the 
author for any problems caused by or correlated with the 
use of this software, including, but not limited to, 
damages, non-suitability, misuse, data loss, or wasted time. ** 

***** By choosing to install this software you are accepting 
the terms of this license.  If you do not want to accept these
terms, you must not install the software *****
---------------------------------------------------------------------

Contents of this File:
-- Files shipped with the BioEdit v7.7.1.0 installation
-- Features included in BioEdit v7.7.1.0
-- Accessory applications included with installation.
-- Installing TreeView
-- Installing ReadSeq for 64-bit machines
-- Bug fixes/changes since last version
-- How to contact the author

---------------------------------------------------------------------

Files shipped with the BioEdit v7.7.1.0 installation:

The following files and folders are installed to the directory
in which you install BioEdit:

In installation directory:

The installation folder will also contain the following files:
	_deisreg.isr
	_isreg32.dll
	BioEdit.exe (main program)
	DeIsL1.isu
	ReadSeqv202.zip (64-bit implementation of ReadSeq sequence format converter)
	TreeV32.zip (the TreeView installation distribution)
	TreeView.txt (TreeView information)
	HttpClient.dll (required for NCBI connectivity)
	msvcr120d.dll (required for NCBI connectivity)
	license.txt (license agreement)
	Readme.txt (this file)

apps (accessory applications, Web pages and WWW bookmarks)
	accApp.ini
	blast.txt
	btblastall.exe
	blastcl3.exe
	blastcli.exe
	bookmark.txt
	cap.doc
	cap.EXE
	clustalw.exe
	clustalw.txt
	DNADIST.DOC
	dnadist.exe
	DNAML.DOC
	dnaml.exe
	DNAMLK.DOC
	DNAMLK.EXE
	DNAPARS.DOC
	DNAPARS.EXE
	DOS4GW.EXE
	fastDNAml.doc
	fastdnaml.EXE
	FITCH.DOC
	Fitch.exe
	btformatdb.exe
	KITSCH.DOC
	KITSCH.EXE
	NEIGHBOR.DOC
	NEIGHBOR.EXE
	ncbi_presets.ini
	phylip.map
	PROML.DOC
	proml.exe
	promlk.exe
	PROTDIST.DOC
	PROTDIST.EXE
	PROTPARS.DOC
	PROTPARS.EXE
	readseq.exe
	ReadSeq.txt


database (empty folder)
	

help
	BioEdit.cnt
	BioEdit.GID (not installed -- will appear after the first time help is accessed)
	Bioedit.hlp

sounds
	A small list of small sound files containing individual character reads

tables
	Bacterial_phylogeny.tab
	BLOSUM62
	BLOSUMcoloring.tab
	chao_fasman.tab
	codon.tab
	codonDegeneracyColoring.tab
	color.tab
	dayhoff
	defcolor.tab
	enzyme.tab
	GC.VAL
	gencodes.tab
	gonnet
	IDENTIFY
	kyteDoolittle.tab
	KyteDoolittleHydrophobicityColoring.tab
	ManuelRuizColorTable.tab
	match
	PAM120
	Pam250
	PAM250Coloring.tab
	PAM40
	PAM80
	SEQCODE.VAL
	taxGroups.tab
	Viral_Phylogeny.tab
	

---------------------------------------------------------------------
			
Features included in BioEdit v7.7.1.0:
 
-- An easy, graphical interface for sequence manipulation 
   and editing, modeled after SeqApp and SeqPup (Don Gilbert).
-- Variable editing options, including 'select and drag' sliding and 
   'grab and drag' sliding of residues, variable selection options, 
   mouse-click insert and delete of gaps, full column selecting, 
   on-screen editing with cut, copy and paste, and auto-scrolling of 
   edit window.
-- Anchor columns to protect aligned areas.
-- Read and edit ABI and SCF sequence files, display traces with several 
   options (reverse complement, select, copy, export, scale, zoom).
-- Print ABI files with professional-looking formatted output and file
   header information.
-- Batch conversion of ABI to SCF format sequence traces.  
-- Group sequences into groups or families.
-- Lock alignment of grouped sequences for synchronized hand alignment 
   adjustements.
-- Annotate sequences with graphical features with dynamic view in
   alignment windows including feature anntation information tooltips. 
-- Lock sequences to prevent accidental edits.
-- Specify characters to be considered valid for calculations in amino acid 
   and nucleotide sequences.
-- Sort sequences by name, LOCUS, DEFINITION, ACCESSION, PID/NID, REFERENCES,
   COMMENTS or by residue frequency in a selected column. 
-- Verbally read back sequences in single sequene editor to verify hand-typed
   sequence entries.
-- Configure accessory application interfaces to run external analysis 
   programs through a graphical interface created by BioEdit.  
   Automatically feed information to and retrieve files from external apps.  
   External apps run in a separate thread to allow simultaneous use of BioEdit 
   while running time-consuming processes.  Output from an external program 
   may be automatically opened by another program.
-- Split window for simultaneous editing of two different places in the same 
   file.
-- Merge alignments through a reference sequence.
-- Append one alignment to the end of another.
-- View phylip trees, manipulate nodes, and print trees.
-- Configure your own menu shortcuts for alignment windows.
-- Block copying of residues to clipboard allowing for pasting of full 
   alignments or parts of alignments into a word processor.
-- Basic sequence manipulations (copy/paste of sequences between documents, 
   translation and degenerate encoding, RNA->DNA->RNA, reverse/complement, 
   upper/lowercase).
-- Multiple document interface  (Maximum of 20 open alignment documents at a 
   time, but no set limit on other open windows).
-- Plasmid Drawing and graphical annotation
-- Dynamic memory allocation with support for up to 20,000 sequences per 
   document. Sequences up to 4.6 million bases (the E. coli genome) and 
   alignments >6000 seqs (the prokaryotic 16S rRNA alignment) have been tested.
-- Open and save large alignment files quickly with the BioEdit Project binary
   file format.
-- Formatted translations of nucleic acid sequences with codon usage summary, 
   choice of one- or three-letter amino acid codes, translation of selected
   region only of nucleic acid, and choice of start/stop codons 
-- Six-Frame translation of nucleic acid sequences into Fasta-format ORF lists.  
   Tested by successfully translating entire E. coli genome (4.6 Mbases) into 
   10,125 sorted raw codon stretches of 100 or more amino acids and 39,880 
   unsorted raw codon stretches of 50 or more amino acids. 
-- Amino acid and nucleotide composition analyses and plots
-- Align protein-encoding nucleic acid sequences through amino acid translation.
-- ClustalW multiple sequence alignment (interface internal, external program by 
   Des Higgins et. al.) with auto-update of aligned protein full titles and 
   GenBank field information, as well as nucleotide coding sequence when aligned 
   from a protein view of nucleotide sequences. 
-- Protein hydrophobicity/hydrophilicity plots
-- Protein hydrophobic moment matrices calculated from 0-180 degrees
-- Full choice of system fonts now available in edit window
-- 'Revert to Saved' and 'undo' functions. 
-- Edit both amino acid and nucleic acid sequences.
-- Easy point-and-click color table editing, with different tables for protein 
   and nucleic acid sequences.
-- Alignment-responsive shading based on information content of alignment positions.
-- Identity / Similarity shading in alignment window with user-defined threshold.
-- BioEdit currently reads and writes BioEdit, GenBank, Fasta, NBRF/PIR,  
   Phylip 3.2 and Phylip 4 formats.
-- Additionally reads (but does not write) Clustal and GCG formats
-- Autodetect of sequence format -- just double click the file and go!
-- Open and import sequences and alignments in any compatible format right
   from the clipboard
-- Import/Export filter for 10 additional formats (Using Don Gilbert's ReadSeq).
   ReadSeq auto-detects the sequence format as well -- 64-bit port by Mathew D. Pagel
-- Import/Append one file on to the end of another (regardless of file format).
   Import also auto-detects format
-- Basic rich-text editor.
-- Restriction mapping with any or all-frames translation, multiple enzyme and 
   output options and circular DNA option.  Manually choose custom lists of enzymes
   for restriction maps
-- Choose restriction enzymes by manufacturer
-- Auto-linking to your favorite Web Browser (e.g., Netscape or Internet Explorer).
-- World Wide Web Bookmarks 
-- NCBI BLAST tools, including BLAST 2.0 Internet client and local BLAST with 
   the ability to compile local databases from Fasta files
-- Configurable formatted text print with dynamic print preview,
-- Configurable formatted shaded graphical output with dynamic preview, identity 
   and similarity shading, and ability to cut and paste directly to 
   graphics/presentation program for generation of figures.
-- Rich text export of formatted, shaded alignment.
-- RNA secondary structure comparative analysis tools, including covariation, 
   potential pairings, and mutual information analyses.
-- 2-D matrix plotter for mutual information output with dynamic data viewing 
   with the mouse pointer. (Also allows image copy/paste and bitmap save).
-- View sections of very large matrices with plotter (tested on up to 5183x5183 
   matrix = 180 Mb file)
-- Paste over sequence blocks and sequence titles\
-- Search and replace in titles with wildcards
-- Store taxonomy inforation for sequences and map taxonomies directly from master 
   taxonomy tables
-- Retrieve sequences and sequence-associated pubmed references directly from the WWW.

---------------------------------------------------------------------

Accessory applications included with this installation 
(preconfigured for use with BioEdit):

	
	blastall     -- Authors: Stephen Altschul, Warren Gish, Webb Miller, 
                               Eugene W. Myers and David J. Lipman 
	blasctcl3    -- Authors: Stephen Altschul, Warren Gish, Webb Miller, 
                               Eugene W. Myers and David J. Lipman 
	CAP          -- Author:  Xiaoqiu Huang
	ClustalW     -- Authors: Des   Higgins, Toby  Gibson, Julie Thompson.
				Rebuilt by Tom Hall (main code not modified) to run 
				under Windows XP)
	DNAdist      -- Author:  Joe Felsenstein
	DNAml        -- Author:  Joe Felsenstein 
	DNAmlk       -- Author:  Joe Felsenstein
	DNAPars      -- Author:  Joe Felsenstein
	FastDNAml    -- Authors: Gary J. Olsen, Hideo Matsuda, Ray Hagstrom, 
                               and Ross Overbeek 
	Fitch        -- Author:  Joe Felsenstein 
	formatdb     -- Authors: Stephen Altschul, Warren Gish, Webb Miller, 
                               Eugene W. Myers and David J. Lipman 
	Kitsch       -- Author:  Joe Felsenstein 
	Neighbor     -- Author:  Joe Felsenstein
	Proml        -- Author:  Joe Felsenstein 
	Protdist     -- Author:  Joe Felsenstein 
	Protpars     -- Author:  Joe Felsenstein 
	readSeq      -- Author:  Don Gilbert, 64-bit port by Mathew D. Pagel
	TreeView     -- Author:  Roderic D.M. Page

If distribution of any of these programs becomes a problem, any or all may have 
to be removed in future releases.  However, the BioEdit configuration interface 
makes it relatively easy to add applications to the BioEdit Accessory Applications 
menu.	 

---------------------------------------------------------------------
Installing TreeView:

TreeView is a phylogenetic tree viewing program written by Roderic 
D.M. Page.  Previous versions of BioEdit included a distribution of
the TreeView executable and supporting libraries in the apps folder.  
At the request of the author full TreeView installation is now 
distributed with BioEdit.  This installation is contained within the 
file called TreeView.zip.

To install TreeView, unzip the file to a temporary directory, then run
the program called "setup.exe" which will be created.  TreeView will 
install itself on your system.

To configure TreeView to run through the accessory apps menu of BioEdit, 
choose Add/Remove/Modify an Accessory Application from the Accessory 
Application menu.  In the "Name of Accessory" box, type “TreeView”.  
Press "Specify" next to the “Program” Box and browse to the new location 
for the TreeView.exe program.  Check the box called “Prompt for input
file”.  In the “General Description” box, type “TreeView version 1.5.2.  
Copyright Roderic D.M. Page, 1998. r.page@bio.gla.ac.uk. 
http://www.taxonomy.zoology.gla.ac.uk/rod/rod.html” without any carriage 
returns.  Then press “Add / Modify” at the bottom of the dialog.  Upon 
closing the window, you will be prompted to have BioEdit close and restart.  
For more information on installing accessory applications, see Configuring 
and Using External Applications in the BioEdit on-line help.


Note For Windows 7, 64-bit users of TreeView:
The version of TreeView distributed with BioEdit will not work correctly.  
Rod Page offers an updated version of TreeView at
http://darwin.zoology.gla.ac.uk/~rpage/treeviewx/download.html
that does work well on this platform. To install this version such that 
it works with pre-configured Phylip accessory apps within BioEdit, it is 
best to override the default installation directory when installing 
TreeViewX to C:\Program Files\Rod Page\TreeView.&nbsp; You can then either 
1.) Change the name of the file C:\Program Files\Rod Page\TreeView\tv.exe to 
C:\Program Files\Rod Page\TreeView\treev32.exe or 2.) modify accessory 
application configurations to point to C:\Program Files\Rod Page\TreeView\tv.exe.

---------------------------------------------------------------------

Installing ReadSeq for 64-bit machines:
Don Gilbert's original readSeq sequence converter was a 16-bit application and
does not operate on 64-bit Windows machines, even in compatibility mode.  
Mathew D. Pagel has produced a Java-based port readSeq that worked flawlessly when
I tested it.  The original distribution of version 2.02 from 
https://code.google.com/p/readseq/downloads/detail?name=ReadSeqv202.zip&can=2&q=
is included in the BioEdit installation with the author's permission to allow users
to install a compatible version of readSeq if they wish.  Follow the instructions in
the file "Instructions.txt" found in ReadSeqv202.zip within your BioEdit installation
directory after installing BioEdit to install the updated port of readSeq.

---------------------------------------------------------------------

BioEdit has not been regularly maintained for several years, however, a few 
updates have been made simply to keep the program generally functional.
The following list is not complete because the time has not been available to 
adequately keep track. The help file has not been updated to reflect most changes:

Since v7.2.6:
-- Rebuilt program to restore Ctrl+Right click functionality for reference sequence choice.

Since v7.2.4:
-- Added functionality for https to fix download of sequence data from NCBI.

Since v7.1.11:
-- The dot-plot feature for pairwise sequence comparison was brought back by request from   
   a user (Under Sequence->Pairwise alignment->Dot Plot (pairwise comparison).
-- Taxonomy mapping from sequence title was brought back under Sequence->Phylogeny / 
   Taxonomy->Extract Taxonomy->(three mapping options).  Only bacterial and viral
   taxonomies are supported by default, but a custom table can be made by opening the file 
   <BioEdit>\tables\ Bacterial_phylogeny.tab or <BioEdit>\tables\ Viral_Phylogeny.tab, 
   copying the contents into MS Excel, and creating a custom table according to the same
   general template, then saving the custom file as a tab-delimited file.  If time permits,
   an auto-map of taxonomy from NCBI may be added in the future for convenience.
-- A preferences option to not write to C:\Windows\ncbi.ini when performing BLAST-related
   functions was added to work around the error received by users without read/write access
   to the C:\Windows directory.  This may mean one needs to manually create ncbi.ini within
   C:\Windows as a one-time event (or have the IT department do it for those without access
   privileges on the computer.

Since v7.0.9:
-- The pairwise alignment function was fixed to agree with examples in the help 
   documentation.
-- Right-click context menu added to title panel in sequence document.
-- Support for local BLAST and accessory application launching fixed in 
   Windows 7 64-bit version.
-- GenBank sequence retrieval updated.
-- String-to-floating point number conversion problems (hopefully) fixed for 
   European computers with particular regional settings.
-- Single-sequence translation in selected frames with codon usage reporting 
   was fixed.  There was a memory bug when translated sequence was not an exact 
   multiple of three in length.
-- Associating a phylogenetic tree with an alignment from the phylogenetic tree view 
   was fixed.
-- Six-frame translations were fixed to allow producing ORF lists from multiple 
   sequences at once.
-- Added option to save six-frame translations to a file rather than loading 
   directly into text editor.


The following changes and/or fixes have been made since version v7.0.8:
-- The restriction map utility was fixed.  It was broken by the relocation 
   of the BioEdit.ini file to the program install directory.
-- An option was put into the preferences to allow temporary redirecting 
   of file paths for blast database creation and search execution to the 
   root directory.  The reason for this is that if the name of the database 
   directory (when doing a search) or source directory for a fasta file 
  (when converting to a blast database) is too long, it can overload the 
   maximum command line length for running blastall.exe or formatdb.exe
   (the NCBI command-line programs used for blast utilities).
   

The following changes and/or fixes have been made since version v7.0.7:
-- Moved BioEdit.ini to the program current run directory.  Hopefully this will 
   help on computers without write access to the system folder.

The following changes and/or fixes have been made since version v7.0.5:
-- Updated NCBI sequence retrieval to deal with recent changes at NCBI that broke the sequence retrieval functions in the 
previous version.
-- Note:  (not a change, per se):  Scoring in pairwise alignment functions does not agree with the example in the help 
document.  This will be investigated if/when I  have time.  I had considered removing the functions, but decided no to on 
the grounds that they generally work OK for quick manipulations and can be useful as a  time-saving utility.  They should 
not, however, be used as a teaching tool.

The following changes and/or fixes have been made since version v7.0.4:
-- Changing proxy setting for sequence retrieval from GenBank had no 
   affect because the routine was looking in the wrong directory for the
   BioEdit.ini file.

The following changes and/or fixes have been made since version v7.0.3:
-- A bug in sequence retrieval from GenBank fixed that caused retrievals 
   to come back saying " ... format unrecognized".

The following changes and/or fixes have been made since version v7.0.2:
-- A memory bug in RNA covariation routine was fixed.

The following changes and/or fixes have been made since version v7.0.1:
-- The blast programs blastall and formatdb were modified to allow passing
   parameters in a file as well as on the command line to get around the 
   Windows xommand line length limit
-- blastall and formatdb were modified to allow passing a darabase name
   with spaces (original verion tries to parse the name into multiple
   file names)
-- When launching an alignment file from the Windows Explorer, BioEdit now
   tries to open the file in an existing BioEdit instance if there is one
   open, rather than opening a new one.
-- Updated installer will hopefully take care of the trouble some people 
   have been having installing BioEdit 

The following changes and/or fixes have been made since version v7.0.0:
-- The optimal pairwise alignment routine was inadvertently overwritten 
   with a test version that was only functional on nucleic acid sequences.  
   This caused pairwise alignment on amino acid sequences to fail.  
   The original alignment method was put back.

The following changes and/or fixes have been made since version v6.0.7:
-- Documentation (online help file) was updated for the first time 
   since version 5.0.6.
-- Automatic links to NCBI BLAST via the World Wide Web were added back 
   with current NCBI pages with editable addresses.
-- Error on doing local blast searches when swap directory contained 
   spaces fixed.  However, BLAST won't work if entire command line is 
   too long for Windows, so keeping the BioEdit swap directory in a 
   path name as short as possible (e.g. C:\BioEdit\Temp) is a good idea.
-- Some context-sensitive help added (not complete).
-- Fixed bug in graphic view that caused Error when view is plotted in
   dot conservation mode and the "reference" sequence is shorter than
   one of the alignment sequences.
-- Fixed a bug in floating point conversion with non-English regional
   settings (when a ',' is used as decimal separator) that would cause
   an error when trying to translate nucleotide sequences into protein 
   (bug manifested when reading in the "codon.tab" file and converting
   frequency numbers -- the regional settings were not being detected
   properly).
-- Added support for mouse wheel in Alignment document window.  Clicking
   the mouse wheel button toggles between vertical and horizontal scroll
   function.
-- Fixed bug in right-click-based gap deletion in grouped sequences with
   group-locked alignment status (gaps were being deleted only for edited
   sequence and no entire locked group).
-- A couple of other bugs relating to adding or deleting gaps around a 
   residue with the right mouse button in a sequence which is a member 
   of an alignment-locked grouped were fixed.  Behavior was updated to 
   only operate upon sequences that are not grouped together in an 
   alignment-locked group with the sequence in question.
-- Fixed bug in clustal auto-link that caused VERSION field to be lost
   in aligned sequences.
-- Removed the sort function "selected sequences by residue frequencies"
   This was a one-time utility that does not work as the title implies and
   was not supposed to be present in the public version.
-- Removed "Group top-down by identical sequences" under Sort menu.  This
   function did not make much sense for most contexts.

The following changes and/or fixes have been made since version v6.0.6:
This is a list of counterintuitive changes to deal with a set of 
counterintuitive features in the short term

-- Removed automatic taxonomy mapping support -- its undocumented and caused 
   confusion.
-- Removed primer pair/oligo mapping and Tm calculation -- undocumented and 
   caused confusion.
-- Removed query functions for sequence features -- again, undocumented and 
   caused confusion.

The following changes and/or fixes have been made since version v6.0.5:

-- Removed "Auto-update View Options" because it causes long delays in 
   Win2000 and XP.
-- Fixed a bug in Graphic View new to v6.0.5 causing access violation 
   if View Features mode is on in document window.

The following changes and/or fixes have been made since version v5.0.9:
Note that this list is not complete:  
-- Some memory troubles with grouped sequences fixed.  Using sequence 
   groups is now more stable.
-- Access violations when deleting sequences in dot conservation mode 
   or vertically scrolling very long alignments in dot conservation mode 
   fixed.
-- Retrieve sequences directly from GenBank over the WWW.
-- Automatically retrieve GenBank info from GenBank for existing
   sequences for Genbank-fasta formatted titles
   (eg. gi|16082679|ref|NC_003132.1|).
-- Automatically retrieve Pubmed references for GenBank sequences.
-- Restriction on number of sequences removed.  All memory allocation
   for sequences was made dynamic.
-- Paste over sequence blocks to quickly create subalignments based upon
   a region of a larger alignment or produce alignment concatenations. 
-- Paste over titles, and paste onto (concatenate to) titles.
-- Copy sequence titles added in a couple of variations.
-- Copy nucleic acid sequence blocks in reverse complemented orientation
-- Copy sequences in a tab-delimited format (for pasting into a 
   spreadsheet)
-- Find/replace function for sequence information
-- flexible find/replace in titles with indexed wildcards
-- filter leading and trailing characters off of sequence titles.
-- Find titles equal to, beginning with, or containing lists of strings.
-- Unique based upon sequences or title with a two-step sort + select 
   & delete process to remove redundant sequences or titles
-- Query sequences by data by TITLE, LOCUS, DEFINITION, ACCESSION, 
   VERSION / GI, PID (or SID), DBSOURCE, KEYWORDS, REFERENCES, FEATURES, 
   COMMENT, and/or Phylogeny.
-- Invert selection of sequences or residues
-- Edit information for multiple sequences at once with Sequence-->Edit
   all selected.
-- Extract subsequences (including orientation for DNA) from lists of
   coordinates (with choice of alignment-gapped or true positions) 
-- Query and extract annotated sequence features.
-- Map true positions from lists of alignment positions.
-- Add tabulated taxonomy information to sequences.
-- Several variable ways of renaming titles in batch mode 
   (Sequence-->Rename-->...)
-- Several ways to filter out sequences based upon inclusion/exclusion
   of specific characters, length, or number of leading, trailing, or 
   total gaps.
-- Sort by phylogeny
-- Invert current sequence order
-- Map oligos and primer pairs to alignments based upon mismatch threshold
-- Calculate DNA oligo Tm's with mismatches based upon thermodynamic
   parameters from John SantaLucia's lab.
-- Calculate Tm's for oligos and compare them to same region of other 
   sequences from alignment window using right mouse button clicks.
-- Several operations on local sequence region selection with right 
   mouse button click.
-- Speed enhanced on pairwise alignment of large similar sequences
-- Align sequences to an existing alignemnt by pairwise alignment to
   phylogenetic near neighbor in existing alignment.
-- Choose individual restriction enzymes when creating a restriction map.
-- Easily flush an alignment out with gaps to produce a rectangular matrix
 
The following changes and/or fixes have been made since version v5.0.8:
-- Made a minor adjustment to preferences for characters to be treated
   as resides -- There's an option to either include them as positions
   or ignore them completely fro similarity/ID shading.
-- Fixed a bug in pasting into the single sequence editor window.

The following changes and/or fixes have been made since version v5.0.7:
-- Protein alignments in new installations may have shading problems
   because when the option to explicitly specify all characters to be
   considered valid for calculations (including ID/similarity shading),
   'N' was accidentally missed for amino acids.  Several installations 
   probably have gone out with 'N' missing from the list of amino acids.
   This can cause protein alignments to have similarity/identity shading
   errors.  'N' has been put back into the default.
-- Access violations that could occurr when typing in an RNA structure 
   mask while in RNA base pair coloring mode, and when there is a non-
   symmetric number of openeing vs. closing brackets.  This has been 
   fixed.

The following changes and/or fixes have been made since version v5.0.6:
-- Added base pair mask support for RNA alignments
-- Added base-pair coloring for RNA alignments with user-defined color
   scheme
-- Fixed bug in creating local Blast databases from within a sequence
   document

The following changes and/or fixes have been made since version v5.0.5:
-- Added support for phylogenetic trees without distance information.
-- Added save function for phylogenetic trees.
-- Added linking of phylogentic trees to an alignment.
-- Multiple trees may be imported from one or several files.
-- Incorporated phylogentic trees are saved with alignment in BioEdit
   alignment format.
-- Added option to view trees with or without distance information.
-- Updated sequence label editing to allow spaces in comments.

The following changes and/or fixes have been made since version v5.0.4:
-- Added node flipping to phylogenetic tree viewer.
-- Added printing to phylogenetic tree viewer.
-- Fixed bug in the "append alignments" (the first alignment was
   appended to itself) -- bugged version was only out for one day. 

The following changes and/or fixes have been made since version v5.0.3:
-- Fixed some issues with accessory app linking (problems keep creeping
   up related to the change made in version 5.0.0 to specify a swap folder
   for temp files).
-- Added the option to merge alignments by appending one alignment to the
   end of another.
-- Added a ruimentary tree viewer (VERY unfinished -- only reads phylip
   trees, only in "phylogram" view, no distance ruler yet, no print, 
   save or manipulate yet) -- The reason for having an internal tree
   viewer is to in the future allow flipping of nodes and resaving the 
   tree for use in nicer tree viewing programs like TreeView that allow
   better formatting, but don't have manipulation options.  Also, it 
   would be nice in the future to directly link phylogenetic tree views
   to alignment files for quick phylogeny reference.

The following changes and/or fixes have been made since version v5.0.2:
-- Added column anchoring to protect areas that are already aligned.
-- Updated translation toggling so that gaps that are expanded back
   from a single gap (when toggling from a protein view to a 
   nucleotide view) are always "locked" (to avoid problems with 
   inadvertently crunching off-screen gaps that spuriously toggled
   back as "unlocked" when aligning by hand).
-- Fixed a bug that caused RNA covariation, potential pairings, or
   mutual information analyses to crash when "mask numbering" was
   chosen but there was no numbering mask specified.
-- Fixed newly introduced bug the caused MI Examiner to crash when
   no masks are specified.

The following changes and/or fixes have been made since version v5.0.1:
-- Updated Mutual Information Examiner to handle lists of positions.
-- Added several options to Mutual Information preferences to allow 
   variable display of list information in MI Examiner.
-- Added option to export and import color table files.
-- Fixed a bug that caused color table to lock sometimes.
-- Added option to toggle translations using the current selected residue
   as a reference frame.
-- Fixed a bug that caused document to appear hung when sort by base
   frequency was chosen without a selected column.
-- Added ability to sort by selected range of residues.
-- No longer append sequence lengths to titles when saving Fasta files.
-- Added preference (on "General" tab) to require verification for 
   revert to saved function.
-- Fixed problem with creating Local Blast databases which would occur 
   on machines with no NCBI tools installed. 
-- Accessory apps and Blast Internet client are now launched through 
   an auto-generated batch file.


The following changes and/or fixes have been made since version v5.0.0:
-- Added the option to specify user-defined temp (swap) directory for all
   temporary files and user-defined BLAST database directory so that 
   BioEdit may be used from a drive space that does not allow writing 
   (actually added to v5.0.0 a few days before 5.0.1 came out).
-- Fixed some bugs associated with running accessory apps from version
   5.0.0 after the temp directory option was added. 

The following changes and/or fixes have been made since version v4.8.10:
(Probably missed a few -- I hadn't updated this file for a while)
-- Added options to specify which characters in nucleic acid and amino 
   acid sequences are considered to be valid for calculations.
-- Added options for sorting sequences by title, LOCUS, DEFINITION, 
   ACCESSION, PID/NID, REFERENCES, COMMENTS and residue frequency in
   a selected column.
-- Added options to annotate sequences with graphical features, using the 
   standard GenBank FEATURES tags as the standard for keeping track of 
   annotation "type", but allowing full user control over feature names,
   descriptions, colors, shapes and positions.
-- Added function to automatically annotate graphical features using 
   existing GenBank FEATURES field
-- Added options for grouping sequences into groups or families, with 
   user-defined coloring of grouped titles and the option to lock the
   alignment of grouped sequences to allow synchronized hand alignment
   adjustments between grouped and locked sequences.
-- Added option to lock individual sequences to prevent accidental edits.
-- Updated the BioEdit file format to save graphical annotations, sequence
   group information, locked sequence information and positional flags.
-- Added function to update previously saved BioEdit plasmid maps with a
   new restriction enzyme file when the ReBase file is changed (changing 
   the enzyme.tab file can cause mis-indexing of restriction enzyme sites
   in existing plasmid files).
-- Updated shaded graphic view to correctly do conservation (dot) view 
   when that view mode is selected in the alignment window (no longer need
   to create a new dot-plotted alignment and any sequence can be used as the
   reference rather than just the top sequence).
-- Added a "Overwrite" and "Insert" modes to both on-screen and single-
   sequence editor sequence editing.
-- Updated local BLAST interface to feed multiple sequence automatically for 
   a batch job, and to allow specification of a permanent file output and 
   the option to open output automatically in the BioEdit text editor or not. 
-- Modified some menus (Edit and Sequence menus, mainly).  The same options 
   (and more) are still there, but submenus having been created to group 
   certain related functions including: gap-realted functions, pairwise 
   alignment functions, simple manipulations (reverse, uppercase, lowercase,
   remove numbers), and search functions.
-- The "No BLAST" version (BioEdit without local BLAST packaged) was done
   away with -- it's too much of  pain to duplicate everything but one extra
   function and make a whole independent installation when relatively few
   people download that one anyway).
-- At the last minute -- added an option to verbally read back sequences 
   (protein, nucleic acid, or anything else) to verify hand-typed sequence
   entries.
-- The docuentation update is NOT yet completed, but is underway.  Program
   documentation is still stuck at version 4.7.8.


The following changes and/or fixes have been made since version v4.8.9:
-- Fixed the (re-introduced) bug that caused floating point number
   formatting error when translating nucleic acid sequences on non-US
   regional settings machines
-- Fixed a couple of bugs that affected reading in of sample name and 
   version on ABI 310 files

v4.8.8 -- forgot to document changes

The following changes and/or fixes have been made since version v4.8.7:
-- Removed the internal web browser
-- Fixed a bug in codon frequency reporting (nucleotide translations)
   that caused floating point numbers to sometimes get jumbled up in 
   the output
-- Added a conservation plot toggle to the main alignment window with
   the option to choose the character to draw for a "conserved residue"
   (the "reference" sequence defaults to the first sequence in an 
   alignment -- RIGHT-CLICK the mouse over any sequence to change it to
   the current reference sequence for this view option)
-- Fixed a minor bug in setting of custom menu shortcuts for alignment
   documents.  The "Import from clipboard" should now work with a 
   user-defined menu shortcut.

The following changes and/or fixes have been made since version v4.8.6:
-- Added optimal pairwise alignment routine with a summary of percent
   identity and similarity (multiple choices for scoring matrix for 
   amino acid alignment, user-defined gap initiate, gap extend and
   nucleotide match parameters, and option for global alignment or
   alignment allowing ends to slide over each other).
-- Added routine to create an alignment that plots all residues that are
   identical to the top sequence in an alignment as a dot.
-- Added a cheap version of a dot plotter for plotting matrix similarity
   between two sequences -- total sequence length product cannot exceed 
   2000 x 2000, however, so it's not useful for genome comparisons or 
   or even moderately large sequences.
-- Added option to calculate the similarity and/or identity between
   two sequences as they are aligned.

The following changes and/or fixes have been made since version v4.8.5:
-- 3/10/2000 -- added NCBI blastcl3 to distribution and added a more
   versatile linking interface for the BLAST client -- the old 
   BLAST client 2 has apparently been disabled
-- 3/10/2000 -- Added block convention to user-defined motif search.  
   [] brackets indicate ambiguous residues and {} brackets indicate
   exclusions (eg [LIV] will accept 'L', 'I' or 'V', whereas {LIV} will
   accept anything BUT 'L', 'I' or 'V'.
-- 3/10/2000 -- Fixed bug that caused an error and a blank doc to be 
   opened when the alignment control bar was hidden
-- 3/10/2000 -- Fixed a couple of bugs related to reading and writing
   of GenBank files (lines beginning with numbers were truncated and 
   manually updating fields sometimes resulted in misformatting) 
-- Added an alignment merge funcion which merges two alignments based 
   upon a standard common to both alignments
-- Added batch export of ABI raw trace data.
-- Fixed the recently introduced disabling of the ABI/SCF trace print
   option
-- fixed metafile copy and print of reverse-complemented traces
-- improved default scaling of SCF traces for printing and metafile copy
-- fixed bug in graphic view which could affect first time use of 
   the graphic view when used with non-US Windows regional settings 

The following changes and/or fixes have been made since version v4.8.4:

-- 1/28/2000 -- Fixed bug that came out when creating a mask (must have 
   been introduced in version 4.7.8).  This bug caused two masks to be
   formed and sequence memory for the first two sequences to get 
   cross-linked. (caused by accidentally re-assigning a memory pointer
   rather than an entire data structure).
-- 1/25/2000 -- Fixed bug introduced with the last bug fix that causes 
   name mangling of ClustalW 1.4 output and loss of GenBank info when
   running ClustalW 1.4 (the version distributed with BioEdit).
-- Fixed potential bug that comes out if you replace the clustalw 1.4
   (the version distributed with BioEdit) with clustalw 1.8 in the 
   apps folder -- clustalw 1.8 will rearrange the order of the input 
   sequences, causing sequences and titles to become scrambled in the 
   new alignment -- this has been fixed.
-- Added raw data view and analyzed and raw data export from .abi trace 
   files.
-- Added option to change starting point of ruler bar in alignment window. 

The following changes and/or fixes have been made since version v4.8.3:

-- 12/20/1999 -- Added helical wheel diagrams for proteins.  Select a 
   protein or portion of a protein and choose Sequence->Protein->Helical
   Wheel Diagram
-- Fixed bug in accessory app launching that causes spaces to be lost in
   command prefixes for inputs and checkboxes
-- Added option to accessory app launching to auto-feed sequences in 
   separate files (eg, for Lalign from the Fasta package)

The following changes and/or fixes have been made since version v4.8.2:

-- 12/13/1999 -- Fixed bug in hydrophobic moment profiles -- had an 
   exponent missing in Fourier equation 
-- 12/13/1999 -- Added hydrophobic moment matrix plots (0-180 degrees)
-- 12/13/1999 -- fixed a couple of bugs in trace viewer that caused 
   problems with non-U.S. regional settings
-- 12/10/1999 -- Added support for SCF version 2.00 files

The following changes and/or fixes have been made since version v4.8.1:

-- 12/7/1999 -- Fixed problem of accessory application info getting 
   overwritten when a full install is done with a new BioEdit version
-- Added options to accessory application interface:
    1.  Bypass interface when running an accessory
    2.  Link output(s) of one accessory to another/other accessory(s)
    3.  Create accessory app links that are only called by other accessory
        links and do not show up on accessory app menu
    4.  Automatically truncate titles to 10 characters for programs
        that don't accept long names and/or change spaces to '_'
    5.  Rename redundant sequence names and generate a report file
        specifying title changes

The following changes and/or fixes have been made since version v4.8.0:

-- 12/2/1999 -- Fixed a bug in accessory application launching that could
   cause a memory error when running an app from a window that is not a 
   sequence alignment document
-- 12/1/1999 -- Fixed on-screen title editing so that double-clicking
   on a selected title still opens the sequence editing box and overrides
   title editing
-- 12/1/1999 -- Added option to disable on-screen editing 
-- 12/1/1999 -- Fixed bug in consensus sequence generation. A consensus
   generated from less than all of the sequences in an alignment was using
   frequencies calculated using the total number of sequences rather than
   the selected number
-- 12/1/1999 -- Fixed bug that caused an access violation when 
   re-activating a document that had sequences deleted (introduced with
   version 4.7.8)
-- A bug was fixed that caused a memory mix-up when pasting sequences in
   a document in a position other than the end

The following changes and/or fixes have been made since version v4.7.9:

-- Added support for SCF sequence trace files
-- Added horizontal and vertical zoom controls to sequence trace form
-- Added crosshairs with trace position reporting in trace form
-- Added batch conversion of ABI files to SCF format
-- Traces draw faster on the screen
-- Fixed another bug in on-screen sequence title editing (when vertical
   bar was scrolled, it was causing trouble with the identity of the 
   edited title)

The following changes and/or fixes have been made since version v4.7.8:

-- Fixed bug in local BLAST linking that caused failure when operating
   from a directory with a space in its name and using a mtrix other than
   Blosum62
-- Fixed a similar bug in linking to ReadSeq for importing and exporting 
   of extra file formats
-- Added "Import from Clipboard" and "New from Clipboard" functions under
   the file menu -- Clipboard contents are treated exactly like a file and
   automatic linking to ReadSeq for importing formats that BioEdit does not
   internally read is maintained
-- Added function for inserting multiple gaps at selected residue positions
   or at specified position in selected sequences
-- Updated on-screen title editing -- use the arrow keys to scroll up and 
   down when changing several titles in the same document
-- Fixed a bug in plasmid drawing that caused a floating point error when 
   adding a very short feature to a circular plasmid


The following changes and/or fixes have been made since version v4.7.7:

-- Bug that caused edits to sequence titles to also be inserted at cursor
   position when in Edit Residues mode was fixed on 11/17/99 (also caused
   a problem when using alt+ keystrokes to access menus in Edit mode)
-- User-defined motif search function added for amino acid, nucleic acid,
   or simple text.
-- Memory allocation for sequences changed to use less memory (memory was
   being allocated to set aside space for 20,000 sequence structures 
   regardless of the number of sequences in a file -- now a single pointer 
   is set aside for the max number of allowed sequences (20,000), but no
   memory is allocated until a sequence is created)
-- Bug in ABI trace reader was fixed that caused trace / nucleotide colors
   to be mismatched when the file contained an order other than "GATC"
-- The online help and printable documentation were updated on 11/8/1999


The following changes and/or fixes have been made since version v4.7.6:

-- ABI files may be edited and saved, and edited sequence may be reverted
   to the original, non-editable version.  The edited sequence is opened
   as a sequence/alignment doc upon opening an ABI file.
-- Extended capabilities of restriction mapping module.  Long sequences
   may be mapped (tested up to 1.75 Mb on machine with 128 Mb RAM).  My
   mapping procedure is pretty slow, but 500,000 bp runs in ~2 minutes 
   on a 366 MHz Celeron).  Progress indicators added for long sequences.
-- Added local BLAST interface to main program interface (rather than 
   just in sequence/alignment docs)
-- The paste in the sequence edit box that caused it to go very slow 
   with long sequences has been fixed (>500,000 residue pasting is no
   longer a problem). 

The following changes and/or fixes have been made since version v4.7.5:

-- Fixed bug in link to ReadSeq that caused it to fail with long file
   names. 
-- Added Read-in filter for GCG format
-- fixed small glich in sequence spacing control placement

The following changes and/or fixes have been made since version v4.7.4:

-- Fixed a few leftover bugs in the graphic shaded views (mostly spacing)
-- user control over vertical spacing of sequences
-- Added view of similarity scoring matrix files from doc windows
-- edit titles on screen (highlight a title, then click it again)
-- Fixed bug in local blastp -- matrix choices other than BLOSUM62 
   should work now

The following changes and/or fixes have been made since version v4.7.3:

-- A rich text export was added to the shaded graphic view utility.  This
   uses the highlight command in the Rich Text Format specification 1.5,
   and is probably compatable only with relatively modern word-processors.
-- Made a few changes and fixes to the shaded view.  
-- Added a "find in next title" function to the main document window
-- Added a few normal and auomated web links 

The following changes and/or fixes have been made since version v4.7.2:

-- Clustal format (.aln) filter was updated so it now compatible with
   the sequence numbers option in ClustalX
-- A "delete numbers" option was put in under the sequence menu to allow
   easier compatability with copying and pasting from numbered formats
-- In the shaded graphic view, an option to print lines continuously (not
   broken by a space every ten residues) was added
-- An option to place translations below nucleotide sequences in either
   one-letter or three-letter format was added (allows for coloring with
   amino acid color table colors, but no similarity shading of the amino
   acids in this view).

The following changes and/or fixes have been made since version v4.7.1:

-- 8/27/1999: Added option for outlines around identity and similarity
   shading in shaded graphic view of alignments
-- 8/27/1999:  Fixed small bug in restriction maps.  If more than one
   enzyme cut at the very position starting a new line on the printed 
   map, only the first enzyme would show on the map (though all would 
   appear in the lists). 
-- User options are provided for a (hopefully) more useful consensus
   sequence generation.
-- The ABI trace viewer was updated to provide summary information and
   to allow copying of the trace window as a bitmap (in last version, 
   I forgot to add that the option to copy print pages as Metfiles was
   also added).
-- Support for reading Clustal format has been added (no save, only open).

The following changes and/or fixes have been made since version v4.7.0:

-- The graphic shaded view was improved.  It's more like a print preview.
   Also, the option to add numbers to the sides of the sequences has been 
   added.
-- *Another* introduced bug was fixed in the accessory applications launch
   interface.  This bug was preventing input and output file name command
   prefixes from being added to the command line (needless to say, many 
   apps would not run"
-- Font size control has been added to the single sequence editing box.
-- Accessory apps no longer need to be run from an alignment doc unless
   they operate upon sequence output.
 
The following changes and/or fixes have been made since version v4.6.3:

-- Support for ABI chromatographs has been added.  Display, zoom, scale,
   select, copy, export and reverse complement sequences from ABI trace 
   files.  Also print with professional-looking formatted color output 
   similar to commercial output.
-- Some memory leaks were fixed.

The following changes and/or fixes have been made since version v4.6.2:

-- Corrected 'Del' key behavior in edit residues mode and in single
   sequence edit interface
-- Added sequence number to beginning of mouse position labels
-- Fixed alignment of ruler ticks for non-type-set fonts

The following changes and/or fixes have been made since version v4.6.1:

-- Fixed a bug that caused simulataneous entry of characters into mutual
   information examiner X or Y entry and sequence when in Edit Residues
   mode
-- Fixed glich that caused ruler to not extend to end of window in very
   high screen resolutions with small font size
-- Fixed problem (I think) with disappearing window controls (minimize,
   maximize and close controls)
  
The following changes and/or fixes have been made since version v4.5.10:

-- Scroll a full screen at a time with the PageUp/PageDown keys and 
   with Ctrl+arrow keys -- also refined cursor movement in edit mode
   and keyboard-controlled scrolling
-- BioEdit now remembers your last window state as the default
-- Fixed a bug in the single sequence edit window -- applying twice
   in a row after creating a new sequence no longer causes an access
   violation
-- Improved speed of dynamic shading of protein alignments in the edit 
   window 

The following changes and/or fixes have been made since version v4.5.9:

-- Fixed bug in edit-window shading (maximizing window shouldn't cause
   a problem now).
-- Added Select to End, Select to Beginning and Select Residues of  
   Selected Sequences functions
-- Changed open and save file dialogs to remember file extensions
   and last directory as defaults
-- Added recent file list to the file menu
-- Added function to open an edit box at the current cursor position
   (when in Edit Residues mode) 
-- Added Tile and Cascade window functions

The following changes and/or fixes have been made since version v4.5.8:

-- Added identity/similarity-based shading in the alignment window
-- Fixed a bug in the matrix plotter which caused it to periodically
   crash when plotting a half matrix (above diagonal only).
-- Fixed bug in N-best reporting of mutual information and N-best and 
   P-best reports when data are organized for the whole alignment rather
   than by position (I forgot that those things had never been finished).

The following changes and/or fixes have been made since version v4.5.7:

-- Added information-based searching for conserved segments (may be 
   useful for designing PCR primers or defining motifs)
-- Made the sequence titles window adjustable in width
-- Fixed bug in six-frame translations:  An "N" in the sequence no 
   longer causes an amino acid to be skipped
-- Added a "Minimize Alignment to Mask" function to allow trimming
   an alignment to positions present in a mask sequence
-- Added positional numerical summary for nucleotide alignments
-- Changed entropy plots to area plots that resize with the window
-- Added a full-text summary of entropy (Hx) values when an entropy
   plot is run 
-- Got rid of the "three-way information" thing (too much noise to be
   useful)


The following changes and/or fixes have been made since version v4.5.6:

-- The vertical split has been  improved -- no longer flickers wildly 
   when going between windows (also, no longer "left" and "right" 
   panes -- it's just one window now).  The horizontal split view is
   still not-so-great.
-- Added option to hide panels for controls at top (to allow for a bigger
   sequence editing window)
-- Sped-up right-click driven insertions and deletions.  Added option
   to reverse mouse buttons (to allow inserting and deleting gaps with
   a left click)
-- Fixed glich in window updating when switching between color and B&W
-- Fixed glich in translations on restriction maps -- spacing was off if
   an "X" resulted from a codon with a non-A, C, G or U/T character.
-- Added menu items for all button-driven controls
-- "Lock gaps" no longer causes an error when residue selection goes 
   beyonf the end of a sequence.


The following changes and/or fixes have been made since version v4.5.5:

-- Fixed bug in residue selecting that was introduced with the sequence
   handling rewrite:  The location of a selected block of residues was
   not scrolling correctly in the horizontal direction
-- Changed the way the matrix plotter draws matrices.  The speed is
   improved several hundred fold.  
-- Added threshold control to matrix plotter.

The following changes and/or fixes have been made since version v4.5.4:

-- Fixed glich in amino acid composition reporting -- previously, non-
   amino acid characters were assigned a mass of 110 Da.  Now, only 'X'
   is assigned 110, other characters are 0 Da (not counted as amino 
   acids).  The weight of 'B' is considered the average of 'D' and 'N',
   and the weight of 'Z' is the average of 'E' and 'Q'.  Also, a stop 
   codon at the end of a sequence no longer adds 1 amino acid to the
   reported length of the sequence.
-- A couple of changes were made to the accessory application 
   configuration interface and the way accessory apps are run:
      1. Options to include or not include the input and output files in
         the command line were added, as well as the option to include
         them at the beginning or end of the command line.
      2. changed the method of calling accessory apps:  redirection of 
         stdin and stdout now *appears* to work correctly in all cases
         The few PHYLIP programs distributed with BioEdit now have stdin
         redirected so they may be run fully automated.
-- Forgot to report in an earlier version: a bug in converting selected
   regions to lowercase was fixed (left out 'A')

The following changes and/or fixes have been made since version v4.5.3:

-- The on-line help system was updated (the printable documentation 
   still needs updating -- also the WWW documaentation needs to be 
   updated (don't know when that'll get done)).
-- Fixed a bug in resizing split windows (introduced with version 
   4.5.3 -- would cause an exception when the window was increased 
   vertically due to an oversight in creating a new graphic sequence
   display object).

The following changes and/or fixes have been made since version v4.5.2:

-- Sequence handling and memory allocation for sequences was re-written.  
   Alignments load much faster and editing of large alignments is more 
   reasonable.  When using the new BioEdit Project file format, the 
   prokaryotic 16S rRNA alignment (6205 sequences, 29 Mb file) opens in 
   less than 10 sec. on a Pentium 233 MHz with 80 Mb RAM. 
-- Created a new binary file format (the BioEdit Project file) for fast 
   Open and Save of large alignments.
-- A bug in formatting when exporting an aligment as raw text was fixed 
   (the spacing would be randomly messed up -- this bug was introduced 
   with version 4.3.8 and was only recently discovered because this 
   feature apparently does not get used much). 
-- Two bugs in the vertical split window view were fixed:  
     1.  When the original window's vertical scrollbar was not at the top, 
         the right side of the split window would start out of register 
         with the left side.
     2.  The left side of the window would not scroll all the way to the 
         end.
-- A couple of changes to the sequence edit box:
     1.  The first digit of ruler positions >1,000,000 is no longer deleted
         from the ruler bar.
     2.  The "Delete" key now works in the edit box as well as "Backspace"
-- A typo on the vertical axis of Eisenberg mean hydrophobic moment plots
   was fixed.
-- Changes to matrix plotter:
     1.  Clicking on the plot when there is no 1-D line plot open no longer 
         crashes the program
     2.  Highlighting of the selected matrix position on the plot has been
         fixed (the selected position is inverted and outlined).
     3.  The data summary reported for a highlighted matrix position reflects
         the position numbers in the matrix file rather than the absolute 
         row or column number (x and y position numbers may be discontinuous,
         as when alignment numbering is used to generate the Mxy data or when
         a numbering mask different from the sequence mask is used).
     4.  The row or column numbers shown on the 1-D matrix row/column plots 
         reflect the position numbers in the matrix file.
     5.  A bug in reporting of the current row or column that showed up when an
         asymmetric section of a matrix file was plotted has been fixed (if a 
         matrix contained more rows than columns, row numbers beyond the total
         number of columns would be mis-reported).
-- "Flags" are now available to graphically mark any position in an alignment
   for keeping track of positions while when going back and forth a lot.
-- The sequences have been crunched together slightly for a tighter view with 
   more sequence data on the screen at once.
-- User may enable or disable position reporting at the mouse arrow.
     

The following changes and/or fixes have been made since version v4.5.1:

-- Added option to translate selected regions of nucleic acid sequences
   for formatted translation with codon summary, with the option to 
   display the entire nucleic acid sequence or only the translated region
-- Added option for single-letter or three-letter codes for amino acids
   in formatted translations
-- Fixed a couple of bugs related to non-U.S. versions of Windows: errors
   resulting from the difference between U.S. and European decimal separators
   (period vs comma) have been fixed in the text print, RNA anaylises outputs,
   the matrix plotter, and formatted translations. 
-- Updated matrix plotter to provide a summary of matrix dimensions before
   loading up a matrix, and added the capability to plot user-defined regions
   of matrices.  The plotter can now handle a nearly unlimited matrix size (but
   can still only plot ca. 1500 x 1500 (maybe up to about 2000 x 2000) at one
   time.  The largest file tested was 179 Mb (5183 x 5183).
-- Expanded sequence limit to 10000 (sequence size is limited only by system 
   resources and speed). 

The following changes and/or fixes have been made since version v4.5.0:

-- Vertical split window view was added
-- About 16 billion bugs were fixed in the split window view synchronization

The following changes and/or fixes have been made since version v4.4.2:

-- Improved shaded views:  added color table-based shading, shading with
   sequences in color, and improved Metafile copying
-- New sequence edit box, with sequence view, ruler and color
-- Added ORF searching (under Nucleic Acid submenu of Sequence menu)
-- Added split window option for simultaneous editing of two different 
   places in the same file

The following changes and/or fixes have been made since version v4.4.1:

-- blastx was added to the local BLAST interface
-- Image Export (Bitmap or Windows Metafile) added to plasmid utility
   with variable output size options
-- Clipboard copy as a Windows Metafile added to plasmid utility and
   to shaded graphic view utility


The following changes and/or fixes have been made since version v4.4.0:

-- Fixed "Cut" and "Copy" options for working with linked 
   nucleotide/protein views.
-- Added user control over menu shortcuts in alignment documents
   (to customize shortcuts, go to "Customize Menu Shortcuts" from
   the "View" menu)
-- Added "Auto-Update View Options" item under the "View" menu -- 
   when checked, the "Save Options as Default" item is not visible,
   and view options are automatically saved whenever a change is
   made
-- Added multiple file handling for opening and importing files
-- Fixed redraw of ends of sequences when in a non-typeset font.


The following changes and/or fixes have been made since version v4.3.10:

-- Fixed bug in translating and translation toggling (no longer
   bombs out after several translations)
-- Non-typeset font handling was improved for the editing window
   and in graphic shaded view
-- Read filters for NBRF/PIR and Phylip 4 formats were improved
-- Monochrome sequence view fixed (can't remember when or how
   I broke it -- but it got broken).
-- Three options were added for handling gaps for translating
   when toggling between nucleotide and protein views:
      1. gaps automatically adjusted to occur in groups of three
         that do not disrupt codons
      2. gaps that disrupt codons or do not occur in groups of 
         three may be ignored in trnaslating, but no automatic
         adjustment of gaps
      3. No automatic adjustments to gaps made, and gaps not
         ignored when translating 


The following changes and/or fixes have been made since version v4.3.9:

-- Two bugs that were introduced into version 4.3.9 were fixed:
      1.  Access Violation that would occur after previewing "Print 
          Alignment as text"
      2.  Access Violation that would occur upon running mutual 
          information analysis

* These two bugs only occurred in version 4.3.9 *

 
The following changes and/or fixes have been made since version v4.3.8:

-- The program was restructured internally to use less memory and much 
   fewer system resources.  As a result, the program loads much faster 
   and is not as demanding of the operating system.  If you have 
   experienced any trouble with starting BioEdit, this may solve the 
   problem.
-- Two bugs were fixed in the display of selected residues:
      1. The entire selection is now highlighted correctly in very 
         long stretches of selected residues (more than ca. 25000 
         residues).
      2. When selecting entire columns by selecting on the sequence
         position ruler, the selection highlighting would sometimes
         get broken, with some selections not appearing highlighted.
         This has been fixed.  

The following changes and/or fixes have been made since version v4.3.7:

-- Added click-select capability fo viewing data points in the matrix 
   plotter
-- When creating a line graph from matrix data, the row selected on 
   the matrix plotter is graphed
-- When toggling between row and column views in matrix row/column
   graphs, the selected data point on the matrix plotter is used
-- When rows or columns are scrolled through on a line graph, the 
   selected data point on the matrix plotter (if there is one) is 
   updated to match
-- Rows or column may be selected for an open matrix line graph by
   selecting a point on the matrix plotter.
-- Fixed a bug in memory allocation for the matrix plotter:  The last
   point of the matrix no longer disappears
-- Matrix table reading is now more flexible (It can handle 
   inappropriate spaces, tabs or returns in the file without giving
   an error)
-- Matrix plotter now read .csv (comma-delimited) matrices as well as
   tab-delimited
-- A bug was fixed for updating feature titles in the plasmid drawing
   utility:  The updated title is selected and sized correctly on the 
   screen now
-- Linear vector maps should now shade better on a grayscale laser
   printer (only circular maps were fixed previously)
-- Moving the ends of horizontal or vertical arrows in the plasmid 
   drawing utility now works correctly (doesn't get stuck horizontal 
   or vertical anymore)
-- A bug in the new nucleotide/protein translation view toggling was
   fixed:  Previously, if gaps were accidentally introduced into the last 
   codon of a nucleotide sequence and several gaps also occurred at the 
   end of the sequence, an error would occur when BioEdit attempted to
   readjust gaps to mend codons.  This should no longer be a problem
  

The following changes and/or fixes have been made since version v4.3.6:

-- The on-line help was updated with a full searchable index and full-
   text search capability
-- Nucleotide sequences which encode proteins may be switched between 
   their protein and nucleic acid sequences, and alignments may be 
   edited in either view
-- Simple translations of nucleic acids and reverse translations of 
   proteins now take gaps into account rather than treating them as 
   unknown residues
-- ClustalW may now be run without modifying sequence titles to be 
   non-redundant and 10 or few characters long
-- When ClustalW is run from the accessory menu, the new alignment is 
   automatically updated with GenBank information (features, references, 
   accession, etc.) and full titles


The following changes and/or fixes have been made since version 4.3.5:
(These changes were both made to the plasmid drawing utility)

-- Grouped drawing objects now scale as a unit
-- Changed feature drawing to be more compatible with most printers


The following changes and/or fixes have been made since version 4.3.4:
(These changes were all made to the plasmid drawing utility)

-- Added linear vector capability
-- Made titles selectable and editable
-- Made vector structure selectable and mouse-movable
-- All objects and labels move along with vector when moving by hand
-- Restriction sites and feature labels locations adjust themselves
   when vector is resized
-- Bug fixed in plasmid utility:  selecting multiple restriction site
   labels then hitting "delete" was causing trouble with the enzyme-label
   links


The following bug fix has been made since version 4.3.3:

-- A bug in the positioning of restriction cut sites at the origin 
   junction of circular DNA sequences was fixed.  This error occured
   when running a map on circular sequences that had a restriction site 
   that overlapped the origin and cut after the overlap point.  This would
   cause an error also when generating a plasmid map from such a sequence.


The following changes and/or fixes have been made since version 4.3.2:

-- Only one change:  The sequence editing box now behaves better, and there
   is no set limit on the size of the sequence that can be opened and 
   edited in an edit box (well, actually the theoretical upper limit is
   10 million bases, but that would be too slow to be worth it, anyway).
-- The printable documentation has been updated (It's only available for
   MS Word'97 or later).


The following changes and/or fixes have been made since version 4.3.1:

-- An incorrect value was corrected in the Kyte and Doolittle hydrophobicity 
   data (valine was set at -4.2 instead of 4.2).
-- Arrows were added to plasmid drawing interface
-- Enzyme marks automatically follow their labels
-- linking of enzyme sites to their labels seems to work well now (if an
   enzyme label is deleted, the site is taken off the map)
-- Arrow heads on features automatically scale down in length when 
   the feature is short
-- Print scale problem has been fixed for plasmid drawing

The following changes and/or fixes have been made since version 4.1.1:

-- Modified hydrophobicity plotting to conform to Kyte and Doolittle mean 
   hydrophobicity profile.
-- Added file save and open capability for plasmid drawing files
-- Added direct print for plasmid drawings
-- Added object property editing for plasmid drawing
-- Added copy and paste functions for plasmid drawing and modified 
   copy to allow copying objects as bitmaps for pasting into other apps
-- Added object ordering support in plasmid drawing utility


The following changes and/or fixes have been made since version 3.1.4:

-- Several bug fixes and improvements in plasmid drawing utility.  This still
   has a long way to go

The following changes and/or fixes have been made since version 3.1.2:

-- Added new graphical plasmid drawing and annotation program
-- Fixed graphc alignment view (no system crash on multiple pages
   anymore -- also made it more efficient)

The following changes and/or fixes have been made since version 3.1.1:

-- Fixed bugs in opening of Fasta files from Mac or UNIX format (was losing
   the first line of sequence)
-- Fixed minor bug in opening of NBRF/PIR sequences (spaces in the title would 
   truncate the title and tack extra characters at the beginning of the sequence
-- Fixed color matching between series lines and legend of hydrophobicity plots
-- Added scrolling/keyboard control of row/column number in line plots of
   mutual information matrix data


The following changes and/or fixes have been made since version 2.0.4:

-- fixed bug in LOCUS field of GenBank files (was duplicationg part of the LOCUS in
   some cases
-- Better handling of Macintosh-formatted GenBank files
-- Automatic scrolling in Grab and Drag mode.
-- arrow key control over window scrolling
-- added horizontal scroll speed controller
-- Fixed information-responsive residue shading (capital/lowercase residues no longer seen
   as different, and multiple gaps now reduce the alignment strength rather than increase it)
-- Uppercase/lowercase, lock/unlock and degap control of sequence selections as well as 
   complete sequences.
-- Added zoom capabilities to RNA data matrix plots
-- Added Single-row plotting for individual rows of data matrices, with the option to
   print graphs or copy as Bitmap, Metafile or Enhanced Metafile.
-- Added capability for three-way information analysis (doesn't seem to be very worthwhile, however).
-- Fixed font handling in edit window to allow proper scaling of any font
-- Added hydrophobicity/hydrophilicity profile plotting for proteins
-- Added nucleotide and amino acid composition summaries and plots
-- Added codon-parsed translation and codon-usage summaries for all three 
   frames of nucleotide sequences
-- Reorganized some of the "Sequence" menu, now with separate protein and
   nucleic acids submenus
-- Added selection of restriction enzymes by manufacturer and reporting of 
   manufacturers that carry each enzyme
-- Updated restriction enzyme table to gcgenz.811, from REBASE version 811 (Oct 28 98)
   (added to BioEdit Nov 3 98) 

---------------------------------------------------------------------

How to contact the author:

Tom Hall
760-201-6089
tomandhall@gmail.com
