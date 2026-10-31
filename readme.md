Repo includes codes used for empirical part of Crypto event study which help answer research questions.
Names of the files tell which RQ they address, which window is used and under which model
RQs in the study are:
RQ1 - Does the type of event (regulatory, social, security & exchange hacks, or macroeconomic) matter for how cryptocurrency prices react — that is, do abnormal returns differ systematically across event groups?
RQ2 - Does a coin's market-capitalization tier matter for the strength of its reaction — that is, do abnormal returns differ systematically across coin groups?
RQ3 - Does the overall cryptocurrency market react efficiently to new information, showing immediate price adjustments following events?
RQ4 - Are certain events anticipated by investors before the official announcement?

Different windows used are:
[0,1] as main specification
[0,4] as robustness
[0,0] as check after RQ3 findings
For RQ3 and RQ4 window [-2,+4] is used and test each day separately

Two models are used:
1 - Mean adjusted model
2 - Market model using S&P500 as a benchmark

The files with "Unexpected" are robustness checks if the result differ when event that could be anticipated (as a result in RQ4) are removed from the analysis.
