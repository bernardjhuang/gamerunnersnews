---
layout: post
title:  "Hidden Gems - Armor Penetration: Part 1"
description: "In this article, I will use Armor Penetratin to refer to both Physical Armor Penetration and Magic Penetration as well. Also, when I say Armor, I am referring to Magic Resist as well to save text space. I will also be using Armor Penetration to refer to Armor Reduction as well."
author: "Samuel Kuo"
author_profile: "Invented the troam'er role (troll and roam) and the triple brut. build (Youmu's Ghost Blade, Black Cleaver, and The Brutalizer)"
author_coach: ""
date: 2014-10-27
categories: lol
tags: theorycraft
---

Hi. I'm Sammy, an enthusiast of League of Legends since launch (and of MOBA since Defense of the Ancients). I'm here to shed light on various aspects of League of Legends that may be unknown many Summoners in the public scene and perhaps even alien information to the LCS Summoners! In this article, we will look at what I believe is the most misunderstood stat in League of Legends: Armor Penetration. It is definitely one of the most situational stat in the game which gives it its complexity. However, from item building to play style, I see that people are building Flat Armor Penetration inappropriately in such a way that it would hinder one's ability to play optimally. 

This is part 1 of a 2 part series. In part 1, we will cover some of the basics of Flat Armor Penetration and Flat Armor Reduction. But don't worry - no ground-breaking stuff here in part 1. We'll start by taking it slow and easy. And once we're ready, we'll move into part 2 where things will be getting interesting. Part 2 will delve into more theoretical aspects of Flat Armor Penetration/Reduction including item builds and  and hint at possible future meta builds! However, to understand all this glorious information requires an understanding of the basics.. So, let's get started!

## The 4 Kinds of Armor Penetration

In League of Legends, there are 2 sets of Armor Penetration - Flat Armor Penetration and Flat Armor Reduction, and % Armor Penetration and % Armor Reduction. This makes up for a total of 4 different kinds of Armor Penetration. 

Flat Armor Penetration and Flat Armor Reduction helps us deal damage as if our targeted opponent had X number of less Flat Armor or Armor Reduction. For example, let's say we have the Brutalizer:

![Armor penetration lol theory crafting the brutalizer](/images/content/armor-the-brut.jpg)

*(image from leagueoflegend.wikia.com)*

The Brutalizer provides 10  Flat Armor Penetration. Then if our targeted enemy has 20 Armor, then we would deal damage as if the target had 10 Armor. 

Let's take a look at Abyssal Scepter:

![Armor penetration lol theory crafting abyssal scepter](/images/content/armor-abyssal-scepter.jpg)

*(image from leagueoflegend.wikia.com)*

Abyssal Scepter provides 20 Armor Reduction (Don't confuse this with 20 Flat Armor Penetration!). The calculation is almost the same as Flat Armor Penetration. If our target opponent has 20 Armor, then we reduce their Armor to 0 and calculate from there. So what's the difference? Armor Reduction is calculated first and then Armor Penetration. And Flat Armor Reduction can also reduce a target's Armor below 0 while Flat Armor Penetration cannot (the lowest being 0 Armor). So for example, if our target opponent has 25 Armor. We have 10 Flat Armor Penetration and 20 Armor Reduction. The 20 Armor Reduction first reduces the opponent's Armor to 5. Then our 10 Flat Armor Penetration reduces it to 0. Remember, Flat Armor Penetration cannot reduce Armor below 0! However, if we had 30 Armor Reduction, we would have reduced the opponents Armor to -5.

% Armor Penetration and Reduction is just as it sounds. We deal damage as if the target enemy had a % less amount of Armor. For example, if we have 30% Armor Penetration, and the target enemy has 100 Armor, then we deal damage as if the target enemy had 70 Armor (100*.7=70). And just as it is with Flat Armor Penetration/Reduction, % Armor Reduction is calculated before % Armor Penetration. And also, % Armor Penetration/Reduction are both calculated before Flat Armor Penetration; thus, Armor Penetration is calculated in this order:

1) % Armor Reduction

2) % Armor Penetration

3) Flat Armor Reduction

4) Flat Armor Penetration

In this article, I will use Armor Penetration to refer to both Armor Penetration to refer to both Physical Armor Penetration/Reduction and Magic Penetration/Reduction. Also, Armor will refer to both the AD Armor and the Magic Resist Armor.

## When Armor Penetration is Good
I want to point out two correlations with Armor Penetration:

1) Flat Armor Penetration is EXTREMELY effective on squishy targets with low amounts of armor while being EXTREMELY ineffective against targets with high amounts of Armor. 

2) Conversely, % Armor Penetration is EXTREMELY ineffective against squishy targets while being perhaps the best stat to have against tanky target enemies stacking armor. 

Many people understand the latter correlation well enough - We see many Summoner's building a Void Staff (35% Magic Penetration) or Last Whisper (35% Armor Penetration) mid-late game when the enemy team has a significant amount of Armor when many of the opposing Champions are geared in Armor. Since most people already understands % Armor Penetration fairly well, I won't go too much into % Armor Penetration until part 2 when things get really jazzy. 

What I do want to cover is the first correlation regarding Flat Armor Penetration/Reduction. Because many Summoners don't fully grasp how Flat Armor Penetration works, we find ourselves in a meta of item build and playstyle that mathematically questionable.

To get the best out Armor Penetration, let's dive deep and venture into a little bit of math behind Armor Penetration.

## Scenario Damage Comparison

Let's say we have 10 Flat Armor Penetration, 100 AD, and our target enemy has 100 Armor. 

**Without 10 Flat Armor Penetration:**

(100*(1-(100/200)))=50 damage

**With 10 Flat Armor Penetration:**

(100*(1-((100-10)/(100+(100-10)))=52.63 damage

Dividing the two scenario damages, we see that we deal... 

52.63/50=1.053% more damage

Therefore, with 10 Flat Armor Penetration against a 100 Armored-target, we deal about 5% more damage. 

But, let's say, this time, our target enemy has 10 Armor only. Let's see if there is any difference to our % bonus damage coming from 10 Flat Armor Penetration: 

**Without 10 Flat Armor Penetration:**

(100*(1-(10/(10+100)))=100 damage

**With 10 Flat Armor Penetration:**

(10*(1-((10-10)/(100+(10-10)))))=90.9 damage

And comparing the two damage...

100/90.9=1.10% more damage!

Ouch! Against a target enemy with 10 Armor, we deal about **10% MORE DAMAGE!** That's about **TWICE** as effective than when we were hitting the 100 Armored-target.

Conclusions

Because the difference in damage dealt in relation to how much Armor the enemy has in arsenal is quite significant, Flat Armor Penetration becomes a very situational item. So what conclusions can we come to?

1) Flat Armor Penetration is a good item to have early game when everyone has a low amount of Armor. It goes by no surprise many top laners build The Brutalizer early. 

Even Corki is in on the fun getting Sorcerer's Shoes! 

![theory crafting - sorcerer's shoes LoL](/images/content/armor-shoes.jpg)

*(image from leagueoflegend.wikia.com)*

Sorcerer's Shoes provides 15 Flat Magic Penetration. This synergizes well with Corki since he has a lot of Magic Damage.

On the other end, however, Flat Armor Penetration and Reduction is generally bad late game when everyone is bulked up with Armor. This is why many Summoners sell The Brutalizer for another item mid-late game.

2) If we have an item build that has lots of Flat Armor Penetration or Flat Armor Reduction, then we ought to be targeting the enemy backline where the squishies are. This sounds like common sense, but in many situations, it's not reasonable to actually target the backline since not all champions have the mobility to do so. And in many situations, peeling (attacking and cc'ing the enemy frontline from reaching your team's backline) for your teams backline is more important, which means hitting tanks. And sometimes, it's more important to try to AOE as much enemies as possible, even if it means excluding the enemies squishy backline. 

3) We should then ask ourselves a question, "What kind of champions are we talking about that have enough mobility to jump to the enemy backline where the low-Armor squishies are to utilize Flat Armor Penetration or Flat Armor Reduction to its full extent?" 

Since our goal is more damage with Armor Penetration, and we need a mobile champion to reach the enemies backline, we are essentially speaking of the Assassin role. For example,  Zed would be a great champion to stack Flat Armor Penetration since he can shadow step and jump to the enemy backline to dunk those squishies. Guess what Zed's core items are?

![theory crafting - zed's core items LoL](/images/content/armor-zed.jpg)

*(generated at leaguecraft.com)*

Items such as Youmu's Ghost Blade and The Black Cleaver, which both provide Armor Penetration, are very popular items on Zed for partially this reason. To top it off, Blade of the Ruined King, the core item of any Zed build, has its active and passive augmented by Armor Penetration. 
With these three key points in mind, we have laid good foundation on our understanding of the Armor Penetration stat - that it is effective early game and good for Assassinating backline squish. We're now ready to jump into the advanced aspects of Armor Penetration. When you're ready, click the button below for Part 2! 

