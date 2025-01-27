# Interest-Ing:	How Interest Rates Combat Inflation

#### **INFO-201: Technical Foundations of Informatics - The Information School - University of Washington for Winter 2022**

**Authors**: Mat Medina, Jaden Wang, Seung Lee

## Abstract
The *federal interest rates* are a key driving force of the United States economy; from combating inflation to stimulating economic growth, no one move affects the economy more than the federal reserve. That being said, how effective is the adjustment of interest rates really? How does the economy scale with this supposedly highly effective system? We plan on cross analyzing the federal interest rate changes with the rates of economic growth, decay, and inflation. **Keywords:** *Basket of Goods*, *Unaccounted Factors*, *Estimation*.

## Introduction
For the Project, Jaden, Mat, and Seungjoo are cross-analyzing data on changes in the federal interest rate to data on rates of economic decline, growth, and inflation to explore the effectiveness of the action of adjusting the interest rates by the government. We also plan to explore the consequences and benefits that these adjustments have on the economy as a whole and see how well it scales against the adjustments. The 4 main data sets that we are using for our project are the **Federal Reserves Interest Rates**, which displays sub data sets such as Unemployment rates and Real GDP as well as displaying the inflation rates set the year to year from 1954 to the present, the **Historical Federal Interest Rates** which serves to supplement extended looks into the inflation rates from the previous dataset, **the Consumer Price Index of all urban consumers in the US**, as well as the **US Consumer Price Index** data sets which displays the average CPI in each city.

## Design Situation
#### Framing the topic of concern
*Governmental oversight* is always a necessary step in maintaining a functioning society. An extremely important aspect of the society which is the United States is an *immensely strong economy backed by an effective federal reserve*. Based on the state of the economy, the fed increases and decreases the federal interest rate to combat inflation or stimulate spending. That being said, **government entities are by nature highly flawed**, thus we must **validate the efficacy** of the fed by *cross referencing* inflation and the relative fed response.

#### Human Values
A human value that could be involved with the datasets provided could be **integrity**. If an influential figure such as a politician or, more specifically, someone who is campaigning to run for Presidency had access to these datasets, they could use it to push their own agendas instead of ones that are for the common good. These figures of massive influence could use the datasets provided to *skew or push* a certain narrative that *benefits them* and allows them to gain an unfair political advantage. Data compiled when formulating the basket of goods may not always accurately reflect the actual mix of goods and services that individuals within the economy are purchasing.

#### Stakeholders 
The *American people* (as well as other countries that look to the United States' interest rates and federal) are all **primary stakeholders** in this project. It is extremely important for the American People (those whom the economy affects the most) to understand how effective the entities in charge of the economy are. The motivations are simple: ensure those who are in in control of the most powerful economy in the world stay *accountable*. The **indirect stakeholders** are *everyone outside of the United States*. There are an exorbitant amount of countries that *rely on the US economy* for support and guidance; they too should have validation that the fed knows what its doing.

#### Benefits and Harms
The result of this technological intervention **benefits almost every demographic**. Keeping government entities accountable ensures *informed voters and healthier environment*. The drawbacks are that an increase in data and awareness may allow **select few** to *exploit that information* and find ways to *manipulate the economy* in ways we can't foresee. Additionally, it also *harms those who bet against the market* such as bearish options traders and those of a similar caliber.

## Research questions
For our research questions, we aim to look into our choice of topic while utilizing these three questions as a basis and guide for the information that we would look and dissect into:
* **What are the factors that determines the federal interest rate?**
* **What intended effects are considered when calculating the federal interest rate?**
* **What sort of outcomes have the shift of the federal interest rate over time caused our economy?**

We're aiming to answer these questions in hopes of getting a better understanding on  how and why we came to be have the amount of federal interest rate that we have today, what it tells us of the current state of the economics of our society, its prior circumstances that might show entail why it grew the way it did, and the future implications for whether it continues to grow at a steady rate, exponentially increases, or unexpectedly diminish.

## The Dataset
#### Size and Complexity:
For our primary dataset, **Federal Reserve Interest Rates, 1954-Present**, it contains about *904 Observations*, and about *10 variables*. Along with our secondary datasets, **US Consumer Price Index and Inflation (CPI)**, **Historical Federal Interest Rates-Daily**, and **U.S. Inflation Data**, we'll have a total of *27420 observations*, and *17 variables*.

#### Origins:
[Federal Reserve Interest Rates, 1954-Present](https://www.kaggle.com/federalreserve/interest-rates) represents the federal interest rate starting from July of the year 1954, it details a the federal funds higher target, lower target, the desired target rate, and the effective rate, along with the Real  GDP, unemployment rates, and the inflation rates. The interest rate data came from the Federal Reserve Bank of St. Louis' economic data portal. The gross domestic product data was from the US Bureau of Economic Analysis, and the unemployment and consumer price index data was provided by the U.S. Bureau of Labor Statistics. This is published by the Federal Reserve, and is under public domain.

 [Historical Federal Interest Rates-Daily](https://www.kaggle.com/dennisholeski/historical-fed-funds)similarly represents the federal interest rate starting from July of the year 1954, up to January of 2021, while it is more up to date than the previous dataset, it only contains the interest rate percentage over the months/years. It seems to source from MacroTreneds and was published by Dennis Holeski who aimed to use the dataset as a reference in conjunction with other economic data and indicators.

[U.S. Inflation Data](https://www.kaggle.com/varpit94/us-inflation-data-updated-till-may-2021) represents the consumer price index starting in the January in the year 1913 by the months until the January in the year 2021, the data comes from the U.S. Bureau of Labor Statistics where it was downloaded into Excel and rearranged by Arpit Verma, a risk modeller at Wells Fargo for the purpose of detailing the Average CPI for all US cities, in a given month since it was first tracked.

[US Consumer Price Index and Inflation (CPI)](https://www.kaggle.com/tunguz/us-consumer-price-index-and-inflation-cpi) similarly also represents the consumer price index starting in the January in the year 1913 but it only goes up to the January of the year 2014, what this dataset makes up for its unaccounted years is the amount of inflation compared to the previous years but otherwise it tells a similar tale from the U.S. Bureau of Labor Statistics. This one was published by Bojan Tunguz, a data scientist from Nvidia.

## Expected Implications
**Technologies** by design aim to improve within their field of industry, so for ones who effectively are aware of the implications of the federal interest rate, they'd have adjusted how the industry would need to operate within the confines of the policies pushed out in the most efficient way possible. **Designers** who serve as a medium between consumers and the industry would have to relay their understanding of how the federal interest rate affects the consumers to the backers of the industry, and in reverse would have to properly push forward the policies given to them. **Policymakers** would be the ones to hold the highest implications within the topic as they are the ones who have to make the calls for the federal interest rate by the months and years, according to what they plan to use them on and if whether the resulting expense falls within their predicted range.

## Limitations
Using CPI to **measure** inflation, however, has *many* drawbacks. These drawbacks are due to the fact that the Consumer Price Index *fails to take into consideration other factors* that impact inflation as well such as product quality, new products, substitute products’ availability, and the different spending or buying habits of each individual in a market anywhere in the world. The CPI *ignores technological advances or changes* that may improve the quality of a certain product which does not necessarily increase in price which solely impacts the CPI. **New products** that are released in a market *do not always make it into the* **basket of goods** used to calculate CPI. Due to the vast and diverse amounts of substitutes currently available in any market for most types of goods, consumers may choose to not purchase what they were initially going to and seek out a cheaper alternative. The CPI *cannot accurately account for such shifts of preferences* to substitute goods. The actual mix of goods that any individual acquires is on average very different from what the CPI accounts for its basket of goods. Also, the CPI’s basket of goods does not take into account the level of income each individual may have (may be people from lower-income households where they use bigger portions of income on food). These factors may make it *difficult to accurately* calculate inflation rates with just the CPI because a lack of these factors may *overestimate* or *underestimate* the **real inflation value**.

## References
Banton, Caroline. “Interest Rate.” Investopedia, Investopedia, 8 Feb. 2022, https://www.investopedia.com/terms/i/interestrate.asp.

Comenity Direct, https://direct.comenity.com/financial-learning/why-the-fed-funds-rate-should-matter-to-you. 

“Why Does the Fed Care about Inflation?” Website, 21 Oct. 2014, https://www.clevelandfed.org/en/our-research/center-for-inflation-research/inflation-101/why-does-the-fed-care-get-started.aspx#:~:text=When%20inflation%20is%20too%20high,economy%20and%20move%20inflation%20higher. 
