---
title: 'Path of Honors: Towards a Model for Interactive History Texts with Twine'
cover_index: /imgs/mccall/julius-caesar-bm.png
cover_detail: /imgs/mccall/11224698395_b8b8228321_k.jpg
author: 'McCall, Jeremiah'
doi: "10.22215/epoiesen/2017.16"
tags: interactive fiction
date: 2018-01-21 15:35:32
---

Jeremiah McCall
_Received 2018-01-21_
Citation: McCall, Jeremiah. 2018. "Path of Honors: Towards a Model for Interactive History Texts with Twine". _Epoiesen_. DOI: http://dx.doi.org/10.22215/epoiesen/2017.16

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" align="left" /></a><br />

_Jeremiah McCall teaches at Cincinnati Country Day School and maintains [Gaming the Past](http://gamingthepast.net/) (jmc.hst@gmail.com). [ORCID ID: 0000-0002-6915-5890](https://orcid.org/0000-0002-6915-5890)._

## Theory, History, and Media
If we consider that history is just the contemporary representation of the past through a medium, and doing history is the practice of making these representations, then histories exists in all manner of media: texts, of course, films, speeches, statues, images, exhibits, and video games, just to name some possibilities. There are more or less sound histories in all these media, but what unites them is the imaginative act: to do history requires imagining the past, how people lived, why things happened, and so on. Viewed this way, a sharp divide between academic and other forms of history does not exist. Viewed this way, historical video games are a way of doing history as are, I shall argue, interactive texts.

Historical video games, as Chapman (2016) pointed out, can be grouped to some extent by the way that they simulate the past. Some, like _Assassin's Creed_ and _Call of Duty_, are realist simulations, games that focus on a visually verisimilitudinous environment, a world that can be explored and navigated by the player and that in some ways claims to present the past as it looked. Others, like _Civilization_ and _Crusader Kings 2_, are conceptual simulations. They represent the past with their symbols, rules, and procedures, not within a high-fidelity visual model of a past world. Rather than suggest they are showing the sights and sounds of the past world, they rely on more abstract symbols and rules--procedural rhetoric--to tell players how the past was.

Both realist and conceptual simulations structure their virtual pasts as historical problem spaces (McCall 2012 & McCall 2012). They do this by presenting the past in terms of:

- A player agent with one or more roles and goals, **contained within**

- a physical environment, a geography that **includes**

- a variety of elements, including AI models of other agents, that can afford player actions, restrict player actions, or both depending on the circumstances; **and so the player makes**

- strategies and choices to capitalize on affordances, work within restrictions, and achieve their goal.

This is not an unproblematic view of the past, but it does do a reasonable job conceptualizing agents in the past facing challenges and pursuing goals - arguably something many did at least some of the time.

Different media have different characteristics, which is certainly the case with video games and static text. Video games are multimodal, variable, systemic, and, most importantly, interactive. They form closed dynamic systems where the player makes choices and experiences the results of those choices. This can be an advantage when considering, among other things, human agency, choice-making, and the historical context of choice-making. Still, there are significant obstacles to historians, whether students or professionals, designing video game histories. Most notable of these are the skill and resource requirements for game design. Furthermore, many academics find it regrettable that designing historical video games often requires sacrificing much of the precise descriptive value of text.

Choice-based historical texts, however, designed using a tool like [Twine](http://twinery.org), offer a relatively untapped medium for students, amateurs, and professionals to design interactive text histories that leverage the descriptive precision of text (including, if desired, the ability to provide citations) in addition to the powerful interactivity of video games through choice-making. They allow designers to straddle the boundaries of realist and conceptual simulations and design both highly scripted historical problem spaces and more dynamic systems-based ones.

And so we come to the *Path of Honors* project. I began this project in interactive history text design to address this question: What kind of interactive history can a historian make with the choice-based text design tool,[Twine]( http://www.twinery.org/)? I have already experimented a fair amount with teaching my history students to research, design, and write their own Twine-based histories for class--Twine is a powerful tool with great potential. But can a historian make an interactive historical text that fulfills some of the desire for precision and citation while allowing for interactivity and perhaps even systems-based environments?

(More details about my early reasoning and process can be found in my essays on the topic at playthepast.org: [Part 1](http://www.playthepast.org/?p=5739) [Part 2](http://www.playthepast.org/?p=5752) [Part 3](http://www.playthepast.org/?p=5771) [Questions about POH](http://www.playthepast.org/?p=5815)).

Ultimately, the project needs to speak for itself as a rough and very incomplete prototype of what one type of interactive historical text might look like. A few comments follow, however, to introduce readers to aspects of the project:

## Concept Comment:

_Design a historical game based on a young Roman aristocrat rising through the ranks of elected political offices in the Republic (the *cursus honorum* or 'Path of Honors', hence the title)._

Romans of the senatorial class who sought elected political office in the Republic competed intensely with their rivals to demonstrate their greater dignity and authority based on qualities like _virtus_, martial manliness, distinguished lineage, and service to the Republic. Those fortunate enough to achieve the highest positions, praetors and consuls, and hold the military commands that came with those offices, especially the consulship, were driven to demonstrate themselves and win glory for their family line by leading armies to victory in battle against the enemies of Rome, long-standing or newly-provoked. In many ways, it was a very different world and world-view from that of your average modern person, certainly your average North American teenager (and I hoped this game would also prove useful for the 12th graders in my Roman Republic elective at Cincinnati Country Day School). I wanted to design a game that could put a player virtually into the competitive environment of aristocratic politics, feeling pressures, making choices, and experiencing the consequences of those choices.

## Tool Comment:
_Twine allows designers to create choice-based texts, branching narratives, where the player reads some text describing their situation, conventionally written in second person, then choose from two or more choices (hyperlinks) that take the player to new passages where they read the results of their choice and make further choices._

The [Twine interactive fiction tool](http://www.twinery.org/) was designed and is updated by Chris Klimas, who deserves a great deal of thanks for his efforts.
The story map in a simple Twine game might look something like this:

![Twine story map with a basic story](/imgs/mccall/1.png)

Fundamentally, designing a Twine choice-based text is quite simple. The player enters text into a passage editor and provides some simple code for links like so:

![Twine passage editor with a basic passage](/imgs/mccall/2.png)

Yet the design tool is quite powerful and includes several formats, which are essentially scripting languages. A finished Twine is rendered into a single html file with Javascript and can be easily circulated either by posting on a website or sharing the file.

## Design Comment:
_*Path of Honors* most closely follows the structure of a role-playing game, a structure that it has gravitated toward slowly through a series of design challenges and attempted solutions._

I'd like to discuss the reasoning behind adopting an RPG structure more fully at another time. For now,the game is moving toward the critical design element of meaningful choices. Since this is a text, not a video game, the challenge in most options presented to the player lies in their nature as trade-offs. Some choices are straight risk-reward propositions, like risking death in battle to increase one's reputation. Others are more about deciding which skills to develop or political approaches to take. The full stat-based approach has developed only very recently and is implemented in only a few instances. The advocacy system, for example, gives a glimpse of an rpg-style but not wholly unreasonable system for practicing in the law courts.  The military service system needs to be overhauled to look more like the advocacy system. Both need a great deal more content. I had originally thought I would start PoH with the player's first political office. Then I realized I wanted to include the 10 years of prerequisite military service, since these shaped an aristocrat's life. Only recently has it become clear that I need to overhaul and add more descriptive depth and variety to the military service segment to make more specific episodes for the player based on the ancient sources.

## Historical Sources and Citations Comment:
_Of course, clear arguments based on sound historical sources and clear citation of said sources are foundational to historical writing._

I wanted to find some way to incorporate citation that would not hinder the enjoyment and flow of the text. I have adopted an approach with notes at the bottom of passages, which remain hidden unless the reader wants them. I have not even attempted to cite secondary scholarship yet, but have started with references to the ancient sources. The work needs a great deal more citation. Since this is my academic area of expertise, I have not conducted independent research for the game, but I would like to go back and fill in the reference gaps to further develop this as a model for interactive history.

## Improvements Comment:
Since this is meant to be a think-piece/prototype, there are so many areas that can be improved. Some elements of the game are the way they are for historical reasons. Other elements are part of a trial-by-error design, as I continue to find more elegant (and fun) solutions available that still preserve historical authenticity. Some obvious areas for improvement:

- Content in the advocacy system: there are currently only a few cases. The system coded is ready to take more when I have written them

- The military service segment: Instead of the more generic and blatant risk/risk reward system, I plan to make it more like the advocacy system in that the player will face a specific military challenge each year and determine whether that challenge is worth the risk.

- The game does not actually go past setting priorities for the office of aedile. There is a lot of writing and design to come.

I'd be delighted to talk about your impressions of the project and choice-based text as a medium for history.

## Play

Explore the [Path of Honors](http://www.philome.la/gamingthepast/path-of-honors-1-12-18/play)

<a href="https://epoiesen.github.io/artefacts/McCall-A_Path_of_Honors_1-22-18.html" target="_blank">Archived Version as of January 21 2018</a>

## Works Cited

Chapman, Adam (2016). Digital Games as History: How Videogames Represent the Past and Offer Access to Historical Practice. London: Routledge.

McCall, Jeremiah (2012). Navigating the Problem Space: The Medium of Simulation Games in the Teaching of History. The History Teacher 45, 9-28.

McCall, Jeremiah (2012). Historical simulations as problem spaces: Criticism and classroom use. Journal of Digital Humanities 1.

_Cover Image_ A screenshot from the [British Museum Sketchfab account]((https://sketchfab.com/models/dde432311eb748e19e76bbb888fb0730), of a 3d model of a bust of [Julius Caesar](http://www.britishmuseum.org/research/collection_online/collection_object_details.aspx?partId=1&objectId=465555).

_Masthead Image_ "Image taken from page 343 of 'Cassell's Illustrated Universal History.'"[British Library](https://www.flickr.com/photos/britishlibrary/11224698395/)
