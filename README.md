# Delivery_X Database Design Implementation and Reporting

![Delivery X logo](https://github.com/SuryaNageshBabu/Delivery_X-Database-Design-Implementation-and-Reporting/blob/main/Delivery_X%20logo.png)

A complete end to end project involving design, implementation of a database using Microsoft SQL Server for a quick delivery startup and ad-hoc reports using Power BI.

![techstack1](https://camo.githubusercontent.com/3fb5c666007b264dde797b2d7e258cae7f336848f3408cef902f04c6065cc146/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6d7973716c2d2532333030662e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6d7973716c266c6f676f436f6c6f723d7768697465)
![techstack2](https://camo.githubusercontent.com/ecef4c543198952452b882c5551593f6c6a7f1f4a2b304d61b0d79ce7cbf1bad/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f706f7765725f62692d4632433831313f7374796c653d666f722d7468652d6261646765266c6f676f3d706f7765726269266c6f676f436f6c6f723d626c61636b)
![techstack3](https://camo.githubusercontent.com/a0089bc3cb81a201fafb501952309feba97e5062e0bda984b24d5906670bba12/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d6963726f736f66745f506f776572506f696e742d4237343732413f7374796c653d666f722d7468652d6261646765266c6f676f3d6d6963726f736f66742d706f776572706f696e74266c6f676f436f6c6f723d7768697465)
![techstack4](https://camo.githubusercontent.com/3accba4a9c3c86c5cd18300b2fc80c4890666662e6ea18361d16d9974a6d8590/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d6963726f736f66745f457863656c2d3231373334363f7374796c653d666f722d7468652d6261646765266c6f676f3d6d6963726f736f66742d657863656c266c6f676f436f6c6f723d7768697465)
![techstack5](https://camo.githubusercontent.com/b0dd0c2b3bbe007ae4eef1f59c17c24ce53a334ad46bfdb80b5c841eaeccdde3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6d61726b646f776e2d2532333030303030302e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6d61726b646f776e266c6f676f436f6c6f723d7768697465)


## Overview

Delivery_X is a quick grocery delivery service startup with stores across 2 different cities in Germany, it is currently experiencing significant growth and facing customer service challenges, including order processing delays, delivery issues, product quality issues and as a result there is an increase in customer complaints & refunds made on the orders. Negative reviews are rising which could harm the startup's growth.

The company's database contains extensive data on order histories, refunds, type of complaints etc. And the Head of Operations at Delivery_X wants to use this data to analyse the performance of the stores (for the period of summer 2022 between April - September) and implement solutions to improve customer satisfaction. Here below I have attached a business knowledge document containing information on all the key metrics and performance indicators used in the project.

## 1. Database design

Inorder to have a stuctured approach to the design process, I have adapted *Kimball's 4 step process to design the data models*.

* **Understanding the business process & requirenments gathering**

  Delivery_X is a quick delivery service which delivers groceries in relatively smaller delivery windows in comparison to conventional delivery services. It is currently 
  offers its services in 2 different cities across Germany and both the cities have a Delivery_X store each. The company delivers groceries to its customers who place orders   through Delivery_X's mobile application.

  Considering the nature of the service and based on my previous experience I assume that the delivery, customer satisfaction and store operations to maintain product 
  quality are a few aspects which would be core to its value proposition to the customers.

  Different stakeholders involved directly and indirectly: Head of Operations, Customers, Store Operations manager, Operation associates, Delivery riders & Customer service.   
* **Declare the grain**

  Having concluded on the key stakeholders, based on the requisites from the problem statement I beleive the grain of the data should be the different type of customer 
  complaints at the store level and the timeline of theie timeline.

  The company's database (a flat file containing a table with all the attributes relevant to the store, customer and customer complaints) [here](www.comingsoon.com). I have 
  used this as my primary data source and I have further normalized this data to create a data model for better analysis.

* **Identifying the dimensions**
* **Identifying the facts**







