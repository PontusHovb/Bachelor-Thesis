# Predicting Equity Fund Returns: The Impact of the Momentum-Factor on Performance
Bachelor Thesis in Mathematical Statistics (15 ECTS) <br />
Authors: Pontus Hovberger & Hugo Brunlid <br />

In this thesis we explored the kurtosis of momentum, and 'momentum crashes' both from 2008 as discussed in previous research but also in the light of recent covid-19 stock crash. This is done both using a singlefactor model split by Morningstar Category (based on style and size orienation) and also a multifactor model that in addition to momentum (excess past returns) incorporates size orientation, style orientation and management fee are used to predict excess future returns. Findings of predictive power and longevity of momentum by Carhart are still true for US Equity funds 2000-2023 although impact of size & style factors have significantly changed since Carhart Four-Factor model was first presented in 1997. 

## Abstract
Momentum has been a persistent and robust factor in explaining excess future returns, generating great interest from investors and financial analysts. Following the financial crisis of 2008 and the Covid-19 pandemic, there have been instances of significant momentum crashes. US Equity funds are used to gain insights about the properties of momentum and its predictive ability. Momentum performance is evaluated over the period 2000 to 2023. A multifactor model is developed, using factor attribution to explain the impact on fund performance over time by factors such as risk, size, value-growth orientation and momentum. Conclusions can be made that while momentum have previously been successful in predicting future returns, particularly for growth-oriented funds, recent market situations have lead to underperformance. The multifactor model, incorporating size and value-growth orientation, suggests that momentum is not entirely responsible for the poor performance following the Covid-19 crisis.

## Autocorrelation
![](Auto-correlation matrix return)
*Autocorrelation matrix for absolute returns*
The correlation matrix for absolute returns shows positive autocorrelation for shorter time-periods (1
to 3-months) but a negative for longer time-periods (especially 2 to 4-years). However, this not only captures the time-series component of individual fund returns but also the time-series component of the market as a whole. This correlation matrix is therefore of more interest examining the strengths and lengths of market cycles rather
than momentum in fund-specific returns.

![](Auto-correlation matrix return)
*Autocorrelation matrix for excess returns*
The autocorrelation matrix for excess returns instead indicates that most of the auto-correlation in the shorter time-span is explained by market autocorrelation but that there is a positive correlation between excess past and future returns in the 1 to 4 year time frame.

## Singlefactor model
In the simplest model, future returns are expected to be a function of past returns. To account for other factors (such as style and size orientation), funds are categorized in 6 categories based on their respective Morningstar categories:

| **Region & Size / Style orientation** | Value                       | Growth                       |
|---------------------------------------|-----------------------------|------------------------------|
| US Large-Cap                          | _US Large-Cap Value Equity_ | _US Large-Cap Growth Equity_ |
| US Mid-Cap                            | _US Mid-Cap Value Equity_   | _US Mid-Cap Growth Equity_   |
| US Small-Cap                          | _US Small-Cap Value Equity_ | _US Small-Cap Growth Equity_ |

![](Singlefactor model)
*Momentum coefficient over time for singlefactor model*

## Multifactor model
In a multifactor model, size and style are included as independent variables instead of splitting dataset based on Morningstar category. This enables to capture differences within categories and include all funds in the same regression model.
![](Size distribution)
*Distribution of max-min standardized size factors split per Morningstar category*
![](Style distribution)
*Distribution of max-min standardized style factors split per Morningstar category*

The results shows the predictive power of momentum (positive and significant coefficient) but also the kurtosis of momentum, and 'momentum crashes' both from 2008 as discussed in previous research but also in the light of recent covid-19 stock crash.
![](Multifactor model)
*Momentum coefficient over time for multifactor model*

## Carhart Four-Factor model
![](Average Excess Return for each Decile)
*Average yearly excess returns for each decile*

![](Carhart Four-Factor model)
*Post-formation returns on portfolios of mutual funds sorted on lagged one-year return (Carhart, 1997)*

Findings of predictive power and longevity of momentum by Carhart are still true today although impact of size & style factors have significantly changed since Carhart Four-Factor model was presented in 1997. Our paper and Carhart, 1997 uses different methods for estimating but excess returns but the pattern remains the same in the period 2000 to 2023 as from 1962 to 1987 (Carhart, 1997).

## Links
- [Diva](https://urn.kb.se/resolve?urn=urn%3Anbn%3Ase%3Akth%3Adiva-342321)
- [Google Scholar](https://scholar.google.com/scholar?q=Predicting%20Equity%20Fund%20Returns%3A%20The%20Impact%20of%20the%20Momentum-Factor%20on%20Performance)
