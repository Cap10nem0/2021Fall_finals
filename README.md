# Effect of Covid on Boston City’s Service requests(311 requests).

Covid has affected every person and company either physically, mentally or financially. Although there were positive outcomes such as Work from home became a norm and mental health is being taken seriously than ever before, the negatives clearly outweigh the positives. Even during these challenging times, front line workers had to put up strong facade and head to work. 

![](https://github.com/Cap10nem0/2021Fall_finals/blob/main/images/311.jpg?raw=true)

311 is one such helpline that helps with issues like abandoned or stolen vehicles, noise complaints, sanitization issue, etc. Although it is not nation-wide, major cities like NYC and San Francisco have it and people often use it to address their non emergency issues. When you call 311, operator picks up the call, hears your concerns and send help accordingly.

In this project, we studied the trends of these requests from  2015 to 2020 in order to study how COVID has affected service response. As part of exploratory data analysis we looked in following points:-

1. Most cases by type before and during pandemic
2. Most cases by location before and during pandemic
3. Most cases by season before and during pandemic
4. Most cases by call source before and during pandemic
5. Mean Time taken to resolve cases per year before and during pandemic

Furthermore ,we tested following hypotheses:

Hypothesis 1: For the customer service requests raised between Jan 1, 2020, and Dec 31, 2020, in Boston, resolution time increased than previous years(2014-2019) due to Covid protocols.
Hypothesis 2: During the peak period of Covid, the frequency of calls per day reduced significantly as citizens were forced to stay indoors.

### Dataset

Before executing the notebook, please extract the [dataset](data.zip) files.

### Results

While working on classifying requests by type, we found out that top 3 categories viz. General Request, Parking Enforcement and Requests for Street Cleaning for which 311 receieved calls remained the same. These 3 requests saw small to minute raise in calls post covid i.e. in 2020. A side by side comparison table is shown below:-  

![](https://github.com/Cap10nem0/2021Fall_finals/blob/main/images/type1.png?raw=true)

Next, as we move on to classify requests by location, locations - 1 City Hall Plz, Boston, MA 02108 and 100 City Hall Plz, Boston, MA 02108 do not lose their top positions. Although they maintain their top positions, it is evident that there has been rise in calls by seeing their percentage contribution. Furthermore, 6 of these locations are same irrespective of covid implying trend did not change. Refer following image for comparison-

![](https://github.com/Cap10nem0/2021Fall_finals/blob/main/images/location1.png?raw=true)

Next we look at the call source, i.e. sources from which these requests were made. Order of top sources does not change pre and post covid times. This implies that Covid did not have any effect on the way requests are made. People's first choice of preference is always Mobile Request, second being Constituent Call and third being City worker App. It is worthy to note that mobile requests and City Worker App saw a rise in requests by approximately 8 and 1 percent respectively.

![](https://github.com/Cap10nem0/2021Fall_finals/blob/main/images/sources.png?raw=true)

### Hypothesis 1: For the customer service requests raised between Jan 1, 2020, and Dec 31, 2020, in Boston, resolution time increased than previous years(2014-2019) due to Covid protocols.

---
To test out this hypothesis, we calculated mean resolution time over years and plotted it on same graph for easy comparison. We can observe from the following graph that the resolution time in 2020 is less than the resolution time in previous years and hence disproving the the hypothesis that the resolution time increased during peak covid period due to Covid Protocols.

![](https://github.com/Cap10nem0/2021Fall_finals/blob/main/images/resolution_time.png?raw=true)
---


### Hypothesis 2: During the peak period of Covid, the frequency of calls per day reduced significantly as citizens were forced to stay indoors.

---
Our second hypothesis that during the peak period of Covid, the frequency of calls per day reduced significantly is true since we can observe from the above graph that during Spring 2020, the frequency of calls reduced significantly compared to pre covid Spring seasons.

![](https://github.com/Cap10nem0/2021Fall_finals/blob/main/images/seasons.png?raw=true)
---
