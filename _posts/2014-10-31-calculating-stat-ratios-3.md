---
layout: post
title:  "Calculating Optimum Stat Ratios - Part 3: Balanced Defense x AP Ratio"
description: "Enjoy playing beefy AP Champions (Gragas, Swain, Singed, Maokai, and the such)? Ever wondered what the perfect ratio was to achieve Off-Tank Status whilst maintaining a high damage?"
excerpt: "Enjoy playing beefy AP Champions (Gragas, Swain, Singed, Maokai, and the such)? Ever wondered what the perfect ratio was to achieve Off-Tank Status whilst maintaining a high damage?"
author: "Samuel Kuo"
author_profile: "a LoL theory crafter and an innovator that digs deep"
author_coach: "http://gamerunners.gg/coaches/3"
date: 2014-10-31
categories: lol
tags: theorycraft
thumbnail: "/images/content/hxa-swain.png"
---

**The material in this article is cumulative of materials covered in the previous articles, so if you haven't checked them out yet, [here's a link to Article 1](http://news.gamerunners.gg/lol/calculating-optimum-stat-ratios/).**

Enjoy playing beefy AP Champions (Gragas, Swain, Singed, Maokai, and the such)? Ever wondered what the perfect ratio was to achieve Off-Tank Status whilst maintaining a high damage? If so, then let's delve into the dimension of mathematics and quantify the perfect Balanced Defense x AP Ratio. 

The calculations methods will be the same methods as in the previous article - measuring the True Value or the Effectiveness of stats, and minimalizing Diminishing % Returns. For more information on Effectiveness, check the [previous article](http://news.gamerunners.gg/lol/health-x-armor-3/). For information on minimalizing Diminishing % Returns, check the optimum [Health x Armor Article](http://news.gamerunners.gg/lol/calculating-optimum-stat-ratios/). Alright, the bell has rung. Take your seats because class has begun!

## The Cost of Health, Armor, and AD/AP

To calculate the optimum ratios for a balanced build, we first need to figure out what the "true value" of each relevant stats are. Let's first take a look at gold cost.

To determine the cost of stats per unit, we take the cheapest item of a given unit, and take its cost divided by the amount of unit it offers.

![HXA LoL Theory crafting - Cloth Armr](/images/content/hxa-cloth-armor.png)

*(image from leagueoflegends.wikia.com)*

Cloth Armor is 300g. It gives 15 Armor; so if we divide 300 gold by 15 Armor, we find that we are paying **20 gold per unit of Armor**. Magic Resist is actually the same cost as well. How convenient!

Let's check how much Health costs.

![HXA LoL Theory crafting - Ruby Crystal](/images/content/hxa-ruby-crystal.png)

*(image from leagueoflegends.wikia.com)*

Ruby Health provides 150 Health at the cost of 400 gold. Dividing 400 gold by 150 Health, we get 8/3, or about **2.67 gold per Health stat**.

Amplifying Tome.

![HXA LoL crafting theory - amplifying tome](/images/content/hxa-amp-tome.png)

*(image from leagueoflegends.wikia.com)*

Amplifying Tome provides 20 AP for 435 gold. The quotient of 435 and 20 is **21.75**.

Now that we have the gold value of each stat of interest, we can now calculate the true value of each stat! We simply divide the value of each stat by its gold amount.

## True Value

Most of the stats value are pretty straightforward - 1.0. However, there are confusing ones including Cooldown Reduction and Armor Penetration. Check out for details on Cooldown Reduction, and for details on why Armor is so much less than the others, [check my optimum defense ratio article](http://news.gamerunners.gg/lol/calculating-optimum-stat-ratios-2/)).

> Health = 1.0/(8/3) = 0.375

> Armor = .01/20/2 = 0.00025

> AD = 1.0/36 = 0.0277777777777778

> AP = 1.0/21.75 = 0.0459770114942529

**Cooldown Reduction = [Check the previous article for info](http://news.gamerunners.gg/lol/calculating-optimum-stat-ratios-4/).**

**Magic Penetration = [Check my Armor Penetration article for info](http://news.gamerunners.gg/lol/hidden-gems-armor-penetration-1/).**

With these units of measuring, we now just have to keep them in symmetry to minimalize Diminishing % Returns to optimize our stat ratios.

## Optimum Balanced AP Caster Ratio

Ideal sample ratios:

> With 1 unit in Health, Armor, Magic Resist, and AP, we have 0.375 Health x 0.00025 Armor x .0046 Magic Resist x  .092 AP

> With 2 units in Health, Armor, Magic Resist, and AD, we have 0.75 Health x 0.0005 Armor x 0.0005 Magic Resist x 0.051 AD

> With 3 units in Health, Armor, Magic Resist, and AD, we have 1.125 Health x 0.00075 Armor x 0.00075 Magic Resist x 0.14 AP

...

...

...

> With 2000 units in Health, Armor, Magic Resist, and AP, we have 750 Health x 0.5 Armor x 0.5 Magic Resist x 92 AP

> **(750 Health, 0 Armor and 0 Magic Resist, and 92 AP)**

> With 3000 units in Health, Armor, Magic Resist, and AP, we have  1125 Health x 0.75 Armor x 0.75 Magic Resist x 138 AP

> **(1125 health, 0 Armor and 0 Magic Resist, and 138 AP)**

> With 4000 units in Health, Armor, Magic Resist, and AP, we have 1500 Health x 1.0 Armor  x 1.0 Magic Resist x 184 AP

> **(1500 Health, 0 Armor and 0 Magic Resist, and 184 AP)**

> With 6000 units in Health, Armor, Magic Resist, and AP, we have 2250 Health x 1.5 Armor x 1.5 Magic Resist x 276 AP

> **(2250 Health, 50 Armor and 50 Magic Resist, and 276 AP)**

> With 8000 units in Health, Armor, Magic Resist, and AP, we have 3000 Health x 2.0 Armor x 2.0 Magic Resist x 368 AP

> **(3000 Health, 100 Armor and 100 Magic Resist, and 368 AP)**

> With 10,000 units in Health, Armor, Magic Resist, and AP, we have 3750 Health x 2.5 Armor x 2.5 Armor x 460 AP

> **(3750 Health, 150 Armor and 150 Magic Resist, and 460 AP)**

> With 12,000 units in Health, Armor, Magic Resist, and AP, we have 4500 Health x 3.0 Armor x 3.0 Magic Resist x 552 AP

> **(4500 Health, 200 Armor and 200 Magic Resist, and 552 AP)**

## Against Only One Type of Damage

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

To know how much AP is needed, simply refer to the first chart of ideal sample ratios. The Health and offensive stat ratios are the exact same.

## % Stat Increase : Rabadon's Death Cap & Archmage

Sources that provide a % Stat bonus obscure the amount of stat that we need. Take for example, Rabadon's Deathcap:

![HXA thoery crafting - rabadons deathcap](/images/content/hxa-rabadon.png)

*(image from leagueoflegends.wikia.com)*

Rabadon's Deathcap increases our AP amount by +30%. Our AP ratio still remains the same; however, the amount of AP we have is obscured. For example, if our ideal AP ratio is at 300, we need to buy 300 AP. However, our HUD will show our Health at 300*1.23 = 330 AP. To un-obscure-ize how much Health we need, we have a formula:

**Ideal stat*%Stat Increase=Hud-Displayed Stat**

or...

**Ideal Stat=(HUD-Displayed Stat/% Stat Increase)**

So say for example, we have 330 Health, and we know we have a 30% Health increase, but we don't know if we have hit our 300 ideal stat, we can plug Health and %Stat increase in:

> Ideal Stat = (300/1.30) = ... 330 AP. Yes, we have hit our AP quota!

Also, watch out for Archmage from Masteries, which provides +5% AP!

## The Set-Up and First Item

Let's take a look at our ideal stat ratios and see what the math is telling us. As a reference, let's use Swain's stats at level 1 for analysis. 

![HXA theory crafting - Swain](/images/content/hxa-swain.png)

Swain starts with 0 AP,  463 Health, 20 Armor, and 30 Magic Resist.

Our goal to reach early is:

> (750 Health, 0 Armor and 0 Magic Resist, and 92 AP)

Because we are lacking in Health and AP, our best option to start is:

![HXA doran's ring + lolcrafting](/images/content/hxa-dorans-ring.png)

Doran's Ring gives us a balance of Health and AP, which are the 2 stats we need to hit our early quota. Of course, we'll still need a lot of Health and AP.

Let's see if our Mastery Page can help a bit.

![HXA masteries swain - lolcrafting](/images/content/hxa-masteries-swain.png)

Mental Force provides 0.89 AP per level. Arcane Mastery provides 6 AP.  This will help us reach our AP quota faster. We have 9 points in Utility to help sustain us in lane. 

We can't forget our Rune Page:

![HXA rune page swain - lolcraft](/images/content/hxa-runes-swain.png)

*(generated at loldb.gameguyz.com)*

With the bonus 25.56 AP, 15 AP (Doran's Ring), 6.89 AP (Mastery Page), we achieve **47.45 AP** at level 1. Our innate Health is 463. With the bonuses from 60 Health (Doran's Ring) and 72 Health (Rune Page), we achieve **595 Health** at level 1.

We still aren't there, but it's the best set-up possible. 

## 1st and/or 2nd Item to Max

By now, we should be level 6, and our stat profile should be something like this:

![HXA swain level 6 - lolcrafting](/images/content/hxa-swain-6.png)

Because we still haven't hit 92 AP, we should buy a Blasting Wand for +40 AP to help us hit our quota. When we do, here is our new goal:

> (1500 Health, 0 Armor and 0 Magic Resist, and 184 AP)

Same as level 1, we need more Health and AP (and Mana for the Mana-Thirsty Swain). All this can be acheived via:

![HXA Rod of ages - lolcrafting](/images/content/hxa-rod-of-ages.png)

Rod of Ages, at max stats, provides 80 AP and 650 health. While we'll hit our Health quota, we're still a bit short on AP.

For Mana-less AP Champions, such as Rumble, go ahead and build:

![HXA liandrys torment - lolcrafting](/images/content/hxa-linadry.png)

Liandry's Torment provides a decent amount of Health and AP. While we won't be hitting our quotas, we get Magic Penetration, which is strong Early Game, and a nice Unique Passive to deal more damage. 

I would, however, not upgrade Haunting Guise to Liandry's Torment Early Game. Hitting our Health and AP quotas are much more important than the passives. Therefore, we have second item to pair it with to meet our quotas:

![HXA Rylai's crystal sceptre - lolcrafting](/images/content/hxa-rylais.png)

Our other option is Rylai's Crystal Scepter, which gives more Health and AP than Liandry's Torment, but less than Rod of Ages. This is another great item choice on Mana-less Champions, such as Rumble. If we need Mana, get Rod of Ages.

## 2nd and/or 3rd Item to Max 

By now, we should be around level 8-11. Our stats, with just a Rod of Ages and Doran's ring, would look like this:

![HXA Swain level 11 - lolcrafting](/images/content/hxa-swain-11.png)

### We've hit the previous Health quota, but we still haven't hit our optimum AP ratio. 
Let's adjust our new goal for Mid Game:

> (2250 Health, 50 Armor and 50 Magic Resist, and 276 AP)

We have almost enough Health, Armor, and Magic Resist. We just need AP now. Therefore, we need Rabadon's Deathcap, the best AP item in the game.

![HXA Rabadons Deathcap - lolcrafting](/images/content/hxa-rabadon.png)

Rabadon's Deathcap. Tons of damage. This is ideal for when we are in Mid Game.

However, if we are still in laning phase, meaning we only face against 1 type of Damage, we need to use this ratio:

> (2250 Health, 200 Armor or Magic Resist, and 276 AP)
So if we are facing against a Physical Damage Dealer, our ratio is telling us that we need 200 Armor. If against a Magical Damage Dealer, we need 200 Magic Resist.

This, however, doesn't mean we should actually build 200 Armor. We don't know when laning phase ends, and if we build 200 Armor, but we end up dieing to a Magical Damage Dealer, we built in a way that was not optimum. Therefore, it's safe to build to just 100 Armor or Magic Resist.

## Against Magic Damage Dealers

![HXA Abyssal sceptre - lolcrafting](/images/content/hxa-abyssal.png)

Abyssal Scepter gives us 70 AP and 45 Magic Resisitance, and a nice AOE Flat 20 Magic Reduction. We won't be hitting our AP ratio; however, since we live longer, we'll be doing more damage to make up for it!

Either Abyssal Scepter or...

![HXA athene's unholy grail](/images/content/hxa-grail.png)

Athene's Unholy Grail doesn't give us too much AP nor Magic Resistance, but it gives us a huge Cooldown Reduction boost. The Cooldown Reduction, however, isn't as effective on Swain nor Rumble whom can maintain a Spell for an extended amount of time.

## Against Physical Damage Dealers

![Zhonya's Hourglass - hxa lolcrafting](/images/content/hxa-zhonya.png)

Zhonya's Hourglass gives a ton of AP and some Armor. It will help us almost hit our AP quota. The Unique Active is also argueably the best utility for AP Carries. This is especially highly recommended on Swain because he can still Channel his Ultimate while activating Statis.

![Iceborn Gauntlet - hxa lol theorycraft](/images/content/hxa-iceborn.png)

This is an item ideal for AP Champions that go melee range often, such as Gragas. It provides a nice Cooldown Reduction on well. Remember, hitting 40 CDR is equivalent to approximately +1.67% DPS on spells!

Swain could benefit from item too; however, due to the lack of AP and Statis outclassing Iceborn Gauntlet, we shall go with Zhonya's Hourglass on our Swain. 

## 30 Minutes into the Game...

30 minutes is that golden number when tanks are just getting too tanky. It's time to build some % Magic Penetration!

### Void Staff

To get an idea of how much more damage we will be dealing with Void Staff, let's see how much the 35% Armor Penetration portion itself will give us:

> **Against 300-Armor Target:**

> *(1-(300*.65/(100+300*.65)))/(1-(300/400)) = 1.36 or +36% increased DPS*

> **Against 250-Armor Target:**

> *(1-(250*.65/(100+250*.65)))/(1-(250/350)) = 1.33 or +33% increased DPS*

> **Against 200-Armor Target:**

> *(1-(200*.65/(100+200*.65)))/(1-(200/300)) = 1.30 or +30% increased DPS*

> **Against 150-Armor Target:**

> *(1-(150*.65/(100+150*.65)))/(1-(150/250)) = 1.27 or +27% increased DPS*

> **Against 100-Armor Target:**

> *(1-(100*.65/(100+100*.65)))/(1-(100/200)) = 1.21 or +21% increased DPS*

![HXA Void staff - lolcrafting](/images/content/hxa-void-staff.png)

*(image from leagueoflegend.wikia.com)*

Void Staff (2295 gold) is very cost efficient in comparison to say - Rabadon's Deathcap (3300 gold), which only gives 30% more AP, essentially a +30% increased DPS via spells.

If we want  to optimize our damage, Void Staff is the third highest damaging AP item (1st. Rabadon's Death Cap 2. Deathfire Grasp 3. Void Staff)

**This item isn't required, it's just cost efficient. If we built it on Swain, plan to sell it later on for a more expensive item.

## Last Items

In Late Game factoring in Doran's Ring, Rod of Ages, Zhonya's Hourglass, and Void Staff, our stat profile is now:

![HXA Swain level 16 - lol theory craft](/images/content/hxa-swain-16.png)

Since we should be out of definitely be out of Laning phase by now, let's use this new ratio:

> (3000 Health, 100 Armor and 100 Magic Resist, and 368 AP)

There's a lot of ways to achieve this, let's take a look at some final builds:

### Example Item Build

**Cost-Efficient Final Build**

![HXA swain cheap build - lol crafting](/images/content/hxa-swain-cheap-build.png)

![HXA swain cheap build stats - lol crafting](/images/content/hxa-swain-cheap-stats.png)

This build costs a measely 14,720 gold. However, it is cost-efficient and will outclass most other builds witht he same gold amount. Of course, we can resell items so that we can hit our next plateau ratio:

> (3750 Health, 150 Armor and 150 Magic Resist, and 460 AP) 

To achieve this, we're going to need to sell half our items to go beast mode.

**Beast Mode Swain**

![HXA beast mode Swain - league of legends theory crafting](/images/content/hxa-swain-final-form.png)

![HXA Swain final level stats - lol crafting](/images/content/hxa-swain-final-stats.png)

We are a bit short on Magic Resist and Health. But our Guardian Angel and Zhonya's Hourglass will keep us from focus fire. Also, if we die, our Ultimate will continue to heal us will Ressurecting. Rylai's Crystal Scepter will make up for the loss of boots. Void Staff was sold for Rabadon's Deathcap, even though the damage difference won't be too noticeable, Rabadon's Deathcap is slightly better. 

If we play a Champion that needs 40% Cooldown Reduction, we'll have to fall back to our old ratio (the 3000 Health one) to squeeze in 40% CDR. 

### 40% CDR Balanced AP Build

![HXA Garagas 40 - lol crafting](/images/content/hxa-gragas-40.png)

*(made at leaguecraft.com)*

![HXA Garagas 40 stats - lol crafting](/images/content/hxa-gragas-40-stats.png)

Build Rod of Ages first. We can build Ice Gauntlet first as well; however, be sure to follow up with Rod of Ages as the Health provided is paramount in the path to becoming a monster of destruction. Hourglass can replace Ice Gauntlet; however, switch Magic Penetration boots to Cooldown Reduction or adjust the rune page.

With Elixers, we hit max Cooldown Reduction. This build will get us close to:

> (3000 Health, 100 Armor and 100 Magic Resist, and 368 AP)

## The Magic Penetration Route:

If our Champion's AP/AD ratio is severely low, then it may be a better option to forget about the optimum AD/AP ratio, and to just replace the AD/AP item that we would have had with Armor Penetration. Of course, keep the Cooldown Reduction at max. 

![HXA magic penetration route - lol theory craft](/images/content/hxa-magic-pen-route.png)

*(generated at leaguecraft.com)*

![HXA magic penetration route stats - lol theory craft](/images/content/hxa-magic-pen-route-stats.png)

These builds hit around the same optimum stat ratios. 

If we want max CDR, replace Void Staff with Athene's Unholy Grail. Then the Elixers will take take us to max CDR. 

There's a lot of different item builds/Rune Page/Masteries combination that can get us to the optimum ratios. See if you can invent your own!

## Conclusion

**Early Game** - Invest in Health and AP (Doran's Ring)

**Late-Early Game** - Invest in more AP and Health via Rod of Ages, or Haunting Guise and Rylai's Crystal Scepter 

**Mid Game** - Purchase Rabadon's Deathcap if out of Lane Phase; otherwise, buy hybrid AP tank items

**Late-Mid Game** - Invest in % Magic Penetration (Void Staff)

**Late Game** - Up to you!
