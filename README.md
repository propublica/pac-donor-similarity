# PAC Donor Similarity Scores

This repository contains cosine similarity scores for PAC donors to congressional recipients, as described in the ProPublica story "[Campaign Donations Reflect the Sharp Split in Congress Among Republicans](https://www.propublica.org/article/campaign-donations-reflect-the-sharp-split-in-congress-among-republicans)," published on Jan. 22, 2016. ProPublica’s analysis used a calculation called cosine similarity to compare each House members' donors to others; two members with an identical set of donors would receive a score of 1, while two with no PAC donors in common would get a score of 0. The cosine similarity was produced using [Bedfellows](https://github.com/TheUpshot/Bedfellows/blob/master/introduction.md), a Python library for analyzing Federal Election Commission data.

This repository currently has cosine similarity scores comparing 2014 PAC donors to Paul Ryan, the current Speaker of the House of Representatives, to other House members during the 113th Congress (2013-2014).
