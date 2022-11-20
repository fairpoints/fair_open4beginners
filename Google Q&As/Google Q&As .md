# Google Q&As notes
### Contributors
Donny Winston, Lisanna Paladin, David Butcher, Sara El-Gebali, wider FAIR & Open commmuntity

**How to contribute: Feel free to send us a PR with a question or an answer any of the questoins outlined in the issues. **

### Intro:
- Google has recently launched Educational Q&A structured data to help students better find answers to educational questions by adding Schema.org Quiz structured data to your flashcard pages 
- Try it out yourself, Google “the ratio of surface energy to surface area is”
Examples:
	- What do we mean by Open Science?
	- What does FAIR stand for? 

### Community sessions

> - What are the key elements to communicate, and what should they understand about Open or FAIR?
> - Describe the learning objectives.
> - Consider the script trainers may utilize with presentation slides to aid in instruction. 

**Links:**

* https://schema.org/Quiz
* https://developers.google.com/search/docs/appearance/structured-data/education-qa
* https://developers.google.com/search/docs/appearance/structured-data/education-qa#examples

**Notes**
-
Answers to fundamental questions related to FAIR and open science will be added to the FAIRpoints website with the appropriate Schema.org schema. This will allow the questions and answers to be indexed by Google and added to search results. Quiz schema should be populated with definitions/terms from existing groups as much as possible, _e.g._ UNESCO definition of “open science”. Answers need to be submitted as pull requests to the FAIRpoints GitHub repository (https://github.com/fairpoints/www).


* What is Open Science? +1+1 +1+1+1
    * **Answer 1:** As defined by UNESCO, “open science is … an inclusive construct that combines various movements and practices aiming to make multilingual scientific knowledge openly available, accessible and reusable for everyone, to increase scientific collaborations and sharing of information for the benefits of science and society, and to open the processes of scientific knowledge creation, evaluation and communication to societal actors beyond the traditional scientific community.”
        * [https://en.unesco.org/science-sustainable-future/open-science/recommendation](https://en.unesco.org/science-sustainable-future/open-science/recommendation) 
    * **Answer 2:**  As defined by NASA-TOPs: Open Science is a social movement to make scientific activities, data, and results available to all members of society, whilst respecting contextual needs such as available resources, data sovereignty and personal privacy 
    * **Answer 3:** “Open Science is transparent and accessible knowledge that is shared and developed through collaborative networks” (Vicente-Saez & Martinez-Fuentes, &lt;a href="[https://doi.org/10.1016/j.jbusres.2017.12.043](https://doi.org/10.1016/j.jbusres.2017.12.043)">2018&lt;/a>). 
* What are the main elements of Open Science?
    * **Answer 1:** The six principles of Open Science are: Open methodology, Open source, Open data, Open access, Open peer review, Open educational resources _FORRT open science glossary, [https://forrt.org/glossary/open-science/](https://forrt.org/glossary/open-science/)) _
    * **Answer 2:** Key pillars: open scientific knowledge, open science infrastructures, science communication, open engagement of societal actors and open dialogue with other knowledge systems `(UNESCO, &lt;a href="https://unesdoc.unesco.org/ark:/48223/pf0000379949.locale=en">2021&lt;/a>).`
* Does Open Science mean everything you do is open? +1+1+1
    * **Answer 1:** It means that open is “opt-out”. That is, by default, unless you have good reasons for something you do to not be open (which happens!), make it open.
    * **Answer 2:** As open as possible, as closed as necessary and always secure
* How do I start to do Open Science?+1
    * You keep doing what you do, but think about which part of your research / study / work processes could be useful to other people and could be opened up. For example, if you are studying by summarising this topic, or drawing a mind map of it, you could start by sharing it in a study materials repository.
* What is the difference between open and fair? +1+1+1
    * **Answer 1:** FAIR means machine-actionable. Open means trying to have actionable data _accessible_ to as many humans (and their machines!) as practical. Ref: FAIRPoints community
    * **Answer 2:** The FAIR principles for scientific data management and stewardship are guidelines to improve the Findability, Accessibility, Interoperability and Reusability of digital assets [[7](https://doi.org/10.1038/sdata.2016.18)]. A dataset that is FAIR is not necessarily Open. The phrase “as open as possible, as closed as necessary” [[8](https://ec.europa.eu/research/participants/data/ref/h2020/grants_manual/hi/oa_pilot/h2020-hi-oa-data-mgt_en.pdf)] is often used to describe the interaction between the principles. Ref: [https://github.com/opensciency/OpenData](https://github.com/opensciency/OpenData) 
* Why is Open Science important? +1+1
    * Peer review, and resulting consensus or qualified disagreement, is essential for scientific progress. This was limited in the past due to costs of publication (printing paper, shipping books, etc.). It is not as costly now to publish results for peer review.
* Where do I put data to make it open?
* Where can I find FAIR data?+1+1
    * **Answer 1:** A keyword here is “repository”. Or a phrase may be “research data repository”. Or “dataset repository”. Ref: FAIRPoints community 
    * **Answer 2:** There are three major ways to find Data shared by researchers – **repository**, **web search**, and **literature** search. 

Repositories can be field specific or generic, [Generalist Repository Comparison Chart](https://zenodo.org/record/3946720#.YUKQ18RS-Uk) and [comparative review of eight data repositories](https://dataverse.org/blog/comparative-review-various-data-repositories) published by Dataverse provide comparisons between a number of repositories. 

**Web Search:**

**Generic data search portals:**



* Google[ https://datasetsearch.research.google.com/](https://datasetsearch.research.google.com/) 
* Kaggle[ https://www.kaggle.com/datasets](https://www.kaggle.com/datasets)
* Wikidata[ https://www.wikidata.org/wiki/Wikidata:Main_Page](https://www.wikidata.org/wiki/Wikidata:Main_Page) 
* Open Data Network [https://www.opendatanetwork.com/](https://www.opendatanetwork.com/) 
* Awesome Public Datasets[ https://github.com/awesomedata/awesome-public-datasets#readme](https://github.com/awesomedata/awesome-public-datasets#readme) 

**Examples of Discipline specific:**



* NASA Earth[ https://www.earthdata.nasa.gov/](https://www.earthdata.nasa.gov/) 
* Cern[ https://opendata.cern.ch/](https://opendata.cern.ch/) 
* NCBI National Center for Biotechnology Information[ https://www.ncbi.nlm.nih.gov/](https://www.ncbi.nlm.nih.gov/) 

**Literature search **

While not ideal, datasets are often attached to scholarly publications in the form of supplementary material, or referenced in text where to find them. 

Ref: [https://github.com/opensciency/OpenData](https://github.com/opensciency/OpenData) 

* What makes data ‘interoperable’ and why is that a good thing?
    * It is when people (or their computers) speak different “languages” (different terminology), and yet, for certain datasets, one can “crosswalk” in order to “translate” from one language (“schema”) to another. This is a good thing because people can reuse data even if it was not originally formatted _exactly_ how they want it by the people who produced it.
* Is Open Science a new trend? (the answer is no)
    * Open Science is as old as science
* What documentation should I provide with a dataset that will be shared with others? What should that documentation include?
*  Can I make a living if I share my science openly? +1 +1
* Is Open Science allowing for others to use my data as their own?
* Is open data free? What is the true cost of open data? +1 +1+1
* How do I get credit if I share my work online? 
    * Always provide a suggested citation when sharing work online. Citation/attribution is a cornerstone of ethical research.
    * Assign a Creative Commons licence that requires attribution (CC-by at minimum). 
*  Why would a scientist want to publish his/her code?
*  Can somebody scoop me with having my data open?+1
*  How often are scientists scooped due to having Open Data?
*  What tools can i use to practice open science/research?
