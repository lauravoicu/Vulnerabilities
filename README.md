# Vulnerabilities

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/voiculaura/)](https://www.linkedin.com/in/voiculaura/)

The datasets used in this project are open source and freely available online. Common Vulnerabilities Exposures (CVE) is a list of publicly disclosed information security vulnerabilities and exposures.

CVE was launched in 1999 by the MITRE corporation to identify and categorize vulnerabilities in software and firmware. CVE provides a free dictionary for organizations to improve their cyber security. MITRE is a nonprofit that operates federally funded research and development centers in the United States.

A CVE entry describes a known vulnerability. Each CVE entry contains a standard identifier number with status indicator (i.e. "CVE-1999-0067", "CVE-2014-12345", "CVE-2016-7654321"), a brief description and references related vulnerability reports and advisories. Each CVE ID is formatted as CVE-YYYY-NNNNN. The YYYY portion is the year the CVE ID was assigned or the year the vulnerability was made public. Unlike vulnerability databases, CVE entries do not include risk, impact fix or other technical information.

Steps:

- Exploratory data analysis and data pre-processing: functions needed to process all input data and visualizations and statistic about the threat proliferation over the years, threat exploitability different exploit types and most affected vendors and products.

- Time series analysis and statistics: moving averages, stationarity, autocorrelation plots. 

- Clustering: kmeans algorithm on multi-dimensional feature space and model evaluation using elbow method and silhouette analysis.

- Topic modelling on the CVE descriptions. 

- CVSS base scores prediction based on vulnerability description using text mining.


## Acknowledgments:

- https://www.kaggle.com/andrewkronser/cve-exploratory-analysis
- https://towardsdatascience.com/k-means-clustering-algorithm-applications-evaluation-methods-and-drawbacks-aa03e644b48a
- https://www.machinelearningplus.com/nlp/topic-modeling-visualization-how-to-present-results-lda-models/

## Contributing

I use this for my own projects, I know this might not be the perfect approach for all the projects out there. If you have any ideas, just [open an issue][issues] and tell me what you think.

If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

## License

Distributed under the MIT License. See `LICENSE` for more information.
