# Data anlysis for Used phone sellers
## Purpose of the project
In this era of digitalization everyone needs a phone, and whats better then good condition used phones. I have a niche for mobile phones and so after some market research
I wanted to start my own small business of selling used phone to the people, though, I had no Idea which phones will have higher selling rate and which phones are to avoid. To
tackle this I created this project where 
- I analyzed Used phone data
- I extract useful information such as Which phone to buy which to avoid, which phone is most likely to get sold easily and earlier compared to other. etc.
- Also created a model to know the price of a used phone. This will help me from getting scammed (Model had .92 R2 score which pretty high)


## Resoruces and Code used
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn

## EDA
Below are the just a few screen shots of my analysis.
**Number of different Mobile Brands**
![alt text](https://github.com/Zain-UlAbedin/used-phone-EDA-and-price-prediction/blob/master/phone%20brands.png "Different Mobile brands")

**Battery VS weight**
![alt text](https://github.com/Zain-UlAbedin/used-phone-EDA-and-price-prediction/blob/master/battery%20vs%20weight.png "Battery vs Weight")

## Actionable Insights and Recommendations

**From above analysis, we saw that many factors are affecting used_price of a mobile phone, following are some Recommendation on which phone to choose to recell**.

- One of the main reason people buy used_phone is because they get high end phones with less money, and that is the driving factor, though, if the used phone 
costs the same as new phones , people might avoid buing it so the company has to keep any eye on the price of the phone. How the price of the phone is affected, is given below.
- Both rear and front camera have huge impact on the phone price, the startup should focus on reselling a phone with rear-camera being the great one and the front 
camera somewhat normal, that way the price will be lower, and people might not complain, because many people prefer the back rather the the front camera.
- 5g also increase the price of the phones, though, 5g phones are good but right now the startup should avoid such phones, as there are yet less development on the 
5g network and it will be long before the 5g actually worth it in the phone, most people are getting by fine with 4g phones, so instead of 5g, 4g phones should be bought to 
make the phones most desireable.
- The last thing, I think will bring down the price of the phone is RAM, althoug RAM is essential but more than 4 GB RAM in a phone will not much effect the performance 
unless heavy games and apps are the desired of the person that is perchasing the phone, there are not much who buys phone for such heavy tasks, and I thing the company 
should avoid buying phones with more than 4 GB RAM, though, if they want they should then only go for phones with 6GB of RAM and no more, 6GB is more than enough.
