---
title: 'A decentralized public transportation system'
date: 2023-02-01
permalink: /posts/2023/02/decentralized-public-transportation/
tags:
  - travel
  - Africa
  - research
---

In conventional wisdom, a local government or companies control and manage its city public transportation in centralized or federated fashions. In this paper, we[^1]  introduce a decentralized public system without centralized control. This public transportation system achieves low cost and low latency overhead with price and traffic flexibility that can adapt to the complex and dynamic operating cost and traffic flow. Those features ensure that such a system is practical, efficient, and optimal to be deployed in a city of low-income developing countries. We demonstrate that it is possible to “design” a suitable city-wised public transportation system without any system designer.

## System Goals

Before introducing the decentralized public transportation system, we outline some goals suitable deployed in a city of low-income developing countries.
1.	Low Cost: The transportation fee should be minimal.
2.	Low Latency Overhead: The waiting time should be acceptable. 
3.	Price Flexibility: The price should be flexible enough to incorporate the changes in the operating costs.
4.	Traffic Flexibility: The system can adapt the traffic demands dynamically. 
5.	Decentralization: There is no centralized planning or control. 

## Protocol Overview

We introduce the system with illustrative examples to distinguish this paper from other hard-to-understand system research papers. All the examples are real and happened on our trip to Nouakchott (the capital city of Mauritania with one million population), where there is almost no city bus available, and the only available option for local people to travel is to take shared taxis.

### Example one: from nowhere to somewhere

We got off at an unknown place when we first arrived in Nouakchott and we knew the GPS location of where we should go next; however, we did not know how to take city buses to the destination (as there is no city bus), nor know how to take a taxi with the destination named in English or French rather than a pair of numbers. 

We searched the nearby area to find something famous to be the name of our destination. Suddenly we found a Carrefour. We were amazed that they have the Carrefour in Mauritania, as we had not seen a single Carrefour supermarket after we left Agadir in Morocco. However, we soon realized that this is not the supermarket Carrefour, but a real carrefour as a crossroad. The carrefour is named Aziz. As soon as we were confident enough to pronounce the name, we were ready to take a taxi to our destination.

After a few failed tries, we soon realized that no taxi would take us to carrefour Aziz, which is too far (but only 7km). Instead, a local guy told us we should take a taxi first to carrefour of police routière, where we could take another taxi to carrefour Aziz. Soon, we found a taxi that took us to carrefour of police routière, and there we found another taxi to carrefour Aziz. Figure 1 presents the detailed route.

<figure>
<img src="{{url}}/images/blog/2023-02-01-decentralized-public-transportation-1.jpeg" style="width:100%">
<figcaption align = "center"><b>Figure 1: From nowhere (Point A) to somewhere (Point C) with one transit at carrefour of police routière (Point B)</b></figcaption>
</figure>

Unlike a real taxi, all taxis in Nouakchott are shared taxis, meaning one has to take the taxi with other passengers. As no shared taxis are heading toward carrefour Aziz directly from where we were (because it is not in the same direction), it is not surprising that we could not find any taxis initially. 

The taxi price is amazingly low, only 10 MRU (0.28 USD as of Jan 2023) per ride per person, although we were special “treated” and asked to pay 20 MRU per person for the first ride as new foreign travelers who did not know the local price. 

The system is similar to the modern metro system in that one may change lines multiple times to reach their destination, and one metro car carries multiple people. In the case of shared taxis in Nouakchott, the de facto number of passengers is six, even though the taxi only has four seats for passengers (obviously, locals are skinny).

### Example Two: From Carrefour Aziz to Ouad Naga

Ouad Naga is a small town with some camels 50 km from Nouakchott. We departed for this town at 6:30 am when it was still dark. Nevertheless, the public transportation system was operating. We first took a taxi ride from carrefour Aziz to carrefour Madrid and then took another taxi ride to Toujounine where we could transfer again to our final destination, Ouad Naga. The cost within the city limit is 10 MRU per person per ride, whereas the long intercity ride costs 50 MRU (1.35 USD as of Jan 2023). Figure 2 shows the detailed route, and Figure 3 presents the transit station in Toujounine: nearly every car serves as a shared taxi.

<figure>
<img src="{{url}}/images/blog/2023-02-01-decentralized-public-transportation-2.jpeg" style="width:100%">
<figcaption align = "center"><b>Figure 2: From carrefour Aziz (Point A) to Ouad Naga (Point D) with two transits at carrefour Madrid (Point B) and Toujounine (Point C)</b></figcaption>
</figure>

<figure>
<img src="{{url}}/images/blog/2023-02-01-decentralized-public-transportation-3.jpeg" style="width:100%">
<figcaption align = "center"><b>Figure 3: Transit station in Toujounine: nearly every car serves as a shared taxi.</b></figcaption>
</figure>


## Achieving the System Goals

1.	Low Cost: The price is low and affordable by locals.
2.	Low Latency Overhead: Finding shared taxis is amazingly fast, as there are many taxis with two more places in each taxi. We rarely wait more than 3 mins. 
3.	Price Flexibility: There is no listed price. The driver can tell the passengers if this trip would not use the conventional price (in the local language, of course).
4.	Traffic Flexibility: If a driver finds out that another route is more profitable than the route they[^2] are operating now, they can change to operate in the more profitable one immediately.
5.	Decentralization: The local government or companies do not manage or control public transportation. It is decentralized and operated by each shared taxi driver. 

## Future work

It is unclear how to provide safety to passengers, as nobody wears a safety belt. Even if they want (as we do), a shared taxi needs more safety belts for six passengers, if it has any. Furthermore, it needs to be clarified how to apply this efficient and **environmentally friendly** transportation system in developed countries. 

## Acknowledgments

This research was not supported by any grant or fund.

[^1]: "We" use "we" as a convention in academic writing, even though this article has only one author and I travel alone in this trip.

[^2]: "We" use "they" as a convention in academic writing, but I have not seen a single female taxi driver in Nouakchott.