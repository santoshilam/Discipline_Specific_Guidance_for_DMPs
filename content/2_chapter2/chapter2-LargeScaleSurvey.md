# Case study 2: Large Scale Survey

Author: Nicolas Dintzner

## Project background

The research team is investigating people's preferences regarding potential public policy changes. The objective is to obtain the perspective of 'the population' on specific health-related public measures. 

To ensure that a representative sample of the population will participate in the survey, the research team will outsource the execution of the survey to a private company specialised in this domain. The population in question is from a single European country in which the research team is located. For this study, the research team prepares the survey and the company disseminates it on their behalf. 

## Research data management considerations

### Data collection

The suvey responses are a representative sample of the whole country, and the research team expects between 1000 and 2000 responses. To collect data on the preferences of survey repondents a scale system is used, such as: 'On a scale of 1 to 5, to what extent do you agree with the following statement...'

The data collected via the survey comprises a section regarding the demographic profile of the respondents. The demographic information collected are: 
- Education
- Income range
- Age range

The survey data is used in combination with a script (in R or Python) to obtain descriptive statistics. 

### Ethics 

Informed consent is required from respondents who participate in the survey. Respondents are made aware that the survey results will be made pubicly available in an aggregated format upon completion of the research. It is important to note that respondents were not asked about their state of health but were asked about their preferences regarding health-related public measures which is deemed less sensitive.

### Privacy  

The survey responses contain personal data relating to the demographic profile of respondents, however, this data does not allow for re-identification of respondents. Despite the high number of survey respondents, due to the limited demographic information being collected the privacy of respondents is not considered to be at risk.

### Data storage and sharing

They survey tool and responses reside within institutional storage to ensure data security. The raw survey data is not shared externally but only accessed by the research team. The company disseminating the survey can only view the survey questions and not the responses. Only the aggregated survey data is made publicly avaialble upon completion of the research.  

## Solutions and advice

### Data storage

- The survey tool should be approved by the institutional privacy and ethics team.
- A secure storage location should be accessible by the research team (e.g. an institutional cloud storage solution).
- Informed consent forms may only be accessed by members of the research team.
- Personal data should not be shared beyond the research team; only aggregated data should be shared.

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
