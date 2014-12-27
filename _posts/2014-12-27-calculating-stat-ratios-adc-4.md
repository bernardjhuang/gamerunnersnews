---
layout: post
title:  "Calculating Optimum Stat Ratios - Part 4: AD Carry"
description: "Do you main AD Carry? Ever wondered how much Life Steal you should invest in? Want to know what the perfect ratio between Crit. Rate, Attack Speed, and AD is? Then read on!"
excerpt: "Do you main AD Carry? Ever wondered how much Life Steal you should invest in? Want to know what the perfect ratio between Crit. Rate, Attack Speed, and AD is? Then read on!"
author: "Samuel Kuo"
author_profile: "a LoL theory crafter and an innovator that digs deep"
author_coach: "http://gamerunners.gg/coaches/3"
date: 2014-12-27
categories: lol
tags: math
thumbnail: "/images/content/adc-3.png"
---

*The material in this article is cumulative of materials covered in the previous articles, so if you haven't checked them out yet, [here's a link to Article 1](http://news.gamerunners.gg/lol/calculating-optimum-stat-ratios/).*

**<a href="#ratios">Skip to the optimum AD carry stat ratios</a>**

Do you main AD Carry? Ever wondered how much Life Steal you should invest in? Want to know what the perfect ratio between Crit. Rate, Attack Speed, and AD is? Then read on!

Our [previous article decoded the optimum ratio between Health, Armor, AD and Attack Speed](http://news.gamerunners.gg/lol/calculating-stat-ratios-4/). However, Health and Armor is not as relevant for AD Carries. We want mour damage! This article will add Life Steal and Crit. Rate as additional value to replace the Health and Armor variable (I will keep the Health and Armor variable in place for those that want a balanced build). So let's get rockin' and rollin,' and figure out if there is some way we can quantify Crit Rate. 

## The Value of Crit Rate

In League of Legends, proccing a Crit. Strike means we deal twice the damage. At 100% Crit Rate, obviously we would be dealing 2 times more damage since every hit is Critting; thus, twice the DPS. But what's the DPS of when we have 1% Crit Rate?

Let’s say we have a 1% Crit Rate, and we deal 1 damage per hit. Over the course of 100 hits, it is statistically likely that we’ll Crit. Strike approximately 1 time. If we do Crit Strike only once, we deal 99 damage through normal hits, and 2 damage through a Crit Strike. In total, we deal 101 damage. Compare this damage to 100 damage if we had no Crit Rate (100 damage by 100 normal hits). Dividing the two where we had 1% Crit Rate and where we had 0% Crit Rate, we see that 101/100 = 1.01, or essentially a **1% increase** in DPS. We then can simply say the true value of Crit Rate is **.01**.

**Remember, since it is 101/100 = 1.01, the 1.00 is equivalent to 100 free units in Crit. Rate. Therefore, 1.01 Crit Rate is actually 101 units invested into Crit Rate (1.01/.01=101). 

We can also calculate DPS with a formula: **(1+(1*(Crit Rate/100)))**. To check our previous work, plug 1 into Crit Rate. We'll get **(1+(1*(1/100)))=1.01**. We've got a matching number!

Now, what if we have Infinity Edge? Infinity Edge changes our Crit Damage from dealing 2.0 more damage to 2.5 damage. The DPS formula via Crit Rate changes: **(1+(1.5*(Crit Rate/100)))**. This basically changes the true value of Crit. Rate by x1.5. Therefore: .01*1.5=**0.015**. Because of this, when I list the optimum ratio for DPS later, I'll have a set for "Before Infinity Edge," and one for "After Infinity Edge." 

We still need to factor in gold value, which will further change the True Value of Crit Rate.

## The Cost of Health, Armor, AD, Attack Speed, and Crit Rate

To determine the cost of stats per unit, we take the cheapest item of a given unit, and take its cost divided by the amount of unit it offers.

![Calculating Stat Ratios - ADC, cloth armor](/images/content/cloth-armor.png)

*(image from leagueoflegends.wikia.com)*

Cloth Armor is 300g. It gives 15 Armor; so if we divide 300 gold by 15 Armor, we find that we are paying **20 gold per unit of Armor**. Magic Resist is actually the same cost as well. How convenient!

Let's check how much Health costs.

![Calculating Stat ratios - adc, ruby crystal](/images/content/ruby-crystal.png)

*(image from leagueoflegends.wikia.com)*

Ruby Health provides 150 Health at the cost of 400 gold. Dividing 400 gold by 150 Health, we get 8/3, or about **2.67 gold per Health stat**.

Long Sword.

![Calculating Stat Ratios - ADC, long sword](/images/content/long-sword.png)

*(image from leagueoflegends.wikia.com)*

Long Sword provides 10 AD for 360 gold. The quotient of 360 and 10 is **36**. 1 AD = 36 gold.

And Dagger...

![Calculating Stat Ratios - ADC, dagger](/images/content/dagger.png)

*(image from leagueoflegends.wikia.com)*

Dagger costs 450 gold and provides 15% Attack Speed. 450/15 = **30 gold per unit of Attack Speed (AS)**.
And the new stat value we will be calculating in this article, Brawler's Gloves:

![Calculating Stat Ratios - ADC, Brawler's gloves](/images/content/brawlers-gloves.png)

*(image from leagueoflegend.wikia.com)*

Costing 400 gold and giving a 8 Crit Rate, we can calculate that 400/8 = **50 gold per unit of Crit Rate**.

## True Value Per stat

Simply take the value of each stat and divide it by its respective gold cost to the true value.

**Health = 1.0/(8/3) = 0.375**

**Armor = .01/20/2 = 0.00025**

**AD = 1.0/36 = 0.0277777777777778**

**Attack Speed= .01/30 = 0.0003333333333333**

**Crit. Rate = .01/50 = 0.0002**

The true value of Crit. Rate changes with Infinity Edge, which provides a 50% bonus damage to damage dealt when we proc a crit. strike: 

**Crit. Rate w/ Infintiy Edge = (.01/50)*1.5=0.0003**

Basically, we're going to have 2 different ratio charts for DPS for before Infinity Edge and after Infinity Edge.

With these units of measuring, we now just have to keep them in symmetry to minimalize Diminishing % Returns to optimize our stat ratios.

<h2 id="ratios"> Optimum AD Carry Stat Ratio w/ Infinity Edge</h2>

Ideal sample ratios:

> With 1 unit in Health, Armor, Magic Resist, AD, and Attack Speed, we have 0.375 Health x 0.00025 Armor x 0.00025 Magic Resist x 0.028 AD x 0.00033 Attack Speed x 0.0003 Crit. Rate
 
> With 2 units in Health, Armor, Magic Resist, AD, and Attack Speed, we have 0.75 Health x 0.0005 Armor x 0.0005 Magic Resist, 0.056 AD x 0.00067 Attack Speed. x 0.0006 x Crit. Rate

> With 3 units in Health, Armor, Magic Resist, AD, and Attack Speed, we have 1.125 Health x 0.001 Armor, 0.001 Armor, about 0.083 AD, and about 0.001 Attack Speed x 0.0009 Crit. Rate

...

...

...


> With 3000 units in Health, Armor, Magic Resist, AD, Attack Speed, and Crit. Rate, we have 1125 Health x 0.75 Armor x 0.75 Magic Resist x 83 AD x 0.99 Attack Speed x 0.6 Crit Rate 

> **(1125 Health, 0 Armor, 0 Magic Resist, 83 AD, 0 Attack Speed, 0% Crit Rate)**

> With 4000 units in Health, Armor, Magic Resist, AD, Attack Speed, and Crit. Rate, we have 1500 Health x 1.0 Armor x 1.0 Magic Resist x  111 AD x 1.33 Attack Speed x 0.8 Crit. Rate 

> **(1500 Health, 0 Armor, 0 Magic Resist, 111 AD, 33% Attack Speed, 0% Crit Rate)**

> With 5000 units in Health, Armor Magic Resist, AD, Attack Speed, and Crit. Rate, we have 1875 Health x 1.25 Armor x 1.25 Magic Resist x 139 AD x 1.67 Attack Speed x 1.0 Crit Rate 

> **(1875 Health, 25 Armor, 25 Magic Resist, 139 AD,  67% Attack Speed, 0 Crit Rate)**

> With 6000 units in Health, Armor, Magic Resist, AD, Attack Speed, and Crit. Rate,  we have 2250 Health x 1.5 Armor x 1.5 Magic Resist x 167 AD x 1.99 Attack Speed x 1.2 Crit. Rate 

> **(2250 Health, 50 Armor, 50 Magic Resist, 167 AD, and 99% Attack Speed, 20% Crit Rate)**

> With 7000 units in Health, Armor, Magic Resist, AD, Attack Speed, and Crit. Rate, we have 2625 Health x 1.75 Armor x 1.75 Magic Resist x 194 AD x 2.33 Attack Speed, 1.4 Crit Rate 

> **(2625 Health, 75 Armor, 75 Magic Resist, 194 AD, 133 Attack Speed, 40% Crit Rate)**

> With 8000 units in Health, Armor, Magic Resist, AD, Attack Speed, and Crit. Rate, we have 3000 Health x 2.0 Armor x 2.0 Magic Resist x  222 AD x 2.67 Attack Speed x 1.6 Crit Rate 

> **(3000 Health, 100 Armor, 100 Magic Resist, 222 AD, and 167% Attack Speed, 60% Crit Rate)**

> With 9000 units in Health, Armor, Magic Resist, AD, Attack Speed, and Crit. Rate, we have 3375 Health x 2.25 Armor x 2.25 Magic Resist x 250 AD x 2.99 Attack Speed x 1.8 Crit Rate 

> **(3375 Health, 125 Armor, 125 Magic Resist, 250 AD, 199% Attack Speed, 80% Crit Rate)**

> With 10000 units in Health, Armor, Magic Resist, AD, Attack Speed, and Crit. Rate, we have 3750 Health x 2.5 Armor x 2.5 Magic Resist x 278 AD x 3.33 Attack Speed x 2.0 Crit Rate 

> **(3375 Health, 150 Armor, 150 Magic Resist, 278 AD, 233% Attack Speed, 100% Crit Rate)**

With Infinity Edge, we see that at 194 AD, we should already be maxing out Crit Rate. This means building items that comes with a lot of AD, such as Blood Thirster, will really hurt ones DPS early if building an Infinity Edge. Instead, we should look to invest into Attack Speed or Armor Penetration. Items such as Youmuu's Ghostblade, Statikk Shiv, and Blade of the Ruined King are a great complement to Infinity Edge. 

## Against Only One Type of Damage (if we are interested in defense)

In scenarios where we are only facing against one type of damage, such as when we are in lane requires more Armor. Since the value of Armor is basically twice as effective (since there's only one type of damage), we simply take the ideal stat ratio of Health and Armor or Magic Resist stat listed above, and double it.

Ideal sample ratios:

> With 1 unit in Health, Armor we have .375 Health x .0005 Armor

> With 2 unit in Health, Armor we have 0.75 Health x .001 Armor

> With 3 unit in Health, Armor, we have 1.125 Health x 0.0015 Armor

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

## Innate Stats

Champions come with innate stats that increases per level. For example, Tristana gains +2.5% Attack Speed per level. At level 18, this innate Attack Speed bonus totals to +42.5%.

It's important to know how much free stats our Champion is already getting, and how much more we need when planning an item build. I use leagueoflegend.wikia.com as a reference this. Just land on that website and search the Champion of interest in the search bar.

## The Set-Up and First Item

Let's take analyze the ideal stat ratios, and see what the math is trying to tell us.

> **(1125 Health, 0 Armor, 0 Magic Resist, 83 AD, 0 Attack Speed, 0% Crit Rate)**

The first and foremost stats that we want, according to the ratios, are Health and AD. This means that the best item to start with is Doran's Blade. 

![Calculating Stat Ratios - ADC, doran's blade](/images/content/dorans-blade.png)

*(image from leagueoflegend.wikia.com)*

Doran's Blade provides a balance of Health and AD. We also have a small boost to Life Steal, which will help sustain us in lane. Of course, which just a Doran's Blade, we won't hit our Health or AD quota. Let's check our Masteries:

![Calc stat ratios - adc masteries](/images/content/adc-mastery.png)

We invest points in Brute Force and Martial Mastery. Together, these 2 will provide us 4.55 AD at level 1. We also invest in Veteran's Scar for a bonus +36 Health and Juggernaut, which gives us a +1.03% Health bonus. 

Let's check our Rune Page:

![calc stat ratios - adc runes](/images/content/adc-runes.png)

To meet the ideal stat ratio quota, this Rne Page achives just that the best by pumping stats into Health and AD. Of course, we can adjust these Runes depending on preference. For example, if we want to sustain longer in lane, we can replace Health with Armor, and AD Quints with Life Steal Quints.

## 2nd and/or 3rd Item - AD and Attack Speed

Let's take a look at our next ratio plateau:

> **(1875 Health, 25 Armor, 25 Magic Resist, 139 AD,  67% Attack Speed, 0 Crit Rate)**

We see that we do not need to invest in Crit Rate yet. AD and Attack Speed are the stats that we need. However, of the cost-efficient damage items, there are none that give us only Attack Speed and AD. But there are some close candidates!

![Calculating Stat Ratios - ADC, blade of the ruined king](/images/content/blade-of-the-ruined-king.png)

*(image from leagueoflegend.wikia.com)*

Blade of the Ruined King is a very popular first item among short-ranged Champions, such as Vayne and Twitch. It gives a good Early Game Power Spike because of its Active to steal Health. It also steals Speed which offers unmatched utility. It provides Life Steal for Early Game lane-sustain. Moreover,it is a very cost-efficient item for the damage that punishes Health-mongers - Blade of the Ruined King passive deals 8% of our target's Health in bonus damage. At 1000 Health, we do 80 damage. At 2000 health, 160 Damage. At 3000, 240. And so on and so forth. 

Blade of the Ruined King also helps us reach our stat ratio quotas. Because we build 2 Long Swords in the process of making Blade of the Ruined King, we gain the Early Game AD that we need. We also build 2 Daggers which meets our Attack Speed need.

![Calculating Stat Ratios - ADC, youmu's ghostblade](/images/content/youmus-ghostblade.png)

*(image from leagueoflegend.wikia.com)*

Youmu's Ghostblade is also a very cost efficient item. Mathematically, with Youmu's Ghostblade's Active activated, Youmu's Ghostblade outdamages Infinity Edge! A new recent build that many Challenger AD Carries are doing is rushing Blade of the Ruined King paired with Youmu's Ghostblade for 2 Actives for the strongest Early Game Power Spike possible.
Youmu's Ghostblade, when activated, helps us reach our Attack Speed Quota and also gives us AD that we need.

![Calculating Stat Ratios - ADC, trinity force](/images/content/trinity-force.png)

*(image from leagueoflegend.wikia.com)*

Trinity Force is a popular first item on Caster-Type AD Carries, such as Ezreal and Corki. Though Trinity Force is an expensive item, Trinity Force's Spellblade is best utilized Early Game where it's strongest. Spellblade's bonus damage seemingly begins to diminish Late Game when we start Critting for 800 Damage. That's why contrary to it being a gold-inefficient item, it's at the same time good for Early Game, because that's when it shines. 

Trinity Force helps us reach close to our stat ratio with its Attack Speed and Damage provided. It also provides some Health, unlike Youmu's Ghostblade or Blade of the Ruined King.

Some of you may be wondering why I didn't list Infinity Edge here. Don't worry! I'll explain it in due time.
  
## 3rd and/or 4th item - Crit Rate

Let's take a look at our next plateau ratio:

> **(2250 Health, 50 Armor, 50 Magic Resist, 167 AD, and 99% Attack Speed, 20% Crit Rate)**

We can see that we finally should start building Crit Rate. But before that, it's time to explain why Infinity Edge wasn't listed above. The plateau ratio before this doesn't list Crit Rate. However, some Champion's come with innate Attack Speed, such as Tristana or Miss Fortune, that we can skip the previous ratios and jump to the Crit Rate ratios. So depending on what Champion we are playing, we can jump straight to building Crit Rate.

![Calculating Stat Ratios - ADC, infinity edge](/images/content/infinity-edge.jpg)

*(image from leagueoflegend.wikia.com)*

If we skipped the previous plateau ratio, we are probably low on AD. Therefore, the only item that we can build if we skipped the previous items is Infinity Edge, which provides AD and Crit Rate, both of which we need to meet our quotas.

Many people build Infinity Edge blindly as their first item. People hail Infinity Edge as the best first item because it provides a +50% Critical Strike Damage. But don't be fooled by the numbers! A +50% Critical Strike Damage is only a +25% increase in DPS (2.5/2=1.25). 

Building Infinity Edge first doesn't work on every AD Carry. The meta is shifting to rushing Blade of the Ruined King and Youmu's Ghostblade (and I mathematically calculated all this!). So unless we have Tristana or Miss Fortune, or someone with an innate Attack Speed boost, DO NOT rush Infinity Edge. It is not the most cost-efficient of items!

![Calculating Stat Ratios - ADC, phantom dancer](/images/content/phantom-dancer.png)

*(image from leagueoflegend.wikia.com)*

If we did not skip the previous plateau ratio, and have bought a Youmu's Ghostblade or Blade of the Ruined King, our next item should be Phantom Dancer. Phantom Dancer will hit our needed Crit Rate and Attack Speed quota. Nothing more to say.

![Calculating Stat Ratios - ADC, Statikk Shiv](/images/content/statikk-shiv.png)

*(image from leagueoflegend.wikia.com)*

The alternative to Phantom Dancer is Statikk Shiv. This is better to build if we had built a Trinity Force first. Trinity Force and Statikk Shiv together combines to create a strong burst damage. This item combination is popular on Quinn for Assassination missions. Statikk Shiv is also a popular choice for farming as it builds from the gold item, Avarice Blade. Once upgraded Statikk Shiv also gives a nice AOE damage to help clear creep waves for farming purposes.

## 4th or 5th Item - Last Whisper
Last Whisper is usually an item bought around 30 minutes as a 3rd or 4th max item (not including Doran's Blade). To get an idea of how much more damage we will be dealing with Last Whisper, let's see how much the 35% Armor Penetration portion itself will give us:

> Against 300-Armor Target:

> (1-(300*.65/(100+300*.65)))/(1-(300/400)) = 1.36 or +36% increased DPS

> Against 250-Armor Target:

> (1-(250*.65/(100+250*.65)))/(1-(250/350)) = 1.33 or +33% increased DPS

> Against 200-Armor Target:

> (1-(200*.65/(100+200*.65)))/(1-(200/300)) = 1.30 or +30% increased DPS

> Against 150-Armor Target:

> (1-(150*.65/(100+150*.65)))/(1-(150/250)) = 1.27 or +27% increased DPS

> Against 100-Armor Target:

> (1-(100*.65/(100+100*.65)))/(1-(100/200)) = 1.21 or +21% increased DPS

So now that we know how much we are getting from the Last Whisper, we still need to know how this amount of effectiveness that we are getting relates to other items. To get an idea of when to buy Last Whisper, let's see how much the +35% Armor Penetration aspect costs.

First, let's extract the unnessary stats. 

![Calculating Stat Ratios - ADC, last whisper](/images/content/last-whisper.jpg)

*(image from leagueoflegend.wikia.com)*

Last Whisper provides 40 AD. AD costs 36 gold each; therefore, 40 AD x 36 gold = 1440 gold. Last Whisper, in total, costs 2300 gold. Subtract 2300 gold - 1440 gold = 860 gold. Therefore, the remaining 860 gold is the cost of +35% Armor Penetration.

Last Whisper isn't THAT cost efficient in comparison to say, Phantom Dancer, which gives +50% Attack Speed and +30% Crit Rate. Having +30% Crit Rate is the same as +30% increased DPS. Therefore, just the 30% Crit Rate part of Phantom Dancer equals a Last Whisper hitting a 200-Armor target. Considering if we had no item, Phantom Dancer or just about any other offense items have a better cost efficiency than Last Whisper. 

The only difference is that Attack Damage, Attack Speed, and Crit Rate all have Diminishing % Returns. So say for example, if we build Infinity Edge and Phantom Dancer, then we will have a lot of Diminishing % Returns coming from AD, Attack Speed, and Crit Rate. It's just better to invest our stat elsewhere so our Diminishing % Returns don't stack up as high. That's where Last Whisper comes in shining as a 3rd or 4th item bringing a new variable - % Armor Penetration.

## 5th or 6th Item - Bloodthirster or Defense

Another variable we could have introduced in place of % Armor Penetration was Life Steal. 

Bloodthirster should be bought late since Life Steal does not shine until we have a significant amount of damage. Basically, a Bloodthirster is an optional item after we have our core items, which was the first 4 items. Of course I'm not saying we shouldn't build Life Steal to sustain in lane, but making a commitment to buying 20% Life Steal early is expensive, and not damage cost-efficient.

Bloodthirster is only an option if there are no Assasssins or people trying to dunk us (why get Life Steal if we won't even make it out alive?). 

In case of ninjas, such as Zed, we should invest in meeting our defense ratio quotas instead.

![Calculating Stat Ratios - ADC, mercurial scimitar](/images/content/mercurial-scimitar.jpg)

*(image from leagueoflegend.wikia.com)*

Mercurial Scimitar's Quicksilver active helps remove Zed's Deathmark. It also provides a nice +80 AD boost. But to be honest, we already have so much Diminishing % Returns from all the previous items that +80 AD isn't going to be doing much at this point.

![Calculating Stat Ratios - ADC, guardian angel](/images/content/guardian-angel.png)

*(image from leagueoflegend.wikia.com)*

Knowing that our AD Carry will ressurect upon Death, Guardian Angel is a great way to dissuade the enemy team from focusing fire on our AD Carry. It also provides the lack of Armor our build has to reach a balanced stat build defensively and offensively. However, Guardian Angel isn't so useful when it's Unique Passive is on Cooldown. Therefore, sell Guardian Angel for another optional item after death if possible. 

![Calculating Stat Ratios - ADC, randuin's omen](/images/content/randuins-omen.png)

*(image from leagueoflegend.wikia.com)*

Randuin's Omen is a great item for kiting Physical -Damaging Champions. The active slows nearby enemies allowing us to create distance. Randuin's Omen also provides a good Health and Armor boost. Only buy Randuin's Omen if there is or are Physical Damagers trying to dunk our AD carry!

![Calculating Stat Ratios - ADC, banshee's veil](/images/content/banshees-veil.jpg)

*(image from leagueoflegend.wikia.com)*

Banshee's Veil is hailed as being the greatest defensive item for AD carries. While I do not personally like it, Banshee's Veil is a great item for preventing enemy Crowd Control. Buy this item especially if there are AP Assassin Champion's on a bounty hunt for Lucian. Champions, such as AP Amumu and Le Blanc will find it a million times more difficult to Assassinate our innocent Lucian because of the Magic Resist boost, Health boost, and Spell Block. I firmly believe that just better positioning can solve these problems however. But if getting in the thicks of fight is your playstyle, Banshee's Veil may be for you.

![Calculating Stat Ratios - ADC, frozen mallet](/images/content/frozen-mallet.png)

*(image from leagueoflegend.wikia.com)*

This is another item to help us survive against burst damage with its hefty +700 Health boost. But it also has a nice Unique Passive - Icy. Icy will slow our enemy target helping us to kite more effectively and to chase our opponents with greater ease for the Pentakill. Icy is especially effective because it is a 40% slow. 40% slow is much more effective than a 40% boost to speed mathematically. Thus, Frozen Mallet can even help us replace our need for Boots.
Frozen Mallet is particularly a good item on Graves. Graves passive, True Grit:

![calculating stat ratios - adc carry, true grit](/images/content/true-grit.png)

Because True Grit offers a hefty amount of Armor, Graves building Health balances the Health x Armor ratio optimizing his defense.

## Example Final Item Build

If there are no Assassins, this is one possibility of what our build may look like:

![Calculating stat ratios - adc carry, trist build](/images/content/adc-3.png)

*(generated at leaguecraft.com)*

![Calculating stat ratios - adc carry, trist build stats](/images/content/adc-2.png)

*(generated at leaguecraft.com)*

### If There Are Ninjas...

If there are ninjas, we simply do not buy Bloodthirster (what's the point of Life Steal if we are Assassinated?). Instead we buy a defensive item in its slot. Here's an example build:

![Calculating stat ratios - adc carry, trist build if ninjas](/images/content/adc-1.png)

*(generated at leaguecraft.com)*

![Calculating stat ratios - adc carry, trist build stats if ninjas](/images/content/adc-4.png)

*(generated at leaguecraft.com)*

We can see that our DPS has dropped dramatically. However, it may be arguable that our DPS has actually risen because we can make more risky plays (such as jumping in and Assassinating the enemies AD Carry while surviving). The boot seem can be swapped our for Zephyr for increased DPS and tenacity. Tenacity will also synergize with our ability to play more aggressively. 

I chose Banshee's Veil in this example. However, remember our other options: Mercurial Scimitar, Guardian Angel, Randuin's Omen, and Frozen Mallet. They are all situational. Choose carefully.

## Conclusion

**Early Game** - Invest in Health and AD (Doran's Blade).

**Late-Early Game** - Invest in AD and Attack Speed (Blade of the Ruined King, Youmu's Ghostblade, Trinity Force). If we have built-in Attack Speed steroid like Tristana, skip this phase.

**Mid Game** - Invest in Crit Rate (Infinity Edge, Phantom Dancer, Statikk Shiv).

**Late-Mid Game** - Invest in % Armor Penetration (Last Whisper)

**Late Game** - Invest in % Life Steal (Bloodthirster) or defensive (Guardian Angel, Mercurial Scimitar, Randuin's Omen, Banshee's Veil, or Frozen Mallet)
