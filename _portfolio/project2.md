---
title: Milestone 2
subtitle: Validation

caption:
  title: Milestone 2
  subtitle: Validation
  thumbnail: assets/img/portfolio/M2.png  

---

# Problem identification

A few months ago I traveled by train between my hometown and Bucharest. With my CCNP exam being close, I took the opportunity to study for the duration of the trip. The person that was standing near me happened to be a senior network engineer at Vodafone, and he provided me with some useful advice for my CCNP exam.

As the conversation progressed, one of the issues he told me that he is currently struggling with was migrating his topology from Cisco to Huawei. As part of Huawei’s TAC, he found my feedback regarding his configuration valuable.

He told me how, in the past, there used to be network command translators, especially for the smaller vendors. Even that limited functionality turned out to be extremely useful. Yet, these kinds of translators are currently discontinued. And this difficulty of working in multi-vendor environments was something that, at that time, I had already experienced.

## Finding a solution


We are planning on implementing a network translator to address the issue of topology migration. To make this process even easier on the customer side, we are planning on implementing automatic configuration of the devices using NETCONF.

# Customer discovery plan


In order to verify that our claim about changing vendors in the networking space is a relevant issue, we decided to conduct an online survey, targeting both network professionals and hobbyists, as these are the customer segments we identified. We decided to disguise the survey as a data collection and assessment about our claims, being careful not to pitch our idea in any way.

# Customer Segment & problem validation

In order to verify that our claim about changing vendors in the networking space is a relevant issue, we decided to conduct an online survey, targeting both network professionals and hobbyists, as these are the customer segments we identified. We decided to disguise the survey as a data collection and assessment about our claims, being careful not to pitch our idea in any way.

We managed to reach a number of respondents via different social media platforms, such as LinkedIn, Facebook or WhatsApp.

<div class = "Mycontainer"> 
    <img class = "screenshots" src="assets/img/proof/Alex_Facebook.png">
    <img class = "screenshots" src="assets/img/proof/Alex_Linkedin.png">
    <img class = "screenshots" src="assets/img/proof/linkedin.PNG">
    <img class = "screenshots8" src="assets/img/proof/whatsapp.PNG">
</div>

# Customer Segment 

For our survey platform we decided to use Google Forms as it satisfies our needs. The questions we asked can be found <a href = "https://forms.gle/NtaNibz5MrkmYVRi9" target="_blank">here</a>. In order to reach all of our customer segments, we used a plethora of platforms, such as: LinkedIn, Microsoft Teams, Facebook, WhatsApp and directly distributing it to people we might think are interested in this domain.

After distributing our survey, we managed to collect a number of 37 answers. Considering that the survey is aimed at a very specific IT domain, we expected a smaller number of respondents. This didn’t however affect the overall quality of our answers: we received a fair number of useful insights that we’ll discuss next.

# Discussing the results 

<img class="center" src = "assets/img/results/res1.JPG">
 This question was used to have an approximation of the market share each vendor possesses. This will be used by us to know which vendors we should prioritize over others. You can clearly see that Cisco is the number one technology used, followed by Huawei and Juniper on slightly equal spots.

 

 <img class = "center" src = "assets/img/results/res2.JPG">
 Certifications, especially in the networking world, are a good enough estimation of someone’s skill level. For us, this information is relevant because it provides us with a rough understanding of each person’s proficiency in the subject. We have answers across the whole segment, 81% of them are from people with entry-level experience - having no certification or just the CCNA, yet 19% of the answers are from people with one or multiple CCNPs and even a CCIE. 
 
 

 <img class = "center" src = "assets/img/results/res3.JPG">
 
Out of our answers, about half of them came from professionals and half from hobbyists. This can be interpreted as a balance between our two target groups (but can also be just an imbalance resulting from a bias in the will to respond to surveys between the two groups)

 

 <img class = "center" src = "assets/img/results/res4.JPG">
We used this metric as an approximation for the network size. 

 

 <img class = "center" src = "assets/img/results/res5.JPG">
When asked whether they have changed vendors in their production environment, 52,6% of the respondents have answered affirmatively
The respondents that have changed vendors have stated that the transition process took at least two months to at most six months, depending on the size of the network and the number of devices that composed the network; 50% of the respondents stated that the transition process took three to six months, depending on the complexity of the process

 

 <img class = "center" src = "assets/img/results/res6.JPG">
Out of the professionals that changed vendors, over half of them (60%) found one aspect or another to be difficult and take more time than expected, with most of them stating that the configuration of the devices or the trainings were the main factor of the delay.

 

 <img class = "center" src = "assets/img/results/res7.JPG">
One especially insightful answer stated that the main difficulty that made things take longer than expected while changing vendors was the lack of functionality on the new vendor. While this could be a negative sign, we think that the product we want to develop will help with identifying these kinds of situations in a more timely manner, providing the network engineers with powerful insight from the start: they will need to change the approach when configuring the new devices.
When asked whether they have used NETCONF, only 26,3% of our professional respondents have answered affirmatively, stating that the
While more respondents have used SNMP in the past, compared to NETCONF, the main use case of SNMP was monitoring, while NETCONF was used for configurations. We find the 26.3% of respondents that have used NETCONF a relevant percentage to justify our plan to also use NETCONF to automatically push the configurations generated by our product.


 
<div class="Mycontainer">
 <img class = "centerRes8" src = "assets/img/results/res8_1.JPG">
 <img class = "centerRes8" src = "assets/img/results/res8_2.JPG">
</div>
On the hobbyist side, things were also interesting. When asked how satisfied our respondents are with the vendors they currently use, the responses were positive, the hobbyists stating that they are moderately satisfied to very satisfied with their current vendors.

 
<div>
<img class = "center" src = "assets/img/results/res9.JPG">
</div>
While a higher satisfaction means that they are unlikely to change the vendor or learn a new one, we can observe a very high interest in other technologies among (amogus?) hobbyists, with most of them stating that they would spend less than a month or two learning something new. We find this time to be on the low side. This shows that the idea of a tool to help you see the difference between configurations would be a helpful one.
  

 <img class = "center" src = "assets/img/results/res10.JPG">
While a higher satisfaction means that they are unlikely to change the vendor or learn a new one, we can observe a very high interest in other technologies among (amogus?) hobbyists, with most of them stating that they would spend less than a month or two learning something new. We find this time to be on the low side. This shows that the idea of a tool to help you see the difference between configurations would be a helpful one.

# Moving to customer validation stage

We consider that the project is ready to be moved to the Customer Validation stage. While changing vendors isn’t the prevalent problem in the networking space, we find that it is a relevant one. This transition took between two and six months, so this can be a real problem for the company. We find that our product will be a valuable addition to the networking space.
