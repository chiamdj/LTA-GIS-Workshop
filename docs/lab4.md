# Lab Practice #4

!!! abstract "Learning Objectives"

	* Proximity and Overlay analysis
	* Space-time analysis using Space time pattern mining tools

## Case Study

Read the brief abstract below taken from the Parliament Hansard on 10 Mar 2022 [(link)](https://sprs.parl.gov.sg/search/sprs3topic?reportid=oral-answer-2787).
> 1 Mr Darryl David asked the Minister for Transport (a) whether he can provide an update on the number of lifts installed at pedestrian overhead bridges across Singapore in 2021; (b) how does this number compare to the number of lifts installed in 2019 and 2020; and (c) what is the projected annual number of lifts that will be installed at pedestrian overhead bridges for the next three years.

> The Senior Parliamentary Secretary to the Minister for Transport (Mr Baey Yam Keng) (for the Minister for Transport): As of end 2021, a total of 77 pedestrian overhead bridges (POBs) have been retrofitted with lifts as part of LTA's lift retrofitting programme. Of these, 26 and four POBs were retrofitted with lifts in 2021 and 2020 respectively.

 > In 2018, LTA completed Phase 2 of its lift retrofitting programme for 41 POBs, primarily near public transport nodes. LTA was preparing for Phase 3 of the lift retrofitting programme in 2019. Preparatory works such as site investigations and technical studies have to be done before commencing construction, hence it takes about 14 to 22 months to retrofit lifts at POBs.

 > Phase 3 focuses on POBs near places such as healthcare institutions so that lifts installed will benefit a high number of seniors and commuters with mobility challenges. This phase, which started from 2020, will see around 60 POBs being retrofitted with lifts. The remaining 30 lifts will be installed progressively over the next three years.

 Your division is involved in Phase 3 of the lift retrofitting programme for Pedestrian Overhead Bridges (POBs).

## 4.1 Proximity and Overlay Analysis

1. Add a folder connection to `C:\Data for Hands On\LTA\Exercise 4\Exercise4.gdb` and add the `CoveredLinkway` and `Healthcare` feature layers to the map.

2. Next, we will identify covered linkways that are within a 200m walking radius from Train Stations. 

3. Create a 200m service area buffer

!!! info "Difference between buffer and service area"
	lorem ipsum

4. Intersect the service area with the covered linkways 

## 4.2 Spatial Analysis


## Challenge

Using feedback cases, perform the same analysis to identify places with hotspots of feedback cases.