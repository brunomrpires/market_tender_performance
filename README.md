# market_tender_preformance
In this repository you can find the source code and main data used in my Master's Thesis project at Instituto Superior Técnico.

In this project we analyse real life data from a portuguese company working in the construction adn service provider business. This project has two main goals:

- Study the influence of the market state on profit margins practiced by the company in tender auctions.
- Create a decision support tool for the company managers to optimize the offered bids.

After gathering the data from previous auctions where the company participated we first did an initial exploratory data analysis, then, we developed a market index specific to the company itself and its target market. Afterwards, we developed an integrated model to estimate future values of this market index. The next steps consisted of developing several logistic regression models using frequentist and bayesian approaches to predict the company's performance in future tenders and also give a data driven strength level to each proposal so that the company managers can now have a way to quantify the strength of individual proposlas given the market conditions at the time. Finally, using HMM's (Hidden Markov Model) we developed a model that incorporates the market index influence and finds two market states between which the market fluctuates. New logistic regression models were constructed taking now into consideration the markets states found by the HMM. After comparing the performances of the models with and without the market states we found that the former have overall better performance and thus we HMM is well adjusted to the data and is able to create a two state configuration that represents well the evolution of the market in question over the years.

This project was done in parternship with a portuguese company in Lisbon who provided internal data from their performance in past auctions. The internal data will not be available in this repository, however, the models constructed during the project and the public data we gathered to constrcut and estimate the market index are all available in the respective folders.
