# ai-organizational-scalability-sample-databook

This is the repository for a book using a real case of a Jupyter Notebook with the analysis of a survey.     

An experiment in transitioning to open data and free the approach to report writing done for decades with customers in activities in cultural, organizational, technological change    
And sharing ideas about the future of corporate uses of Artificial Intelligence

Release: 
- 2021-01-05 Jupyter Notebook (V6 as of 2021-01-23) at https://www.kaggle.com/robertolofaro/ai-organizational-scalability-and-kaggle-survey
- 2021-01-06 Reproducibility and output archive at https://www.kaggle.com/robertolofaro/20210106-reproducibility-and-output 
- 2021-01-22 Draft version of the book as PDF archive at https://www.kaggle.com/robertolofaro/ai-organization-scalability-and-kaggle-survey-book
- due 2021-01-31 The (non-free) book with additional attachments will be on https://leanpub.com/ai-organizational-scalability
- due 2021-01-31 The free version (without attachments) will be on https://issuu.com/robertolofaro

This repository contains the following files, as of 2021-01-25:
- Jupyter Notebook Version 6, as released on 2021-01-23
- HTML version of the Jupyter Notebook Version 6 (ZIP file)
- Draft version of the book, as released on 2021-01-22

The Jupyter Notebook follows the narrative of a report as if it were released to an audience that read the 2020 Kaggle Survey Executive Summary.

In order to enable producing the outputs for inclusion in both a reproducibility set (i.e. to "freeze results") and a publication as it would be for any analysis report within a corporate environment, the Jupyter Notebook contains a logic to redirect the output toward files:
- a text file as an audit trail of all the steps execution
- a separate file for each image
- for plotly-generated images, the output contains an HTML, that allows to use plotly feature to interact with data via the HTML output without having access to the original data

