# Problem Statement

Societe Generale (SocGen) is a French multinational banking and financial services company. With over 1,54,000 employees, based in 76 countries, they handle over 32 million clients throughout the world on a daily basis.

They provide services like retail banking, corporate and investment banking, asset management, portfolio management, insurance and other financial services.

With this problem, we’ll help SocGen in building the intelligence to predict, act and maximise their portfolio returns. Think of a portfolio as a basket. The basket can contain diverse instruments such as equity stocks, debentures, mutual funds etc. Each portfolio is allotted to portfolio managers. Intelligence about future performance would help these portfolio managers to act and take necessary steps in order to overcome losses.

In this challenge, given the randomly sampled data, you’ve to predict the portfolio’s annual returns. Keeping data privacy in mind, some of the variables have been anonymised.


# Description

You are given three files to download: train, test and sample submission. You have to make predictions for 4801 portfolios.

Variable Name	Description
portfolio_id	unique ID
desk_id	manager ID (the person handling the portfolio, it can be a team)
office_id	place where portfolio is managed
pf_category	portfolio category (anonymised)
start_date	date when portfolio started
sold	currency (amount sold)
euribor_rate	euribor lending rate (monthly average)
currency	currency in which transaction was made
libor_rate	libor lending rate (monthly average)
country_code	country where office is
bought	currency (price at which portfolio is bought)
creation_date	date when portfolio instruments were traded
indicator_code	anonymised
sell_date	date when portfolio is sold
type	type of portfolio
hedge_value	if a portfolio got hedged
status	anonymised
RETURN	target variable


# Explanation

Start_date might differ from creation_date. Creation_date is the date when the instrument (such as a stock) got transferred to the buyer's account. Stocks are bought on start_date. Instruments don’t immediately get credited to the buyer’s account. Most stock exchanges, make the trade on next day or might take more days. For example, in india, it takes 24 hours for the stocks to show up in buyers account.
Hedging is used to offset risk chances by investing in negatively correlated instruments. For example: Gold is generally a favourite choice of investors to be used as a hedging investment for stock investments i.e when stock market falls, gold prices go up.
