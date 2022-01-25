# Case study 2 : Large Scale Survey

Author: Nicolas Dintzner

## Researcher's voice

The research team is investigating people's preferences regarding potential public policy changes. The objective is to obtain the perspective of "the population" on specific health-related public measures. 

To ensure that a representative sample of the population will participate in the survey, the research team will outsource the execution of the survey to a private company specialized in this domain. 

For this study, the population in question is the population of a single European country, in which the research team is currently located. 

## Data perspective

### Data collection

The data is collected through a survey, with a section regarding the demographic profile of the respondents. 
All questions are preferences, using a scale system, such as: on a scale of 1 to 5, to what degree do you agree with the following statement: "a statement". 
The demographic information collected are: 
- education
- income range
- age range

The data is first collected, and then used in combination with a script (in R or python) to obtain descriptive statistics. 

The population is expected to be a representative sample of the whole population of the country, and as such we expect 1 to 2 thousand responses. 


### Ethics perspective

The survey results (in aggregated format) are meant to be made publicly available. It was therefore very important for the participants to be fully aware of what would happen with the expression of their preferences. 

However, the survey being about preferences and not their current health status, emphasis was put on informing participants about what would happen to the provided data rather than anything else. 


### Privacy 

Due to the high number of respondents involved in the survey, and the limited demographic information being collected, the privacy of the participants was not considered to be at risk. 

However, it is important to note that we do not collect "medical information" about the participants, but their perspective on potential health policy. So, while being related to health, this survey did not fall into the "special category" of personal data. 

Because the survey is being run by a 3rd party, it is important to lay out which data will be transfered from the company to the research team and vice-versa. 

### Data sharing

<!---
Comment: some case studies focus on internal data sharing during research, others on data sharing afterwards. Maybe good to differentiate and mention both? I tried to do this below with my edits.
-->

During the project, it was decided to limit the data sharing to the bare minumum: no data collected from the survey should be shared between the survey company and the researchers. The survey company should not have access to the results of the participants, but may see the questionaire itself. 

The survey results (in aggregated format) are meant to be made publicly available after the research is complete.

## Solutions & advice

### Data storage
The data should be stored within the research institution as to limit data leaks. 

The researchers have access to an internal tool, approved by the local privacy and ethics team - and this tool is to be used. 

### Legal 

Because we managed to eliminate any personal data flow between the research institution and the survey company, we do not need to address GDPR related concerns from a legal perspective. 

## Advice (process)

We decided that the process should run as follows: 
- the researchers create the survey using their internal tool
- once ready, the link is shared with the survey company
- the survey company shares the link to selected participants
- the participants click on the survey provided by survey company and get redirected to the researcher's platform
- the data is collected there. 

<!---
Not necessary but a diagram would be nice here- no time to make one now though so I haven't attempted it
-->

## Tags 
- [human research](https://nzr.github.io/DS-BOK/search.html?q=human+research).
- [Far away land](https://nzr.github.io/DS-BOK/search.html?q=far+away+land).
- [online survey](https://nzr.github.io/DS-BOK/search.html?q=online+survey)

<!---
Is the 'Far away land' tag very meaningful, especially if people from all over the world could be reading this book?
-->

Human research, Far away lands, online survey
