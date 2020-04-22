# CogX - Talk Proposal

- **Proposer:** [Sarah Gibson](https://www.turing.ac.uk/people/researchers/sarah-gibson)
- **Conference website:** <https://cogx.co/>
- **Date:** 8th - 10th June 2020
- **Location:** Online

## Talk Title

Sharing Reproducible Analyses with Binder

## Talk Description

_Please give a brief description of your talk (max 500 words)._
_The evaluation criteria of proposals will be:_

- _Expected general interest of the talk_
- _Academic standard and global impact_
- _Breadth of domain application_

The crisis of reproducibility in scientific research is well known.
The combination of 'publish or perish' incentives, secrecy around data and the drive for novelty at all costs can result in fragile advances and lots of wasted time and money.
Even in data science, when a paper is published there is generally no way for an outsider to verify its results, because the data from which the findings were derived are not available for scrutiny.
Such science cannot be built upon very easily: siloed science is slow science.

As reproducibility gains traction in the data science and research communities, the need to package code, data and the computational environment is growing.
There are many tools that address different aspects of this type of packaging, such as Jupyter Notebooks for literate programming, Docker for containerising and porting computational environments, and so on.
But they represent barriers to reproducibility as each one requires time and effort to learn.

Scientists work with multiple tools, pipelines and collaborators to produce results.
Project Binder integrates Notebooks and Docker for generating reproducible computational analyses and combines them with a web-based interface and cloud orchestration engines.
This means that analysts do not have to worry about all the moving parts so long as they have followed basic software best practices: their code is version controlled and they've captured the dependencies the analysis needs to run.
Binder then hosts the compute in the cloud and makes it easily shareable by providing a unique URL to the code repository, without imposing additional overheads on the analyst.
Binder, as a platform, provides easy access to the research for stakeholders.

mybinder.org is both a public service and a proof of concept of Project Binder's technologies.
This site serves over 140,000 sessions per week and combines resources from four entities in the US and Europe, including The Alan Turing Institute.
We support a range of programming languages and analysts from a range of research domains, and even facilitate a number of remote workshops and tutorials.
The flexibility of mybinder.org in allowing users to configure their environments provides scope to support a broad range of domains.
For example, the Natural Language Processing course powered by mybinder.org (https://course.spacy.io/) has over 5000 users, and the Institute of Computer Science at the University of St. Gallen uses our infrastructure for their university-wide Machine Learning course for explainable AI (https://ics.unisg.ch).

During the Covid-19 pandemic, mybinder.org has seen a significant increase in usage correlating with the beginning of lockdown and many researchers began working and collaborating remotely.
It is quickly becoming the "go to" tool for sharing results and facilitating remote teaching in this new landscape of research culture.

| ![mybinder.org Usage Statistics](https://www.dropbox.com/s/lnemjlsov0mkog5/image.png?raw=1) |
| :---: |
| mybinder.org usage statistics showing an increase in running sessions correlating with the beginning of lockdowns in Europe. |

Dr Sarah Gibson is a member of the mybinder.org operating team and is personally responsible for maintaining the Binder infrastructure deployed at the Turing.
During this talk, she will introduce Binder (the service), BinderHub (the technological infrastructure) and mybinder.org (a public instance of a Binder service, free for anyone to use) and demonstrate how it can be utilised to share reproducible computational environments and analyses.

## Descriptors

_Please select all descriptors that best apply to your talk._

- [ ] Technical / specialist
- [x] Big picture
- [x] Detailed
- [ ] Humorous
- [ ] Serious
- [ ] Retrospective
- [x] Prospective
- [ ] General / accessible

## Domain Application

_Please select up to two domains that best apply to your research and talk proposal._

- [ ] Natural world
- [ ] Security
- [x] Engineering
- [ ] Health
- [x] Society & Culture
- [ ] Economics

## Methodological Application

_Please select which methodological problem areas apply to your research and talk._

- [ ] Finding ways to automate the lengthy process spent preparing data for analysis
- [ ] Preventing misuse of data-driven technologies and artificial intelligence
- [ ] Using and analysing data in order to confidently infer causal relationships
- [x] Empowering citizens to access, understand and exploit the world's data
- [ ] Improving the ways in which we collect and analyse data
- [x] Effectively and efficiently convey information to varying audiences
- [ ] Merging multiple sources of data
- [ ] Using data while protecting privacy
- [ ] Merging human knowledge with data-driven machine learning and AI systems
- [ ] Eradicating failures within interacting systems
- [ ] Optimising algorithmic and system performance for bigger and more complex datasets
- [ ] Building on the most effective methods across data science to produce the next gen of techniques

## Relevance

_Please explain the relevance of your talk to the CogX audience, and the global impact of your research._
_500 words max._

CogX 2019 convened 20,000 visitors from government, third sector organisations, and businesses of all sizes.
They represented expertise in technology, finance, advertising, media, and energy and aerospace engineering.
All these audience members use open source tools and systems to leverage insights from data.
Project Binder represents one pathway that technology can be utilised to lower the barrier to producing and sharing reproducible scientific insights with all stakeholders across domains and organisational structure, such as management teams.
Binder is also an open source tool in and of itself and can therefore be deployed and modified within an organisation to suit their specific needs and be more opinionated regarding who has access than the free implementation at mybinder.org.

This talk will be relevant to attendees interested in the next generation of infrastructure and cloud computing and educational tech revolution tracks.
I will explain how cloud computing resources can be utilised with no overheads imposed on the users.
I will also give examples on how mybinder.org is being utilised for remote workshops and teaching in such a way that the students don't have to worry about setting up their environments correctly.

The talk will be accessible for all audiences, there will be no assumed knowledge or technological expertise required.

## Additional Information

_Please let us know any other information you would like to share to support your application._
