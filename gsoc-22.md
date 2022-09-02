---
layout: default
---

[Github](https://github.com/satvik-tha-god)

## Google Summer of Code 2020 Work Product Submission
_August 31, 2022_

#### Student
Satvik Singh

#### Organization
[INCF](https://www.incf.org/) -- International Neuroinformatics Coordinating Facility

#### Project Title
[LORIS](http://loris.ca/) Contribute to LORIS: Development of modules and API

#### Mentors
Christine Rogers, Rolando Acosta

### Project Description and Overview
The aim of this project is to contribute to the LORIS codebase in a general sense. This was a highy flexible goal that zeroed in on to improve the pre-exisiting or add new visualizations at the dashboard. Apart from that some secondary goals were to also improve the codebase by adding documentation and improving RB dataset.

#### Deliverables
The list of deliverables for this project were set as follows

1. Familiarization with LORIS codebase
2. Improvements to the pre-existing code and issues
3. Existing API and module bug fixes
4. Code or improve a feature and feature requests
5. Produce documentation about the changes and suggest changes
6. Refactor code after review

#### Timeline
##### May 
My primary goal throughout May was to focus on setting up and setting in on my LORIS and test development environment. I also took this time to get to know my mentors and create a detailed roadmap for the summer with their help. In order to familiarize myself with the LORIS workflow, I created a few very small, mostly documentation-related PRs. I also began to help with manual testing for the 21.0 release, which was a good way to learn about the LORIS codebase and about what automated testing was lacking.

##### June
This period was mainly spent developing unit tests for core LORIS libraries. After discussion with my mentors, it was determined that the unit testing coverage as of the beginning of the summer was not sufficient and that this should take priority over integration test development. I completed unit testing coverage for 7 core libraries in total, improving code coverage by 23% overall. The related PRs are listed below. 

##### July - August
This period was spent working on integration testing, improving RaisinBread, and developing a code coverage tool. I wrote integration tests for modules that were lacking coverage, as well as two helper functions to test new project permissions across all modules. I improved the RaisinBread dataset by adding and making changes to the data that were requested by developers. I configured the PHPUnit code coverage tool to work with LORIS and developed a  script to edit the generated HTML reports. Finally, in the last weeks of August, I created a finalized version of the LORIS Developer's Guide and added it to the publicly available documents on the LORIS repository. 

### Merged Pull Requests
This is the list of my [merged Pull Requests](https://github.com/aces/Loris/pulls?q=is%3Apr+author%3Asatvik-tha-god+is%3Amerged) from the timeline. The PRs will be expanded upon in more detail below.

### Open Pull Requests
This is the list of my [open Pull Requests](https://github.com/aces/Loris/pulls?q=is%3Apr+author%3Asatvik-tha-god+is%3Aopen) from the timeline. The PRs will be expanded upon in more detail below.  

### Visualisation PRs
1. [Visualising of Total in study progression line charts](https://github.com/aces/Loris/pull/6553)
2. [Updated recruitment bar chart to stacked and add total](https://github.com/aces/Loris/pull/6744)
3. [Added a dynamic candidate pie chart to recruitment dashboard](https://github.com/aces/Loris/pull/6765)

### General PRs
1. [Helper functions to test user project permissions, integration tests for the Candidate Profile module](https://github.com/aces/Loris/pull/6912)
2. [Integration tests for the Electrophysiology Browser module](https://github.com/aces/Loris/pull/6922)

### [My Mid-term Presentation](https://docs.google.com/presentation/d/13-NGAn7sJSqOfM19iyXBeyOrk8iFa_uEFE9nRaDywI0/edit?usp=sharing)
I presented my work to the LORIS development team on July 28th. I presented my journey and the progress I had made in my project at that point over the timeline. I discussed the current state of visualisations and LORIS codebase and gave suggestions to the possible directions that LORIS could go in.

### My Experience
The whole timeline of Google Summer of Code was really great for me. I learned a lot in terms of technologies, workflow etc and 

I would like to thank my mentor Christine and also Shen Wang for their help throughout the project. Thank you to the entire LORIS and INCF team for everything, I had a really wonderful experience!
