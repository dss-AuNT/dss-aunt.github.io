---
title: Milestone 2
subtitle: Validation 1

caption:
  title: Milestone 2
  subtitle: Validation 1
  thumbnail: assets/img/timeline/M2.jpg

---

# Problem identification

<em>„A few months ago, I was traveling by train between my hometown and Bucharest. With my CCNP exam being close, I took the opportunity to study for the duration of the trip. The person that was standing next to me happened to be a Senior Network Engineer at Vodafone, and he provided me with some useful advice for my CCNP exam.</em><br>
<em>As the conversation progressed, one of the issues he told me he was struggling with at that moment was migrating his topology from Cisco to Huawei. As part of Huawei’s TAC, he found my feedback regarding his configuration valuable.</em><br>
<em>He told me how, in the past, there used to be network command translators, especially for the smaller vendors. Even that limited functionality turned out to be extremely useful. Yet, these kinds of translators are currently discontinued. And this difficulty of working in multi-vendor environments was something that, at that time, I had already experienced.”</em>
<h5>Alexandru Năstase, Product Owner</h5><br><br>



## Finding a solution


Our plan is to implement a network configuration translation tool to address the issue of vendor transition. To make this process even easier on the customer side, we are planning on implementing automatic configuration of the devices using NETCONF.

# Customer discovery plan


In order to verify that our claim about changing vendors in the networking space is a relevant issue, we decided to conduct an online survey, targeting both network professionals and hobbyists, as these are the customer segments we identified. We decided to disguise the survey as a data collection and assessment about our claims, being careful not to pitch our idea in any way.

# Customer Segment & problem validation

In order to verify that our claim about changing vendors in the networking industry is a relevant issue, we decided to conduct an online survey, targeting both network professionals and hobbyists, as these are the customer segments we identified. We decided to disguise the survey as a data collection and assessment about our claims, being careful not to pitch our idea in any way.

We managed to reach a number of respondents via different social media platforms, such as LinkedIn, Facebook or WhatsApp.

<div class = "Mycontainer"> 
    <img class = "screenshots" src="assets/img/proof/Alex_Facebook.png">
    <img class = "screenshots" src="assets/img/proof/Alex_Linkedin.png">
    <img class = "screenshots" src="assets/img/proof/linkedin.PNG">
    <img class = "screenshots8" src="assets/img/proof/whatsapp.PNG">
</div><br>

# Customer Segment 

For our survey platform we decided to use Google Forms as it satisfies our needs. The questions we asked can be found <a href = "https://forms.gle/NtaNibz5MrkmYVRi9" target="_blank">here</a>. In order to reach all of our customer segments, we used a plethora of platforms, such as: Facebook, LinkedIn and WhatsApp, distributing it to people we thought that might be interested in this domain.

After distributing our survey, we managed to collect a number of 37 answers. Considering that the survey is aimed at a very specific IT domain, we expected a smaller number of respondents. This didn’t however affect the overall quality of our answers: we received a fair number of useful insights that we’ll discuss next.

# Discussing the results
Below you can find an analysis of the answers provided by our form's respondents. The plain answers can be found <a href="https://docs.google.com/spreadsheets/d/1iFS3vL05lR2ij8GXKsBvtCh1oeYSta3hTrJatOAoLP0/edit?usp=sharing" target="_blank">here</a>.

<img class="center" src = "assets/img/results/res1.JPG">
 This question was used to have an approximation of the market share each vendor possesses. This will be used by us to know which vendors we should prioritize over others. You can clearly see that Cisco is the number one technology used, followed by Huawei and Juniper on slightly equal spots.

 

 <img class = "center" src = "assets/img/results/res2.JPG">
 Certifications, especially in the networking world, are a good enough estimation of someone’s skill level. For us, this information is relevant because it provides us with a rough understanding of each person’s proficiency in the subject. We have answers across the whole segment, 81% of them are from people with entry-level experience - having no certification or just the CCNA, yet 19% of the answers are from people with one or multiple CCNPs and even a CCIE. 
 
 

 <img class = "center" src = "assets/img/results/res3.JPG">
 
Out of our answers, about half of them came from professionals and half from hobbyists. This can be interpreted as a balance between our two target groups (but can also be just an imbalance resulting from a bias in the will to respond to surveys between the two groups).

 

 <img class = "center" src = "assets/img/results/res4.JPG">
The size of our respondents' working teams is a metric that we intend to use as an approximation for the network size. 

 

 <img class = "center" src = "assets/img/results/res5.JPG">
When asked whether they have changed vendors in their production environment, 52,6% of the respondents have answered affirmatively. <br>
The respondents that have changed vendors have stated that the transition process took at least two months to at most six months, depending on the size of the network and the number of devices that composed the network; 50% of the respondents stated that the transition process took three to six months, depending on the complexity of the process.

 

 <img class = "center" src = "assets/img/results/res6.JPG">
Out of the professionals that changed vendors, over half of them (60%) found one aspect or another to be difficult and take more time than expected, with most of them stating that the configuration of the devices or the trainings were the main factor of the delay.

 

 <img class = "center" src = "assets/img/results/res7.JPG">
One especially insightful answer stated that the main difficulty that made things take longer than expected while changing vendors was the lack of functionality on the new vendor. While this could be a negative sign, we think that the product we want to develop will help with identifying these kinds of situations in a more timely manner, providing the Network Engineers with powerful insight from the start: they will need to change the approach when configuring the new devices.<br>
While more respondents have used SNMP in the past, compared to NETCONF, the main use case of SNMP was monitoring, while NETCONF was used for configurations. We find the 26,3% of respondents that have used NETCONF a relevant percentage to justify our plan to also use NETCONF to automatically push the configurations generated by our product.


 
<div class="Mycontainer">
 <img class = "centerRes8" src = "assets/img/results/res8_1.JPG">
 <img class = "centerRes8" src = "assets/img/results/res8_2.JPG">
</div>
On the hobbyists side, things were also interesting. When asked how satisfied our respondents are with the vendors they currently use, the responses were positive, the hobbyists stating that they are moderately satisfied to very satisfied with the vendors they currently use.

 
<div>
<img class = "center" src = "assets/img/results/res9.JPG">
</div>
While a higher satisfaction means that they are unlikely to change the vendor or learn a new one, we can observe a very high interest in other technologies among hobbyists, with most of them stating that they would spend less than a month or two learning something new. We find this time to be on the low side. This shows that the idea of a tool to help you see the difference between configurations would be a helpful one.
  

 <img class = "center" src = "assets/img/results/res10.JPG"><br>

When asked how much time they would spend on learning a new vendor's technology, 55,6% of our hobbyists respondents stated that they would not allocate more than one month. Considering the complexity of the current networking vendor technologies, this time is not enough for learning all the requirements of a new vendor. This emphasizes the lack of time our respondents present, meaning that an improvement meant to save as much time as possible is more than needed in this domain.

# Survey analysis conclusions
After analyzing our respondents' answers, we learned that many professionals find the vendor transition process long and difficult due to the complexity of the networks requiring this process and, most importantly, the lack of automation. For this, we consider these responses a good enough validation for our startup project idea.

# Moving to customer validation stage
We consider that the project is ready to be moved to the Customer Validation stage. While changing vendors isn’t the prevalent problem in the networking space, we find that it is a relevant one. This transition took between two and six months, so this can be a real problem for the company. We find that our product will be a valuable addition to the networking space.
