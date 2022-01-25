# Case study 2 : Large Scale Survey

Author: Nicolas Dintzner

## Researcher's voice

The research team is investigating people's preferences regarding potential public policy changes. The objectives is to obtain the perspective "the population" on specific health related public measures. 

To ensure that a representative sample of the population will participate to the survey, the research team will outsource the execution of the survey to a private company specialized in this domain. 

For this study, the population in question is the population of a single european country, in which the research team is currently located. 

## Data perspective

### Data collection

The data is collected through a survey, with a section regarding the demographic profile of the respondents. 
All questions are preferences, using a scale system, such as: on a scale of 1 to 5, to what degree do you agree with the following statement:"a statement". 
The demographic information collected are: 
- education
- income range
- age range

The data is first collected, and the used in combination of a script (in R or python) to obtain descriptive statistics. 

The population is expected to be a representative sample of the whole population of the country, and as such we expect 1 to 2 thousands responses. 


### Ethics perspective

The survey results (in aggregated format) is meant to be made publicly available. It was therefore very important for the participants to be fully aware of what would happen with the expression of their preferences. 

However, the survey being about preferences and not their current health status, emphasize was put on informing participants about what would happen to the provided data rather than anything else. 


### Privacy 

Due to the high number of respondents involved in the survey, and the limited demographic information being collected, the privacy of the participants was not considered to be at risks. 

However, it is important to note that we do not collect "medical information" about the participants, but their perspective on potential health policy. So, while being related to health, this survey did not fall into the "special category" of personal data. 

Because the survey is being ran by a 3rd party, it is important to lay out of the data that will be transfered from the company to the research team and vice-versa. 

### Data sharing

It was decided to limit the data sharing in this project to the bare minumum: no data should be shared between the survey company and the researchers. The survey company should not have access to the results of the participants, but may see the questionaire itself. 

## Solutions & advices

### Data storage
The data should be stored within the research institution as to limit data leaks. 

The researchers have access to an internal tool, approved by the local privacy and ethics team - and this tool is to be used. 

### Legal 

Because we managed to restrict the personal data flow from the research institution and the survey company, we do not need to address GDPR related concerns from a legal perspective. 

## Advice (process)

We decided that the process should run as follows: 
- the researchers create the survey using their internal tool
- once ready, the link is shared with the survey company
- The survey company shares the link to selected participants
- the participants click on the survey provided by survey company and get redirected to the researcher's platform
- the data is collected there. 



## Tags 
- [human research](https://nzr.github.io/DS-BOK/search.html?q=human+research).
- [Far away land](https://nzr.github.io/DS-BOK/search.html?q=far+away+land).

Human research, Far away lands
