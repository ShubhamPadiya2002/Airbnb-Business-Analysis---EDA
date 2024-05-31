# Airbnb Business - EDA

<p align = "center">
    <img src="https://github.com/ShubhamPadiya2002/Airbnb-Business-Analysis---EDA/blob/main/airbnb43.gif" alt="Example GIF" width="800" height="400">
</p>


Airbnb, Inc. is an American company operating an online marketplace for short- and long-term homestays and experiences. The company acts as a broker and charges a
commission from each booking. **The company was founded in 2008 by Brian Chesky, Nathan Blecharczyk, and Joe Gebbia.** The idea originated when Chesky and Gebbia,
struggling to pay rent, rented out air mattresses in their San Francisco apartment, which evolved into **"Air Bed & Breakfast."** Airbnb has built a vast global community, operating in
over 220 countries with millions of listings. The company went public in December 2020, marking a significant milestone. Today, under CEO Brian Chesky's leadership, Airbnb
continues to innovate, adapting to changing travel trends and fostering cultural exchange through personalized travel experiences
                                                                                                 
**Let's understand the Business Model** 

<p align = "center">
    <img src="https://github.com/ShubhamPadiya2002/Airbnb-Business-Analysis---EDA/blob/main/Business%20Model%20Picture.png" alt="Example IMG" width="800" height="400">
</p>

Airbnb’s revenue model primarily revolves a **two-sided marketplace** around charging service fees to both hosts and guests for facilitating bookings through its platform. Airbnb
generates revenue through service fees charged to both hosts and guests for each booking made on its platform. For guests, the service fee typically ranges from **6% to 12%** of the
booking subtotal, while hosts are charged around **3%** of the subtotal. This fee structure allows Airbnb to earn a commission on every transaction. In addition to these fees, Airbnb
offers various value-added services to hosts, such as professional photography and property management services, which also contribute to its revenue.
                 

## Project Summary
❑ **Purpose of the Project** -- The purpose of this project is to conduct **comprehensive data analysis** on Airbnb with the aim of extracting meaningful insights and identifying trends
or patterns.By performing end-to-end analysis, including some advanced analytics techniques such as **IQR techniques**, exploratory data analysis (EDA).Wtih the help of this project,
we will solve various business problem statements and enhance business strategies & drive overall business growth in the Airbnb ecosystem.                                                                                                                                                        

❑ **Tools & Libraries**

<img src="https://github.com/ShubhamPadiya2002/Airbnb-Business-Analysis---EDA/blob/main/Project%20Images/Screenshot%202024-05-30%20213724.png" alt="Example IMG" width="40" height="40"><a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a><a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <img src="https://github.com/ShubhamPadiya2002/Airbnb-Business-Analysis---EDA/blob/main/Project%20Images/64640642e787ce0fd0e671a1_Matplotlib-100.jpg" alt="matplotlib" width="60" height="40"/> </a>



❑ **Content**  

<table>
  <tr>
    <td><b>Overview of Airbnb</b></td>
    <td>An introduction to the Airbnb platform, and its business model.</td>
  </tr>
  <tr>
    <td><b>Description of Dataset</b></td>
    <td>A detailed explanation of the variables in a dataset.</td>
  </tr>
  <tr>
    <td><b>QnA</b></td>
    <td>Some question and Answer related to Airbnb to getting comfortable with data.</td>
  </tr>
  <tr>
    <td><b>Business Problem Statement</b></td>
    <td>Some problem statement related to Airbnb to find data driven insights.
</td>
  </tr>
  <tr>
    <td><b>Steps of EDA</b></td>
    <td> Perform some steps of Exploratory data analysis such as data cleaning, data mining.
</td>
  </tr>
  <tr>
    <td><b>Explanation of QnA</b></td>
    <td>Detailed explanation of QnA section.</td>
  </tr>
     </tr>
    <td><b>Analysis Problem Statement</b></td>
    <td>Analyze the business problem statement to identify trend or pattern.</td>
  </tr>
  <tr>
    <td><b>Business Conclusion</b></td>
    <td>Discussion about the insights or patterns which help in making future - decisions.
</td>
  </tr>
    
</table>
                                                                                                                                                      
## Business Problem Statement

• Analyze the distribution of prices across the dataset to identify common price ranges.                                                                                                                         
• Find out Top 10 Neighbourhood based on listing properties to identify the neighborhoods with the highest number of listed properties to understand the popularity and demand in different areas.                                            
• Find out Top 10 host based on listing properties to determine the hosts who have the highest number of listed properties to recognize key contributors to the platform.                                                            
• Find the best location for travelers to identify the ideal locations for travelers based on factors such as average price and user reviews.                                                                                              
• Analyze the price trends of different room types (e.g., entire home/apt, private room, shared room) across various cities.                                                                                                              
• Identify any unique characteristics or preferences in each city that influence the distribution of room types.                                                                                                                    
• Determine the city with the highest average price and investigate the reason behind to its pricing.                                                                                                                               
• Examine the relationship between availability of listings and different cities.                                                                                                                                                 
• What is the relationship of diversity of price in each city.                                                                                                                                       
• Investigate the relationship between user reviews and room types across different cities.   

<p align = "center">
    <img src="https://github.com/ShubhamPadiya2002/Airbnb-Business-Analysis---EDA/blob/main/Project%20Images/Screenshot%202024-05-29%20150245.png" alt="Example IMG" width="800" height="300">
</p>

<p align = "center">
    <img src="https://github.com/ShubhamPadiya2002/Airbnb-Business-Analysis---EDA/blob/main/Project%20Images/Screenshot%202024-05-29%20150412.png" alt="Example IMG" width="800" height="300">
</p>

<p align = "center">
    <img src="https://github.com/ShubhamPadiya2002/Airbnb-Business-Analysis---EDA/blob/main/Project%20Images/Screenshot%202024-05-29%20150614.png" alt="Example IMG" width="800" height="400">
</p>

<p align = "center">
    <img src="https://github.com/ShubhamPadiya2002/Airbnb-Business-Analysis---EDA/blob/main/Project%20Images/Screenshot%202024-05-29%20150649.png" alt="Example IMG" width="800" height="400">
</p>

<p align = "center">
    <img src="https://github.com/ShubhamPadiya2002/Airbnb-Business-Analysis---EDA/blob/main/Project%20Images/Screenshot%202024-05-29%20150721.png" alt="Example IMG" width="800" height="400">
</p>


## Business Conclusion

• With the help of price analysis, it can be highly beneficial for Airbnb’s business. Airbnb understanding common price ranges to guide hosts in setting up their listing
properties price to stand out in competitive market. 

• Through this analysis, Airbnb examine where the no. of listing properties are high which help in decisions about where to invest in new features or services based on the
popularity of neighborhoods.      

• By this analysis, Airbnb recognizing top hosts by providing incentives, or loyalty programs to maintain and enhance their engagement with the platform.

• This analysis helps Airbnb to identify the best location for travelers based on reviews and price which helps Airbnb in marketing campaigns to attract travelers who
prioritize staying in well-reviewed places & also marketing promotions for budget-conscious travelers, showcasing locations where they can find the best value for
money.                 

• Through this analysis, Airbnb understands the average price differences between room types which helps Airbnb business to optimize pricing strategies like - cities Brooklyn
and Manhattan where there’s a significant price gap, Airbnb could encourage hosts to offer competitive pricing for private and shared rooms to attract budget-conscious travelers.

• With the help of analysis of market demand, Airbnb understands the trend or pattern of demand (%) of room_type which helps business to make demand & supply strategies
like - Offer incentives to hosts in the Bronx for listing shared rooms and to Manhattan hosts for listing entire homes/apartments.

• This analysis helps airbnb business understanding the diversity of price range which helps in Targeted Marketing like Manhattan offers a wide range of pricing options ,this
insights help to build marketing strategies to attract visitors with varying budgets.      

• This analysis help airbnb business to understand the popularlity of each room_type which helps business to make decisions regarding financial investment like airbnb
support host for listing private room_type in queens city financially.








