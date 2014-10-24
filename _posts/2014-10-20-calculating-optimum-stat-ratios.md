---
layout: post
title:  "Calculating Optimum Stat Ratios ­ Part 1: Health x Armor"
description: "Ever wondered what your Health to Armor ratio should be? If so, then you're reading the right article!"
author: "Samuel Kuo"
author_profile: "Invented the troam'er role (troll and roam) and the triple brut. build (Youmu's Ghost Blade, Black Cleaver, and The Brutalizer)"
author_coach: "http://gamerunners.gg/coaches/3"
date: 2014-10-20
categories: lol
tags: theorycraft
thumbnail: "/images/content/hxa-cho-gath.png"
excerpt: "Ever wondered what your Health to Armor ratio should be? If so, then you're reading the right article! When it comes to optimized Health to Armor ratio, there are mainly three factors to building the perfect build: the Diminishing % Returns of stacking Health and Armor, the cost efficiency that the game develepors have set, and average Physical and Magic damage the opposing team has."
---

Ever wondered what your Health to Armor ratio should be? If so, then you're reading the right article!

When it comes to optimized Health to Armor ratio, there are mainly three factors to building the perfect build:

* The Diminishing % Returns of stacking Health and Armor

* The cost efficiency that the game develepors have set

* Average Physical and Magic damage the opposing team has

Don't worry if you don't understand what Diminishing % Returns are or if this already sounds like Calculus. It's actually really simple if we break it down. So let's take things step by step and figure out what the optimized Armor x Health ratio is for you!

## Diminishing % Returns

![LoL Theory Crafting - Armor Returns](/images/content/armorreturns1.jpg)

In this graph, we can see that as we stack more and more Armor, the Resistance that Armor gives becomes less and less significant. However, I am aware many may say that Armor and Magic Resist does not have Diminishing Return since Armor does not become weaker per unit. What I refer to as Diminishing % Return is the reduce in how much a certain amount of stat actually gives to us. For example, let's say we decide to stack Chain Vest on Cho'Gath at level 18. 

![LoL Theory Crafting - Cho'Gath armor](/images/content/hxa-cho-gath.png)

*(image from [lolwikia.com](lolwikia.com))*

At level 18, Cho'Gath has 38.2 Armor, which means Cho'Gath will live 38.2% longer against physical damage. Let's increase his Armor by 40 via a Chain Vest and see how tankier Cho'Gath becomes.

![LoL Theory Crafting - Cho Gath Armor w/ Chain Vest](/images/content/hxa-chain-vest.png)

*(image from [lolwikia.com](lolwikia.com))*

Buying a Chain Vest, Cho'Gath's Armor is increased from 38.2 to 78.2 Armor. At 78.2 Armor, Cho'Gath now can survive against physical damage by 78.2% longer. Compared to the previous 38.2%, Cho'Gath lives 1.782/1.382 = about 1.29 or about **29% longer from the 40 Armor via Chain Vest.**

Now let's say we decide to purchase a second Chain Vest. From 78.2 Armor, we jump to 118.2 Armor, which means Cho'Gath lives 118.2% longer. Compared to the previous 78.2%, Cho'Gath lives 2.182/1.782 = about 1.22 or **22% longer from the same 40 Armor via Chain Vest.**

We clearly see a reduction in effectiveness of the same 40 Armor provided by Chain Vest when we take the quotient of the new amount of Armor by the previous amount of Armor. I refer to this diminishing of effectiveness of stacking the same stats as Diminishing % Return.

Diminishing % Return can also be seen on the Health Stat. Say for example, let's look at a level 18 Cho'Gath and see what happens when we stack Giant's Belt.

![LoL Theory Crafting - Cho'Gath Giant's Belt](/images/content/hxa-giants-belt.png)

*(image from [lolwikia.com](lolwikia.com))*

Cho'Gath has, innately, 1880 Health at level 18. Buying Giant's Belt, Cho'Gath gains 380 Health totalling to 2260 Health. How much longer will we survive? Divide 2260 Health with the previous 1880 Health. 2260/1880 = 1.20. Therefore, we will survive 20% longer against ALL kinds of damage at the cost of 1000g. 

Let's see what happens if we stack one more Giant's Belt. Adding 380 Health to 2260 Health, we now have 2640 Health. Divide 2640 Health with the previous 2260 Health, and we now have 2640/2260 = 1.17. We will now survive 17% longer against all types of damage. We can see that the Health stat too suffers from Diminishing % Returns. This is why we cannot just stack Health nor Armor. So how do we decrease our loss from Diminishing % Return? The answer is symmetry.

If we had 100 units (these units can be anything, such as Health, AD, Armor, etc....), and these units can be distributed into groups that multiply, what is the distribution that gets us the biggest number? 

2 group example:

48 x 52 =  2496

49 x 51 =  2499

50 x 50 = 2500

We can see that symmetry gets us the biggest bang for our bucks. This works because Diminishing % Return is minimized optimally. For example, adding 1 more unit to 52 gets us 53, but 53/52 = about 1.02. But if we had added that 1 unit to 48, we would have less Diminishing % Return. Therefore, that 1 unit is best spent on the unit of stat least invested in until all stats are symmetrical, in which then, our unit of distribution is optimized!

So how does this relate to Health and Armor? Basically, we can think of Health and Armor as those units in two groups that multiply together. All we have to do is make Health and Armor equal. However, while Health works like a normal unit, each unit of Armor does not work in the same way; therefore, we need delve into the mathematics of Armor. Exciting stuff! 

## The Armor Formula

For those who aren't familiar with how Armor works, Armor reduces damage based on the formula:

*Armor/(Armor+100)*

So, for example, if we had 100 Armor, then we plug 100 into the formula and get 100/(100+100) = 100/200 = .5. We now have a 50% Resistance. Simple right?

And if we have a 50% Resistance, it means we take 2 times less damage, or we live twice as long. To calculate this, we use another formula:

**1/(1-Resistance%)**

So if we plug in .5, we would find 1/(1-.5) = 2, meaning that we live twice as long.

So let's mash these two formulas together!

1/(1-(Armor/(Armor+100))

Now let's calculate how much longer we live from 1 Armor to 5 Armor:

1/(1-(1/(101)) = 1.01

1/(1-(2/(102)) = 1.02

1/(1-(3/(103)) = 1.03

1/(1-(3/(103)) = 1.04

1/(1-(3/(103)) = 1.05

Do we notice a pattern? 1 Armor means we live 1% longer. 100 Armor means we live 100% longer. Basically, 1 Armor adds 1%, or +.01 longevity to our lives!

Now, all we need to know now is how much do these stats cost to make our calculations.

## The Cost of Armor and Health

To determine the cost of Armor and Health per unit, we take the cost of the cheapest Health or Armor item, and see how much gold the Armor or Health the item provides per stat. Let's first take a look at Ruby Crystal, the cheapest Health item in the game.

![LoL Theory Crafting - Armor Ruby Crystal](/images/content/hxa-ruby-crystal.png)

*(image from [lolwikia.com](lolwikia.com))*

Ruby Health provides 150 Health at the cost of 400 gold. Dividing 400 gold by 150 Health, we get 8/3, or about **2.67 gold per Health stat.**

Now, let's take a look at the cheapest Armor item in the game - Cloth Armor. 

![LoL Theory Crafting - Armor Cloth Armor](/images/content/hxa-cloth-armor.png)

*(image from [lolwikia.com](lolwikia.com))*

Cloth Armor provides 15 Armor at the cost of 300 gold. If we divide 300 gold by 15 Armor, we find that we are paying 20 gold per unit of Armor. 

I want to point out that not all items in League of Legends do not necessarily follow these standard of measurements for units; however, most items in the game do follow these basic unit of stats as a reference. Thus, while we should know that the stats of other items do not deviate too much from the basic unit of measurement in LoL, we should also know that this unit of measurement is only an approximate.

We now have everything we need to calculate optimum Health:Armor ratio!

1 unit of Armor helps us live 1% longer, or +.01. However, we know that Armor costs 20 gold per unit. Therefore, we divide the value of Armor, 1%, by 20, .01/20 = 0.0005, which is the true value per unit of Armor.

Health is simpler since 1 Health just means 1 unit of Health. All we have to do is divide it by 8/3, or about 2.67 gold to find that Health's true value is 0.375.

So now that we have the true value per unit of Health and Armor, all we have to do is distribute Health and Armor symmetrically to minimalize Diminishing % Return.

## Optimum Health and Armor Ratio Against Only Physical Damage

Ideal Sample Ratios:

*With 1 unit in both Health and Armor, we have: 0.375 Health x .0005 Armor*

*With 2 units in both Health and Armor, we have: 0.75 Health x 0.001 Armor*

*With 3 units in both Health and Armor, we have 1.125 Health x 0.0015 Armor*

*With 2000 units in both Health and Armor, we have 750 Health x 1.00 Armor*

**(750 Health and 0 Armor)**

*With 3000 Units in both Health and Armor, we have 1125 Health x 1.50 Armor*

**(1125 Health and 50 Armor)**

*With 4000 units in both Health and Armor, we have 1500 Health x 2.00 Armor*

**(1500 Health and 100 Armor)**

*With 5000 units in both Health and Armor, we have 1875 x 2.50 Armor*

**(1875 Health and 150 Armor)**

*With 6000 units in both Health and Armor, we have 2250 Health and 3.00 Armor*

**(2250 Health and 200 Armor)**

*With 7000 units in both Health and Armor, we have 2625 Health and 3.50 Armor*

**(2625 Health and 250 Armor)**

*With 8000 units in both Health and Armor, we have 3000 Health x 4.00 Armor*

**(3000 Health and 300 Armor)**

*With 9000 units in both Health and Armor, we have  3375 Health x 4.50 Armor*

**(3375 Health and 350 Armor)**

*With 10,000 units in both Health and Armor, we have 3750 Health and 5.00 Armor*

**(3750 Health and 400 Armor)**

So we see that Armor is not worth getting at 750 Health; however, at 1500 Health, we want 100 Armor. And at 3000 Health, we want 300 Armor, etc... These stat ratios are ideal if the entire enemy team had only physical damage (or if they only had Magical Damage). The ratios are also ideal if we are facing off one-on-one in a lane with only one type of damage.

In order to factor in both physical and magic damage, we need to adjust the true value of Health and Armor. Basically, we're trying to maximize the average of how long we live against both physical and magic damage.

To do this, we simply need to multiply the true value of Health by 1.5, and divide the true value of Armor by 4/3. Therefore, 

Health = (1/(8/3))*1.5 = **0.5625**

Armor = .01/20/(4/3) = **0.000375**

Using these new values, we can find our ratios against an opposing team with equal magical and physical damage.

## Optimum Health and Armor Ratio Against Split 50/50 Magical and Physical Damage

Ideal sample ratios:

*With 1 unit in both Health and Armor, we have 0.5625 Health and 0.000375 Armor*

*With 2 units in both Health and Armor, we have 1.125 Health and 0.00075 Armor*

*With 3 units in both Health and Armor, we have 1.6875 Health and 0.001125 Armor*

*With 8000/3, or about 2666.67 units in both Health and Armor, we have 1500 Health and 1.00 Armor/MR*

**(1500 Health and 0 Armor and 0 Magic Resist)**

*With 4000 units in both Health and Armor, we have  2250 Health and 1.50 Armor/MR*

**(2250 Health and 50 Armor and 50 Magic Resist)**

*With (8000/3)*2, or about 5333.33 units in both Health and Armor, we have 3000 Health and 2.00 Armor/MR*

**(3000 Health and 100 Armor and 100 Magic Resist)**

*With 2.5/.000375, or about 6666.67 units in both Health and Armor, we have 3750 Health and 2.50 Armor/MR*

**(3750 Health and 150 Armor and 150 Magic Resist)**

*With 8000 units in both Health and Armor, we have 4500 Health and 3.00 Armor/MR*

**(4500 Health and 200 Armor and 200 Magic Resist)**

*With 3.5/.000375, or about 9333.33 units in both Health and Armor, we have 5250 Health and 3.50 Armor/MR*

**(5250 Health and 250 Armor and 250 Magic Resist)**

*With (8000/3)*4, or about 10666.67 units in both Health and Armor, we have 6000 Health and 4.00 Armor/MR*

**(6000 Health and 300 Armor and 300 Magic Resist)**

Compared to the previous ideal sample ratios for against only one type of damage, the new ratios emphasizes much more Health than Armor. However, in the current meta, many Summoners tend to build too much Armor and Magic Resist and completely undervalue Health.

*Damage may not be distributed as perfectly; therefore, the ratios should be used only as a guideline to about how much Health and Armor we need. 

**When trying to follow these ratios, adjust the stats if we see spells that increase our Health and Armor amount. Take for example, Renekton's Dominus:

![LoL Theory Crafting - Dominus skill](/images/content/hxa-dominus.png)

*(image from [lolwikia.com](lolwikia.com))*

Dominus provides 800 Health at max level; therefore, since we probably will have our Ultimate up for each big team fights, we can subtract 800 Health from the idealistic ratios since Dominus will make up for it.

Obviously, there are many other factors that would affect the math: 

* Whether we are Ignited or not

* Whether the opposing team has True Damage spells or not

* Whether the opposing team builds Armor Penetration/Reduction or not

* How Frozen Heart and Randuin Omen changes % of physical to magical damage ratio

* Whether the opposing team builds Blade of the Ruined King or not

However, I wouldn't worry too much about these because the point that the ideal sample ratio have shown is that Health is simply undervalued in many cases. Therefore, when building tanky, generally just having a Randuin Omen's and/or Frozen Heart (if a teammate already has a Frozen Heart, build Randuin's Omen) is already enough Armor. Afterwards, we should be pumping our gold into Health.

## Example Item Build

To give an example of what an ideal tank build would like like (against a team of a perfect 50/50 physical and magical damage split), let's take a look at Renekton.

![LoL Theory Crafting - Renekton](/images/content/hxa-renekton.png)

*(image from [lolwikia.com](lolwikia.com))*

At level 18, Renekton has 1992 Health, 87.6 Armor, and 52.5 Magic Resist. Including the Health bonus from his Ultimate, Renekton has a total of 2792 innate Health. From our Mastery Page, we should have 3 points in Veteran's Scar and a point in Juggernaut for +36 Health and +3% Health. With these bonuses, Renekton's Health has a total of 2828, or 2912.84 counting Juggernaut's +1.03% Health bonus. Let's say we are facing a heavy AD burst champion at top lane; therefore, we set up ith an Armor Rune Page for +15 Armor, giving Renekton a total Armor of **102.6 Armor**. Because our Renekton was facing against one type of damage in lane, we used this sample ratio:

**(1500 Health and 100 Armor)**

At level 6, Renekton has about 986 Health (1186 with Dominus) and 57 Armor including the Rune Page. To reach the ideal sample ratio, we build a Sunfire Cape early game for +450 Health and +45 Armor.

![LoL Theory Crafting - Sunfire Cape](/images/content/hxa-sunfire.png)

*(image from [lolwikia.com](lolwikia.com))*

With Sunfire Cape, we hit 1636 and 102 Armor. We have approximately matched our stats with the ideal ratio sample against one type of damage. When Renekton is level 18, this Sunfire Cape will give him **3278 Health**, or 3376.34 counting Juggernaut's +1.03% Health bonus. His Armor increases from 102.6 to **147.6 Armor**.

When Renekton enters mid-game, Renekton will be soaking up both physical and magical damage mid-game; therefore, we can refer to the ideal ratio samples for both magical and physical damage. But for simplicity sakes, let's say it's already late-game, so our Renekton is level 18.

Referring to our ideal ratio samples, we find that we need Magic Resist:

**(3750 Health and 150 Armor and 150 Magic Resist)**

To meet the ideal ratio, we see that we are low on Health and Magic Resist. We currently only have only 52.5 Magic Resist. Therefore, our next best item choice would be either Banshee's Veil, Locket of the Iron Solari, or Spirit Visage. Because Renekton's Q heals, we decide that Spirit Visage is a better fit. 

![LoL Theory Crafting - Spirit Visage Theory Craft](/images/content/hxa-spirit-visage.png)

*(image from [lolwikia.com](lolwikia.com))*

With Spirit Visage, we gain 400 Health and 55 Magic Resistance. Our 52.5 Magic Resist jumps to 107.5 Magic Resist, and our Health is now 3678 Health. However, we still are missing 42.5 Magic Resist. Therefore, we should finish our boot into Mercury's Treads for 25 more Magic Resist for a total of 132.5 Magic Resistance. 

![LoL Theory Crafting - Merury's Treads](/images/content/hxa-mercurys-treads.png)

*(image from [lolwikia.com](lolwikia.com))*

We have approximately hit our ideal 3750 Health x 150 Armor ratio! Since we have approximately hit the quota ratio, we should pump more into Health to hit the next plateau ratio. We thus purchase Giant's Belt for 380 Health, bringing us to 4058 Health, or 4179.74 counting Juggernaut's +1.03% Health bonus. 

After the game progresses, we can now afford to upgrade Giant's Belt into Randuin's Omen.

![LoL Theory Crafting - Randuins Omen](/images/content/hxa-randuins-omen.png)

*(image from [lolwikia.com](lolwikia.com))*

With Randuin's Omen, the bonus 500 Health and 70 Armor brings our Health to 4558, and our Armor to 217.6. We are now approaching our next plateau ratio: 

**(4500 Health and 200 Armor and 200 Magic Resist)**

Since we only have 132.5 Magic Resist, we need 67.5 more to hit our quota. 

We have many options, such as Locket of the Iron Solari, Banshee's Veil, Maw of Malmortius, Mercurial Scimitar to help us increase our Magic Resist. Since we probably won't be hitting the next plateau of ideal ratios (it is possible, however, if we go full tank), we can probably dedicate our next 2 items to help us reach approximately 200 Magic Resist. Or we can get 1 Magic Resist item and 1 damage item, such as Ravenous Hydra (this could be bought earlier, of course) or The Black Cleaver. It's up to you on how you want to play your Renekton.

What I do find intriguing is that the build I have mathematically conjured up in this article matches many of the top Renekton builds posted on mobafire. Those builds that were created probably were not mathematically generated; but rather, builds created through many trial and error. I'm not saying that we should follow the trend item builds. While our late game build may look like many standard Renekton builds, the mathematics in this article gives us a guideline on how to perfect our Health and Armor ratio early game as well, which may involve stacking Ruby Crystal and Cloth Armor. In the next article, I will be covering the optimum stat ratios for a balanced offensive and defensive item build. Stay tuned if you enjoy playing Bruisers! [Part 2 is now available to be read here.](http://news.gamerunners.gg/lol/calculating-optimum-stat-ratios-2/)
