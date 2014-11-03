---
layout: post
title:  "Calculating Optimum Stat Ratios - Part 2: Health x Armor x Offense - The AA Bruiser"
description: "Bruisers have some of the most flexible but complicated item build. Bruisers must invest heavily in damage items to be able to take down enemy carries."
excerpt: "Bruisers have some of the most flexible but complicated item build. Bruisers must invest heavily in damage items to be able to take down enemy carries."
author: "Samuel Kuo"
author_profile: "a LoL theory crafter and an innovator that digs deep"
author_coach: "http://gamerunners.gg/coaches/3"
date: 2014-10-24
categories: lol
tags: theorycraft
thumbnail: "/images/content/hxa-cloth-armor.png"
---

*The material in this article is cumulative of materials covered in the previous articles, so if you haven't checked them out yet, [here's a link to Article 1](http://news.gamerunners.gg/lol/calculating-optimum-stat-ratios/).*

Bruisers have some of the most flexible but complicated item build. Having to invest heavily in damage items to be able to take down enemy carries; but at the same time, being in the forefront in team fights means taking heavy damage. Thus, Bruisers are in a crisis searching for perfect balance of offense and defense. Buying items has never been more mathematically critical!

I see there being two kinds of Bruisers - Auto-Attack Dependent Bruisers and Caster-Type Bruisers. Auto-Attack (AA) Dependent Bruisers include Champions but are not limited to Irelia, Udyr, Xin Zhao, Aatrox, Shyvana, Trundle, Warwick, Jax, Nocturne, and the such. The other kind are Bruisers that are more spell-reliant for dealing damage. This article will be looking at Auto-Attack Dependent Bruisers. For Caster-Type Bruisers, check this page (link). In this article, we will be combining the math for optimum damage and optimum defense to figure out the perfect Bruiser stat ratio. It is accumulative of Calculating Optimum Stat Ratios - Part 1, so if you haven't read that yet, [check it out here](../../lol/calculating-optimum-stat-ratios/). So without further ado, let's figure out how offense stats relate to defense stats.


## The Best Offense is a Good Defense... and Vice-Versa 

Let's say we deal 100 damage per second. We have 500 Health, but our opponent is dealing 250 damage per second to us. This means that we die in 2 seconds. However, each second, we deal 100 damage, so in 2 seconds, we deal **200 damage** before dying. 

Now let's increase our Health to 1000. This time, we die in 4 seconds. However, in 4 seconds, we deal **400 damage** before dying, which is **2 times more damage** than when we had 500 Health! 

In this example, we see that have a 100% increase in defense (500 Health -> 1000 Health) meant a 100% increase in offense (200 damage -> 400 Damage). Thus, we can see that offense is related to defense - The longer we live, the more damage we do. Or - The more damage we do (the faster we take down our opponent), the less damage we take. All we had to do was add the % increase in defense to offense, and we got our answer. Simple right?

## Effectiveness

Knowing this relation, we can treat offensive stat and defensive stat as one thing. We simply multiply the two and get a variable. Let's call this variable effectiveness. For example, Attack Speed, which provides a +1.0% to our offense is also the same as providing a +1.0% to our defense. Therefore, we say that the effectiveness of Attack Speed = +1.0% or +.01 per unit. 

Besides the effectiveness of units, we need to factor in how much gold each stat cost in relation to one another to calculate their true value.

## The Cost of Health, Armor, AD/AP, and Attack Speed

To determine the cost of stats per unit, we take the cheapest item of a given unit, and take its cost divided by the amount of unit it offers.

![HXA Cloth Armor - Theory Crafting LoL](/images/content/hxa-cloth-armor.png)

*(image from leagueoflegends.wikia.com)*

Cloth Armor is 300g. It gives 15 Armor; so if we divide 300 gold by 15 Armor, we find that we are paying **20 gold per unit of Armor**. Magic Resist is actually the same cost as well. How convenient!

Let's check how much Health costs.

![Ruby Crystal HXA - Theory Crafting LoL](/images/content/hxa-ruby-crystal.png)

*(image from leagueoflegends.wikia.com)*

Ruby Health provides 150 Health at the cost of 400 gold. Dividing 400 gold by 150 Health, we get 8/3, or about **2.67 gold per Health stat**.

Now let's take a look at some of our offense stats.

![Long Sword HXA - Theory Crafting LoL](/images/content/hxa-long-sword.png)

*(image from leagueoflegends.wikia.com)*

Long Sword provides 10 AD at the cost of 360 gold. Dividing 360 by 10, we see that 1 AD costs 36 gold.

And Dagger...

![HXA Dagger - Theory Crafting LoL](/images/content/hxa-dagger.png)

*(image from leagueoflegends.wikia.com)*

Dagger costs 450 gold and provides 15% Attack Speed. 450/15 = **30 gold per unit of Attack Speed (AS)**.

I want to point out that not all items in League of Legends do not necessarily follow these standard of measurements for units; however, most items in the game do follow these basic unit of stats as a reference. Thus, while we should know that the stats of other items do not deviate too much from the basic unit of measurement in LoL, we should also know that this unit of measurement is only an approximate.

**As attractive as Crit Strikes are in this game, the Crit. Rate stat is generally not viable for Bruisers. Crit Rate is dependent on many other offense items, such as a large quantity of AD, Attack Speed, and Armor Penetration. We simply do not have room for that much offensive items. Rather, building on-hit effect items for offense is much more cost-efficient and more independent items than Crit items which rely on other stats (AD, Attack Speed) to be effective. Since we are building as a Bruiser, we need to find the highest damaging items done in the least amount of item slots.

**I did not include Armor Penetration. This does not mean that Armor Penetration is not viable. If you're interesting in an Armor Penetration build, check [this article for all the information you'll ever need to know about Armor Penetration](../../lol/hidden-gems-armor-penetration-1/).

## True Value

Now that we have the cost of stats, we can find the true value of our stats in interest to create a unit of measurement. We simply divide the stat by its gold value:

**Health = 1.0/(8/3) = 0.375**

**Armor = .01/20/2 = 0.00025**

**AD = 1.0/36 = 0.0277777777777778**

**Attack Speed= .01/30 = 0.0333333333333333**

**Unless the opposing team has nothing but only physical or only magical damage, then we need to build damage against both. The true value of Armor changes when we take into account that we will be building two different Armor. Because our Armor is split 50/50 now to mitigate the opposing balanced damage, Armor's effectiveness is basically cut in half; thus, divide by 2. 

## Optimum Attacker-Based Bruiser Ratio

Ideal sample ratios:

*With 1 unit in Health, Armor,  Magic Resist, AD, and Attack Speed, we have 0.375 Health x 0.00025 Armor x 0.00025 Magic Resist x 0.028 AD x 0.033 Attack Speed*

*With 2 units in Health, Armor, Magic Resist, AD, and Attack Speed, we have 0.75 Health x 0.0005 Armor, 0.0005 Magic Resist, 0.056 AD, and about 0.067 Attack Speed*

*With 3 units in Health, Armor, Magic Resist, AD, and Attack Speed, we have 1.125 Health x 0.001 Armor, 0.001 Armor, about 0.083 AD, and about 0.1 Attack Speed*

*With 4000 units in Health, Armor, Magic Resist, AD, and Attack Speed, we have 1500 Health x 1.0 Armor x 1.0 Magic Resist x  111 AD x 133 Attack Speed*

**(1500 Health, 0 Armor, 0 Magic Resist, 111 AD, and 133% Attack Speed)**

*With 6000 units in Health, Armor, Magic Resist, AD, and Attack Speed, we have 2250 Health x 1.5 Armor x 1.5 Magic Resist x 167 AD x 199 Attack Speed*

**(2250 Health, 50 Armor, 50 Magic Resist, 167 AD, and 199% Attack Speed)**

*With 8000 units in Health, Armor, Magic Resist, AD, and Attack Speed, we have 3000 Health x 2.0 Armor x 2.0 Magic Resist x  222 AD x 267 Attack Speed*

**(3000 Health, 100 Armor, 100 Magic Resist, 222 AD, and 267% Attack Speed)**

*With 10000 units in Health, Armor, Magic Resist, AD, and Attack Speed, we have 3750 Health, 2.5 Armor x 2.5 Magic Resist x 278 AD x 333 Attack Speed*

**(3750 Health, 150 Armor, 150 Magic Resist, 278 AD, and 333% Attack Speed)**

*With 12000 units in Health, Armor, Magic Resist, AD, and Attack Speed, we have 4500 Health, 3.0 Armor, 3.0 Magic Resist, 333 AD, and 399 Attack Speed*

**(4500 Health, 200 Armor, 200 Magic Resist, 333 AD, and 399% Attack Speed)**

*Though it is not possible to get more than 2.5 Attack Speed, buying more than 2.5 Attack Speed is relevant if the opposing team has Frozen Heart or Randuin's Omen. If the opposing team has Frozen Heart or Randuin's Omen, the ideal Attack Speed value listed above remains the same.

## Against Only One Type of Damage

In scenarios where we are only facing against one type of damage, such as when we are in lane requires more Armor. Since the value of Armor is basically twice as effective (since there's only one type of damage), we simply take the ideal stat ratio of Health and Armor or Magic Resist stat listed above, and double it.

Ideal sample ratios:

*With 1 unit in Health, Armor, and AD, we have .375 Health x .0005 Armor*

*With 2 unit in Health, Armor, and AD, we have 0.75 Health x .001 Armor*

*With 3 unit in Health, Armor, and AD, we have 1.125 Health x 0.0015 Armor*

*With 2000 units in Health, Armor, and AD, we have 750 Health x 1.0 Armor*

**(750 Health, 0 Armor)**

*With 3000 units in Health, Armor, and AD, we have 1125 Health x 1.5 Armor*

**(1125 Health, 50 Armor)**

*With 4000 units in Health, Armor, and AD, we have 1500 Health x 2.0 Armor*

**(1500 Health, 100 Armor)**

*With 5000 units in Health, Armor, and AD, we have 1875 Health x. 2.5 Armor*

**(1875 Health, 150 Armor)**

*With 6000 units in Health, Armor, and AD, we have 2250 Health x 3.0 Armor*

**(2250 Health, 200 Armor)**

*With 7000 units in Health, Armor, and AD, we have 2625 Health x 3.5 Armor*

**(2625 Health, 250 Armor)**

*With 8000 units in Health, Armor,  and AD, we have 3000 Health x 4.0 Armor*

**(3000 Health, 300 Armor)**

*With 9000 units in Health, Armor, and AD, we have 3375 health x 4.5 Armor*

**(3375 Health, 350 Armor)**

*With 10,000 units in Health, Armor, and AD, we have 3750 Health x 5.0 Armor* 

**(3750 Health, 400 Armor)**

To know how much Attack Damage or Attack Speed is needed, simply refer to the first chart of ideal samp ratios. The Health and offensive stat ratios are the exact same.

Note that we do not need any Armor until after 750 Health. Also, with just an AD rune page for +9-15 AD, we already pass the AD ratio needed at lvl 1 by having 80 or more AD. At 1125 Health, 50 Armor is almost free from Champion innate stats, and 83 AD is already fulfilled as well. The only thing that needs pumping into is Health. 

Of course, it may be argueable that having more Armor is better for laning since it gives a better heal ratio from Healing Pots. However, if we find ourselves in a situation where one fight decides it all, these stat ratios are ideal. 

## Max Attack Speed
Champions max out their Attack Speed at 2.5 Attacks Per Second. To see how much bonus Attack Speed our Champion needs to hit max Attack Speed, refer to this site: [http://leagueoflegends.wikia.com/wiki/List_of_champions%27_attack_speed](http://leagueoflegends.wikia.com/wiki/List_of_champions%27_attack_speed)

If our ideal ratio is set above what's listed on the website, then simply readjust the Attack Speed so that we don't go too much Attack Speed. 
For example, Warwick needs 219.04% bonus Attack Speed to max out. Therefore, if we are trying to hit a goal like:

**(4500 Health, 200 Armor, 200 Magic Resist, 333 AD, and 299% Attack Speed)**

We need to readjust the Attack Speed to:

**(4500 Health, 200 Armor, 200 Magic Resist, 333 AD, and 219.04% Attack Speed)**

With the readjusted ratio, we know when to stop buying Attack Speed. 

**The amount listed on leagueoflegends.wikia already factors in innate Attack Speed provided per level to hit maximum Attack Speed. So we are looking to hit the quota on the website via Items, Runes, and Masteries.

## Items of Interest

![HXA Sunfire Cape - Theory Crafting LoL](/images/content/hxa-sunfire.png)

*(image from leagueoflegends.wikia.com)*

Sunfire Cape is a great early game item that offers us a balanced defensive and offensive stat. The 450 health and 45 bonus Armor easily our ideal ratio against only physical damage:

**(1500 Health, 100 Armor, 111 AD, and 133% Attack Speed)**

Though Sunfire Cape does not provide Attack Speed, Sunfire's Cape passive that deals anywhere from 26-43 damage is mathematically the same as bonus added to AD if we were at an attack rate of 1 per second. However, during late-game, we should sell Sunfire Cape because our AD stats become more valuable as our Attack Speed stat rises.

![HXA Trinity Force - Theory Crafting LoL](/images/content/hxa-trinity-force.png)

*(image from leagueoflegends.wikia.com)*

Trinity Force is one of those items we see every game. It's flexible as it provides many different stat ranging from both AD to AP. It is also used as a replacement for boots late-game when items are maxed. However, what really makes Trinity Force stand out is its passive - Spellblade.

**Spellblade deals 200% of our Champions base AD as bonus damage on the next Auto Attack.**

Take for example, Irelia has a base AD of 56. 200% of 56 is 112 damage. Therefore, if we can trigger Spellblade immediately when it comes off cooldown, we have an increased DPS of 112/1.5 = 74.67!  This boost to DPS in addition to the +30 AD, +30% Attack Speed, and +10 Crit. Rate makes Trinity Force perhaps the only damage we may need. It then goes by no surprise then that we see many builds in current meta that buys Trinity Force as their only damage item.

![HXA Blade of the Ruined King - Theory Crafting LoL](/images/content/hxa-blade-of-ruined-king.png)

*(image from leagueoflegends.wikia.com)*

Blade of the Ruined King is a highly cost effective item for the damage-output it provides.

Against a 1000 HP target, Blade of the Ruined King gives +80 damage. At 2000 hp, +160 damage. 3000 hp, +240 damage... at 4000 hp, +320 damage! We can substitute these numbers for AD. This means that Blade of the Ruined King, if we purchase, is probably the only Attack Damage item we need. The rest of the item slots can be dedicated to tankiness. Many people actually build this way!

Another super useful thing about Blade of the Ruined King is its passive. The passive helps Bruisers stick to their target or to just give them an extra burst. 

![HXA Frozen Mallet - Theory Crafting LoL](/images/content/hxa-frozen-mallet.png)

*(image from leagueoflegends.wikia.com)*

Frozen Mallet is a great bruiser item, though expensive, that provides a massive +700 Health, and a good +30 Attack Damage. But forget those puny stats! Heavy Mallet is bought for its passive to slow the target. This passive has helped many Bruisers in the past that had trouble sticking to targets. However, with the introduction of Blade of the Ruined King, Frozen Mallet  fell out of meta. Frozen Mallet is still a useful item, but it is just not cost-effective to buy early. 

![Wit's End HXA - Theory Crafting LoL](/images/content/hxa-wits-end.png)

*(image from leagueoflegends.wikia.com)*

Wit's End is a great item that combos well with Frozen Mallet. Frozen Mallet helps us stick to the target to keep our Wit's End passive effect active. 

Wit's End 42 bonus Magic Damage is similar to having +42 AD. Despite providing great damage, Wit's End fell out of meta as well with the introduction of Blade of the Ruined King. However, I still find Wit's End as a useful item built after Frozen Mallet. The two provide an awesome balance of defense and offense. 

## Example Item Build

To give an example of an ideal Bruiser build, let's take a look at Warwick. Warwick is a very flexible Champion that can fall under the category of Tank, Bruiser, and Assassin. I've even seen many AP Warwick as well as AD Warwick. We'll be focusing on an Auto Attack Based Bruiser Warwick build.

![HXA Warwick - Theory Crafting LoL](/images/content/hxa-warwick.png)

*(image from leagueoflegends.wikia.com)*

At level 18, Warwick has 2192 Health, 83 Armor, 52.5 Magic Resist, 118 AD, and 49% Attack Speed. 

Let's aim for these ideal stats:

**(4500 Health, 200 Armor, 200 Magic Resist, 333 AD, and 399% Attack Speed)**

However, Warwick maxes out his Attack Speed at 219%, so we need to adjust: 

**(4500 Health, 200 Armor, 200 Magic Resist, 333 AD, and 219% Attack Speed)**

## The Set-Up

First, let's consider the stats we gain for Masteries. 

![Warwick Masteries HXA - Theory Crafting LoL](/images/content/hxa-masteries.png)

This Mastery Page Set-up is for tankiness. It offers us a+3% boost  to Health; therefore, we must adjust our ideal stats:

**(4635 Health, 200 Armor, 200 Magic Resist, 333 AD, and 399% Attack Speed)**

It also provides us +5 Armor from Hardiness as well as +3 Armor and 1.5 Magic Resist per enemy Champion in range via Legendary Guardian. Let's just say we have +3 Armor for simplicity sakes totaling to +8 Armor from Masteries. Therefore, we total to 91 Armor and 54 Magic Resist.

Fury gives us +5% Attack Speed and Brute and Martial Mastery provides us a bonus 14 AD at level 18. We then total to 132 AD and 54% Attack Speed.

We can't forget our Rune Page.

For laning, I would take Magic Penetration since Warwick's spell all deal Magic Damage. Against an AD damage dealing opponent, having a lot of Armor would help us sustain greatly.

![Rune Page HXA - Theory Crafting LoL](/images/content/hxa-rune-page.png)

If we are going to the jungle, I would use a full Attack Speed rune page:

![Rune Page HXA 2 - Theory Crafting LoL](/images/content/hxa-rune-page-2.png)

This Rune Page, with +41% Attack Speed, will help us get through the Jungle the fastest while keeping us alive (we heal more the faster we attack with Warwick's passive). We now have 90% Attack Speed. Also, Warwick has a spell that augments his Attack Speed by 80% - Hunters Call.

![Hunters Call HXA - Theory Crafting LoL](/images/content/hxa-hunters-call.png)

With Hunters Call, we total to 175% Attack Speed without any items!

Warwick also has pretty much a built-in +48 AD with his passive - Eternal Thirst.

![Eternal Thirst HXA - Theory Crafting LoL](/images/content/hxa-eternal-thirst.png)

Eternal Thirst, at max level, does 16 additional damage per stack applied on each hit. This stacks 3 times totalling to a bonus 48 damage per hit. Thus, we hit 180 AD.

## Early Game

Next, let's figure out our core items. Warwick has a lot of Healing skills. 

![Warwick Skill HXA - Theory Crafting LoL](/images/content/hxa-warwick-skill.png)

If we are playing a lane Warwick, we should purchase an item that helps us take advantage of our Healing abilities. Buying a lot of Armor is one idea. Armor increases the effectiveness of Health, shield, and Healing abilities mathematically. Therefore, if we are facing against an AD damaging dealing Champion, Sunfire Cape or Frozen Heart would be a great choice. Sunfire Cape would help us hit our 1500 Health and 100 Armor quota early game:

**(1500 Health, 100 Armor, 111 AD, and 33% Attack Speed)**

**We are using the ideal stat ratios against only one type of damage. In lane, we should be using these ratios since most likely, our enemy Champion only deals mostly one type of damage.

On the other hand, Frozen Heart would help us sustain longer in lane. Also, the amount we heal is also mathematically the same as more Health. Therefore, Frozen Heart may be better since we may pull off so many heals that we may actually have mathematically more Health via heals in comparison to Sunfire Cape. 

## Mid Game

Moving into Mid Game. We now will be faced Physical and Magical Damage. Therefore, we should change our goals to a new one:

**(3000 Health, 100 Armor, 100 Magic Resist, 222 AD, and 167% Attack Speed)**

Sunfire Cape or Frozen Heart should have brought us to and above 100 Armor. What we are missing is a lot of Health, Magic Resist, AD, and Attack Speed. Let's take a look at some of our options.

Spirit Visage, which provides Health and Magic Resistant help us meet our ideal stat ratios. Also, since Spirit Visage increases the effectiveness of healing by 20%, Warwick, it is even more attractive on Warwick whom has a lot of built-in Healing.

![Spirit Visage HXA - Theory Crafting LoL](/images/content/hxa-spirit-visage.png)

A lot of built-in Healing also means we need less Health. For example, if we're confident that we can heal for 500 Health in a fight, then we need 500 less Health than the ideal values for Health. So we can adjust our goal:

**(2500 Health, 100 Armor, 100 Magic Resist, 222 AD, and 167% Attack Speed)**

We should have hit close to our Magic Resist goal and Health goal. I would throw in a Giant's Belt just to be closer to our Health goal, but it's up to you. We should also try to address our Attack Speed and AD needs (A Blade of the Ruined King or Wit's End would be great). However, if our team needs a tank, then I would just meet the defense stat ratio quotas.

## Late-Game

Now that it is late-gane, we can aim for our final goal:

**(4000 Health, 200 Armor, 200 Magic Resist, 333 AD, and 219% Attack Speed)**

A must-have by late game is Randuin's Omen. It is basically the best Armor item in the game. We see this item just about every game which hints at its awesomeness. So we can turn that Giant's Belt bought mid-game into a Randuin's Omen.

![Randuins Omen HXA - Theory Crafting LoL](/images/content/hxa-randuins-omen.png)

Since we are now looking at a full end-game build, we will take Elixer of Fortitude into account. 

![Elixir of Fortitude HXA - Theory Crafting LoL](/images/content/hxa-elixer-fortitude.png)

*(image from leagueoflegends.wikia.com)*

Elixer of Fortitude provides us 235 Health and 15 Damage.

With these 2 must-buy items and our Elixer of Fortitude, our defensive stat now totals to 3327 Health, 161 Armor, and 109 Magic Resist. Our offensive stat is still at 195 AD and 175% Attack Speed. To meet our quota, we still need about 793 Health, 39 Armor, 91 Magic Resist, 234 AD, and 44% Attack Speed.

Our next four items are very flexible. 

### Path 1: 

We can build the Frozen Mallet and Wit's End Combo. Frozen Mallet nearly completes our Health quota. Frozen Mallet and Wit's End gives us mathematically +72 AD bringing us to over 300 AD and Wit's End brings us to about 180% Attack Speed and over 150 Magic Resist. 

We then can complete our Armor requirements with Guardian Angel.

![Guardian Angel HXA - Theory Crafting LoL](/images/content/hxa-guardian-angel.png)

Guardian Angel brings us to over 200 Armor and 200 Magic Resist meeting mitigation stat quotas. 

We are now just short on AD and Attack Speed. I would sell Sunfire Cape or our boot for our next best option - Trinity Force since it provides a speed boost, and the spellblade passive and +30 AD will help us hit our AD quota. We hit just over max Attack Speed, but it is okay since the opposing team probably has Randuin's Omen and Frozen Heart.

In all, here the item build for path one:

![Item build for path 1 - Theory Crafting LoL](/images/content/hxa-item-build.png)

*(generated at leaguecraft.com)*

![Item build for path 1 stats - Theory Crafting LoL](/images/content/hxa-item-build-stats.png)

*(generated at leaguecraft.com)*

### Path 2: 

Let's focus more on sustain this time. We can buy Blade of the Ruined King. This item provides so much damage output that it fulfills our AD need. It's passive helps us stick onto targets. It provides Life Steal which will synergize well with Spirit Visage. It also brings us to around 170 Attack Speed.

We then just need Health, Armor, and Magic Resist. Let's replace Randuin's Omen with a Frozen Heart for the 20% Cooldown Reduction and massive Armor boost. The 20% Cooldown Reduction will help Warwick spam his Hungering Strike more often. Let's next buy a Warmog's Armor for all the Health we need, and a nice Health Regeneration that synergizes well with Spirit Visage. 

Let's then work on our offense stats. Purchase a Wit's End to boost our Magic Resist. We will hit around 220 Attack Speed hitting our quota. Our next option is a Mercurial's Tread or Trinity Force for our speed needs. The only stat we are missing would then be Magic Resist. We could replace Warmog's Armor with a Guardian Angel. Or we can adjust the Rune Page a bit to fit in the remaining Magic Resist as well. In all, we have:

![Item build for path 2 - Theory Crafting LoL](/images/content/hxa-item-build-2.png)

*(generated at leaguecraft.com)*

![Item build for path 1 stats - Theory Crafting LoL](/images/content/hxa-item-build-stats-2.png)

*(generated at leaguecraft.com)*

As we can see, matching our Item Build, Rune Page, and  Masteries with a Champion in accordance to optimum stat ratios takes some planning. There is definitely a lot of ways to achieve these ratios. I simply only listed 2 possible items build for Warwick, but there are so many other possibilities out there. Combining the ideal stat ratios and your creativity, I'm sure you can invent a new one. Just have fun, and experiment to see what works for you!
