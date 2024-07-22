# 📘 Predicting Equity Fund Returns: The Impact of the Momentum-Factor on Performance
Bachelor Thesis in Mathematical Statistics (15 ECTS) <br />
**Authors**: Pontus Hovberger & Hugo Brunlid <br />

In this thesis we explored the kurtosis of momentum, and 'momentum crashes' both from 2008 as discussed in previous research but also in the light of recent covid-19 stock crash. This is done both using a singlefactor model split by Morningstar Category (based on style and size orienation) and also a multifactor model that in addition to momentum (excess past returns) incorporates size orientation, style orientation and management fee are used to predict excess future returns. Findings of predictive power and longevity of momentum by Carhart are still true for US Equity funds 2000-2023 although impact of size & style factors have significantly changed since Carhart Four-Factor model was first presented in 1997. 

## Autocorrelation
<p align="center">
  <img src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Autocorrelation%20matrix%20return.png" alt="Autocorrelation matrix for absolute returns" width="400">
</p>
<p align="center">Figure 1: <i>Autocorrelation matrix for absolute returns</i></p>

The correlation matrix for absolute returns shows positive autocorrelation for shorter time-periods (1 to 3-months) but a negative for longer time-periods (especially 2 to 4-years). However, this not only captures the time-series component of individual fund returns but also the time-series component of the market as a whole. This correlation matrix is therefore of more interest examining the strengths and lengths of market cycles rather than momentum in fund-specific returns.

<p align="center">
  <img src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Autocorrelation%20matrix%20excess%20return.png" alt="Autocorrelation matrix for excess returns" width="400">
</p>
<p align="center">Figure 2: <i>Autocorrelation matrix for excess returns</i></p>

The autocorrelation matrix for excess returns instead indicates that most of the auto-correlation in the shorter time-span is explained by market autocorrelation but that there is a positive correlation between excess past and future returns in the 1 to 4 year time frame.

## Singlefactor model
In the simplest model, future returns are expected to be a function of past returns. To account for other factors (such as style and size orientation), funds are categorized in 6 categories based on their respective Morningstar categories:

| **Region & Size / Style orientation** | Value                       | Growth                       |
|---------------------------------------|-----------------------------|------------------------------|
| US Large-Cap                          | _US Large-Cap Value Equity_ | _US Large-Cap Growth Equity_ |
| US Mid-Cap                            | _US Mid-Cap Value Equity_   | _US Mid-Cap Growth Equity_   |
| US Small-Cap                          | _US Small-Cap Value Equity_ | _US Small-Cap Growth Equity_ |

<p align="center">
  <img src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Singlefactor%20model.png" alt="Momentum coefficient over time for singlefactor model" width="400">
</p>
<p align="center">Figure 3: <i>Momentum coefficient over time for singlefactor model</i></p>

## Multifactor model
In a multifactor model, size and style are included as independent variables instead of splitting dataset based on Morningstar category. This enables to capture differences within categories and include all funds in the same regression model.

<p align="center">
  <img src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Factor%20distribution.png" alt="Distribution of max-min standardized factors split per Morningstar category" width="800">
</p>
<p align="center">Figure 4: <i>Distribution of max-min standardized factors split per Morningstar category</i></p>

The results shows the predictive power of momentum (positive and significant coefficient) but also the kurtosis of momentum, and 'momentum crashes' both from 2008 as discussed in previous research but also in the light of recent covid-19 stock crash.

<p align="center">
  <img src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Multifactor%20model.png" alt="Momentum coefficient over time for multifactor model" width="400">
</p>
<p align="center">Figure 5: <i>Momentum coefficient over time for multifactor model</i></p>

## Carhart Four-Factor model

<p align="center">
  <img src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Momentum%20longevity.png" alt="Average yearly excess returns for each decile" width="800">
</p>
<p align="center">Figure 6: <i>Portfolios of mutual funds sorted on lagged one-year return, bachelor thesis to the left (data from 2020-2023), Carhart 197 to the right (data from 1962-1987)</i></p>

Findings of predictive power and longevity of momentum by Carhart are still true today although impact of size & style factors have significantly changed since Carhart Four-Factor model was presented in 1997. Our paper and Carhart, 1997 uses different methods for estimating but excess returns but the pattern remains the same in the period 2000 to 2023 as from 1962 to 1987 (Carhart, 1997).

## 🔗 Links
- [Diva](https://urn.kb.se/resolve?urn=urn%3Anbn%3Ase%3Akth%3Adiva-342321)
- [Google Scholar](https://scholar.google.com/scholar?q=Predicting%20Equity%20Fund%20Returns%3A%20The%20Impact%20of%20the%20Momentum-Factor%20on%20Performance)
