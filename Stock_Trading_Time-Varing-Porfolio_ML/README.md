# Example Stock Trading Strategy for time-varing portfolio

## ML to construct Signal


## Detail

With 3 years of Price/Volume data, Fundamental data, and Reference data on 200 stocks that trade in the same market. Build a time-varying portfolio using python.
 
Including:
1.	Data cleaning methods
2.	Research process i.e. data exploration, signal construction, and robustness
3.	Backtest presentation and signal evaluation metrics
4.	Portfolio construction and risk management


## Environment:

•	aiohttp: 3.8.1

•	beautifulsoup4: 4.9.1

•	flask: 1.1.2

•	gmpy2: 2.0.8

•	jinja2: 2.11.2

•	matplotlib: 3.3.0

•	mpld3: 0.3.1.dev1

•	numpy: 1.19.1

•	pandas: 1.0.5

•	regex: 2020.7.14

•	requests: 2.24.0

•	scikit-learn: 0.23.1

•	scipy: 1.5.2

•	seaborn: 0.10.1

•	six: 1.15.0

•	sqlalchemy: 1.3.19


## Data description:
 
### technical.csv	
date	daily (3 years 2020 - 2022)

id	unique identifier

px_raw	raw price

px_adj	price adjusted for corporate actions

vlm_adj	volume adjusted for corporate actions

beta	adjusted beta
	
### fundamental.csv	
date	quarterly (3 years 2020 - 2022)

id	unique identifier

eps	announced earnings per share

revenue	announced revenue
	
### reference.csv	
id	unique identifier

mktcap	market capitalization as of 31 Dec 2022

gics	GICS sector name

