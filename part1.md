# Assignment: Final Project Part I

### Assignment Overview

In this assignment, we are introducing the outline, sketches, data, and methods and medium for our final data visualization project.

### Outline

**Topic**: What Russia's Invasion of Ukraine Tells the World about the Nature and Consequences of Modern Conflict

**Introduction Narrative**: Since the end of the Cold War, the world has witnessed states gradually losing control of their monopoly on violence. The war in Ukraine gives national security practitioners and humanitarion advocates an opportunity to evaluate the changing nature of conflict. Before Russia's invasion of Ukraine, low-grade conflict across the globe was prevalent, characterized by a high number of low-fatality conflicts scattered across the world's most violent regions. Rather than engage with their own forces, great powers like Russa would use external forces, the most known and effective of which was Wagner group, using them to pursue Russia's national political interests abroad. The war in Ukraine, and Russia's subsequent change in security posture, gives national security acedemcis and practitioners the opportunity to observe how a conventional war waged by a great power impacted its ability to continue to pursue its interests through irregular warfare waged by proxy forces abroad. It also presents an opportunity to evaluate the humanitarian impact of modern day conventional conflict in terms of loss of human life. In comparing these fatality numbers pre- and post-invasion, humanitarian and policy advocates can gain insight into the humanitarian impact of conventional conflict vs. enduring low-grade conflict involving various non-state actors. This could inform decisions on how to best concetrate deterrence efforts, against large scale combat operations or unconventional threats, to best prevent loss of life. 

**Possible Questions to Address**:
1. Has the world gotten more violent post-Russian invasion of Ukraine?
2. Are states, in fact, losing their monopoly on violence?
3. Are the nature of conflict interactions changing (i.e., who's fighting who?)
4. Which types of conflict are most lethal, and has that changed over time?
5. What's the source of the biggest loss of life, conventional war or low-grade conflict?
6. Did Russia's war in Ukraine hinder it's ability to conduct violence abroad in pursuit of its long-term state interests? This analysis would specifically use Wagner Group as a case study.

**Story Objective**: Tell the story of how Russia's invasion of Ukraine changed the security landscape in terms of scope and scale of violent attacks (in terms of fatalities) in Russia's existing sphere of military influence (to include Europe, Africa, and the Middle East). Explain what the implications this could hold for security communities seeking to curb conventional and unconventional violence in a modern context.

**Outline**:
- Set the Stage for the Security Landscape pre-Ukraine Invasion
    - Include a point-map visualization that shows conflict events in Europe, Afica, and the Middle East in the  year prior to the Ukraine invasion
    - Incudlude 1-2 more visualizations that cahracterize the nature of the conflict in the designated regions pre-invasion

- Introduce the Conflict Levels from the Russian Invasion of Ukraine to September 2023
    - Use a point-map to introduce the explosion in conflict and fatalities after the invasion
    - Use another time visulization to show how fatalities accumulated from the war in Ukraine far outpace those from any other type of conflict interaction.

- Show how the Conventional War in Ukraine forced Wagner Group to Largely Cease its Operations in Africa and Return to Europe
    - Use another map visualization or maybe a simpler graph like a line chart to show how Wagner Group activity in Africa dropped off post-invasion

- Show that there is a Baseline Level of Conflict Not Involving Russian Forces that Remained Relatively Constant Pre- and Post-Invasion
    - Highlight either in a new visual or using previous point maps that a baseline level of low-fatality conflict endured through conventional conflict


### Sketches

Here I'll outline some of the draft visualizations I created during my data exploration phase of the project. These initial visualizations serve as my sketches because all subsequent visualizations will build on or slightly branch off of the story they present.

**Visualization Showing All Conflict Events in the Europe, Africa, and the Middle East from FEB-2021 to SEP 2023**:

<div class="flourish-embed flourish-map" data-src="visualisation/15191730"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

**Visualization Showing Which Entities are Engaging in Conflict and the Fatalities Those Conflicts Inflict Over Time**:

<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/15193515"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Data

For this project, I am using data from The Armed Conflict Location & Event Data Project. The below data description is a direct excerpt from the Introduction of The Armed Conflict Location & Event Data Project Codebook:

"ACLED collects reported information on the type, agents, location, date, and other characterstics of political violence events, demonstration events, and other select non-violent, politically-relevant developments in every country and territory in the world. ACLED focuses on tracking a range of violent and non-violent actions by or affecting political agents, including governments, rebels, militias, identity groups, political parties, external forces, rioters, protesters, and civilians...

ACLED concentrates on:
- Tracking rebel, militia, and government activity over time and space;
- Recording violent acts between and across non-state groups, including political and identity militias;
- Recording political violence by unnamed agents, as violent groups may remain unnamed for strategic reasons;
- Recording attacks on civilians by all violent political agents;
- Distinguishing between territorial transfers of military control from governments (and their affiliates) to non-state agents and vice versa;
- Collecting information on rioting and protesting; and
- Tracking non-violent strategic developments representing crucial junctures in period of political violence (e.g. recruitment drives, peace talks, high-level arrests).

ACLED data are derived from a wide range of local, national, and international sources in over 75 languages. The information is collected by trained researchers worldwide."  ACLED, (2019). "Armed Conflict Location & Event Data Project (ACLED) Codebook"

I plan on extracting all the conflict data from the regions with Russian military presence one year prior to the invasion, which includes Europe, Africa, and the Middle East. The data itself is very detailed in terms of listing the specific entities involved in each conflict. The level of detail is too intenseive for the narrative I plan to tell, so I modified the dataset to generalize the material. For example, instead of breaking out each individual actor affiliated with the Russian government, I reclassified them all under the title 'Russian Forces.' I also dropped conflict data that referred to peaceful protests and other civilian interactions. In making these adjustments, I lost some of the detail of the data, but simultaniously make it more accessible for my audience. 

[Here](/russian_centric_acled.csv) is a link to the raw dataset I plan on using/modifying to tell my story.


### Methods and Meidum

I plan on using Shorthand as the platform of the final project. Shorthand will act as a good medium for my narrative because it allows me to seamlessly integrate visualizations and the more descriptive narration my story requires.

### [Back to Homepage](/README.md)