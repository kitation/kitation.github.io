---
layout: post
status: publish
published: true
title: ! "Discomfort and Player Experience Part 4: The Steam Reviews"
author:
  display_name: chad
category: project
tags:
- px
- gaming
---

A common pattern for exploratory studies is to do one study which is broad and shallow, and follow up those findings with a deep but narrow study. My original plan was to do a questionnaire with follow-up interviews; however the subject matter meant that I wasn't likely to get ethical approval and I wasn't in a good place myself. So instead I started off looking at reviews on Steam.

<!--more-->

Academics love "found data". The internet is full of publicly available information that people provide about anything and everything. However, it is important to do this with care. Just because somebody tweets something doesn't mean they know that it could be quoted in a paper somewhere. For this project, I made sure there was nothing in the Steam TOS that said I couldn't use this information, and I didn't use automated bots to scrape the data.

Why Steam in the first place? Steam is still the biggest PC game store. It has user reviews (the data I want) and tagging, which helped me find the games I wanted to look at. Tags were a way for me to systematically find games without a) looking at everything and b) help avoid my personal bias in selecting games. The problem with being a gamer doing a gaming project is that it's really tempting to look at games or genres you already like and ignore ones that you don't, even though those have equal potential for creating the data I want (uncomfortable experiences).

My method was as follows:

1) Find all the games mentioned in the papers from my literature reviews
2) Get the top 10 most common tags for each game and remove duplicates
2) For each tag, get 10 most popular games
3) For each game, read top twenty reviews (sorted by date) and pull out any about discomfort or related negative emotions.

After analysing a bunch of reviews gathered by this method, I realised that I wasn't really getting any good data. A lot of the games I was getting weren't suitable at all. There were a few erotic games in there that I didn't really want to work with, plus I realised that bundles get tagged with all the tags in each bundle, hence why the Metal Gear Solid collection has the tag "Short". I had become too cautious over selecting my data and it all started at the tag level. So this dataset was scrapped. It did however yield my favourite review, which didn't make the paper but I do use in my talk. Somebody was very happy that Bus Simulator (does what it says on the tin) is getting more realistic with real buses and real routes, but was upset that it (realistically) had gay people and children shouldn't be allowed to play this game because of it. Rock on homophobic pretend bus driver.

What I needed to do was hone down tags that were likely to have the kind of games I wanted. Tags like "Short" or "Controller compatible" don't really tell you anything about content. I pulled out the top 200 popular tags and removed any that were solely about gameplay and any that were genre tags (like "Fantasy"). I went over the remaining list with my supervisor and came out with these Tags

• Violent
• Gore
• Story Rich
• Difficult
• Atmospheric
• Dark

I applied the same method of pulling out the top 10 games and then recent reviews. I pulled 100 reviews from each game and removed any that were less than 20 words. This left me with ~1300 reviews to read. A quick once over of randomly selected games from my list showed about a 7% hit rate of useful reviews, so I should get 70 out of the whole lot which was around the amount I was looking for.

Interlude: I ended up writing some javascript to help me out a lot with this. I didn't use a bot to pull the website down, but I did copy and paste the html manually and use a script to pull out just the review text. Another script pulled all of these reviews into a file and randomised them, hiding the game title. This helped me be as unbiased as possible in the analysis. I was surprised about how much I enjoyed writing this code. I had decided I never wanted to be a developer again, but using my ability to do something useful saved me loads of time and boredom in the end.

So 1300 reviews down to 70 right? That's a pretty low expectation right there. In the end, I only ended up with 32 useful reviews. My main contribution to academic game discourse is to show people don't talk about emotions on Steam. Here's how those reviews broke down by game.

Doki Doki Literature Club - 7
XCOM 2 - 3
Conan Exiles - 2
Darkest Dungeon - 2
Don’t Starve Together - 2
Fallout 4 - 2
Final Fantasy XIV - 2
Frostpunk - 2
Lord of the Rings Middle Earth: Shadow of War - 2
Ultimate Custom Night - 2
Black Desert Online - 1
Bless Online - 1
Dark Souls: Prepare to Die Edition - 1
Dark Souls Remastered - 1
Divinity Original Sin 2 - 1
Elder Scrolls Online - 1
Quake Champions - 1
Total War: Warhammer - 2 1

So what did I find? Well three main themes jumped out; "Against Expectations", "Attachment and Loss" and "Hell is Other People". My project has fairly long explanations with quotes for each theme but here is a shorter version.

"Against Expectations" covered reviews that talked about a mismatch between a player's expectations of the game and what the game actually delivered. A few people mentioned the relation of the game they were reviewing and previous games in the series. Fallout 4 has more restrictive dialogue options than the first two games; someone else was upset how the ending of Shadow of War contradicted the content of the previous game. Someone else spoke of how they expect an Elder Scrolls game to be very open in role-play choices, but a quest in Elder Scrolls Online makes your character act sympathetic to refugees and this person was upset that they couldn't play it any other way. The big game in this theme was Doki Doki Literature Club, a game which plays with expectations as a core theme of the game. A lot of people mentioned this in reviews, saying it wasn't what they were expecting based on the genre and presentation of the game.

Interlude: I was expecting DDLC to come up with loads of good stuff as it made me really uncomfortable, but actually people didn't talk about their feelings much at all, or mentioned the dark events of the game. I think this was partially to avoid spoilers, and partially because memes.

"Attachment and Loss" matched up with a lot of the existing literature which shows that "I like character, now character dead and I sad" is a pretty common emotion in games. Two things popped out here though that I found interesting; firstly that people get really emotional about dogs, and also that people become emotionally attached to randomly generated characters. All these characters have is a small description and a name (this can be chosen by the player) but over time people become as upset over losing them as they do to scripted characters with defined arcs.

"Hell is Other People" is kind of an entire project of its own so I didn't end up carrying this theme forward. People are jerks online; blocking other players from content and having offensive names. My favourite review from this theme was from Final Fantasy XIV. It's an online game where there are mechanics to enable high-level characters to assist low level ones without hindering either player's gameplay. This one review though talked a lot about how the social expectation of helping people was making them do things they didn't want to do, but were worried about getting reported for not helping out.

In conclusion, Steam is not where people talk about emotions really. There was enough here though to help me going forward, even if it didn't really answer any of my questions. In a future post will be about the meat of this paper which was the questionnaire, but first, let's talk about ethics!
