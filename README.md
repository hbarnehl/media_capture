# media_capture
This repository contains the replication code for the following article:

Barnehl, H. M., & Schumacher, G. (2024). Media capture, captured: a new computational methodology to measure deteriorating media freedom. Democratization, 1–28. https://doi.org/10.1080/13510347.2024.2331694

We additionally include instructions on how to quickly apply the sentiment-analysis part of the method to new cases.

The folder "replication scripts" contains the code that was used to produce the independence scores and the figures of the article. Because the text is copyrighted, we cannot include it in this repository.

## Implementing the Polarity Independence Score
The sentiment analysis jupyter notebook contains instructions on how to apply the polarity independence score to new cases. All that is required is data in the appropriate form: Tabular data containing texts of news media articles, with additional columns recording the outlet, the publishing date, and (optionally) a column recording the allegiance of the outlet (regime, opposition, or nominally independent).