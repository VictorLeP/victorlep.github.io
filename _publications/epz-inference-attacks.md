---
title: "A Run a Day Won’t Keep the Hacker Away: Inference Attacks on Endpoint Privacy Zones in Fitness Tracking Social Networks"
authors: "Dhondt, Karel; Le Pochat, Victor; Voulimeneas, Alexios; Joosen, Wouter; Volckaert, Stijn"
collection: publications
permalink: /publication/epz-inference-attacks
excerpt: "We show that implementations of endpoint privacy zones by fitness tracking social networks remain vulnerable to inference attacks 
	that reveal the location protect by those zones. Our attack leverages distance information leaked in activity metadata, street grid data, and the locations of the entry points into the EPZ."
abstract: "Fitness tracking social networks such as Strava allow users to record sports
	activities and share them publicly. Sharing encourages peer interaction but also
	constitutes a risk, because an activity's start or finish may inadvertently reveal privacy-sensitive
	locations such as a home or workplace. To mitigate this risk,
	networks introduced endpoint privacy zones (EPZs), which hide
	track portions around protected locations. 

    In this paper, we show that EPZ implementations of major services remain vulnerable to inference attacks 
	that significantly reduce the effective anonymity provided by the EPZ,
	and even reveal the protected location. Our attack leverages distance
	information leaked in activity metadata, street grid data, and the locations of the entry points into
	the EPZ. This yields a constrained search space where we use regression analysis
	to predict protected locations.  Our evaluation on 1.4 million Strava
	activities shows that our attack discovers the protected location for up to 85% of EPZs. 
    Larger EPZs reduce the performance of our attack, while geographically dispersed activities in sparser street grids yield better performance.
	We propose six countermeasures, that, however, come with a usability trade-off, 
	and responsibly disclosed our findings and countermeasures to the major networks."
date: 2022-11-08
venue: '2022 ACM Conference on Computer and Communications Security'
venue_short: 'CCS'
doi: 10.1145/3548606.3560616
paperurl: '/files/epz-inference-attacks-ccs22.pdf'
bibtex: |
    @inproceedings{Dhondt2022EPZInferenceAttacks,
     author = {Dhondt, Karel and Le Pochat, Victor and Voulimeneas, Alexios and Joosen, Wouter and Volckaert, Stijn},
     title = {A Run a Day Won’t Keep the Hacker Away: Inference Attacks on Endpoint Privacy Zones in Fitness Tracking Social Networks},
     booktitle = {2022 ACM Conference on Computer and Communications Security},
     series = {CCS '22},
     year = 2022,
     pages = {XXX--XXX},
     doi = {10.1145/3548606.3560616}
    }
---
