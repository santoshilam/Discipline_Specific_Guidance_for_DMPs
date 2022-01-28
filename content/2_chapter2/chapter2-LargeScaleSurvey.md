# Case study 2: Large Scale Survey

Author: Nicolas Dintzner

## Project background

The research team is investigating people's preferences regarding potential public policy changes. The objective is to obtain the perspective of "the population" on specific health-related public measures. 

To ensure that a representative sample of the population will participate in the survey, the research team will outsource the execution of the survey to a private company specialized in this domain. For this study, the population in question is the population of a single European country, in which the research team is currently located. 

For this experiment, the research team prepares the survey, the survey company spreads the survey among its customer/users, and the answers are directly stored on TUD storage solutions.

## Research data management considerations

### Data collection

The data is collected through a survey, with a section regarding the demographic profile of the respondents. 
All questions are preferences, using a scale system, such as: on a scale of 1 to 5, to what degree do you agree with the following statement: "a statement". 
The demographic information collected are: 
- education
- income range
- age range

While this does constitute personal data, the set of information collected is generic enough as not to allow for re-identification of participants (especially considering the population size).

The data is first collected, and then used in combination with a script (in R or python) to obtain descriptive statistics. 

The population is expected to be a representative sample of the whole population of the country, and as such we expect between 1.000 and 2.000 answers.

### Ethics 

The survey results (in aggregated format) are meant to be made publicly available. It was therefore very important for the participants to be fully aware of what would happen with the expression of their preferences. 

It is important to note that the survey did not ask people about their current state of health (beyond something very generic and imprecise). As such, despite tackling a health related social issue, the questionaire itself does not collect "medical data" from participants. For this reason, the main ethical concern is informing properly the participants as to what will be done with the provided data. 

### Privacy 

Due to the high number of respondents involved in the survey, and the limited demographic information being collected, the privacy of the participants was not considered to be at risk. 

Similarly to the ethical concerns, there are no additional privacy requirements - since we do not collect "medical data" from participants. 

As part of the "normal" setup for such survey, the survey tool as well as the collected data will reside within the university's network - as to ensure sufficient data security. Beyond this, no additional requirements had to be satisfied.

### Data storage and sharing

During the project, it was decided to limit the data sharing to the bare minumum: no data collected from the survey should be shared between the survey company and the researchers. The survey company should not have access to the results of the participants, but may see the questionaire itself. 

Within the research teams, all researchers need access to the full answerset and question set. 

The survey results (in aggregated format) are meant to be made publicly available after the research is complete.

## Solutions and advice

### Data storage
The data should be stored within the research institution as to limit data leaks. Any storage approved by the research institution would be suitable (as the data is not "particularly" sensitive). In this instance, the research team opted for a cloud solution approved by the research team.

The researchers have access to an internal tool, approved by the local privacy and ethics team - and this tool is to be used. 

### Legal 

Because we managed to eliminate any personal data flow between the research institution and the survey company, we do not need to address GDPR related concerns from a legal perspective. This is possible because the survey does not collect personally identifiable information, and the survey company did not have access to the participants' answers. 

## Advice (process)

We decided that the process should run as follows: 
- the researchers create the survey using their internal tool
- once ready, the link is shared with the survey company
- the survey company shares the link to selected participants
- the participants click on the survey provided by survey company and get redirected to the researcher's platform
- the data is collected there. 
- all data processing is internal to the research insitute, allowing for the use of all approved resources.

<!---
Not necessary but a diagram would be nice here- no time to make one now though so I haven't attempted it
-->

## Tags 
- [human research](https://nzr.github.io/DS-BOK/search.html?q=human+research).
- [Far away land](https://nzr.github.io/DS-BOK/search.html?q=far+away+land).
- [online survey](https://nzr.github.io/DS-BOK/search.html?q=online+survey)
