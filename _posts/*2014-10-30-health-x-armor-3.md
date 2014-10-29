---
layout: post
title:  "Calculating Optimum Stat Ratios - Part 3: Health x Armor x Offense - The Caster-Type Bruiser"
description: "Caster-Type Bruisers include Champions that are, of course, tanky but rely on spells as their main source of damage. If you enjoy playing Champions like Wukong, Pantheon, Jarvan, and the such, then read on - this is the article for you!"
author: "Samuel Kuo"
author_profile: "Invented the troam'er role (troll and roam) and the triple brut. build (Youmu's Ghost Blade, Black Cleaver, and The Brutalizer)"
author_coach: "http://gamerunners.gg/coaches/3"
date: 2014-10-30
categories: lol
tags: theorycraft
thumbnail: "/images/content/hxa-pantheon.png"
---

This article covers the optimum stat ratios for Caster-Type Bruisers. For Auto Attack-Dependent Bruisers, [go here](http://news.gamerunners.gg/lol/calculating-optimum-stat-ratios-2/). Caster-Type Bruisers include Champions that are, of course, tanky but rely on spells as their main source of damage. If you enjoy playing Champions like Wukong, Pantheon, Jarvan, and the such, then read on - this is the article for you!

To calculate the optimum Caster-Type Bruiser stat ratio, we will employ the same methods in the previous article - measuring the True Value or the Effectiveness of stats, and minimalizing Diminishing % Returns. For more information on Effectiveness, check the previous article (link). For information on minimalizing Diminishing % Returns, check the [optimum Health x Armor Article](http://news.gamerunners.gg/lol/calculating-optimum-stat-ratios/). Finally, without further ado, let's begin with calculating the gold factor of stats.

## The Cost of Health, Armor, and AD

To calculate the optimum ratios for a balanced build, we first need to figure out what the "True Value" of each relevant stats are. Let's first take a look at gold cost.

To determine the cost of stats per unit, we take the cheapest item of a given unit, and take its cost divided by the amount of unit it offers.

![HXA LoL Theory crafting - Cloth Armr](/images/content/hxa-cloth-armor.png)

*(image from leagueoflegends.wikia.com)*

Cloth Armor is 300g. It gives 15 Armor; so if we divide 300 gold by 15 Armor, we find that we are paying **20 gold per unit of Armor**. Magic Resist is actually the same cost as well. How convenient!

Let's check how much Health costs.

![HXA LoL Theory crafting - Ruby Crystal](/images/content/hxa-ruby-crystal.png)

*(image from leagueoflegends.wikia.com)*

Ruby Health provides 150 Health at the cost of 400 gold. Dividing 400 gold by 150 Health, we get 8/3, or about **2.67 gold per Health stat.**

Long Sword.

![HXA LoL Theory crafting - Long Sword](/images/content/hxa-long-sword.png)

*(image from leagueoflegends.wikia.com)*

Long Sword provides 10 AD at the cost of 360 gold. Dividing 360 by 10, we see that 1 AD costs **36 gold.**

Now that we have the gold value of each stat of interest, we simply divide the value of each stat to find their True Value. 

## True Value

Most of the stats value are pretty straightforward - 1.0. However, there are confusing ones including Cooldown Reduction and Armor Penetration. Check out for details on Cooldown Reduction, and for details on why Armor is so much less than the others, check my optimum defense ratio article (link).

> Health = 1.0/(8/3) = 0.375

> Armor = .01/20/2 = 0.00025

> AD = 1.0/36 = 0.0277777777777778

> Cooldown Reduction = See below

With these units of measuring, we now just have to keep them in symmetry to minimalize Diminishing % Returns to optimize our stat ratios.

## Optimum AD Bruiser Caster Ratio 

Ideal sample ratios:

> With 1 unit in Health, Armor, Magic Resist, and AD, we have 0.375 Health x 0.00025 Armor x .00025 Magic Resist x  .0278 AD

> With 2 units in Health, Armor, Magic Resist, and AD, we have 0.75 Health x 0.0005 Armor x 0.0005 Magic Resist x 0.051 AD

> With 3 units in Health, Armor, Magic Resist, and AD, we have 1.125 Health x 0.00075 Armor x 0.00075 Magic Resist x 0.083 AD

...

...

...

>With 2000 units in Health, Armor, Magic Resist, and AD, we have 750 Health x 0.5 Armor x 0.5 Magic Resist x 56 AD

>**(750 Health, 0 Armor and 0 Magic Resist, and 56 AD)**

>With 3000 units in Health, Armor, Magic Resist, and AD, we have 1125 Health x 0.75 Armor x 0.75 Magic Resist x 83 AD

>**(1125 Health, 0 Armor and 0 Magic Resist, and 83 AD)**

>With 4000 units in Health, Armor, Magic Resist, and AD, we have 1500 Health x 1.0 Armor x 1.0 Magic Resist x 111 AD 

>**(1500 Health, 0 Armor and 0 Magic Resist, and 111 AD)**

>With 6000 units in Health, Armor, Magic Resist, and AD, we have 2250 Health x 1.5 Armor x 1.5 Magic Resist x 167 AD

>**(2250 Health, 50 Armor and 50 Magic Resist, and 167 AD)**

>With 8000 units in Health, Armor, Magic Resist, and AD, we have 3000 Health x 2.0 Armor x 2.0 Magic Resist x 222 AD

>**(3000 Health, 100 Armor and 100 Magic Resist, and 222 AD)**

>With 10,000 units in Health, Armor, Magic Resist, and AD, we have 3750 Health x 2.5 Armor x 2.5 Armor x about AD)

>**(3750 Health, 150 Armor and 150 Magic Resist, and 278 AD)**

>With 12,000 units in Health, Armor, Magic Resist, and AD, we have 4500 Health x 3.0 Armor x 3.0 Magic Resist x 333 AD)

>**(4500 Health, 200 Armor and 200 Magic Resist, and 333 AD)**

These ratios are ideal for the Caster-Type Bruisers that rely heavily on spells to deal damage. These include, but are not limited to - Darius, Wu Kong, Renekton, Garen, Pantheon, and Jarvan IV.

**Exception:** Riven because AD basically gives Riven more Health via her Valor; therefore, do not follow these stat ratios if playing Riven!

![HXA LoL Theorycrafting - Valor](/images/content/hxa-valor.png)

Against Only One Type of Damage

In scenarios where we are only facing against one type of damage, such as when we are in lane requires more Armor. Since the value of Armor is basically twice as effective (since there's only one type of damage), we simply take the ideal stat ratio of Health and Armor or Magic Resist stat listed above, and double it.

Ideal sample ratios:

> With 1 unit in Health, Armor, and AD, we have .375 Health x .0005 Armor

> With 2 unit in Health, Armor, and AD, we have 0.75 Health x .001 Armor 

> With 3 unit in Health, Armor, and AD, we have 1.125 Health x 0.0015 Armor 

...

...

...

> With 2000 units in Health, Armor, and AD, we have 750 Health x 1.0 Armor 

> **(750 Health, 0 Armor)**

> With 3000 units in Health, Armor, and AD, we have 1125 Health x 1.5 Armor 

> **(1125 Health, 50 Armor)**

> With 4000 units in Health, Armor, and AD, we have 1500 Health x 2.0 Armor 

> **(1500 Health, 100 Armor)**

> With 5000 units in Health, Armor, and AD, we have 1875 Health x. 2.5 Armor 

> **(1875 Health, 150 Armor)**

> With 6000 units in Health, Armor, and AD, we have 2250 Health x 3.0 Armor 

> **(2250 Health, 200 Armor)**

> With 7000 units in Health, Armor, and AD, we have 2625 Health x 3.5 Armor 

> **(2625 Health, 250 Armor)**

> With 8000 units in Health, Armor,  and AD, we have 3000 Health x 4.0 Armor 

> **(3000 Health, 300 Armor)**

> With 9000 units in Health, Armor, and AD, we have 3375 health x 4.5 Armor 

> **(3375 Health, 350 Armor)**

> With 10,000 units in Health, Armor, and AD, we have 3750 Health x 5.0 Armor 

> **(3750 Health, 400 Armor)**

To know how much Attack Damage or AP is needed, simply refer to the first chart of ideal sample ratios. The Health and offensive stat ratios are the exact same.

## Cooldown Reduction Variable

Cooldown Reduction is like the Attack Speed stat for spells. The more of it we have, the more frequently we can spam our spells. Considering if our Champion has no cast animation (which is probably not the case!):

> 10% Cooldown Reduction is 1/.9 = 1.11+% increase in DPS

> 20% Cooldown Reduction is 1/.8 = 1.25+% increase in DPS

> 30% Cooldown Reduction is 1/.7 = 1.43+% increase in DPS

> 40% Cooldown Reduction is 1/.6 = 1.67+% increase in DPS

So Cooldown Reduction is OP right? Well, it depends. Many trades/harassing involve casting and running away. In these scenarios, Cooldown Reduction is not helpful. Building more damage would've been more helpful for a larger burst. 

Cooldown Reduction is helpful, however, if we are in a scenario of a long-commited fight. In these scenarios Cooldown Reduction begins to shine, and long-commited fight means the kind of fight Tanks or Bruisers encounter. That's why this is a relevant stat to Balanced AP Casters that can survive a couple of hits.

The +% increase in DPS should probably be curved lower by a bit factoring Champion's have Spell Cast Animation. For example, if our Cooldown Reduction is at 2 seconds, it's probably more like 2.2 seconds because of the time it takes to cast. 

Nevertheless, Cooldown Reduction, for how easy and cheap it is to max out, is a gold-efficient way to increase our Spell DPS tremendously.

To use Cooldown Reduction effectively; however, requires two things:

**Condition 1:** Must be tanky enough to be able to survive long enough to at least cast a Spell twice before dieing 

**Condition 2:** Must have a lot of mana or have mana-cheap Spells or no-mana cost Spells (to sustain Spell spamming)
Thus, Cooldown Reduction isn't necessarily viable Early Game unless we are playing with a Champion that has built-in tankiness (such as Gragas) and spells that either cost very little mana or no mana. So for Champions that can't meet these conditions, Cooldown Reduction should be maxed around Mid-Late game for that awesome 1.67+% tremendous increase to DPS.

**All Champions could use a 40% Cooldown Reduction... except for ones that have a Cooldown of 0, such as Singed who can simply toggle on/off his Poison Trail. Avoid CDR on these Champions!

## The Set-Up and First Item

Let's take a look at our ideal stat ratios and see what the math is telling us. As a reference, let's use Pantheon's stats at level 1 for analysis. 

![HXA LoL Theorycrafting - Pantheon](/images/content/hxa-pantheon.png)

*(image from leagueoflegends.wikia.com)*

Pantheon starts with 53.6 AD, 25 Armor, and 520 Health. Our goal early game is:

**(1125 Health, 50 Armor, and 83 AD)**

Since Bruisers tend to go Top Lane or to the Jungle, the ratio being used assumes that we are facing off against 1 type of damage.

### Top Lane

When going Top Lane, our standard Mastery Set-Up is 21-9:

![HXA Lane Masteries](/images/content/hxa-lane-masteries.png)

Masteries gives us Brute Force, which provides .55 AD per level. Paired with Martial Masteries, which gives +4 AD, we will start off with 58 AD. Also, Veteran's Scars provides +36 Health bringing us to 556 Health.

![HXA Rune masteries - LOL theorycrafting](/images/content/hxa-lane-runes.png)

We gain +15 AD and +72 Health from our Rune Page. Magic Resist can be adjusted to Armor if needed. Factoring in our stats from Rune Page, we have 73 AD and 628 Health.

We still need mostly Health and AD to reach our quota; therefore, our best choice of item to start with is:

![HXA dorans blade - LOL theorycrafting](/images/content/hxa-dorans-blade.png)

*(image from leagueoflegends.wikia.com)*

With Doran's Blade, we have **80 AD** and **698 Health** at level 1. We've almost reached our AD quota, but our Health is still lacking. 

This set-up is optimum for going for the kill. Pantheon is great at dealing damage via spamming his Spear Shots. At level 2, Pantheon can jump in without fear with this set-up because of the high Health start via Runes and Doran's Blade. 

For a more passive style of play, readjusting the Health in Rune Page to Armor would be optimum to heal more efficiently with Health Potions.

### Jungle

For Jungle, sustain is of higher priority, and Armor increases the effectiveness of Health Potions. Thus, Armor takes precedence to Health.

Readjusting our Rune Page, we have:

![HXA jungle runes - lol theory crafting](/images/content/hxa-jungle-rune.png)

This Rune Page set-up will optimize our performance in the Jungle with the high Armor start at level 1.
We also need to readjust our Masteries to fit the Jungle:

![HXA jungle masteries - lol theory crafting](/images/content/hxa-jungle-masteries.png)

Our first item will be the only and only:

![HXA hunter's machete - lol theory craft](/images/content/hxa-hunters-machete.png)

*(image from leagueoflegends.wikia.com)*

Hunter's Machete offers +10 Attack Damage vs Monsters, so it's basically +10 AD in the Jungle. 

Our level stat in the Jungle is 83 AD and 40 Armor.

## 1st and 2nd Item to Max
By now, we should be around level 6. At level 6 with just a Doran's Blade, we have:

![HXA Level 6 Pantheon - theorycrafting League of legends](/images/content/hxa-lvl-6-pant.png)

*(generated at leaguecraft.com)*

Since we have hit the previous stat ratio, we will need a new one. With our Pantheon now Ult'ing all around the map, Mid Game should be starting anytime soon. Therefore, we use the Armor ratio vs. 2 kinds of damage:

**(2250 Health, 50 Armor and 50 Magic Resist, and 167 AD)**

Our Armor and Magic Resist is looking good. However, we see that we're going to be needing lots of AD and Health. There's 1 item that provides a good balance of both:

![HXA the black cleaver - theory craft league](/images/content/hxa-black-cleaver.png)

*(image from leagueoflegends.wikia.com)*

The Black Cleaver, providing both Health and AD, will help us almost hit our AD quota. As our Pantheon naturally levels up, our Pantheon should eventually hit the AD quota. The 10% Cooldown Reduction is a plus. Pantheon also applies the 25% Armor Reduction quickly via Heart Seeker Strike:

![HXA heartseeker - theory craft lol](/images/content/hxa-heartseeker.png)

*(image from leagueoflegends.wikia.com)*

Within just 0.75 seconds, we hit 3 times; therefore, we apply 3 stacks of Black Cleaver's passive. What synergy!

If we want more damage, then just buy another Brutalizer, which is an ideal Brutalizer item becomes we'll get another set of +10% Cooldown Reduction and more Armor Penetration.

We are now short on Health by nearly a 1000 Health... Therefore:

![HXA Warmog's Armor - theory league of legends craft](/images/content/hxa-warmogs-armor.png)

*(image from leagueoflegends.wikia.com)*

+1000 Health. We will hit our Health quota with Warmog's Armor. We can get into the thick of fights, and not be bursted. If we are facing against an AD heavy team, Randuin's Omen would  be a better choice. Against a Magic Damage heavy team, Banshee's Veil would be best.

## Next Items

We should now be around level 11. With Doran's Blade, Warmog's Armor and The Black Cleaver, this is our new stat profile:

![HXA Level 11 Pantheon - lol craft theory](/images/content/hxa-lvl-11-pant.png)

*(generated at leaguecraft.com)*

Let's go for our next plateau ratio:

**(3000 Health, 100 Armor and 100 Magic Resist, and 222 AD)**

We are missing about 75 AD, 40 Armor, and 54 Magic Resist. Our Health should naturally hit 3000 as we level up. So what's our next 2 items?

Well, now that we aren't squish thanks to our high Health, we should first max out Cooldown Reduction. 

![HXA ionian boots of lucidity - lol crafting theory](/images/content/hxa-cd-boot.png)

*(image from leagueoflegends.wikia.com)*

Ionion Boots of Lucidity provides 15% Cooldown Reduction. We should have 5% Cooldown Reduction coming from our Masteries, 10% from The Black Cleaver, and another Brutalizer for 10% Cooldown Reduction. Now, our DPS via spells is up +1.67% (just from Cooldown Reduction)! 

Now, let's focus on our Armor, Magic Resist, and AD needs.

![HXA Randuins Omen - lol theory craft](/images/content/hxa-randuins-omen.png)

*(image from leagueoflegends.wikia.com)*

Randuin's Omen will hit our quota for Armor and Health for our current plateau ratio... and all the way almost to the next set of ratios! The Unique Active can also Pantheon chase his preys.

![HXA Maw of Malmortius - lol crafting theory](/images/content/hxa-maw-of-mal.png)

*(image from leagueoflegends.wikia.com)*

Maw of Malmortius will help us hit our current Magic Resist and AD ratios. It also provides a nice Lifeline against Magical Damage, though I wouldn't rely on it. Maw of Malmortius will be first over Mercurial Scimitar because it is easier to build. Unless we just made a Triple Kill or have a lot of gold on our hand, go ahead and buy Mercurial Scimitar instead.

![HXA Mercurial Scimitar - lol crafting theory](/images/content/hxa-mercurial-scimitar.jpg)

*(image from leagueoflegends.wikia.com)*

This, being the most expensive item, will be the last item in our build. We buy it for the massive AD and Magic Resist. Of course, Quicksilver is helpful too. Mercurial Scimitar will help us hit our next plateau ratio for Magic Resist and AD that Randuin's Omen is hitting for Armor and Health.

## The Final Build

Voila.

![HXA Pantheon final build - lol theory crafting](/images/content/pant-final-build.png)

*(generated at leaguecraft.com)*

Summary: Build The Black Cleaver first. It gives a lot of important stat that we need. Follow up with Warmog's Armor to meet the high Health ratio. With these Health items, we won't burst in 1 hit, so it's time to max out our CDR via boots and another Brutalizer. We then can build Maw of Malmortius alongside with Randuin's Omen. Since Mercurial Scimitar is expensive, buy that last.

Our ideal stat ratio at final build is:

**(3750 Health, 150 Armor and 150 Magic Resist, and 278 AD)**

Let's compare it with our stat profile at level 18:

![HXA Pantheon final build stats - lol theory crafting](/images/content/hxa-pant-final-build-stats.png)

*(generated at leaguecraft.com)*

With Elixers, we hit max Cooldown Reduction. However, Since we are a bit high on Health, when we have the money, feel free to replace Randuin's Omen with Frozen Heart. We then don't need CDR boots, so replace it with another boot or Guardian's Angel.

### The Armor Penetration Route:

If our Champion's AD ratio is severely low, then it may be a better option to forget about the optimum AD ratio, and to just replace the AD item that we would have had with Armor Penetration. Of course, keep the Cooldown Reduction at max. 

![HXA Armor penetration build - LoL theorycrafting](/images/content/hxa-armor-pen-build.png)

*(generated at leaguecraft.com)*

![HXA Armor penetration build stats - LoL theorycrafting](/images/content/hxa-armor-pen-stats.png)

*(generated at leaguecraft.com)*

The Armor Penetration build, in comparison to the previous, will deal more damage; however, it is squishier. We can't have it all. It's a sacrifice to be made. 

Late-late game when we have money, go ahead and replace Last Whisper or Youmu's Ghostblade for Trinity Force. This will help us with our Health while maintaining a good DPS. Then Elixers should take us all the way to our ideal stats.

These builds are simply an example. There are many other builds out there that can hit the ratios above as well. Try out [leaguecraft.com/builder/](http://leaguecraft.com/builder/) to try to create your own build catered to your favorite Champ. You just may open the door to a new meta Item Build ;).

