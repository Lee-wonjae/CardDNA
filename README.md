# The purpose of the project
We aim to create a service that distinguishes consumer characteristics among the recent MZ generation using the popular MBTI personality framework. However, a drawback is that accurately assessing consumer tendencies solely through personality-related questions is challenging. Furthermore, the current service does not extend to providing tailored offerings based on individual personality traits. To address these limitations, we drew inspiration from this service and propose leveraging KT telecommunication's big data platform, specifically utilizing BC card expenditure data. By employing this more precise criterion, we seek to categorize consumers more effectively and recommend cards with benefits tailored to each group.

# The project offers several advantages
By understanding people's economic activities within segmented groups through the service and recommending cards accordingly, it provides a means for businesses to increase card enrollment rates and boost card usage. From the consumer's perspective, there is the benefit of gaining a clear understanding of their spending patterns and using a card tailored to their needs, thereby maximizing personal advantages.

# Dataset
The data used for this project is BC Card usage information provided by KT Telecommunication's Big Data Platform. The dataset records the card usage details of BC Card users, including [Reception Month, Merchant Business Classification (Large), Merchant Business Classification, Age Group Code, Gender Code, Metropolitan City Name, District Name, Amount Indicator, Count Indicator]. The data available on the site spans from January 2020 to August 2023, but for the purpose of understanding the latest consumer spending trends, data from July 2022 to June 2023 was utilized.


# CardDNA Group
**This service distinguishes 16 customer branches through card company data. The classification is as follows:**

|CardDNA|Explanation|
|---|---|
|HBMA|Health and Beauty|
|FCNA|Family Eligibility|
|ITMM|Innovative technologies and range of services|
|TDMM|Digital related technology field|
|HBNE|habits, tourism, travel sector|
|FDNA|Food-related field|
|MANA|There is a mania aspect|
|WLMM|Work&Life Balance Details|
|CENE|Convenient encapsulation for life|
|HCNE|Healthcare field|
|FCNY|Exploring various local restaurants|
|BNMY|A special field in many fields|
|PTMM|Business Related Areas|
|PSNE|Areas of use of public services|
|SPMM|Area of ​​expertise|
|FSMY|Intensive on fashion and style|


**We provide card recommendations and card cover customization services tailored to each customer's pattern group.**

# Python libaries to use in this project
pandas version: 1.3.4 <br>
numpy version: 1.20.3 <br>
matplotlib version: 3.4.3 <br>
sklearn version: 0.24.2 <br>


# Role Allocation
Lee wonjae : EDA and Preprocessing
Park jiwoo : Data Collection and EDA
Nam haeyoon : Model Building 1
Lee seojin : Model BUilding 2

[1] https://carddna.readthedocs.io/en/latest/

