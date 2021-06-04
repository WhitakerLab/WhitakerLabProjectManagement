# Mentoring Sessions with Isla

* [28 May 2021](#date-28-may-2021)
* [8 April 2021](#date-8-april-2021)
* [23 March 2021](#date-23-march-2021)
* [9 March 2021](#date-9-march-2021)
* [23 February 2021](#date-23-february-2021)
* [11 February 2021](#date-11-february-2021)
* [26 January 2021](#date-26-january-2021)
* [15 January 2021](#date-15-january-2021)

**Why?** Building cool connections & supporting learning

**When?** Fortnightly, Tuesdays at 11:30am

**Where?** Google hangout

**For how long?** 1 hour

**Next meeting** 

## Date: 28 May 2021

* Chat about Turing Way chapter, 'Collaborating using sensititve data'. EK keen to collaborate on this.
* Question about Jupyter notebook on GitHub repository - do demonstrate how it works, could I have it open a 'sample' (not real) patient document saved on the GitHub repository?

## Date: 8 April 2021

* We spent the meeting opening an issue in the Turing Way, which proposes [a new sub-section to an existing Turing Way chapter](https://github.com/alan-turing-institute/the-turing-way/issues/1842) 🎇
* IS provided really helpful support as ME was feeling overwhelmed with work - thank you again :tulip: :pray: 

## Date: 23 March 2021

### Questions for the meeting

* ME: Project "let's ensure that sensitive data is not stored in Jupyter notebooks" - would love to discuss the method IS showed during the Whitaker Lab meeting + the method SG mentioned (is it [this](https://pypi.org/project/nbstripout/)? Or was it something 'black'?)

## Date: 9 March 2021

* We discussed IS's answers to ME's questions posted in the previous meeting (the 23 February meeting).
* IS showed ME how to streamline histopathology extract scripts further.

## Date: 23 February 2021

### Questions for the meeting

* ME: How does one remove a commit from the commit history? Say one by mistake commits (and pushes) a file that contains sensitive information. Even once one has deleted the file, the file is still accessible from the commit history? I looked into these answers ([solution 1](https://docs.github.com/en/github/managing-large-files/removing-files-from-a-repositorys-history), [solution 2](https://docs.github.com/en/github/authenticating-to-github/removing-sensitive-data-from-a-repository) and [solution 3](https://stackoverflow.com/questions/43762338/how-to-remove-file-from-git-history)), but could not get them to work, so I ended up deleting the entire repository (and then setting it up again), but that doesn't seem like a sustainable solution...
    * IS: It's typically straightforward to remove things from your local git repo (especially if you don't have collaborators to worry about) but extremely hard to remove things from github. Solution 2 looks promising since it involves contacting someone from github to remove their copy of the data.
*** To scrub the data not just from MEs repos but also from her collaboratos we will need collaborators to run the following on their local copies of the repo: 
    ```
    git filter-branch --index-filter "git rm -rf --cached --ignore-unmatch scripts/dataframe-cleaning/Describing_the_cohort.ipynb" HEAD 
    git push --force --all
    ```
    Then we need to email the GitHub Support team to delete the data
    * IS: let's brainstorm a way to automatically scrub the notebook output- this could be added to the turing way?
* ME: What way of working would IS recommend? There's using the web browser or Terminal, but also GitHub Desktop and VS code?
    * IS: uses emacs for everything: git (via magit) text editing, etc.
* ME: What happens to comments that reviewers leave on files on GitHub? For example, when KW reviewed this file, she left comments, but once those comments were accepted, and the file was merged, those comments seemed to disappear?
    * IS: You should be able to find them in the closed pull requests, e.g. https://github.com/WhitakerLab/WhitakerLabProjectManagement/pull/421
* ME: When creating a .py file that contains functions (which are read into a Jupyter Notebook), does one need to add "import packages" to the .py if the functions defined in the .py file use specific packages, or should those packages simply be imported at the start of the Jupyter Notebook?
    * IS: I suspect you need to import packages within the .py. Either way it's good practice, because it means when the file is reused outside of the notebook it will be explicit about its imports.
* ME: At the top of scona .py files, there is always the line "#!/usr/bin/env python" - what does this mean?
    * It tells your system where to find the python install to run the file with. I think we need to get rid of those actually.
* ME: Several tests use the same key terms to extract the result (for example: T010, T095, T099, T100, T105...)  - can this be streamlined?
    * IS let's discuss next week

### What did we discuss?

### Goals for next week's meeting

### Other

## Date: 11 February 2021

### What did we discuss?
* IS gave ME feedback on one of her text extraction scripts (["Extracting_histo_step_1_210208.ipynb"](https://github.com/MariaEriksson/GOSH-2000-2018-paper/blob/main/scripts/text-extraction/Extracting_histo_step_1_210208.ipynb)), including advice on how it can be cleaned up/streamlined.
  * IS showed ME how several cells that contain the same structure of code can be converted into a function.
  * IS advised that functions that be moved into a separate .py file, and read into the Jupyter Notebook at the beginning.
    * IS explained that Jupyter Notebooks are unable to relocate memory; however, moving functions into a separate .py file can get around this problem and free up memory.

### Goals for next week's meeting
* IS will create a new issue in the [GOSH-2018-2018-paper repository](https://github.com/MariaEriksson/GOSH-2000-2018-paper) that describes the discussed transformation of the above-mentioned text extraction script
* ME will transform repetitive cells in the iscussed text extraction script into functions
* ME will move functions from the discussed text extraction script to a separate .py file

### Other
* IS & ME reflected on how much they enjoyed LC's lab meeting talk :stars:

## Date: 26 January 2021

### What did we discuss?
* Overview of each other's work
  * IS
    * BSc & MSc Maths
    * Cambridge The NeuroScience in Psychiatry Network (NSPN): BIDS
    * Currently B2B software company
  * ME
    * BSc Neuroscience; MSc Paediatric Neuropsychology
    * PhD predicting outcome after epilepsy surgery in children (using retrospective data collected at Great Ormond St Hospital)
* What we want to get out of these mentoring sessions
  * Working openly on GitHub
    * ME will contribute to [scona](https://github.com/WhitakerLab/scona), with the possible long-term goal of applying it to her data set.
    * ME will figure out how to share her code on GitHub, and transform it into interactive Jupyter Notebook tutorials, similar to the [scona tutorials](https://github.com/WhitakerLab/scona).
  * Automating data extraction
    * IS has [previsouly worked on data (text) extraction](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0230416). ME is currently extracting data from electronic medical documents (two different approaches, depending on whether the document is structured or unstructured; neither approach involves NLP though).
    * ME hopes IS might be able to provide feedback on this script.
  * BIDS
    * ME has used BIDS on a few patients' imaging data, but has struggled to automatise this process. ME hopes IS will be able to help her figure out how to batch process her cohort.
    * ME uses BIDS to perform DICOM to NiFTI conversion, anonymise data, and structure data. ME 'prints' date of scan in scan file name, and uses this to sub-divide scans into pre- and post-surgical scans.
    * ME & IS discussed running BIDS on personal desktop versus UCL clusters. Will use personal desktop for now.

### Goals for next week's meeting
* ME put logistic regression code on GitHub
* ME bring info on her project's BIDS details
* IS add a standing Google meeting link

### Other
* [Mozilla Open Leaders training programme](https://foundation.mozilla.org/en/initiatives/mozilla-open-leaders/)
* [XNAT](https://www.xnat.org)

## Date: 15 January 2021

### What did we discuss? 
* [scona's GitHub repo](https://github.com/WhitakerLab/scona). 
  * ME had previously looked through this repo, and [made comments](https://hackmd.io/zzSlKTK8Q4e-qKv-QSEWcw).

# Template

## Date: [INSERT DATE OF MEETING]
### What did we discuss?
### Goals for next week's meeting
### Other
