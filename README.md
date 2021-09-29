# Project Title :  Indian crop production analysis

## Technologies : Python and Tableau for EDA and Visualizations (Buisness Intelligence)

### Domain : Agriculture

### Problem statement : 

The Agriculture business domain, as a vital part of the overall supply chain, is expected
to highly evolve in the upcoming years via the developments, which are taking place on
the side of the Future Internet. This paper presents a novel Business-to-Business
collaboration platform from the agri-food sector perspective, which aims to facilitate the
collaboration of numerous stakeholders belonging to associated business domains, in an
effective and flexible manner.
This dataset provides a huge amount of information on crop production in India ranging
from several years. Based on the Information the ultimate goal would be to predict crop
production and find important insights highlighting key indicators and metrics that
influence the crop production.

### Tools :

- Data Cleaning (EDA) - Python (Pandas & Numpy)
- Visualizations - Python (Matplotlib , Seaborn)
- Dashboard - Tableau

### Data Cleaning :

**IDE - Jupiter notebook**

Data cleaning and EDA process is done through python , Pandas libraies. There are no duplicate records found. Null values can be found for the production tuple.Hence the null values are imputed based on the mean of the productions in similar districts.Post that Bivariate and Univariate analysis is done to analyse the importance of each variable. Two new columns are added into the data frame :- Zones and categorical crops. The states are categorised based on their respective zones such as North zone , South Zone , East Zone , West Zone , North east Zone , Union terriorteries and central India. Different types of crops are classified into their respective categories like Cereals , Pulses , Oilseeds , Vegetables, Spices, nuts , Commercial , Fibres , Beans and fruits. The additional columns aids us to bring more insights and highlight key indicators that influence the crop production. The new data frame after data cleaning is exported into excel file and is loaded into Tableau dashboard to build the dashboard. 


### Visualisations and insights gained :

**IDE - Jupiter notebook**

Visualisation process is done through Matplotlib and Seaborn libaray.
Finding and visualisations are done for 
- Zone wise total production
- Analysing the state in south zone which produces the highest production
- Analysing the district zone in kerala which gives the highest production
- Crop wise and categorical crop wise productions
- Season wise productions 
- Crop year wise productions
- Analysing the growth of categorical crops in different seasons in different states in India
- Production of crop categories
- State that dominates in crop production by producing a variety of crop categories
- To find which crop is grown in high frequency in India and few insights are deduced and visualised
- To deduce and visualise the state that ranks high in Area wise crop production
- Top crops produced in Northen zone
- Top crops produced in Sothern zone
- Top crops produced in Central zone

### Dashboard :

![Dashboard Crop production](https://user-images.githubusercontent.com/51138087/135317317-9c01ee38-8c8d-4f26-95fa-cba78b4a16fc.png)

- South Zone wise - High production crops : Kerala followed by Andhara Pradhesh & Tamil Nadu
- North Zone wise  - High production crops : Uttar Pradhesh followed by Punjab and Harayana
- Production rate for categorical crops : Commercial crops are yeilded the most in high productions
- Production rate for different tyoes of crops : Coconut is yeilded in high rate
- Production rate from 1197 to 2015 : Steady growth fron 2011 to 2015 & higher production in 2011
- Production rate for different season: In whole year season the crops are yeilded in subsequent amount followed by Kharif and Rabi
- Production rate statewise - Kerala followed by A.P ,T.N and U.P
- Area in sq.ft allocated for crop production in different states of India - Kerala , M.P
- Domination of states in regards to different categorical crops - Uttarpradesh provides a variety of categorical crops and its greater in production wise compared to other states.



