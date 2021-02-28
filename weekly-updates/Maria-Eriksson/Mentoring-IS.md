# Mentoring Sessions with Isla

* [11 February 2021](#date-11-february-2021)
* [26 January 2021](#date-26-january-2021)
* [15 January 2021](#date-15-january-2021)

**Why?** Building cool connections & supporting learning

**When?** Fortnightly, Tuesdays at 11:30am

**Where?** Google hangout

**For how long?** 1 hour

**Next meeting** 23 February 2021

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
