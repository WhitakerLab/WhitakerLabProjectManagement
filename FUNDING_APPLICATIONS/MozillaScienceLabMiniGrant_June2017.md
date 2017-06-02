# Mozilla Mini Grant application

***1st June 2017***

### Applicant Details

**Name:** Isla Staden

**Email:**

**Physical address:**

Alan Turing Institute
British Library
96 Euston Road
London NW1 2DB

**Institution:** Alan Turing Institute

**Have you previously received a grant from the Mozilla Foundation?**
*If so, list the amount and purpose of the grant.*

No.

### Proposal summary

**Title** *(10 words)*: Brain Networks in Python

* KW note - this is a pretty crummy title - I'm totally up for a better one..

**Provide a brief description of your project or event**

*(50 words)*

NEEDED. Needs to relate to the goals of prototyping and onboarding new researchers.

**Total proposal budget in US Dollars (USD)**:

4,960

**How much money in USD are you requesting from the Mozilla Foundation?**

4,960

**List your partners, if any, and the role/s they will play.** *(250 words)*

I will be mentored by Dr Kirstie Whitaker. Kirstie is a research fellow at the Turing Institute and outgoing Mozilla Fellow for Science. She is a neuroscientist who studies brain development, using graph theory to understand the brain as a network. Dr Whitaker is a two time mentor for the Mozilla Open Leadership Training Series and she has extensive skills in nurturing and supporting open projects. The Brain Networks in Python is built within the Whitaker Lab GitHub repository where Dr Whitaker is an active contributor. She will review all code and documentation and provide guidance to ensure the Brain Networks In Python project is accessible and usable for all.

I will also work with the research software engineering team at the Turing Institute. The team is lead by Dr James Heatherington....

**On which Internet health issue(s) does your proposal focus?**

- [x] Open Innovation
- [ ] Digital Inclusion
- [ ] Decentralization
- [ ] Privacy and Security
- [ ] Web Literacy

**If you are NOT a US resident or citizen will the proposed project or event involve travel to or activities within the United States?**

- [ ] Yes
- [x] No
- [ ] Not applicable

**Are you requesting support for an event or a project?**

- [ ] Event
- [x] Project

### Proposal description

**Describe the issue/problem you are trying to address.** *(100 words)*

The brain is made of lots of regions. Traditional neuroimaging analyses have considered them all separately. This is no good. Modelling the connections between the different parts of the brain is much more reasonable. This project will implement graph theory to analysis magnetic resonance brain images as a network. The most popular toolbox to do brain network analyses is written in matlab. This project allows researchers who are at all levels of expertise in python programming to conduct the analyses.

**List key project activities (what you will do), outputs (what will be produced through your activities) and outcomes (impact of your project on your beneficiaries during the grant period).** *(1000 words)*

*Activities*

The Brain Networks in Python code was implemented in the Neuroscience in Psychiatry Network publication "Adolescence is associated with genomically patterned consolidation of the hubs of the human brain connectome" published in PNAS in 2016 (doi: [10.1073/pnas.1601745113](http://dx.doi.org/10.1073/pnas.1601745113)). The code conducts structural covariance network analyses on cortical thickness measurements from a cohort of 300 participants and creates all figures and results tables for the published manuscript (GitHub repository: https://github.com/KirstieJane/NSPN_WhitakerVertes_PNAS2016).

As currently written, the Brain Networks in Python code is monolithic. It is very difficult to repurpose for new analyses or for different datasets. The first goal of this project will be to *refactor the code into modules*. Specifically, we will break down the conceptual steps for a network analysis and allow the user to re-combine them as they see fit. For example, one user may want to use the code only for the graph theory measures while another may use the visualisation module alone. It will be possible to link the modules together to complete an entire neuroimaging analysis from start to finish, but this workflow will not be necessary. Modularising the software will permit a more diverse user base and a much more interoperable set of code.

The second best time to add in tests for software is when refactoring. (The optimum time would have been when the code was written in the first place). As part of this 2 month project we will *add in high level and unit tests* for the network analysis code. Testing will give users confidence in our code and allow us to implement continuous integration. As the project develops, we will always be able to verify the accuracy of the modules.

We will also add *new functionality* to the code. There is currently no way (in this codebase) to investigate the difference in brain networks between two groups. We will add a module that permutes the original data and builds up a null distribution so that differences between the two real groups, for example people with a diagnosis of depression and healthy controls, can be statistically tested.

Along with integrated tests, *documentation* will allow the Brain Networks in Python code to be used by many people. We will provide example data and clear tutorials to make it easy for users to install and get up and running with the code. These tutorials will be in the form of Jupyter notebooks that can be either downloaded and run locally or run in a MyBinder (http://mybinder.org) instance online.

Finally, we will release our code as a python packages that can be easily installed via pip (https://packaging.python.org/) or conda (https://conda.io/).

*Outputs*

MIT licensed, documented and tested code.

Package. Will have DOI from zenodo.

Blog posts and promotion to the community.

Once a community grows around the project we hope to inspire additional integrations. For example collaborating with cytoscape to provide interactive visualisations of the networks. Or extending the network analysis methods etc.

*Outcomes*

Make it easier to replicate analyses. Make network analyses more accessible.

Smoother onboarding. Ensure early career researchers can conduct cutting edge neuroimaing analysis in a documented and community supported enviroment.

Better science. Better understanding of the brain!

Lots of exciting extensions. Interactive visualisation, extension to different types of networks.

**Provide key indicators you plan to use to measure project outcomes and source of data.** *(500 words)*

DOI

> All projects should specifically reflect priorities that enhance our broader community efforts toward open innovation, efficiency in regards to practicing open science (lower barriers, ease of use & integration, etc), and reproducibility (transparent research methods & results).

Gooooooood question. I'm not sure. Probably the best would be some papers to come out of it!

* Simone?
* Paula?
* Kirstie NORA

**Explain who will benefit from the project.** *(100 words)*

AAAAAALSO A good question. Scientists. People wanting to study brain as a complex network. Network analysists who want to apply their methods to brain networks?

Allows provenance of analysis and efficient knowledge transfer, so this project also benefits senior scientists who are mentoring members of their group. They don't have to be concerned about

**List any risks or challenges that may affect the overall success of your project and now how Mozilla and/or others can help you to overcome these challenges.** *(250 words)*

These are ALL VERY GOOD POINTS.

Probably the biggest challenge is that it is not usable for others - currently code works perfectly for the Neuroscience in Psychiatry Network but requires Kirstie's idiosyncratic knowledge! Best way forward is to link into the Mozilla network and get early feedback from the community.

**Is this a new project or continuation? If new, please describe your qualifications to initiate the activity. If continued, please describe your accomplishments to date. Feel free to include links to articles and documents online that highlight your recent work.** *(1000 words)*

Continuation of Kirstie's work. INSERT DESCRIPTION OF PNAS PAPER.

New for Isla. INSERT expertise re: graph theory & networks etc.

**Mozilla works in the open. How will you document and share your project progress with the community.** *(250 words)*

GitHuuuuuuub. Already there. Twitter account for lab.

Got a contributing file and code of conduct. Building issues during mozilla global sprint and updating README file.

Embrace working open philosophy. Ensure that work in progress is shared so that others can provide help and feedback.


**How will you continue work on this project beyond the funding period?** *(250 words)*

We hope that users will continue to contribute. Kirstie will be able to mentor contributions.

Isla....applying for other funding?

Importantly - doesn't need to be "me". Whole point of building documentation openly is so that others can fork and contribute even if Isla leaves!

### Upload documents

**Please upload an itemized project budget using the template linked below.**

[http://bit.ly/2riERqd](http://bit.ly/2riERqd)

### Communications

**How did you hear about the mini-grant opportunity?**

- [x] Twitter
- [x] Blog
- [ ] Friend
- [ ] Other

**Do you want to be added to our Mozilla Science Lab mailing list?**

- [x] Yes
- [ ] Not at this time

---

Kirstie's Brain Networks In Python code is already available on github, we want to expand the code base, add tests and improve usability by creating detailed documentation and providing step by step instructions. In short, we want to make the code open source in a greater sense than just putting it out there.
This will serve two purposes. The first: anyone will be be able to learn from it and use it to run network analyses on their own data with minimal friction. It will be straight forward for users to add their own features an build on the code base as needed. The second purpose addresses reproducibility in science. When someone (Kirstie or anybody else) reports a finding using these tools and makes their data available, everything can be checked. We allow people to check the results by providing clear instruction for beginners users- and to check the methodology, by making our code transparent, well-documented and testable.

The goal Kirstie and I have is to show how easy it is to take something you have written for your own analysis purposes and make it useful to others and, by making your analysis reproducible, useful to yourself.
