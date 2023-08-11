# Vieques_Airbnbs_Gentrification
## Project 4

Recent protests have brought attention to Vieques, an island municipality within Puerto Rico's 78 administrative divisions. These demonstrations coincided with Leon Yin's class project, focused on Airbnb’s Undocumented API.

The heart of the protests in Vieques centered around the issue of displacement, with the movement predominantly spearheaded by organized groups of women. This contextual backdrop prompted my exploration of the Airbnb platform in search of deeper insights. 

Upon delving into the listings for rental properties, a pattern emerged: each property had an associated host profile. These profiles often contained information about the host's place of residence. As I navigated through the listings in Vieques, a conspicuous trend emerged — a significant number of hosts claimed residences outside Vieques and Puerto Rico.
The phenomenon of foreigners acquiring properties in economically challenged regions with high tourist appeal, such as Vieques, encapsulates the intricacies of gentrification. It spurred me to investigate further: Who exactly were the hosts behind these Vieques listings, and how many among them actually resided on the island or within Puerto Rico?

## Data Collection Process

Leveraging the power of Selenium, I initiated a web scraping operation targeting Airbnb's website. My primary focus was on Vieques listings, which purportedly numbered 537. However, upon scrutiny, only 270 of these were accessible within the visible span of 15 pages.

To proceed, I compiled a list of URLs corresponding to the 270 Vieques Airbnb listings. This compilation then facilitated the extraction of 219 host profile URLs. Parsing these links, I identified that some hosts were responsible for multiple properties, which amounted to a total of 153 distinct hosts. My endeavors yielded their profiles, which held valuable descriptions.

|  Data                 | File                                                                                                          |
| --------------------- | ------------------------------------------------------------------------------------------------------------- |
|Total of listings by place of living of hosts |[sum_counts_by_livesin.csv](https://github.com/cristinadelmar/Vieques_Airbnbs_Gentrification/blob/main/sum_counts_by_livesin.csv)          |
|Total of hosts living in each place outside of Vieques and Puerto Rico| [value_counts_by_livesin.csv](https://github.com/cristinadelmar/Vieques_Airbnbs_Gentrification/blob/main/value_counts_by_livesin.csv)    |


## Data Analysis Process

I analyzed the results using Pandas. Out of the collected hosts, 20 claimed to reside in Vieques, 47 identified with other parts of Puerto Rico, and a substantial 52 were associated with residences elsewhere in the world, completely unaffiliated with Vieques or Puerto Rico. This notable statistic underscores a compelling truth: nearly half of the proprietors behind Vieques' short-term rental properties are not integral members of the local community, leading to a minimal impact on the local economy.

The story webpage is here: [https://cristinadelmar.github.io/parks-recovery-puerto-rico/](https://cristinadelmar.github.io/Vieques_Airbnbs_Gentrification/)

## Skills learned

This was my first time using Selenium and brwoser automation for a project. I learned about how to get the elements in a webpage and to write the code to loope through differente urls in order to get the information I want for data analysis. 

## Things I would’ve liked to do

The unavailability of host profiles for some listings, possibly attributed to sleep times within the scraping loops, remains a technical aspect I would refine. Additionally, the incongruence between Airbnb's reported 537 listings and the observed 270 listings warrants investigation to unveil the missing information.

While the process of scraping absorbed substantial time that could have been invested in crafting more intricate and captivating visualizations, I view this as an opportunity for future growth and skill enhancement as I progress beyond the scope of this program.


 
