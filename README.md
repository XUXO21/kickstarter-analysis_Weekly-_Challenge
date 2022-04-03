# Kickstarting with Excel

---

## 1. Overview of Project

Kick starter is a cowdfunding platform wich has had great sucess in allowing the people to convert creative projects into life by connecting ideas with great potential with backers that push them into reality. Since Kickstarter launch on April 2009 21 million people have baked a project, 6,5 billion dlls. had been pledged and 218,167 projects have been founded. Source:https://www.kickstarter.com/about?ref=global-footer

For this reason we have been asked to help Louise to undestand how capaigns fared taking in count launch dates and funding goals by using Kickstarter data given to us. This inforation regarding capagns allowed us to know: type and subtype of campaigns, their objetive, how many peolple pledge, the amounts of the actual pledges for the projects and also we have information related to when the capaigns were activated, for how much time and in wich year.

All this on order to give counsil to Louise after her play Fever had good fundraising results in a short amount of time.

### 1.1 Purpose

Purpose of the analysis is that based on the information we have we need to give a recomendation to our client Luise to define her next steps regarding her play. The main objetive is to base on the knowledge we have been generating form previosu classes to undestand data bases, analyse their inforation trough excel tools and learn to come to conlusions and to give recomendations combining, inforation, analysis and comunication skills.

Louise is investing her mony and the money of the people pleadging on her idea so is iportant to be able to give her founded desitions so she can obtain success.

---

## 2. Analysis and Challenges

Anaylisis was generated trough information obtained by the kickstarter .API that gave us inforation from different kind of capaigns like the type of them, a general description, also we had the parameters for undestanding variables for Geography, to undestand not only the US campaigns were our client had interest but also to try to undestand bencharks in other countries or even to know performance in specific markets to determine possible incursion on them. Also wew had information regarding their pledge objectives, actuals pledge, number of bakers and finally we counted with date data like the start and end of the capagins.

The fist challenge we see is that information not allways comes ready or in a friandly way to analyze and generate reports. For example the date was in a non readable format, and because of that we needed to workaround to determine date in an understadable way.

![Date Transformation](/Format%20Date.png)

Another Example is that Category and Subcategory of the campaign were merged making the undestandment of the information more difficult, and for that reason we also divided that information through an additional process.

![Cat and Sub Cat division](/CatDiv.png)

To generate the Analysis we used Excel as the main tool to determine correlation between variables and to segmentate, pivot and use other tools to compare information and move to conclusions.

In this case we faced some challenges with the information included on the data base, for example in terms of information included fot the campagns, both sucessfill and failed, we can see two staditics that let us undestand that the information has opportunties in terms of being representativo or accurate.

Fisrt the standard variation is very far from the mean, indicating strog difference in each quartile and low similarity between the data sets given.

![Stadistics](/StadisticsA.png)

Second the amount of otliers is very big, we have many points outside de quartiles again suggesting strong differences across the data.

![Outliers](/StadisticsB.png)

About the analysis, let's first undestand the category. 

* Theater is the most sucesfull crowdfunind category across the countries and also in the US followed by Music
![All Categories in US](/ALLCATUS.png)

* Within the theaters crowdfounding plays are not only the most important, but also the ones that have most success, but in the other hand also te most failed

![Theaters detail in US](/US_TSUBCAT.png)

### 2.1 Analysis of Outcomes Based on Launch Date

* In terms of the Month of were we can find more amount of succesfull campaigns across countries on May and July, and actually we can discover also that the same trend in the US.

![Trend by Month Global](/Theater_Outcomes_vs_Launch.png)

![Trend by Month US](/MONTHSUS.png)

* But if we undestand the Success to Fail Ratio across the months we can see other months were maybe there is not the same amount of campagns on the air but could be another posiibility to launch if the May-June window gets complicated. Those Months are, Feb, Apr, Jul and Nov.

![Month Ratio](/monthsratio.png)

### 2.2 Analysis of Outcomes Based on Goals

The 92% of the pledges are on the range from $0 yo $14,999 but we can see a bigger amount of succesfull pledges between $0 and $4,999 where the ratio of successful campagns over failed is higer. Also we can see a good ratio in campagns between $35,000 and $44,999 but this range represents only the 1% of the campagns.

![SvsF Ratio](/Outcomes_vs_Goals.png)

Failed Campagns have in average higher mean, median and mode goals so is important to maintain goals on the range below $4,999

![SvsF Ratio](/sTADITICSgOALS.png)

### 2.3 Challenges and Difficulties Encountered

Based on the Analysis we could determine that some challenges can take place for example or the tome period it is important to launch only on the recomended months, the end of the year is not a good idea so the proyect needs to avoid that stage of the year and if timming is not like that taht could mean a difficulty. As per the Objective definition the challenge is the amount of the Goal because if the Goela is above $5,000 the success posibilities get diminished in a great proportion.

---

## 3. Results

### 3.1 Conclusions based on Launch Date

1. Do not extend the campaign for more than 30 days
2. Start the campaign on May or June. If not possible Feb,Apr, Jul or Nov 

### 3.2 Conclusions based on Goals

1. Divide Campagn Goal in two crowdfundings of $5K (Assuming $10k Total Goal)

### 3.3 Limitations of this dataset

Always more information is better, if we could have additional detail of the cast, the post mortem of the play if it was succesful after, the amount of money that they generated in their launch, detail of advertaisemnt, type of media It would be of great help.

### 3.4 other possible tables and/or graphs

We can generate a graph to obtain average pledge per pledger per goal range it would let us undestand the reach of the campaign and aim to attract a specific number of pearsons. Generate a table and graph of the most sucessfull campagns and determine by type and subtype the specifics like duration, details of the campagns and amounts of goal and pledged.

#Link to excel:

https://github.com/XUXO21/kickstarter-analysis_Weekly-_Challenge/blob/main/Kickstarter_Challenge.xlsx
