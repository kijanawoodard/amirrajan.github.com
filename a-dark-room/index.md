---
layout: page
title: A Dark Room for iOS
header: A Dark Room for iOS
group: navigation
---
{% include JB/setup %}

I want to make sure I've logged everything that's happened around the growth and popularity of A Dark Room. I hope that indie developers (or those that want to try to "make it" in the App Store) can benefit from these entries. Notable events are listed below along with any pertinent information about how it affected downloads, reviews, emotions, and anything else that influenced the success (or failure) of A Dark Room for iOS. **If you're looking for the offical website for ADR iOS, it's [here](http://adarkroomios.com).**

<div style="font-size: 28px; color: #C34A2C; font-weight: bold; line-height: 28px">Everything past this point contains spoilers. If you haven't played the game, and don't want the story spoiled. Stop reading now. No really, even the Table of Contents has spoilers. Don't say I didn't warn you.</div>

**Table of Contents**

- [Jun 29, 2013: Picking the Development Environment](#pickingdevenvironment)
- [Jul 7, 2013: A Week Later. First Playtest by a Non-Gamer](#firstplaytest)
- [Jul 8, 2013: Realization That I was Growing as a Developer](#growingasadeveloper)
- [Jul 11, 2013: Realization That I Enjoy Helping Others Break Down Barriers](#breakingdownbarriers)
- [Jul 12, 2013: The First Road Block in Developing A Dark Room](#firstroadblock)
- [Jul 21, 2013: I Want to Stab Cocoa UI In the Face](#stabbingcocoaui)
- [Jul 26, 2013: Making the iOS Version My Own](#myversion)
- [Jul 28, 2013: Creativity is a Drug](#creativityisadrug)
- [Jul 30, 2013: Back to Battle the Dusty Path](#battlingthedustypath)
- [Aug 1, 2013: Reflecting on the .Net Ecosystem - The Microsoft Manifesto](#microsoftmanifesto)
- [Aug 2, 2013: Had to Take Another Break](#takinganotherbreak)
- [Aug 13, 2013: Another Realization That I Was Becoming a Better Developer](#abetterdeveloper2)
- [Aug 25, 2013: Taking a Break to Scratch a NodeJS Itch](#nodejsitch)
- [Sep 18, 2013: My First "Not .Net" Presentation](#notdotnetpresentation)
- [Sep 19, 2013: .Net OSS is DOA](#dotnetossdoa)
- [Sep 25, 2013: I'm Done Debating With Expert .Net Developers and Dealing With the .Net Mono Culture](#donewithdotnet)
- [Oct 1, 2013: The Play Testing Grind... This is Not Fun](#playtestgrind)
- [Oct 19, 2013: A Dusty Path Complete. I Hate You Michael (in a good way)](#ihatemichael)
- [Oct 23, 2013: Space Sequence Complete. The Meeting With Michael.](#meetingwithmichael)
- [Oct 30, 2013: Incorporating Michael's Feedback](#incorporatingfeedback)
- [Oct 31, 2013: My Wife's Final Playtest](#mywife)
- [Nov 1, 2013: Submitted to the App Store at $1.99](#submittingtotheappstore)
- [Nov 8, 2013: One of the Worst Days of My Life](#worstdayofmylife)
- [Nov 9, 2013: The Crash Fix Shipped](#crashfixshipped)
- [Nov 10, 2013: My Obsession with Twitter and @ADarkRoomiOS Begins](#twitterobsession)
- [Nov 15, 2013: A Ray of Hope - Courtney Stanton (@q0rt)](#courtney)
- [Nov 16, 2013: A Rude Awakening](#rudeawakening)
- [Nov 18, 2013: Additional Notable Interactions](#interactions)
- [Nov 22, 2013: Pocket Gamers writes an Entry on A Dark Room](#pocketgamers)
- [Nov 23, 2013: A Dark Room Forum Entry on Touch Arcade](#toucharcade)
- [Nov 24, 2013: The First One Star Review](#onestarreview)
- [Nov 26, 2013: Game Back Story, an Apology, and a Post to Hacker News](#hackernews)
- [Nov 27, 2013: Another Notable Tweet. A Stellar Video Review.](#adrreview)
- [Dec 10, 2013: Blind Gamers Are Playing A Dark Room](#blindgamers)
- [Dec 16, 2013: Cara Ellison - Another Glimmer of Hope for A Dark Room](#cara)
- [Dec 17, 2013: Indie Mega Booth Does A Podcast on A Dark Room](#indiemegabooth)
- [Dec 18, 2013: Maddy Myers (@samusclone) - More Connections With The Gaming Community](#maddy)
- [Dec 22, 2013: Someone Stopped Playing Because of Slaves](#slaves)
- [Dec 27, 2013: A Dark Room, 2013 GOTY Lists, and Zoe Quinn](#zoe)
- [Dec 28, 2013: Elizabeth Simins (@ElizSimins) and Patreon](#elizabeth)
- [Jan 1, 2014: First Check From Apple](#firstcheck)
- [Jan 4, 2014: The Accessible Version of A Dark Room Is Released](#blindversionreleased)
- [Jan 5, 2014: Changes in Routine](#routine)
- [Jan 10, 2014: Tweets Sent to 6k People](#6kpeople)
- [Jan 15, 2014: Tweets Sent to 18k People](#18kpeople)
- [Jan 16, 2014: Pocket Tactics and Owen Faraday](#pockettactics)
- [Jan 19, 2014: Apple Vis Promo Code Give Away](#applevis)
- [Jan 26, 2014: Promo Code Give Away on Touch Arcade](#promocodestoucharcade)
- [Feb 1, 2014: Check #2 Comes in From Apple](#secondcheck)
- [Feb 2, 2014: Another Person Stopped Playing Because of Slaves](#slaves2)
- [Feb 5, 2014: Promo Code Give Away on Reddit](#reddit)
- [Feb 7, 2014: A Hail Mary to Cara Ellison](#hailcara)
- [Feb 11, 2014: A Hail Mary to Brandon Boyer](#hailbrandon)
- [Feb 12, 2014: Appcessible Podcast](#appcessible)
- [Feb 13, 2014: Price Dropped on Game to $0.99 (50% off Sale)](#pricedrop)
- [Feb 14, 2014: A Dark Room Makes it Into the Top 10 under the RPG Category](#top10)
- [Feb 15, 2014: A Dark Room is Free For Two Days](#free)
- [Feb 21, 2014: A Hail Mary to Leigh Alexander](#hailleigh)
- [Feb 24, 2014: Reaching Out to RubyMotion](#rubymotion)
- [Feb 27, 2013: Another Release of A Dark Room, The Review Me Button](#reviewbutton)
- [Mar 3, 2014: Slides Complete for My First Presentation at a Ruby User Group - 12k Lines of RubyMotion](#rubybrigade)
- [Mar 4, 2014: The Review Button in A Dark Room](#reviewbutton)
- [Mar 5, 2014: Check Number 3 From Apple](#thirdcheck)
- [Mar 6, 2014: Leigh Alexander Publishes Her Interview on Gamasutra](#leigh)
- [Mar 8, 2014: Two Days After the Gamasutra Publication](#gamasutra)
- [Mar 12, 2014: Four Days of Promotion](#promotion)
- [Mar 13, 2014: Back in the Top 10, iPad Release](#top10again)
- [Mar 15, 2014: A Dark Room is Ranked 6th Under RPGs](#top6)
- [Mar 18, 2014: The Spike is Over. iPad Version Release](#ipadrelease)
- [Mar 19, 2014: Mystery of the Week Long Spike Solved](#mysterysolved)
- [Mar 24, 2014: What Happened When A Dark Room Was Free for Two Days](#freeagain)
- [Mar 31, 2014: Attack of the Minecraft Clones, and a New Hope in the United Kingdom](#minecraft)
- [Apr 1, 2014: Day Two, at the Number One Spot, in the UK App Store](#topappday2)
- [Apr 2, 2014: Day Three, at the Number One Spot, in the UK App Store](#topappday3)
- [Apr 4, 2014: The Fall From the #1 Spot in the UK App Store. Here Are the Final Numbers](#topappday5)
- [Apr 9, 2014: #1 RPG, #5 Game, #10 App, in the US](#topofus)
- [Apr 15, 2014: #1 in the App Store](#number1us)
- [Apr 29, 2014: Waiting for the New Normal](#newnormal)
- [May 6, 2014: The Fall from the US Top Spot](#thefall)
- [May 26, 2014: A Dark Room's Second Wind](#secondwind)
- [Jun 20, 2014: Taxes, Negative Reviews, Clones, and Open Source](#grrr)
- [Aug 11, 2014: One Million Downloads in Seven Days](#million)
- [Aug 20, 2014: What if ADR Was Written Using Cordova and Was Ad Based?](#alternateuniverse)
- [Sep 27, 2014: After 1 Million Free Downloads, What Happened to Paid Sales?](#afteronemillion)
- [Dec 7, 2014: The Ensign and One Year of ADR](#oneyear)

<a id="pickingdevenvironment"> </a>

**Jun 29, 2013: Picking the Development Environment** <a href="#pickingdevenvironment"><small>permalink</small></a>

Starting off, I knew I didn't want to write an app in Objective C and XCode again. During my time off, I had already built apps using Objective C, Interface Builder, and XCode. I _wanted_ the experience in building an app using the "recommended" development environment... It was just not fun. I've spent too much time with bloated IDE's and visual designers. I didn't want to experience that again.

My first few lines of A Dark Room code were still in Objective C via XCode. After a day of coding, I got fed up with the environment. I had a copy of RubyMotion sitting on my virtual shelf. I put aside my fears of "using something that isn't supported by Apple", dusted it off, and started building the app in RubyMotion instead.

I coded for 12 hours straight on the game. I haven't had this feeling in a very long time... losing track of time like that.

<a id="firstplaytest"> </a>

**Jul 7, 2013: A Week Later. First Playtest by a Non-Gamer** <a href="#firstplaytest"><small>permalink</small></a>

I got huts working and had implemented population growth. The game was far from complete. But I took the chance and showed it to a non gamer. They were thoroughly confused. But slowly got pulled into the game and had built "a tiny village". I consistently heard "it needs pictures, it needs visuals". I actually thought about adding black and white background images to the game that would change as the player progressed... but I wanted to have a complete game before adding my own creativity to it.

<a id="growingasadeveloper"> </a>

**Jul 8, 2013: Realization That I was Growing as a Developer** <a href="#growingasadeveloper"><small>permalink</small></a>

I was working on the game while at the same time preparing for an Austin .Net User Group presentation on using the dynamic capabilities of C#. It's really interesting being proficient in multiple languages now. It's a perspective that's hard to describe. The presentation went well.

<a id="breakingdownbarriers"> </a>

**Jul 11, 2013: Realization That I Enjoy Helping Others Break Down Barriers** <a href="#breakingdownbarriers"><small>permalink</small></a>

I did another presentation on ASP.NET MVC web development using the dynamic capabilities of C#. I'd say that this Dallas .Net User Group presentation was the best presentation I've ever done. The turnout was huge (120+ people). I was presenting on ideas I cared about. I was trying to break down barriers for developers, and share techniques/workflows to development that just simply aren't practiced on the .Net stack. I hope I showed enough good things about fast feedback loops (out of proc build and deploys, fast test feedback), and low friction workflows (command line centric actions). I see the importance of these things given all the work I've now done using NodeJS, JavaScript, Rails, and (now) RubyMotion.

<a id="firstroadblock"> </a>

**Jul 12, 2013: The First Road Block in Developing A Dark Room** <a href="#firstroadblock"><small>permalink</small></a>

I hit my first road block. When I reached out to Michael about porting the game to iOS, I actually hadn't finished playing the web version. I never bought the compass to set out onto the Dusty Path. I thought I was making extremely good progress, but then I saw the complexity of the outside world. The economy management part of the game, that I had been coding on, was just the tip of the iceberg.

The Dusty Path was really hard to fit on a small screen. It took me 10 days to figure out how to approach the next part of the game. I made tiny sample apps and tried different variations of pinch and zoom techniques, scrolling techniques, "follow the player" techniques, and skeuomorphic stuff. Before this day I thought I was so close to finishing the implementation of game....

<a id="stabbingcocoaui"> </a>

**Jul 21, 2013: I Want to Stab Cocoa UI In the Face** <a href="#stabbingcocoaui"><small>permalink</small></a>

I settled on a "follow the player" implementation where the map would center when the player moved on the map. You could scroll around the map if you needed, but as soon as you moved again, it would refocus to your current location. I had to use two layers of overlapping labels to represent landmarks and terrain (Cocoa UILabels can only have one format/font). It took 5 days to get the labels lined up and scrolling correctly. Fifteen days, just gone on trying to display a map.

<a id="myversion"> </a>

**Jul 26, 2013: Making the iOS Version My Own** <a href="#myversion"><small>permalink</small></a>

At this point I needed to take a break from the Dusty Path and do some polish and playtesting. The pacing in the game was an issue. It was too slow to get started. I didn't know if it was because I had played it so many times, or if the game was actually just too slow to get going on a mobile medium.

I decided to add Friedrich Nietzsche quotes that would show up randomly when you stoked the fire (to give the player something to read through the slower points in the game). This didn't make it into the final release, but were in the game for a while. I had accumulated 200 quotes and felt that it was inline with the atmosphere of the game.

<a id="creativityisadrug"> </a>

**Jul 28, 2013: Creativity is a Drug** <a href="#creativityisadrug"><small>permalink</small></a>

I don't know what it was about these Nietzsche quotes. I think it was my first attempt at doing something different and creative... something that set A Dark Room iOS apart from the web version. I spent the day incorporating quotes, thinking to myself how awesome it would be and how eerie it would make the game. Here are some of them:

>every profound spirit needs a mask: even more, around every profound spirit a mask is continually growing.

>when you stare into the abyss the abyss stares back at you.

>a dictator divides mankind into two classes: tools and enemies.

To help again with pacing, I decided to add "flashes of events" that would show up when the player gathered wood. It added just enough of a draw to keep going though the first part. The first message read:

>hope she's okay, have to keep the fire going.

<a id="battlingthedustypath"> </a>

**Jul 30, 2013: Back to Battle the Dusty Path** <a href="#battlingthedustypath"><small>permalink</small></a>

The quotes were in place (I was so excited about showing this to Michael). I had random Room events working too. The after effects created from spending so many days with wrestling the map had worn off. I started specing out the battle sequences now.

<a id="microsoftmanifesto"> </a>

**Aug 1, 2013: Reflecting on the .Net Ecosystem - The Microsoft Manifesto** <a href="#microsoftmanifesto"><small>permalink</small></a>

I haven't booted up Windows for a long period of time at this point. Most of my time was spent building A Dark Room on OSX. I still built small applications and kept my skills sharp with NodeJS, and Rails. I still paired with developers on any stack (.Net or not), and I still went to .Net User Groups to meet up with friends.

But at this point I just had some (for lack of a better term) "resentment" with the .Net ecosystem (and the person I used to be). I've spent a good amount of time "on the other side" and have tried really, really hard to break down barriers for .Net developers. I took the day and wrote a blog entry about my past self: [The Microsoft Manifesto](http://amirrajan.net/meta/2013/08/01/the-microsoft-manifesto/).

<a id="takinganotherbreak"> </a>

**Aug 2, 2013: Had to Take Another Break** <a href="#takinganotherbreak"><small>permalink</small></a>

Development on A Dark Room started to slow down a bit (I hit a bit of a low point in motivation). Combat was working at a cursory level... mostly just animations. The battle sequence was pretty much a real time game with a timer running at 10 frames per second... I was making a real time game using Cocoa controls as opposed to sprites and a canvas... kind of felt weird about that. But it worked.

5 days on and off to work through the loot screen (the screen that came up after you won a battle). Pixel pushing labels and buttons. At this point I dread any kind of UI work in iOS.

<a id="abetterdeveloper2"> </a>

**Aug 13, 2013: Another Realization That I Was Becoming a Better Developer** <a href="#abetterdeveloper2"><small>permalink</small></a>

I was scheduled to speak at Austin Code Camp. I was going to do a presentation on an array of front end JavaScript frameworks. I spent the next few days working on the presentation and spent some time preparing a lighting talk about how you could use VIM for C# development. I also helped one of my friends (Chris Holt), prepare for his presentation on F#. Here I am, 4 months into my sabbatical. Continually gaining proficiency with C#/F#, JavaScript, Objective C, Ruby, VIM, Visual Studio, and XCode.

<a id="nodejsitch"> </a>

**Aug 25, 2013: Taking a Break to Scratch a NodeJS Itch** <a href="#nodejsitch"><small>permalink</small></a>

I've spent the last 8 days on the Dusty Path. Adding the Iron Mine, Coal Mine, Sulfur Mine, working through road creation, and working through unlocking Workshop items. I needed another break. I spent the next week working on a Twitter mashup written in NodeJS (github.com/amirrajan/sortis).

<a id="notdotnetpresentation"> </a>

**Sep 18, 2013: My First "Not .Net" Presentation** <a href="#notdotnetpresentation"><small>permalink</small></a>

I did my very first presentation on NodeJS. It was a quasi workshop that went through a number of NodeJS applications I've built. I helped developers build and deploy their first NodeJS applications to Nodejitsu and Heroku. It was lots of fun :-)

<a id="dotnetossdoa"> </a>

**Sep 19, 2013: .Net OSS is DOA** <a href="#dotnetossdoa"><small>permalink</small></a>

Development of the game continues. Play testing and tweaking the Dusty Path. I was just a grumpy person this month in general with all the annoying pixel pushing. I spent some time reflecting on all the different things I've done on my sabbatical. A Dark Room had been my primary "work" throughout this time. But I continued to spend time working with other stacks.

Another internal struggle with .Net development. I've tried to have discourse on Twitter with a number of .Net devs. I built a Twitter mashup to help me manage that discourse because I was having so many conversations at once. At this point I've learned (or at least gotten better) at objectively analyzing risk and reward. Using NodeJS and Ruby Motion, I have now have a better understanding of what OSS _really_ looks like. So I put another blog post up: [.Net OSS is DOA](http://amirrajan.net/meta/2013/09/19/perception-is-reality-dot-net-oss/). This one got some attention. I wanted to (again) help developers break down barriers and see that all the "answers" don't exist in any single stack.

I was berated by my peers. I was "just plain wrong", I was told it's "just an opinion", and that "I was sorely misguided". Another dev tweets, "Here we go again with all the .Net OSS angst". I wish I never wrote this blog entry.

<a id="donewithdotnet"> </a>

**Sep 25, 2013: I'm Done Debating With Expert .Net Developers and Dealing With the .Net Mono Culture** <a href="#donewithdotnet"><small>permalink</small></a>

Another heated debate on Twitter. This time with regards to test driven development and behavior driven development. I now understand the term "strong opinions, strongly held". At this point, I knew I was done debating with experts of the .Net stack. Many (not all) have formed and solidified their opinions about "how things should be done". So I'm done trying to be respected/acknowledged by these individuals. I've wasted my breath too many times trying to get these guru's to see that they don't have it all figured out (no one has it all figured out, and you're selling yourself short if you think you do).

<a id="playtestgrind"> </a>

**Oct 1, 2013: The Play Testing Grind... This is Not Fun** <a href="#playtestgrind"><small>permalink</small></a>

All of September went to the Dusty Path (and being a grumpy developer). I made sure all the different city and town events showed up. I made sure the workshop items and workers unlocked correctly. I made sure map state rolled back if the player dies.

I chatted with Michael about this. How the hell he managed to test all this... He did what I did, just grinded through it. I spent 2 days creating an automated test suite. It tested all the different random paths the events could take. Glad I did that. Even with all the manual testing, I still had a number of bugs.

<a id="ihatemichael"> </a>

**Oct 19, 2013: A Dusty Path Complete. I Hate You Michael (in a good way)** <a href="#ihatemichael"><small>permalink</small></a>

The Dusty Path is finally to a point where all the events work and the spaceship can be unlocked. I have saving working too. A number of my friends and family have playtested the game to this point (and have frankly gotten sick of it).

During this time period I removed the Nietzsche quotes. It just led to confusion and the pacing was good enough with the "gather wood storyline events". Reading all those quotes helped shape the storyline I put in place. Particularly this quote:

>a dictator divides mankind into two classes: tools and enemies.

There was a specific lull in the gameplay. The time between buying the compass and then building the Smokehouse, Tannery, and Workshop was still a bit of a wait. This is where I decided to shift the story to take a turn for the worse. Through the creation of these three buildings, the player would slowly see that the villagers were being overworked. And finally, the villagers became slaves:

>the villagers...i can see the fatigue in their eyes...

>back breaking labor...the villagers are mine to command...

>leather for finer things, must push the villagers...

>i'll make the villagers work...day and night...they are my slaves...

After the game released, I had a number of people literally reset the game at this point... or simply stop gathering wood because they didn't want their villagers to turn into slaves. I didn't expect this kind of visceral reaction to the events. We murder in video game all the time. We vandalize. We steal cars. We stomp on the heads of turtles and mushrooms that never did anything to us. Why did the slave event cause people to stop playing?

I hate you Michael (in a good way). You didn't build a single game. You built 3 games and stitched them together in a brilliant way. The ship scene was the next thing to tackle. There was an end in sight. The largest part of the game (The Dusty Path) was done.

<a id="meetingwithmichael"> </a>

**Oct 23, 2013: Space Sequence Complete. The Meeting With Michael.** <a href="#meetingwithmichael"><small>permalink</small></a>

I couldn't believe it. I had a fully functioning game from beginning to end. I knew I had a number of things to polish. But the game was "code complete". Around this time I emailed Michael to set up a video conference (he lives in Canada.. I live in Dallas, Tx). I can't believe that all the communication up until this point was done through email and chat.

Michael hadn't seen the storyline additions I made. I was worried he'd say "no" to the changes. It wasn't a lot of work to rip it out, but it was definitely something I felt contributed greatly to the experience of A Dark Room. It made the player feel anxious, uneasy, even worried to continue the game at times.

This is a testament to how awesome and brilliant Michael is. He appreciated the changes I made to the storyline, and loved the enhancements I made to the mobile version of the game. It was as simple as that. He just said, "That's awesome! I like it!" Suffice to say that a huge weight was lifted off of my shoulders. We got to talking in fact about the intricacies of the game. I mentioned that most of the game could have been played without any villagers if iron, coal and sulphur could be mined by the player. Michael said "Hey, why don't you add that? Add a solo mode with an alternate ending?"

<a id="incorporatingfeedback"> </a>

**Oct 30, 2013: Incorporating Michael's Feedback** <a href="#incorporatingfeedback"><small>permalink</small></a>

The primary feedback that I got was removal of pronouns. I didn't realize it, but no part of the web version referred to the player as "you" or "I" or "us". I also incorporated the solo mode and alternate ending into the game. Playtesting. Playtesting. More playtesting. More tweaking. More playtesting.

<a id="mywife"> </a>

**Oct 31, 2013: My Wife's Final Playtest** <a href="#mywife"><small>permalink</small></a>

The game is in its final form. My wife sits down and plays the game for the 50th time. A number of my friends playtested the game. But I really didn't want to ask too much of them. Most of them only playtested the game once, at different points in the development process. I was able to get feedback from them, and they were a tremendous help (thank you Jason Smith, Eric Sowell, Kevin Wade, Matt Florence, Tim Rayburn, Zahan Tariq, Christopher Krailo, Aaron Lasseigne, and Chris Holt).

But my wife stands well above all the others that playtested. She could have said she was tired of playing this game at any point, but she didn't. She was the only person that, without hesitation, would play through the game any time I asked. I handed the final game to her at 10 pm that night. And she played the game non stop, all the way to the end. It was 2 am when she completed the play through. Thank you my dear.

<a id="submittingtotheappstore"> </a>

**Nov 1, 2013: Submitted to the App Store at $1.99** <a href="#submittingtotheappstore"><small>permalink</small></a>

I submitted the game to the App Store. The description of the game was set to "a text based journey... awake. head throbbing. vision blurry." I still spent a day making minor tweaks to balancing. I playtested the game another 4 times before releasing. My game times were pretty damn fast at this point because I knew exactly what to do. I could beat the game in 90 to 100 minutes without even thinking too hard. Now I just have to wait. This was a good week. I shipped A Dark Room for iOS. And I was now preparing for a NodeJS competition: Node Knockout 2013!

<a id="worstdayofmylife"> </a>

**Nov 8, 2013: One of the Worst Days of My Life** <a href="#worstdayofmylife"><small>permalink</small></a>

It took a full 7 days. But A Dark Room was finally in the App Store. I downloaded the release version of the game on my iPhone 5 and was able to play it. It was an unreal feeling given how much work was put in. I know Michael tweeted about the release. I was hoping that many people would tweet about the iOS version. It was 6 months since the Hacker News post of A Dark Room. Everyone who upvoted the game probably have forgotten about it by now. But maybe it would go viral like the web version did.

The first reply to Michael's tweet came in. I was sick to my stomach: "The game just crashes, I have an iPhone 5s". I screamed at the top of my lungs, broke down, literally fell to my knees and cried. No one wants to see that on their release day. No one should ever have that happen to them. I tried my wife's iPhone 5s and it was crashing there too. I texted my friend Eric Sowell and the game was also crashing for him. At that moment I wished I never spent all that time building it.

I pulled myself together and put a debug build of A Dark Room on my wife's iPhone. It crashed immediately with a runtime exception (the error itself is a blur now, but I remember it having to do with compilation flags). My assumption at this point was it had something to do with 64 bit architecture of the new iOS devices.

I drove (sped) to the Apple Store in the Parks at Willow Bend Mall, and bought an iPad Air to test out my theory. I sat at the food court, took the iPad out. I loaded up the developer certs and deployed a debug build of the app. It crashed there too. I ended up explicitly setting the compilation flag to armv7 for all libraries I was referencing. This fixed the debug build.

I repackaged the app and via iTunes Connect, requested an emergency release of the app. Apple got back to me and approved the emergency release. I pushed up version 1.1 of the app. Then I just had to wait... nothing really I could do. I was taking part in a NodeJS competition at the time. So that helped keep my mind off of it.

<a id="crashfixshipped"> </a>

**Nov 9, 2013: The Crash Fix Shipped** <a href="#crashfixshipped"><small>permalink</small></a>

Over the weekend (during the NodeJS competition), I received an email saying that version 1.1 of A Dark Room was ready for sale. That moment, I asked Eric (he was also in the competition) to download the updated version of the app. He started it up, and it worked.

I still have no idea why setting the compilation flag to armv7 worked. But I'm not about to change that now. To this day, it's still extremely stressful deploying to the App Store. I have no idea if the instant crash will come back. I can't recreate it using the simulators either.

Our Node Knockout 2013 team: Team Us - As in "us" not "them", ended up placing 15th overall and placed 6th in the fun/utility category. We built a game called [NodeKick](http://github.com/amirrajan/nodekick). It was an awesome experience.

<a id="twitterobsession"> </a>

**Nov 10, 2013: My Obsession with Twitter and @ADarkRoomiOS Begins** <a href="#twitterobsession"><small>permalink</small></a>

I created the @ADarkRoomiOS Twitter handle and started tweeting in the persona of the game. The plan was to interact with anyone and everyone who ever tweeted about the web version of the game. Having a daily tweet from the game, showed that I wasn't just a random spam bot... that there was a real person behind these tweets. I did a Twitter search for "adarkroom" and began combing through all the tweets... replying to anyone who mentioned the game. Letting them know that there was an iOS version.

<a id="courtney"> </a>

**Nov 15, 2013: A Ray of Hope - [Courtney Stanton (@q0rt)](http://superopinionated.com/)** <a href="#courtney"><small>permalink</small></a>

I've spent 5 days putting up daily tweets about A Dark Room. Reached out to a few people on Twitter in the persona of the game. It was fun. I got a couple of laughs and some people actually interacted with me too. I liked building a relationship with the fans :-). Every single morning I'd wake up and check the downloads of A Dark Room for iOS. They were abysmal. Only 5 to 10 downloads a day. It's such a let down. Such a beautiful game... and no one was downloading it.

Then the ray of hope. Courtney Stanton (@q0rt) tweeted about the release of the game. This was a big deal given that it was the first tweet about the game from someone outside of Michael's and my development circles. Courtney also had large following on Twitter.

This tweet also represented a window into the indie game world. I started following this community more closely. Reports for downloads of the game take a full day to get published in iTunes Connect. Seeing this kind of tweet and not knowing the impact right away is nerve wracking.

<a id="rudeawakening"> </a>

**Nov 16, 2013: A Rude Awakening** <a href="#rudeawakening"><small>permalink</small></a>

I woke up the next morning, awake, head throbbing, vision blurry. In a sleepy stupor, I logged into iTunes Connect and saw the number of downloads caused by Courtney's tweet. It spiked to 30. Thirty downloads... a tweet sent to over 3,000 people... and it lead to only 30 downloads.

<a id="interactions"> </a>

**Nov 18, 2013: Additional Notable Interactions** <a href="#interactions"><small>permalink</small></a>

Using the @ADarkRoomiOS Twitter account, I interacted with Leigh Alexander (@leighalexander), an editor at Gamasutra and Kotaku, about a tweet she posted with regards to A Dark Room. Letting a number of people in the conversation know about the existence of the iOS version. There was no noticeable difference in downloads the next day. A meager 5 downloads on the 19th. I'm glad I was able to have a meaningful interaction with Leigh however.

<a id="pocketgamers"> </a>

**Nov 22, 2013: Pocket Gamers writes an Entry on A Dark Room** <a href="#pocketgamers"><small>permalink</small></a>

I added "search on Google for any mention of A Dark Room" to my routine. I came accross this: [Take a risk on iOS adventure game A Dark Room and you might have a new addiction](http://www.pocketgamer.co.uk/r/iPad/A+Dark+Room/news.asp?c=55477). This review written by Chris Preistman (@CPriestman), is the first review of A Dark Room iOS that I had come across. How freaking cool is that? Unsolicited reviews are starting to come up. A spike to 30 downloads happened that day.

<a id="toucharcade"> </a>

**Nov 23, 2013: A Dark Room Forum Entry on Touch Arcade** <a href="#toucharcade"><small>permalink</small></a>

I received an email from a random person this day. The game was listed in the Touch Arcade forums, and one of the members emailed me to get some details about the game (what the game was about, how long the game was, etc). I answered his questions immediately and was happy to hear that he loved the game and wrote about his experience on the Touch Arcade forums. Every week afterwards, I have emailed a promo code to Touch Arcade for an official review. I have yet to hear back from them.

<a id="onestarreview"> </a>

**Nov 24, 2013: The First One Star Review** <a href="#onestarreview"><small>permalink</small></a>

The game up to this point has had 245 downloads over an 18 day period (that's 13 downloads a day). I had a few 5 star reviews from friends in the development community. But I received my first 1 star review:

>What was a simple and elegant game should not have been messed with. I regret spending $2 on such a mess. Not only is the UI counter-intuitive and clumsy, but the mobile designer took far too much creative license in altering the original statistics and proportions put in place by Michael Townsend, original designer. Additionally, there is a bug that results in permanent thieves with no way to deter them, making the game essentially unplayable.

What do I do? I played through the game hundreds of times. Meticulously place every button, every interaction. There was no bug in the thieves, I checked 10 times to make sure (just impatience on the part of the player, and unlucky random number generation). One bad review offsets 100 good ones. To this day I feel the pains of this review. I see it as incredibly brutal. Empathy was something I've learned through my time as an independent developer. I understood how frustrating it is to pay for an app and get delivered "shit". So I apologized on this support page. I have no idea if blewis1234 will ever read anything on this page. But I hope at some point, he'll re-rate the game.

<a id="hackernews"> </a>

**Nov 26, 2013: Game Back Story, an Apology, and a Post to Hacker News** <a href="#hackernews"><small>permalink</small></a>

I updated the support page for A Dark Room to include some back story. The name of the section is "A letter to the fans of A Dark Room" (near the top). I posted this entry on Hacker News and reddit.com/r/incremental_games to see if it would generate some interest. Again, I ended up hoping against all hope that enough people on Hacker News would remember the "Minimal Text Adventure" and show some love. It didn't happen. The response I got on Reddit was a bit better. I got quite a few kind words, which helped heal the wounds of my first one star review. The next morning, because of the post to Reddit, the game downloads spiked to 27 downloads.

<a id="adrreview"> </a>

**Nov 27, 2013: Another Notable Tweet. A Stellar Video Review.** <a href="#adrreview"><small>permalink</small></a>

Cassandra Khaw (@casskhaw), an editor at USGamer, tweets about A Dark Room on iOS. Again because of an interaction from @ADarkRoomiOS. I'm getting more involved in the indie gamer community. Courtney, Leigh, and Cassandra are all people that @ADarkRoomiOS (and by extension I) follow. That day the downloads spiked to 45. The largest single day download for A Dark Room iOS. The download trend didn't last. Every time I think the download trend will hold, it doesn't.

I also came across a video review Chris Charlton (@reasonjp) did on the [iOS version of the game](http://kaijupop.com/2013/11/iospc-quick-vid-dark-room/). It was an incredible review, and it truly made my day. These small wins help me get through each disappointment in the number of downloads.

<a id="blindgamers"> </a>

**Dec 10, 2013: Blind Gamers Are Playing A Dark Room** <a href="#blindgamers"><small>permalink</small></a>

Blind gamers reached out to @ADarkRoomiOS: Orinks (a member of AppleVis.com) and Aaron (a member of AudioGames.net). I was in complete utter shock that blind people were trying to play A Dark Room. I sent out a promise to them that I'd make the game fully accessible. I fired up RubyMotion and started researching what it would take to make A Dark Room fully playable via VoiceOver.

<a id="cara"> </a>

**Dec 16, 2013: [Cara Ellison (@Carachan1)](http://caraellison.co.uk/) - Another Glimmer of Hope for A Dark Room** <a href="#cara"><small>permalink</small></a>

Cara Ellison, a writer for a number of online gaming website, mentioned that she was considering A Dark Room for her 2013 Game of the Year list. I reached out to her hoping she would have some kind words to write about the iOS version. She said she'd give the game a shot! I emailed her a promo code that day. Can't say this enough, these moments are hard to put in words. It's a chance for all the hard work Michael and I have put into the game to possibly pay off. For A Dark Room to finally make it into the lime lite.

<a id="indiemegabooth"> </a>

**Dec 17, 2013: Indie Mega Booth Does A Podcast on A Dark Room** <a href="#indiemegabooth"><small>permalink</small></a>

Another "search on Google everyday" result: Indie Mega Booth did a full length podcast on A Dark Room. It's hard to believe 4 people can talk so long about such a small game (it was awesome too). Just wonderful to hear different interpretations of the story. They mentioned that the iOS version of the game exists too. Yet again, hoping against all odds that the mention of the game would spur more downloads. I took the time to thank Indie Mega Booth for doing the podcast and personally thanked Maddy Myers (@samusclone) on Twitter.... such an awesome Twitter handle by the way.

<a id="maddy"> </a>

**Dec 18, 2013: [Maddy Myers (@samusclone)](http://metroidpolitan.com/) - More Connections With The Gaming Community** <a href="#maddy"><small>permalink</small></a>

Maddy Myers was part of the discussion on the Indie Mega Booth podcast. She's an editor for Paste Magazine. Another important voice in the gaming community. Every person I've interacted with thus far is trying to be heard. Everyone in the gaming community (whether they are an independent game developer or writer) is struggling in some form. And all I can say is that I'll do what I can to make sure those people who have supported A Dark Room, have my support in turn.

<a id="slaves"> </a>

**Dec 22, 2013: Someone Stopped Playing Because of Slaves** <a href="#slaves"><small>permalink</small></a>

The first public comment about the slaves in the mobile version was posted on Michael's blog. My biggest fear is the vengeful 1 star review. I already had one... I didn't want another:

>I am hoping someone can help. I started to play through and had carted wood to the point the population becomes slaves. I then had thieves and it was taking so long to stop them that I thought you were supposed to stop carting wood before your population became slaves. So I reset. I left the cart alone even though it had a “!” Next to it. I now have the entire map uncovered, I have been to every location and have used the jewel. I have the space ship but I have no option to upgrade it even though I have 40 alien alloy. Is this a bug because I ignored the cart for so long or am I missing something. Very frustrating as I will NOT be replying to get to this point.

Michael was able to get the email address for the person who left the comment. And I emailed him immediately to tell him how to beat the game. I also gave him a hint on how to unlock the alternate ending where his villagers wouldn't become slaves. He was happy to receive the email and I felt like I dodged a bullet.

<a id="zoe"> </a>

**Dec 27, 2013: A Dark Room, 2013 GOTY Lists, and Zoe Quinn** <a href="#zoe"><small>permalink</small></a>

I was holding my breath for this day. A number of online gaming websites posted their 2013 Games of the Year. A Dark Room (the web and mobile version) made three lists: Maddy Myers', Zoe Quinn's and Cara Ellison's.

Additionally A Dark Room was the inspiration for a work of art by Elizabeth Simins (@ElizSimins). She was listed as one of the top 10 works The Bygon Bureau.

This all happened in one day. I felt like I had won the lottery. Surely, this is A Dark Room's moment. These three GOTY entries probably reached 10's of thousands of gamers.

This was also the first time I heard about [Depression Quest by Zoe Quinn](http://www.depressionquest.com/). I know she was feeling the same thing I was. We were two indie game developers, trying to create things that have meaning for us. And we both made 2013 Game of the Year lists.

I played Depression Quest all the way through. It was an _experience_... that's the best way to describe it. I'm glad there are games coming out that connect emotionally with the player... that are more than guns and eye candy. I reached out to Zoe and let her know that the blind community are always in need for video games, and to spend some time in making her game accessible.

I waited till the next day. I woke up in the morning and checked the downloads... there were 54. It's the highest thus far... but that was all the downloads that were generated... soul crushing I tell you.

<a id="elizabeth"> </a>

**Dec 28, 2013: [Elizabeth Simins (@ElizSimins)](http://cargocollective.com/eliz) and Patreon** <a href="#elizabeth"><small>permalink</small></a>

After seeing her art work on Bygon Bureau, I reached out to Elizabeth and asked if I could put her piece on A Dark Room's support page. She said yes :-) Another bit of good news to keep my spirits up. Thank you Elizabeth, I'm forever grateful that you allowed me to showcase your work here (it's at the top of this page). Her work also led me to discover [Patreon](http://www.patreon.com/elizsimins). I'm amazed at how technology has given a means for artists to showcase their works (and potentially make a living off of them). Removing the middle man and making it easy for artists to promote their own works is a big deal.

<a id="firstcheck"> </a>

**Jan 1, 2014: First Check From Apple** <a href="#firstcheck"><small>permalink</small></a>

First check comes in. The grand totals for the month of November:

- Revenue: $478.27
- Downloads: 403
- Reviews: 5 five-star reviews, 1 one-star review
- RPG Rank: 567th at its low point, 27th at its height
- Overall Rank: 1479th for two days (metrics below the 1500th placement aren't kept in AppAnnie)

<a id="blindversionreleased"> </a>

**Jan 4, 2014: The Accessible Version of A Dark Room Is Released** <a href="#blindversionreleased"><small>permalink</small></a>

I worked through the holidays to get the accessible version of A Dark Room completed. It spent about 5 days in the approval process and then finally released on the 4th. I let Orinks and Aaron know about the updates and they subsequently let their respective communities know. The downloads spiked to about 40 downloads for the next two days. I really didn't care about the downloads this time around. I wanted to do the right thing. I also ended up writing about what it took to make A Dark Room accessible: [Raising Awareness, the Blind use iOS Devices](http://amirrajan.net/software-development/2013/12/29/if-you-are-reading-this-you-are-not-blind/).

Given the accessibility updates and the recent media coverage for A Dark Room, I changed the App Store description too:

>Awake. Head throbbing. Vision blurry.

>An unforgettable journey that starts small and slowly becomes much, much, more. Uncover the secrets of A Dark Room. Come light the fire.

>100% accessible and playable via VoiceOver.

>Awards and Recognition:

>Paste Magazine, Maddy Myers: Top 20 Indie Games of 2013

>Giant Bomb, Zoe Quinn: Top 10 Games of 2013

>Giant Bomb, Cara Eillison: Top 10 Games of 2013 (honorable mention)

I also nerfed thieves a little bit... you're welcome blewis1234 ;-)

<a id="routine"> </a>

**Jan 5, 2014: Changes in Routine** <a href="#routine"><small>permalink</small></a>

The iOS version of the game is solid. I still get a little antsy releasing updates and brace for insta-crashes on my iPad Air. It hasn't happened again though. With a little bit of breathing room, I started working through Land of Lisp and started studying Clojure. I also started doing screencasts on NodeJS development (my Coding Out Loud screencasts). @ADarkRoomiOS's Twitter remained active. I kept interacting with fans. It was a great way to relax and joke around with the community.

I also started work on a "spiritual" sequel to A Dark Room. Lots of HTML5 canvas work and AngularJS. Nodekick (the NodeJS game that Team Us built for Node Knockout 2013) also got cleaned up.

I finally started to get used to the number of downloads for the game. I accepted them for what they were. But I still meticulously observed impact to the number and correlated them to what I did online.

<a id="6kpeople"> </a>

**Jan 10, 2014: Tweets Sent to 6k People** <a href="#6kpeople"><small>permalink</small></a>

A notable individual in the iOS community @ScottStevenson mentioned A Dark Room. I replied with a few humorous tweets:

>"Just so you know. I consume a part of your soul every time you stoke the fire. #nomnomnom"

>"Just cause you followed me doesn't mean I'll give you anything back."

I got some retweets because of these interactions :-). Downloads spiked to 40 for a couple of days. Thank you for the support Scott.

<a id="18kpeople"> </a>

**Jan 15, 2014: Tweets Sent to 18k People** <a href="#18kpeople"><small>permalink</small></a>

A notable individual in the game community @RobertAshley interacted with @ADarkRoomiOS too. I sent Robert to this page and told him about how both Michael and I were the sole developers of the game. Robert was kind enough to craft a tweet telling his followers about the web and mobile version of the game. Downloads spiked again to 40 downloads for a couple of days.

<a id="pockettactics"> </a>

**Jan 16, 2014: Pocket Tactics and Owen Faraday** <a href="#pockettactics"><small>permalink</small></a>

Another wonderful interaction for @ADarkRoomiOS. This time, a random follower mentioned @ADarkRoomiOS and @PocketTactics in the same tweet... letting the iOS publication know about the game. I took this opportunity to email Owen Faraday (editor of Pocket Tactics).

I asked if Pocket Tactics would like to do a review on A Dark Room. Owen replied and I sent over a promo code (yay!).

On Feb 4th, Owen emailed with the word: "Amazing". I hope to see a review show up soon on Pocket Tactics. I try to be diligent in following up with Owen... without being annoying. It's hard to find a good balance between the two. A review hasn't gone up yet... but after another release of the game I'll be sure to follow up with Owen. I hope he doesn't take offense to my persistence.

<a id="applevis"> </a>

**Jan 19, 2014: Apple Vis Promo Code Give Away** <a href="#applevis"><small>permalink</small></a>

The blog post I wrote about accessibility received some buzz in the blind community. The AppleVis editorial team reached out to me. They wanted to run a promo code giveaway. I sent them 10 promo codes and they did something really unique. Instead of just giving them away, they asked individuals to go read the blog post I did on making the game accessible to the blind, and about the making of the game. They had to mention something from the write ups to get a promo code. It was a great idea, and I saw a lot of nice things said about the game.

Downloads spiked to 50 during the contest period. I'm burning through my promo codes, but they are generating results.

<a id="promocodestoucharcade"> </a>

**Jan 26, 2014: Promo Code Give Away on Touch Arcade** <a href="#promocodestoucharcade"><small>permalink</small></a>

I took Apple Vis' idea and gave away 20 promo codes across two separate contests at Touch Arcade. The interactions I had with the fans (old and new) was great. A lot kind words and genuine support.

The downloads for the last four days of January stayed at a steady 40.

<a id="secondcheck"> </a>

**Feb 1, 2014: Check #2 Comes in From Apple** <a href="#secondcheck"><small>permalink</small></a>

The second check comes in. The grand totals for the month of December:

- Revenue: $943.00
- Downloads: 698
- Reviews: 3 five-star reviews
- RPG Rank: 201st at its low point, 33rd at its height
- Overall Rank: 1428th at its low point, 486th at its height (fell below the 1500 cut off for only 3 days)

<a id="slaves2"> </a>

**Feb 2, 2014: Another Person Stopped Playing Because of Slaves** <a href="#slaves2"><small>permalink</small></a>

So a bit of background about the iOS version and its ending game sequence. The starship represents the end of the game. It is only unlocked once you've progressed far enough in the storyline. If a player avoids storyline progression, they are effectively stuck, and can't complete the game. The villagers turning into slaves leaves another person in this stuck state.

Here is a part of the email that was sent to me:

>Also I would like to mention that I liked this game until I found out I was getting screwed over.  I am playing it on an iPhone 4.  Just hoping you guys can fix this before a flood of unhappy folks come by and take your stars down a notch. And no I haven't rated your game because I am not the vengeful type.  Video games are hard to make and it seems you put a lot of effort into this. I am sending you screenshots of my game.

The player was kind enough to include screenshots of his current game. I didn't need to look (but I did anyways). He stopped progressing the storyline... Here is what I wrote back:

>Every time you gather wood the storyline progresses toward the end. There is an alternate ending too. Some people are sad with how the storyline progresses. The alternative approach to playing the game (though much harder) leads to a happier ending. Let me know if you have any other questions. And I love hearing from fans. So don't hesitate to reach out. And thanks for the detailed screenshots :-)

He replied with:

>Mmm.  I see now.  Lol I was trying not to further my slave owner persona.  You know if you made a instruction manual and just mentioned a few things, I'm sure this app will be an even better hit. (Example I thought the carbine shot bullets not battery's, because there is a actual rifle named the carbine.  I think its ww2 era). I think anyone who played the older call of duties would make this mistake: Thanks for your help.  Say, if I could rack your brain, do I not need to build huts to get the new ending, or could I build huts but just not gather wood?

And a happy ending:

>Hey thanks!  I sure will.  I left a positive review in the App Store.  I found this game on reddit.  I highly recommend creating a user account and posting something like "great iOS game, free downloads for the first 5 commenters". In the description write please leave review and comment for download.  Those people usually will help generate your sales.  I found a post about this game in r/gaming.  Good luck and thank you for answering my emails.  I really thought the game was busted.  Lol

I ended up putting a more assertive message about gathering wood to progress the storyline within the game. In version 1.4, when you stoke the fire (and there is a storyline element that needs to be dealt with). You get a small message "need to gather wood, the forest beckons". This will hopefully help guide future gamers.

<a id="reddit"> </a>

**Feb 5, 2014: Promo Code Give Away on Reddit** <a href="#reddit"><small>permalink</small></a>

I'm burning through my promo codes at this point. The Apple Vis approach to giving away promo codes leads to a much deeper connection with the fans of the game. It's meaningful and I enjoy having all the good conversations. I ran a couple of promo code giveaways on Reddit.

Downloads spiked to 40 those days.

<a id="hailcara"> </a>

**Feb 7, 2014: A Hail Mary to Cara Ellison** <a href="#hailcara"><small>permalink</small></a>

I was down to my last 15 codes. I reached out to Cara Ellison on Twitter about getting A Dark Room in front of people that may write about it. Being the awesome person she is, she replied. I sent over 6 promo codes. The frustrating thing about promo codes is that I don't know if they've been redeemed. I know Cara is extremely busy, and she probably gets many, many emails from people trying to pitch her games. I'm just glad that I have someone that can advocate for me. She continues to be a ray of hope for A Dark Room. Unsolicited mentions of the game and always responds to my emails. Thank you... thank you Cara.

<a id="hailbrandon"> </a>

**Feb 11, 2014: A Hail Mary to Brandon Boyer** <a href="#hailbrandon"><small>permalink</small></a>

I'm getting more cautions at this point (I'm down to 9 codes). I'm scouring Twitter for connections... people to reach out to... people that may respond. @Kotaku follows only 41 people and is followed by over three hundred thousand. It looks like the people Kotaku is following is fairly exclusive.

There were two people on this list that I had hopes would respond: Leigh Alexander (@leighalexander) and Brandon Boyer (@brandonnn). Both had a large number of followers and (based on their profiles) are receptive to indie developers. Brandon Boyer and Cara Ellison follow each other. Leigh Alexander (someone I've interacted with before) and Maddy Myers follow each other.... is this borderline stalking? ... XD

I end up emailing Brandon Boyer. I tried not to send him a wall of text (it happened anyways). But Brandon replied after a few days (yay!). I sent over a promo code. Now I just have to wait T_T.

<a id="appcessible"> </a>

**Feb 12, 2014: Appcessible Podcast** <a href="#appcessible"><small>permalink</small></a>

Around this same time Jonathan Mosen reached out to me. He is another individual from the blind community and came across the blog entry I did on adding accessibility enhancements to A Dark Room. He wanted to have me on a new podcast he was launching for the blind community. I said yes (of course), [here is a link to the podcast](http://www.appcessible.net/talking-apps-podcast-episode-2-amir-rajan/).

<a id="pricedrop"> </a>

**Feb 13, 2014: Price Dropped on Game to $0.99 (50% off Sale)** <a href="#pricedrop"><small>permalink</small></a>

A Dark Room is now hovering near the top 10 under the RPG Category. I didn't want the ranking to drop. I'm down to 6 promo codes, I have a pending release, but haven't pushed it yet. So I dropped the price of A Dark Room by 50% ($0.99).

I tweeted about it. A bunch of people tweeted about it. Pocket Tactics wrote up a short piece on the game being half off. There was an unsolicited Reddit post on the price drop. There was an unsolicited post on Touch Arcade. I woke up the next day I look at the downloads. They spiked to 351 in one day.

<a id="top10"> </a>

**Feb 14, 2014: A Dark Room Makes it Into the Top 10 under the RPG Category** <a href="#top10"><small>permalink</small></a>

A Dark Room in now number 8 in the App Store under the RPG category. Downloads have dropped to 100 after the initial spike from the previous day. I didn't want it to lose steam. I DIDN'T want it to lose steam. I wondered if I could set A Dark Room to free for two days. Would it reset my app rank? The app dropped to number 11 the next day. It was dropping again.... that evening I made the app free... for two days.

<a id="free"> </a>

**Feb 15, 2014: A Dark Room Is Free For Two Days** <a href="#free"><small>permalink</small></a>

A number of unsolicited posts went up again about the app being free... over the weekend, A Dark Room got ~8,900 downloads and ~10 new five-star reviews. But it lost it's rank entirely in the App Store. The app went back to its $0.99 price. It took a couple of days, but made it's way back to the ranking list. A Dark Room now hovers around 30 in the RPG Rankings. To this day I still wonder if it was a mistake to make the app free for two days.

<a id="hailleigh"> </a>

**Feb 21, 2014: A Hail Mary to Leigh Alexander** <a href="#hailleigh"><small>permalink</small></a>

I reached out to Leigh via email... and let her know via Twitter that I sent her an email :-D. After a few days, she replied back with some interview questions for me and Michael! Hopefully a publication by Leigh will bring some visibility to A Dark Room.

<a id="rubymotion"> </a>

**Feb 24, 2014: Reaching Out to RubyMotion** <a href="#rubymotion"><small>permalink</small></a>

I Talked to Karthik Hariharan about the viability of releasing A Dark Room's source (with an e-book). Trying to think of additional ways to generate income off of this IP. The game isn't making large amounts of money in the App Store. Every time the game gets a "huge" spike in downloads, it tapers off quickly. I keep thinking to myself "this trend will hold, this trend will hold." But it hasn't done so yet. Karthik also recommended that I reach out to the RubyMotion team and that Laruent Sansoetti is a nice guy and may be able to offer some advice.

I sent an email to the RubyMotion team telling them about the success the game had so far. It was incredible getting a response back so quickly from Laurent and then a tweet that reached a number of developers.

<a id="reviewbutton"> </a>

**Feb 27, 2013: Another Release of A Dark Room, The Review Me Button** <a href="#reviewbutton"><small>permalink</small></a>

There is always a side effect to releasing a new version of the app to the App Store. The first side effect: you lose all the reviews for the current version of the App (only ratings for the current version of the app show up in preview screens, the user can go and see the reviews of the previous versions, but it's not immediately obvious). The second side effect: you get more promo codes.

A Dark Room's current version has 56 five-star reviews, 1 one-star review, and 1 four-star review. The app ranking was already shot to hell (relative to where it was before), because of the two day price change to free. So I figured this would be a good time to do an update. I added the "you better go gather wood" notification to help the player through the slavery period. I made more accessibility enhancements to the game to make it a little bit easier for the blind to navigate the Dusty Path. And I added a "review me" button to the game. The app is currently in the App Store's review process. I'll update this log as soon as I get the results/side effects from making these changes.

<a id="rubybrigade"> </a>

**Mar 3, 2014: Slides Complete for My First Presentation at a Ruby User Group - 12k Lines of RubyMotion** <a href="#rubybrigade"><small>permalink</small></a>

A lot is still up in the air at this point. Version 1.4 is waiting for release. I've permanently dropped the price of A Dark Room to $0.99 (I don't know the long term effects of this). I'm hoping that Owen from Pocket Tactics shows some love to A Dark Room on his website. I'm hoping that Leigh publishes the interview questions. I'm hoping that Brandon gets back to me about his thoughts on the game and with any help he can provide. I'm hoping the RubyMotion team likes the slides I've sent them and that I'll get some visibility with them too. I'm hoping that my first presentation at a Ruby user group goes well. I'm hoping the new review button generates more reviews. Lots of hope... few answers at this point. [Here is the link to the presentation I did.](http://amirrajan.net/12k-lines-of-RM/#/title).

<a id="reviewbutton"> </a>

**Mar 4, 2014: The Review Button in A Dark Room** <a href="#reviewbutton"><small>permalink</small></a>

The pending release to A Dark Room hit the App Store. As expected all the reviews from the previous version get removed from the "current" release. The app at this point is ranked 32 under the RPG Category. With zero reviews for the current release. I knew this was a risk going in, but with it, I got 100 more promo codes.

Outside of more accessibilty enhancements, and a bit more storyline elements; the most important part of this release was the review button I added. The review button shows up after the player has beaten the game. I decided to only show it at this point, because I know that the player has experienced the story in its _entirety_ at least once.

That day I received 20 reviews. A small success to be celebrated. I'm hoping to have an influx of reviews every few days given how long it takes to beat the game... I'll probably be dissapointed... but we'll see.

<a id="thirdcheck"> </a>

**Mar 5, 2014: Check Number 3 From Apple** <a href="#thirdcheck"><small>permalink</small></a>

The third check comes in. The grand totals for the month of January:

- Revenue: $1,320.00
- Downloads: 986
- Reviews: 11 five-star reviews, another one-star review
- RPG Rank: 154th at its low point, 25th at its height
- Overall Rank: 1469th at its low point, 432th at its height (stayed in the top 1500 Games for the entire month)

The one star review made me smile a little bit. You can't please everyone:

>its crap ★

>by Bryce68!!! - Version 1.3 - Jan 24, 2014

>its a white screen those other ratings are rigged the game is junk

I knew that the first part of the game was slow to "reveal itself". The web version takes 125 seconds for the builder to finally wake up and open up the rest of the game. In the mobile version, this time was dropped down to 45 seconds (specifically to avoid this kind of review). I added a few "keep going" messages in the mobile version that start revealing themselves 17 seconds into the game. Looks like neither of these carrots kept Byrce68's attention long enough. It sucks... but what can you do but smile and move on.

A message to Bryce68: I'm sorry that I wasn't able to keep your attention, but none of the review are fake... all 20 of them (the grand total at the time Bryce's review was written) are genuine, through and through.

<a id="leigh"> </a>

**Mar 6, 2014: Leigh Alexander Publishes Her Interview on Gamasutra** <a href="#leigh"><small>permalink</small></a>

Leigh, thank you for this. Thank you for taking the time to interview Michael and me. Thank you for skillfully writing about the journey we've had so far.

Here is the write up [Leigh Alexander](http://leighalexander.net/) did on A Dark Room: [A Dark Room's unique journey from the web to iOS](http://www.gamasutra.com/view/news/212230/A_Dark_Rooms_unique_journey_from_the_web_to_iOS.php). It's an amazing read. Gamasutra has 100k followers... it was tweeted by their official Twitter handle. Additionally, the article was shared ~25 times on Twitter and got 15 likes on Facebook.

At this point, I have a better expectations of the impact these kind of publications have on the number of downloads (it's small, but every little bit helps keep me going). The downloads for the day spiked to 68 (a little over double my $0.99-price averages for the month). The drop off is fairly quick for this kind of media coverage (given the historical data I have now... I'll report back after a few days have passed). Regardless, thank you Leigh Alexander. Thank you for this small win I can celebrate.

<a id="gamasutra"> </a>

**Mar 8, 2014: Two Days After the Gamasutra Publication** <a href="#gamasutra"><small>permalink</small></a>

Leigh's article stayed on Gamasutra's Top Articles for two days.

On March 6th, Leigh tweeted about it to 34k Twitter followers. Gamasutra tweeted about it to their 100k followers.

On March 7th, Leigh tweeted about the article a second time.

The game's download spiked to ~100 downloads for each day. Its rank went from number 24 (in the RPG category), to number 16. All these changes were in line with my expectations. I wanted to keep the momentum going, so I decided to spend the next 4 days promoting the game on Reddit, Twitter, and Touch Arcade.

<a id="promotion"> </a>

**Mar 12, 2014: Four Days of Promotion** <a href="#promotion"><small>permalink</small></a>

I posted this write up on /r/IndieGaming and /r/GameDev. To share what I've been through so far.. and yes, to help with visibility... two birds with one stone, right? The posts gained popularity and I had a number of good conversations, specifically about the viability of the Android market (tl;dr; it doesn't look promising).

I did another promo code giveaway on Touch Arcade. But nobody (not a single person), asked for a promo code. That was incredibly surprising. I'm not sure if it was timing or if the people on Touch Arcade just didn't care to get a copy. I let the thread die off. That will be the last time I post on Touch Arcade.

The reception or Reddit was much better. I received a number of good comments and support on /r/iOSGaming and /r/AppHookup. Thirty codes were given away and the downloads for three days stayed at around 80. Being active on Reddit and making sure to reply quickly to conversations took up a couple of hours every day. A Dark Room's App Store ranking (again, under the RPG section), continued to hover around 15.

Good things came out of the the Reddit posts. I had a number of incredibly candid posts about the game and the development logs. Many people empathized and gave words of encouragement. Some didn't. Have I mentioned how important tact and empathy are?

One notable conversation convinced me to try porting the game to iPad. I decided to time box the port to iPad. Surprisingly, I wrapped it up in a few days. I'm playtesting the game now... on an iPhone 5, iPhone 5s, iPad 3, iPad Air, and iPad 2... T_T.

Given that an iPad version was going to be released, I decided to give away 50 more codes, but this time on Twitter (you lose any codes you don't use within a release). I posted the codes and tweeted about it. Cassandra Khaw (Editor at USGamers), Maddy Myers (Editor at Paste Magazine), Laruent Sansoetti (Founder of HipByte and RubyMotion), and Pocket Tactics (ie Owen Faraday) retweeted this promotion to their followers (~13k followers combined). All the codes were claimed. Given the downloads for that day, it didn't seem like they were all redeemed however. There was no spike in sales either. My downloads (and revenue) is flatlining now.

<a id="top10again"> </a>

**Mar 13, 2014: Back in the Top 10, iPad Release** <a href="#top10again"><small>permalink</small></a>

I woke up this morning. Awake, head throbbing, vision blurry ;-). Checked my app rank... A Dark Room made it into the top 10 RPGs... and finally cracked the top 200 in the overall Games category. Back to testing the iPad/Universal version of the game.

<a id="top6"> </a>

**Mar 15, 2014: A Dark Room is Ranked 6th Under RPGs** <a href="#top6"><small>permalink</small></a>

For the past two days, A Dark Room has gotten ~200 downloads. I haven't done any recent marketing of the game to result in that kind of spike. True, the game made it into the top 10 spot a couple of days ago... but I didn't experience this kind of spike the last time it was there.

The only thing I can think of was that the web version of the game got 1000+ upvotes in an AskReddit thread: [Reddit, what is a fun webgame I can sink a lot of time into?](http://www.reddit.com/r/AskReddit/comments/20al3n/reddit_what_is_a_fun_webgame_i_can_sink_a_lot_of/cg1cxfy). Michael mentioned that there was also an iOS version of the game within the thread comments... I still don't think it could have such an impact given that the [comment was buried way way down in the post](http://www.reddit.com/r/AskReddit/comments/20al3n/reddit_what_is_a_fun_webgame_i_can_sink_a_lot_of/cg1s9ho). Maybe it did... I have no idea.

Also. This dev blog was linked to in the following newsletters (I received emails and tweets from a couple of readers): [RubyMotion Dispatch](http://rubymotiondispatch.com/) and [TapFame's](https://tapfame.com/) Newsletter. Again, I don't think that such a spike could come from these distributions (I may be wrong).

Regardless, it didn't last. A Dark Room's rank is back down to number 10 (/le sigh). The iPad update is in the App Store review process, and will hopefully be released to the public next week (and hopefully without that dreaded first day crash I experienced and still can't explain). Perhaps the combined downloads from iPhone and iPad will bring up the ranking again. From what I hear, getting into the top 5 in your category is a big deal... and from the looks of it you have to be bringing in over 200 downloads for a solid week to break into that spot number 5 (in the RPG category... no telling what you have to be bringing in to get a top spot in another category).

All I can really do is wait. I'm out of promo codes. I have no control over App Store ranking. Any amount of engagement I try to have on Twitter won't bring in numbers like what happend in the last two days. So I guess I'll geek out on something else for a while, and take a break for the next few days :-).

<a id="ipadrelease"> </a>

**Mar 18, 2014: The Spike is Over. iPad Version Release** <a href="#ipadrelease"><small>permalink</small></a>

The unexplained spike is over. Downloads are coming back down to "normal" levels. This morning I received an email that the iPad verison of the game is ready for sale. Of course, with every new release, I get a new set of promocodes, and all the reviews get "archived" (wiped out frankly, frustrating). From March 4th to today. A Dark Room received 85 reviews. One of them was a 4-star review, one of them was a 1-star review, the rest were 5-stars. The game was getting an average of 6 reviews a day.

With the release of the iPad version. A Dark Room will now be searchable on all devices with default search filters. I'm also hoping that the combined download numbers between iPhone and iPad will help bring A Dark Room's ranking back up (which is currently hovering around #17). The game did not crash when I installed it on my iDevices. This was a huge relief for me, and possibly something I can put behind me now... I'd be lying if I said I slept well these past few nights.

<a id="mysterysolved" > </a>

**Mar 19, 2014: Mystery of the Week Long Spike Solved** <a href="#mysterysolved"><small>permalink</small></a>

[Last week there was a spike in A Dark Room's download numbers that I couldn't explain](#top6). Kevin Wade of OrgSync figured it out. It was because of Spring Break. A bunch of people with time on their hands came to the App Store and bought the game. A Dark Room's rank didn't increase in the App Store with this large week long spike in downloads, because every game was experiencing a similar spike.

This is also the first day after the iPad relese. Downloads are back to normal levels (a little over 100 a day). I didn't expect a big spike because of the iPad release. The game still needs to make it through the iPad ranking system (the iPhone rankings list is different than the iPad rankings list). From historical data, it looks like A Dark Room can make it into the top 20 in about a week. We'll see if my prediction holds true.

Also, the first day after a relase is always frustrating. When you push out a new release, you don't lose your rank in the app store, but you do lose all the reviews. So there sits A Dark Room, ranked #17 in the App Store, zero reviews, one boring screenshot, who will buy that? Thankfully, the trusty review button in the game pulled through again. I got twelve 5-star, and one 4-star review yesterday.

<a id="freeagain"> </a>

**Mar 24, 2014: What Happened When A Dark Room Was Free for Two Days** <a href="#freeagain"><small>permalink</small></a>

Spring Break (and the spike that came with it) was over... A Dark Room's ranking was falling. Part of this fall was related to the new release of the game (I think). This game has a huge risk every time a new version releases: previous reviews of the game get archived, which makes people, who've never experienced the game, hesitant in buying it. I was lucky to get twelve 5-star reviews the first day of the v1.5 release... it didn't look like it was enough to convince people to buy a game with only one screenshot, and a vague description. By the 19th, A Dark Room had 18 five-star reviews, but its rank had fallen to 28th in the RPG section.

At this point I decided that the game could benefit from a little bit of publicity, so I made the app free for two days. [I've done this once before](#top10), the difference this time was A Dark Room was now equipped with a well placed review button. It was worth the risk of losing my app rank if it meant I could get a good surge of reviews.

For the 20th and 21st the app was free. I posted the announcement to Touch Arcade, reddit/r/iOSGaming, reddit/r/AppHookup, and Twitter. As expected, the game got a lot of love on all fronts. The "App discount" syndications also published that the app went free.

The combined downloads for the next two days was 13,997. The last time I did this, I received ~9,000 downloads. So it seems that these numbers weren't a fluke at all. This is actually the amount of downloads "top rated" free apps get on a daily basis.

The game (depending on how addicted the player gets), can be completed in 3 hours, or up to 3 days of casual play. So now it was just a matter of waiting to see if the review button was doing its job. I waited two days before drawing any conclusions.

Here is the download history for time the app went free (with a couple days before and after):

- Mar 18th: 161
- Mar 19th: 124
- Mar 20th: 4,654
- Mar 21st: 9,343
- Mar 22nd: 221
- Mar 23rd: 187

Again, I wasn't surprised that the downloads went back to their regular numbers after the sale was over. But, during that time period, A Dark Room received an additional 112 5-star reviews, one 1-star review, and one 2-star review. It seems like players either "get" the game or they don't... thankfully, the ratio is well in A Dark Room's favor. Also, it seems that even with the well placed review button, the conversion rate for reviews is about 1%... geez.

On the 18th, A Dark Room's iPhone and iPad RPG ranks were 28 and 71 respectively (and falling). The rankings were reset during the time period when the app was free (a risk I was well aware of). Today, A Dark Room's iPhone and iPad ranks are 16 and 40 respectively (and rising... so far). I'd say the two day sale was a success.

<a id="minecraft"> </a>

**Mar 31, 2014: Attack of the Minecraft Clones, and a New Hope in the United Kingdom** <a href="#minecraft"><small>permalink</small></a>

For the past two weeks, a certain "anomaly" has existed in A Dark Room's small part of the App Store. There are two games that have managed to take top spots in the RPG category: Skyblock - Survival Game Mission Flying Island (which I'll call Skyblock1) and Skyblock - Mini Survival Game in Block Sky Worlds (which I'll call Skyblock2). Skyblock1 and Skyblock2 hold the _first_ and _tenth_ spot in the RPG category. The average rating for both games are two stars.

I'm not sure what is going on here. I am well accustomed to the "I don't get it this is dumb" one-star review (I see that as a failure on my part by the way...). And here are two apps, that are in the top 10, and their reviews are mostly poor. Are the people that are reviewing this game, simply "not getting it"? Where are the reviews of people that enjoy the game?

[As I've mentioned before](#top6), getting a top spot in rankings takes a consecutively high number of downloads, day after day. These games have been holding a top spot now for what looks like _two weeks_. These games are definitely bringing in a high number of downloads, but very few good reviews.

Is the Minecraft "franchise" simply that popular? Here is a list of Minecraft based games that are high ranking right now:

- Skyblock - Survival Game Mission Flying Island (#1 spot, 2-star average)
- Hunt Games - Mine Mini Survival Game with Blocks (#9 spot, 2-star average)
- Skyblock - Mini Survival Game in Block Sky World (#10 spot, 2-star average)
- Minecraft Skin Studio - Official Skins Creator for Minecraft (#12 spot, 4.5-star average)
- Adventure With Companions - 3D Online Multiplayer Block Building Sandbox With Creative (#17 spot, 4-star average)
- Minecraft Explorer Pro (#18 spot, 3.5-star average)
- World Explorer - Made for MineCraft (#19 spot, 2.5-star average)

A Dark Room is currently ranked 20, with 220 reviews, average 5-star rating... in the United States.

A few days ago, I saw a small spike in downloads. I didn't think too much of it. Yesterday, there was a 300% increase in A Dark Room's downloads. This got my attention. I tried to make sense of why this spike existed. App Annie, a site I use to track this stuff, showed a disproportionate number of downloads in the United Kingdom App Store. After looking at rankings, I saw that A Dark Room was recently promoted to the #1 spot in the UK App Store. Not #1 RPG, not #1 Game, **A Dark Room is currently the #1 app _overall_.**

I don't have any details (yet) about what impacted this, or how many downloads this will translate to in the long run. One thing I've learned so far, you have to have tempered expectations. I've reached out to [Cara Ellison](#cara) and [Leigh Alexander](#leigh) (editors in the UK) to see if they have any idea about what's going on. I'm still trying to connect the dots... trying to understand how this happened. I'll add another entry as soon as I do.

<a id="topappday2"> </a>

**Apr 1, 2014: Day Two, at the Number One Spot, in the UK App Store** <a href="#topappday2"><small>permalink</small></a>

A Dark Room has managed to stay number 1 in the UK App Store for March 30th and 31st (so far). Here are my observations:

Downloads have dropped 10% from D-day (March 30th). This was surprising given that when the [app was free](#freeagain), the downloads were higher on day two.

The gains in the UK App Store don't seem to be influencing US sales. It may be too early to say this, but that's what I've seen so far.

<a id="empathy"> </a>

Another observation (and I think this is unique to the game), is there is now a higher number of 1-star reviews. For the past two days, A Dark Room has received 59 5-star reviews and 38 1-star reviews.

If you've played the game, you know that the first part of the game has a slow reveal, and opens up "phase 2" only after you've bought the compass. I'm trying to put myself in the shoes of those that are in the UK. Here is a game... and it's the top app in the App Store. There is only one screen shot, a vague description and many of the review say the same thing:

>**A-MAZING** - I don't write reviews. I find those "Rate this Game" popups extremely annoying. This game doesn't have those. Instead it waits until right at the end, after it has blown your mind, to ask for a rating. And for the first time ever, I felt obliged.

>**One of a kind! Superb** - "I never write reviews," or "I hardly write reviews!" That's how all of the others have begun and if that doesn't draw you in then you shouldn't be on the App Store. This unique game has kept me entertained for hours on end...

>**Wow!** - Well where to begin, I read the reviews and not knowing anything about the game I took a punt on it and I'm glad I did! What a brilliant game! ...

>**;)** - A brilliant game very addictive and interesting concept. I would highly recommend it

>**Fantastic** - Really atmospheric, very minimalist: an rpg, a survivor sim, a text adventure. Absolutely brilliant and shows you don't need grafix to make a really absorbing atmospheric game.

I decide to give the game a shot. I _pay_ money for it. Pressing the buy button is a very powerful gesture. It doesn't matter if the app I am buying is $1 or $100. The act of buying something in the App Store has become an exchange of trust, more so than an exchange of money. When I hit the buy button, I am putting trust in the developer, trust in the App Store to curate apps, trust in the reviews that they are accurate and true.

So here I am, a random person browsing the App Store, I may not even be a gamer, I may not even _like_ RPG's. And here's this app, it's in the _top spot_, and I decide to give a token of _trust_. I open up the app, and am presented with a black screen, and a single progress bar. I press the "light fire" button, and the screen changes color. I play for 5 seconds?, 10 seconds?, 5 minutes? The "game" does effectively nothing, a few pieces of text comes onto the screen, the progress bar updates, some new buttons show up, leading to more progress bars, the screen changes colors... that's it?

I want immediate gratification for my _trust_, and I'm not getting that. My trust is short lived, since its being placed in the hands of complete strangers. I'm enraged, I'm so incredibly angry right now that I gave my trust to the developer, Apple, the reviewers, strangers, humanity... and I feel _betrayed_. So I leave a review to show my dissatisfaction:

>**Fake reviews** - It's literally the most repetitive boring game. Was interested for about half an hour thinking it would get better but after a whole and giving it a chance, it just turns out it's pointless tapping

>**Bit of a scam** - I bought this a week ago thinking the reviews looked positive. Now having played the game and read through further reviews I feel scammed. Poorly hidden "I don't usually write" fake reviews are littered everywhere.

>**SCAM!!!** - Worst game ever!!! Don't buy it! Reviews are fake!!!

>**Awful! The worst!** - his is the most awful game I have ever played ! It costs £0.69 which I would like back and it has fake reviews written about it by it's own company! DO NOT EVER BUY THIS "game".

>**Con Artist of 2014 award goes to...** - Well I don't usually write reviews either, but after reading the hundreds of reviews below I can only come to the conclusion that they were paid to do them....

When the game was in a quiet spot in the App Store, a lot of the downloads came from people recommending it word of mouth. You really couldn't find the game unless you specifically looked in the RPG section and scrolled down a couple of pages. When a real person, a friend, a fellow gamer, an esteemed editor recommends something to you... you give their recommendation more trust, and as a by product, you give A Dark Room more of your time.

The trust in the App Store, the trust in developers who develop products for the App Store is forever waning. And I can see the exhaustion and frustration that people feel (I feel it myself when I'm browsing for apps). And right now, that frustration is being directed to A Dark Room.

No, adding another screen shot or more details about the game won't help. One, because the game isn't visually appealing, and two, because I'm a stranger... I could be a scam artist that is putting up fake screen shots (I'm not of course). Most importantly, if I added any kind of hint to what was in the game, it would take away from the discovery that the player experiences. And I won't do that.

At this point, all I can do is wait. It takes anywhere from 3 hours to 3 days to beat the game and get a "review me" button presented to you. I have to put _my_ trust in the player, and hope that they take the time to review the game, and show that A Dark Room really is something brilliant and unique.

As a consolation, I've got some chuckles out of the reviews, specifically this one:

>**Avoid** - To summarise, I would actually rather be in a dark room, with nothing else is in it, until my untimely death before playing this app again. The endless time that is spent tapping could be spent building a time machine that would take you back to the time you pressed 'install' just so you can slap yourself in the face. Take your 70p and go purchase a lettuce and tap that, it would be more productive... And at the end you have a lettuce.

<a id="topappday3"> </a>

**Apr 2, 2014: Day Three, at the Number One Spot, in the UK App Store** <a href="#topappday3"><small>permalink</small></a>

A Dark Room has been in the top spot in the UK App Store for 3 days now. Downloads have fallen 56% from day two, but A Dark Room's rank still remains #1. From what I've observed so far, the rankings are heavily determined by the number of downloads you get (not the reviews). Given that the downloads are falling, this rank position may not last much longer.

I don't have enough data yet, but it seems like the rankings in the UK App Store _are_ influencing the US App Store. With no noticeable spike in US downloads, A Dark Room has jumped to the #9 spot in the RPG Category and the 146th spot in the Games category. That is both exciting and _terrifying_. From what I've read, the US App Store market share is 5 times the size of the UK.

The reviews have a definite pattern. You either _love_ the game or _hate_ it. Here are the review number for yesterday:

- 5-star: 44
- 4-star: 3
- 3-star: 0
- 2-star: 1
- 1-star: 26

The reactions in the reviews continue to be visceral. Here are a couple:

>**Amazingly bad!** - I lasted 30 seconds. I dont know what's worse, being charged more than a penny for this rubbish or reading the obviously faked reviews after purchasing or finding the developers epic long long long faked diary in making this 'game' that a 5 year old could put together. he also actually seems to believe that no one can review the 'game' without having completed it! Will be getting onto apple for a refund. Yes i can do that too!

>**Fraudsters!!** - This game is awful. All the reviews are fake. The people behind this have broken the law as this is clearly fraudulent activity designed to get you to part with your money for false promises. Absolute disgrace. Pure theft. Pure criminality.

One person from the UK actually "called @ADarkRoomiOS out" on Twitter. Against my better judgement, I decided to engage with her. I'm glad I did. Conversation follows:

>her - @ADarkRoomiOS what a con! Waste of money, I wish I could warn others the reviews are fake.

>me - I'm truly sorry you feel conned. More info about the game here, please take a moment to read if you can: http://amirrajan.net/a-dark-room/

>me - did you get a chance to read the development log I had put up with regards to A Dark Room and my sabbatical?

>her - I'm sure the game is great; maybe it's just not for me. But all the best to you, and I hope your success grows.

>me - I appreciate that, but perhaps put yourself in my shoes. Any ideas how I can communicate that it isn't a con?

>her - hey look, don't pay attention to the likes of me. Keep creating and keep making the cash, I would do the same!

>me - thank you... you're a part of A Dark Room's history now. In a good way. :-)

>her - haha thanks! Maybe I should reinstall the app and uninstall my ignorance

<a id="topappday5"> </a>

**Apr 4, 2014: The Fall From the #1 Spot in the UK App Store. Here Are the Final Numbers** <a href="#topappday5"><small>permalink</small></a>

After <s>four</s> five days in the top spot of the UK App Store, A Dark Room finally dropped to the #2 spot.  Observations:

- You either love A Dark Room or hate it.
- Once you make it to the top 5 of your category, things begin to pick up.
- There doesn't seem to be any correlation between the UK and US App Stores.
- The US App Store is _definitely_ larger than the UK App Store.

Here are the final numbers leading up to the #1 spot in the UK:

Date | Downloads (UK) | RPG Rank (UK) | Overall Rank (UK)
:--- | -------------: | ------------: | ----------------:
3/22 |             40 |            10 |               403
3/23 |             58 |             6 |               333
3/24 |             38 |             6 |               337
3/25 |             36 |             5 |               277
3/26 |             47 |             3 |               211
3/27 |            108 |             1 |               100
3/28 |            296 |             1 |                29
3/29 |           1088 |             1 |                 5
3/30 |           5959 |             1 |                 1
3/31 |           5037 |             1 |                 1
4/01 |           2812 |             1 |                 1
4/02 |           2654 |             1 |                 1
4/03 |           2195 |             1 |                 1

Here are the US numbers:

Date | Downloads (US) | RPG Rank (US) | Overall Rank (US)
:--- | -------------: | ------------: | ----------------:
3/22 |            125 |            21 |               636
3/23 |            109 |            20 |               573
3/24 |             83 |            20 |               643
3/25 |             88 |            20 |               605
3/26 |            106 |            19 |               604
3/27 |             82 |            22 |               774
3/28 |            100 |            21 |               637
3/29 |            117 |            24 |               719
3/30 |            140 |            20 |               623
3/31 |            103 |            16 |               560
4/01 |            127 |            12 |               468
4/02 |            181 |             7 |               314
4/03 |            176 |             6 |               242

During the 5 days at the top spot, users of the UK App Store gave A Dark Room the following ratings:

- 5 stars: 195
- 4 stars: 17
- 3 stars: 2
- 2 stars: 6
- 1 stars: 94

As for the reviews, I'd be lying if I said that I wasn't affected emotionally by people claiming that A Dark Room was a scam and I was a con artist. There were three individuals on Twitter that actually called out A Dark Room publicly. I addressed each tweet individually, exercising an extreme amount of empathy. Each person ended up retracting their statement about A Dark Room and apologizing (one even said that they'd give A Dark Room another shot). If anything, this was preparation for what _will_ come if I make it to a top spot in the US App Store.

<a id="topofus"> </a>

**Apr 9, 2014: #1 RPG, #5 Game, #10 App, in the US** <a href="#topofus"><small>permalink</small></a>

Here we are. Ten days after A Dark Room made it to the #1 spot in the UK. This morning, A Dark Room is ranked #1 in the RPG category, #5 in the Games category, and is the #10 app, _overall_. I still have no idea what's happening. I don't know definitively whether the buzz in the United Kingdom somehow caused the same kind of viral outbreak in the United States.

But (so far) the trends are holding. As soon as A Dark Room hit the #1 spot in the RPG category, a snowball effect occurred (similar to what I saw in the UK). If you look at the [rank progression in the UK](#topappday5), you'll notice that A Dark Room hit the #1 spot overall, three days after it became #1 in the RPG category. A Dark Room hit the #1 RPG spot, in the US, late on April 6th... which makes day number 3, today. I doubt it'll jump 10 spots in one day, but it's worth noting how similar the trends are.

Outside of impacts associated with being #1 in the UK. The following _may_ have given A Dark Room more steam in the United States.

As soon as A Dark Room hit the #1 spot in the UK I reposted what I wrote here on /r/gamedev: [What happens when your iOS game goes viral and becomes the #1 app in the UK App Store](http://www.reddit.com/r/gamedev/comments/220quk/what_happens_when_your_ios_game_goes_viral_and/). The post received 200 up votes, and there were many good conversations to be had.

Out of sheer luck. A Reddit user asked the following question on /r/askreddit, which Michael ended up responding to: [Has anyone here ever built a $20 or $40 desktop application, or $0.99 to $5 mobile app, and made real money from it?](http://www.reddit.com/r/AskReddit/comments/227qln/has_anyone_here_ever_built_a_20_or_40_desktop/cgk7rhp). The question received 1159 upvotes, and Michael's response was the top comment.

Around this same time, a review site, that I reached out to a couple weeks ago, gave A Dark Room 3 stars (the review said mostly good things about the game, so put your torches and pitchforks down): [148Apps - A Dark Room Review](http://www.148apps.com/reviews/dark-room-review/)

That's all that's happened as far as I know. A Dark Room has dropped to #5 in the UK. Downloads are still dropping and haven't leveled off. Positive reviews out score negative reviews 3 to 1. Given what I've seen in the UK, if A Dark Room does indeed hit the top spot, it won't stay there for long.

<a id="number1us"> </a>

**Apr 15, 2014: #1 in the App Store** <a href="#number1us"><small>permalink</small></a>

A Dark Room iOS finally clawed its way to the #1 spot. It happened on April 13, 2014. It took seven, very long days to make it there from the #1 RPG spot. I was in shock when it passed Mine Craft in the rankings. I literally gasped out loud when it passed Monument Valley. I laughed sinisterly when it took down RBI Baseball 14 (an officially licensed game of the MLB). This marks the third day at the #1 spot.

The trends in the United Kingdom should give an indication as to what will happen in the US. Here are some observations and predictions:

- The US App Store market is a little over 3x the size of the UK (not 5x).
- iPad sales have been insignificant relative to iPhone.
- Not a single major gaming website has done a piece about A Dark Room (yet).
- The reviews in the US have been overall positive! (a ratio of 9 to 1 as opposed to UK's 3 to 1)
- A Dark Room will fall out of the #1 US spot _very_ soon.
- It'll see a 20% drop in downloads, day over day, until it levels out.
- It'll take ~25 days for this "leveling" to occur.

In the UK, A Dark Room is currently ranked #12. It _seems_ that the game has finally leveled out (or at least the fall has slowed down considerably). A Dark Room is averaging 400 downloads a day over there.

I'll of course continue to post new observations as soon as I have more data. Also, there is going to be another _unique_ update to the game that may cause another viral out break (probably not, but I can hope).

tl;dr; I won't be able to retire on the revenue A Dark Room is generating (not by a _long_ shot), but it'll definitely extend my sabbatical.

<a id="newnormal"> </a>

**Apr 29, 2014: Waiting for the New Normal** <a href="#newnormal"><small>permalink</small></a>

A Dark Room has been #1 in the App Store for 17 days now. During that 17 day period, the game has gotten 241,494 downloads. Every trend and projection I've made against what I saw in the UK has been broken:

1. In the UK, it took 3 days to make it to the #1 spot overall, from the #1 RPG spot. In the US, this took 7 _long_ days.

2. In the UK, A Dark Room was taken out of the #1 spot by an Apple Editor's Choice pick (Monument Valley). In the US, A Dark Room has survived _two_ Editor's Choice picks (Hitman GO and Leo's Fortune).

3. In the UK, the reviews had a ratio of 3 positive reviews for every 1 negative. The negative reviews called the game a scam and claimed that all the other reviews were bought by me. In the US, the reviews have a ratio of 9 positive reviews for every 1 negative review. There are some that state the game is a scam, but most of the critical reviews in the US are valid (they found the game boring, over hyped, incomplete, etc).

4. In the UK, A Dark Room stayed at the #1 spot for 6 days. I thought to myself "Okay, it took twice as long to get to #1 in the US, I can expect to stay at #1 twice as long." A Dark Room is going on to the 18th day now.

5. In the UK, A Dark Room's downloads dropped 20% day over day after the initial days at #1. In the US, the downloads are _level_ and spiked _again_ on 4/20 and 4/27. None of this makes sense.

Every day has been a bit stressful. Which app will take me out of the top spot?

1. Goat Rampage: A game "inspired" by the viral hit Goat Simulator. How the heck is A Dark Room going to survive a popular meme? For four days, I kept a close eye on this game, waiting for it to swap places with me and take the #1 spot. It didn't.

2. Hitman GO: When this was featured by Apple, I thought I was done. Here is a game built by a powerhouse, Square Enix. What chance does A Dark Room have against that kind of shop? A Dark Room survived.

3. The Amazing Spider 2: This game was wire to wire with Hitman GO, climbing up the ranks. Two threats at the same time. A Dark Room survived.

4. Heads Up!: On April 22nd, Ellen DeGeneres plays Heads Up! on her talk show. The game shoots up to #2. How the hell will A Dark Room survive a game that has _celebrity sponsorship_? It did.

5. Wayward Souls: A rouge-like RPG with a cult following. So incredibly awesome that it's available on iOS. "If Wayward Souls takes out ADR, I'm okay with that. That will be an honorable defeat," I said to myself. But it fell down the ranks too.

6. Leo's Fortune: Apple stops promoting Hitman GO and picks Leo's Fortune. Another beautiful game that showcases the "beauty of iOS". I watch it climb day after day. And then it drops too.

7. Blek: This game, just yesterday, jumped _13_ spots in one day to claim #2. It's built by an indie dev too. I know he is going through the same thing I've been going through. A mix of hope and stress. He is eyeing how quickly he gets new reviews, he probably wakes up in the middle of the night to see if he's over taken A Dark Room... just like I wake up to see if I'm still #1.

Now, all I can do is survive till Tuesday. Tuesday, is a magical day. It's the day where the media takes notice of the top apps in the App Store (whether they want to acknowledge A Dark Room or not). This however doesn't cause any kind of spike in downloads. But it's nice seeing what the internet has to say about A Dark Room every time it survives another week. By far, the best unsolicited article was published by [The Knox Student](http://www.theknoxstudent.com/news/2014/04/17/procrastination-station-mobile-gaming-for-hipsters/).

All I can do now is wait for the "new normal". That moment where I get used to this unfamiliar terrain, and I can finally get a decent night's sleep.

This is the best way I can describe what I'm feeling right now: I've bought a lottery ticket, and the lottery commission has revealed 5 of the 6 numbers. And so far, I've gotten those 5 numbers right. I know I've got at least the winnings for those 5 numbers in the bag. But now I'm waiting for the 6th number... that jackpot number that changes your life forever. The lottery commission hasn't revealed the 6th number yet, they haven't even told me when they'll show the 6th number. So I'm stuck in this weird limbo, where others see success and all I can do is temper expectations, be "responsible", and move forward as if that 6th number will be wrong.... still number 1, just checked.

<a id="thefall"> </a>

**May 6, 2014: The Fall from the US Top Spot** <a href="#thefall"><small>permalink</small></a>

It finally happened. On April 30th, around 5pm, A Dark Room lost the #1 spot in the US App Store to Blek. I knew ADR would lose the spot at some point, but its still hard to describe what I felt when that happened.

I refresh the App Store list on my iPhone and see the two mostly-black icons still holding the number one and number two spot (A Dark Room and Blek). It takes a split second to realize that the #1 spot isn't A Dark Room anymore. I feel defeated and relieved. The climax of this story has passed. I am finally into the falling action and dénouement.

During this time period, A Dark Room received quite a bit of news coverage:

- Not [one](http://www.cultofmac.com/277035/dark-room-iphone-top-paid-game/), but [two](http://www.cultofmac.com/277118/dark-room-lights-app-store-big-heart-open-world/) write ups on The Cult of Mac, an online publication that reaches _millions_.
- A write up on [Huffington Post](http://www.huffingtonpost.com/2014/05/01/a-dark-room-iphone-game_n_5241335.html), which reaches _millions_ (even Ellen DeGeneres follows them on Twitter).
- A write up on Medium by [Barrett Sheridan](https://medium.com/@bsheridan), formerly a tech editor at Bloomberg Businessweek.
- An interview with DFW CBS 11... I was on local TV! But I don't have cable/bunny ears, so I couldn't watch it #sadpanda.
- An article/interview for the Dallas Morning News.
- That plus a few small independent blogs wrote about the game.

All this, and A Dark Room _still_ fell from #1. It's, in fact, struggling to keep the #6 spot now. US downloads have dropped 80% from the weeks before. On the bright side, being out of the top spot gave me the window to push out a crucial release of the game. The reviews will reset, but it's (now) worth the risk.

In other news, on Apr 29th, ADR hit the #1 spot in both Australia and Singapore.

- In Singapore, ADR got 161 downloads at the top spot and fell soon after.
- It took only a day to get there after becoming #1 under RPGs.
- In Austrialia, ADR got 1300 downloads, but _rose_ for another 3 days, before starting its plummet.
- It took 7 days to get to the top after being #1 under RPGs.
- Reviews have been mostly positive in both countries.

With regards to reviews, I still wonder why the app [was received so negatively in the UK](#topappday2). Here are my two working theories:

- Smaller markets are more susceptible to scam apps. It's much easier for an app to quickly move to a high spot with a hundred or so paid for reviews.
- Reviews are ordered based on number of stars and length. The top reviews _set the tone_ for the rest of the reviews. I think we are subconsciously influenced by the "top" reviews. If a long, critical/angry 1-star review is posted (and the velocity for new reviews is low), then that "top" negative review will influence every person that tries out your app. In the case of the UK, a couple of reviews were long and extremely negative, calling the game a scam. And they stayed at the "top of the list" for a long, long time.

The stress I've continued to feel is this lack of consistency. No market is the same, download numbers are a constant roller coaster (the game spiked moderately in the UK again yesterday), human behavior isn't predictable, and media impact is hard to correlate. All in all the App Store feels impossible to rationalize.

With regards to the new release. There is a "secret" that I added, which is only available to those that have beaten the game. We'll see what kind of impact it has to downloads and review velocity. I expect review conversion rates to _significantly_ increase for those that have beaten the game. Regardless... I feel that A Dark Room's time at #1 has passed, and I won't see that spot again.

<a id="secondwind"> </a>

**May 26, 2014: A Dark Room's Second Wind** <a href="#secondwind"><small>permalink</small></a>

Twenty four days ago, A Dark Room fell from the #1 spot. This fall gave me the opportunity to release an updated version of the game. With the release, ADR lost its average rating, and all of its glowing reviews got archived.

The new release was an attempt to deepen the connection the game had with the current fan base. If you've beaten the game at least once, a section to the game would be unlocked where you can listen to developer commentary given by me and Michael.

I had started working on this commentary back in March. [Around this time](#mysterysolved) it didn't look like ADR was gaining any ground... I was entertaining the idea of making ADR free, and providing the developer commentary as an In-App Purchase. I was nearing finished with the release of the IAP, but ADR suddenly [went viral in the UK](#minecraft). Given the risk involved with resetting reviews, I decided to hold off on publishing the new version. When ADR made it to the [#1 spot in the US](#number1us), Michael and I decided to remove the IAP and release the commentary as a free update to the game.

[ADR fell](#thefall). I published that same day. By the time the new release hit the App Store (a week later), ADR's rank had fallen to the #7 spot over all. The next day, the game fell another spot. But then, two days after the release (9 days after falling from #1)... ADR stopped falling. It gained one rank day after day. By May 23th (22 days after the fall), A Dark Room made it back to the #1 spot.

So many variables were at play during this 22 day rise back to the top. I've done my best to summarize what all occurred. Any conclusions I draw are pretty speculative given that time and time again my predictions are proven wrong.

_Variable 1: App price drops_

Blek, the #1 game in the App Store made a smart move. About 4 days into their #1 streak, they dropped the price for their game to $0.99. [I did something similar](#pricedrop) back when I was struggling to stay relevant in the RPG category. Imagine what kind of increase Blek saw when they dropped the price of their game by _66%_. From what I've observed, a drop in price leads to an inversely proportional increase in downloads (with the added benefit of being able to say "I'm running a sale"). This little maneuver solidified Blek's #1 spot.... until A Dark Room took it back.


_Variable 2: Review velocity and quality_

Here is ADR's rating breakdown along with "quality" metrics (average number of words).

From Apr 8th to May 6th (version 1.5 without developer commentary), ADR received the following review breakdown:

- 5 stars: 3,710 ~82%
- 4 stars: 301 ~6%
- 3 stars: 107 ~2%
- 2 stars: 81 ~2%
- 1 stars: 345 ~8%
- Average Rank (not to be confused with rating): 2.44
- Total reviews: 4,544
- Reviews per day: ~162
- Conversion Rate: 1.47%
- Average Review Length: 31 words

From May 7th to May 25th (version 1.6, with developer commentary), ADR received the following review breakdown:

- 5 stars: 1,613 ~87%
- 4 stars: 72 ~4%
- 3 stars: 24 ~1%
- 2 stars: 33 ~1%
- 1 stars: 95 ~5%
- Average Rank (not to be confused with rating): 3.60
- Total reviews: 1,837
- Average reviews per day: ~102
- Conversion Rate: 1.61%
- Average Review Length: 38 words

It _does_ seem that the developer commentary helped give a little more reason to give a 5 star review (but not by much). Outside of that, it doesn't look like the new release significantly impacted ADR's rise.

_Variable 3: Number of downloads before hitting #1_

It took a much longer time to get back to #1 from similar "low" ranks. It took fewer average downloads, but a longer period of time.

Number of downloads from the #15 spot to the #1 spot on version 1.5:

- 4/08: 2,153
- 4/09: 4,310
- 4/10: 6,152
- 4/11: 7,669 (placed #2, day before #1)
- Average: 5,071
- Total: 20,284

Number of downloads from the #7 spot to the #1 spot on version 1.6:

- 5/07: 2,820
- 5/08: 2,531
- 5/09: 3,074
- 5/10: 3,528
- 5/11: 4,135
- 5/12: 4,878
- 5/13: 6,659
- 5/14: 6,164
- 5/15: 6,271
- 5/16: 6,300
- 5/17: 6,052
- 5/18: 5,690 (placed #2 in the US, #1 in Canada!)
- 5/19: 4,313
- 5/20: 4,845
- 5/21: 5,462 (day before #1 in the US)
- Average: 4,848
- Total: 72,722

_Variable 4: Relative performance of others in the App Store_

Heads Up! briefly knocked Blek out of its #1 spot (for a few hours), but soon fell back to #2 (and then #3). On the 14th, Ellen DeGeneres [posted a Heads Up! session with Emily Blunt](http://www.ellentv.com/videos/0-vrobj813/), which may have contributed to its very brief bump. But that's how Heads Up! rolls (see what I did there). It's an quality game with celebrity sponsorship. And because of this, it's held a top 10 spot _since May of 2013_.

Minecraft is Minecraft. This game is an "expensive" premium app with a review velocity of _300+ a day_. I think it's found a happy balance between rank and price. It's held a top 10 spot _since July of 2013_.

Plague Inc. has had a volatile existence. Its rank has fluctuated in the top 20 _since May of 2012_. That's _two years_ of "top spot" daily revenue.

Blek (can I call it my arch nemesis?) did an awesome job with timing its sale, making it really hard to take back #1. They _did_ eventually change the price back to $2.99, which may have contributed to their fall.

I have no idea what kind of price elasticity exists with regards to high ranking apps. My assumption is that Blek is measuring this elasticity themselves, or felt that net revenue at a lower rank/higher price was better than net revenue at a higher rank/lower price.

Michael and I have wondered what would happen if we increased the price of ADR, but have decided against it. Other games have precedence on other platforms, are celebrity backed, or have been around a long time. They show everything they have to offer, invest a lot in marketing, and ask for a fair price up front. ADR has no official media coverage, says nothing in the description, looks absolutely ridiculous with its single screen shot, and asks for $0.99.

To summarize my summary:

- The v1.6 update didn't seem to have a noticeable effect on ADR's rise back to the top.
- There's an incredibly complex symbiotic relationship with other ranked apps.
- It's too soon to tell how ADR will perform in the long run.

One thing's for sure, this roller coaster isn't over yet. Oh look... we're back at #2... Blek dropped their price back to $0.99. Oh look... estimated federal taxes are due next month... time to visit with my CPA again. Oh look! [Ruboto](http://ruboto.org/)! Oh look... [ADR scam apps](http://www.windowsphone.com/en-us/store/app/a-dark-room-game/a7fd3901-7020-4cb8-93b4-fdf3974dd205)... `(╯°□°）╯︵ ┻━┻`

<a id="grrr"> </a>

**Jun 20, 2014: Taxes, Negative Reviews, Clones, and Open Source** <a href="#grrr"><small>permalink</small></a>

Alrighty, this one has been on my mind for a while. It's going to be difficult to exercise empathy and be tactful within this post, but I'll try. Let's get started.

_Taxes_

There's no escaping it, you have to pay taxes. ADR is subject to income taxes. Period. No way around it. And given that App Store revenue is considered self employment income, I get hit with an additional 15% self employment tax, all of which has to be paid quarterly. Paying estimated taxes in itself has its challenges given the volatility of the App Store revenue. I don't want to get penalized for underpaying, but at the same time, I don't what to give the government an interest free loan either. June 15th, I wrote a check to the IRS for $60,000. Based on projections of this depreciating asset, I'll have to pay $30,000 quarterly. Hopefully the annual amortization is accurate, and I end up owing a penalty free amount at the end of the year.

So... after Apple's 30% take, royalties of 50% (no complaints here, ADR iOS wouldn't exist if it weren't for Michael's permission), and then a 45% hit in income taxes, I net 19.5 _cents_ on every download. YTD downloads are ~635,000. No way in hell we'll get that many downloads H2.

The terrifying part is that very few apps see even a fraction of this success. So think twice before selling almost everything you own, taking a year long learning sabbatical, and spending months porting a minimal text based RPG to mobile... you may be better off building apps after hours, or charging high dollar hourly rates to build an app for some company.

_Negative Reviews_

Just as death and taxes are inevitable, so are negative reviews for A Dark Room. I've been keeping a collection of [heart warming positive reviews here](http://adarkroomios.com/reviews.html), I hope you find them a great read. Let's enumerate the categories of negative reviews.

The _Honest, Critical_ Review:

A number of reviews in the App Store fall into this category. They are fair, well written, and simply didn't like what they bought. They spent the time to share their thoughts and warn others.

>Not That Brilliant... (1 star): The novelty of this game wears down almost immediately after the first time around. The whole point of this I suppose is to make us introspective and question particular things in the universe. But as much as this game would like you to think, you're not really in control. The fate of the game has pretty much been decided and no matter what you do there are pre ordained responses that characters like 'the builder' will have no matter what. I found that incredibly annoying.I guess it got the message through to me, but I don't think of this game as very deep or thought-provoking. Give me Angry Birds any day and I'll ponder the higher meaning of destroying smiling green pigs while actually believing that my 1 dollar wasn't for naught.

The _It's a Scam_ Review:

[I've talked about this before (and exercised large amount of empathy when doing so)](#empathy), so let me be a little mean. Here's the review:

>Absolute scam!! Manipulated reviews!! (1 star):	It's a text based game. That's ALL you get. Nothing like any review said how fancy and interesting the game play is. I suspect all the reviews are done by the developer himself using auto generated review. It is done by developer by purchasing the game himself through hundreds, if not thousands iTunes account, then give good rating over a period of time.

And here's my response:

>Dear reviewer, you're an idiot.

The _I didn't get my money's worth_ Review:

I live in a world where we carry $600 super computers in our pockets. We pay $15 for a two hour movie leaving satisfied, but paying $0.99 for _only_ two hours of entertainment is considered a rip off.

>Not worth the .99 (1 star): I beat the game in 2 hours, and the game doesn't do anything to reward you for winning. I like the game but it's missing depth and replay value.

The _Ransom_ Review:

The App Store is actually a great way to get feedback on what's broken. Pay attention to these "ransom" reviews. Because they'll give you insight on what needs to be fixed.

>Magnificent (3 stars): Game but the thieves take too long	Great game, i read your post about the making of the game and I am very sorry about making a 3 star review, but I spent more than 30 minutes with the thieves. I hope they'll go away soon, and the second they do ill rate it 5 stars. Thank you.

In this case though, [I've already nerfed the thieves once](#blindversionreleased), I'm not doing it again.

The _Just Plain Mean_ Review:

Welp. They are just mean. Really mean. No other way to describe them.

>What is this? (2 stars) - Before I bought this I was unsure so I looked at the reviews. They were all glowing which intrigued me, so I downloaded.. Played for about 2 minutes then deleted it! Absolute load of rubbish, it's sort of like sims but with no graphics, like a weird text version. Just utter nonsense how it has so many good reviews! If it was between watching a blind man trying dismantle a computer and playing this came I know which one I'd get bored of first!

The _Leg Sweeper_ Review:

These reviews are simply there to bring you down. They want so badly to explain the success of something they don't see as "good". Belittling me, and others that have reviewed the game. These are by far the most poisonous reviews. They bring me down and bring down every other person who played and enjoyed the game.

>Garbage (1 star) - It's so nice to have this hive-mind community full of hipsters and morons raving about the worst goddamn games. Same thing happened with Angry Birds and Flappy Birds. You people are disgusting. Horrible unwashed masses of brainless consumers. Hey morons, take a step back and really consider the piece of crap you rated 5 stars. No, really, just take a moment.

I have no words for this person. Here's another:

>Snake Oil (1 star) -	A cynical/realist lawyer's perspective..Finished the entire game, thoroughly, discovering all the secrets. Listened to the end commentary.  Only did so because I was promised an emotional experience, which is something no game has really done for me since, oh, Final Fantasy 10 or so.  Here, there was none to be had. This is just a 1980's, pre-Final Fantasy text-based RPG with some Friedrich Nietzche quotes thrown in. The plot twist toward the end of the game is trite and unmoving for anyone who has ever played a few video games or watched a few sci-fi movies.So why has this game blown up with so many gushing reviews? At the end of the game, the two developers left 20 minutes of commentary, in which they talk about their emotional and philosophical struggle creating the game, Friedrich Nietszche (who really has nothing to do with the game), and how the game changed the lives of blind people. Then they ask that you leave a review. Well, here's my review. Don't be fooled...

Here's my reply, again with a lack of empathy:

>How do you explain v1.5's 18 day streak at #1? There wasn't any developer commentary in that one asking people to review ADR. Lawyered.

Here are the YTD numbers for 1 star reviews:

- United Kingdom: 191 of 1081 (18%)
- Canada: 68 of 767 (9%)
- Singapore: 4 of 46 (9%)
- Australia: 51 of 605 (8%)
- United States: 557 of 8730 (6%)

Lesson learned. Don't release text based adventures to the UK. I've become numb to the words "rubbish", "bore", "scam/fake reviews", and "dreadful" because of the UK.

_Clones and the Spirit of Open Source_

Michael released ADR under MPL. And what do some do? They take what Michael built, wrap it in a browser control. They add advertisements at the bottom of the screen, and deploy it to the App Stores/Google Play as a free app. We've requested take downs for some of these apps. And they simply give us the finger by using the MPL as their defence.

It's frustrating, not that these apps exist, _but that these bottom feeding apps are being created by developers who went onto GitHub and cloned Michael's repo._ Michael said it best:

>I open-sourced A Dark Room exactly because I wanted people to be able to learn from it, and use it as a starting point for their own projects. That said, I'll admit to being a little disheartened that people are taking advantage of the brand that I've built to make a quick buck.

What these devs are doing is legal (outside of potential common law trademark violations, but that'll be a whole-nother entry). Morally, however, this goes against the grain of what open source is all about. And that, is truly heart breaking.

<a id="million"> </a>

**Aug 11, 2014: One Million Downloads in Seven Days** <a href="#million"><small>permalink</small></a>

It's been over a month since I've posted. I've slowly watched the rank and downloads of A Dark Room fall day over day. I thought there was a point where ADR's daily downloads would level out, but there really wasn't. By the end of July, A Dark Room was bringing in approximately 200 downloads a day. This is a level I haven't seen since [February where I did a 50% off sale](#pricedrop). Isn't that insane? A game that took the #1 spot for 18 days straight was now averaging downloads as if it were a game that just hit the App Store. I guess this shows again that you can't count on a consistent income from the App Store.

One thing was different however with these downloads. I was slowly increasing the price of ADR to $3.99. At this point, it was safe to assume that the game wasn't being "sold" by its overall game ranking (which was barely in the top 100), and most downloads (if not all) were coming from the fact that ADR was one of the top 5 RPG's. Here are some download numbers at each price point. You'll notice that there is _very little_ inelasticity in price (even for top ranking apps).

[ Date ] | [ Downloads ] | [ Price Point ] | [ Revenue\* ] | [ RPG Rank ] |
:------- | ------------: | --------------: | ----------:   | -----------: |
7/14     |           756 |            0.99 |         756   |            1 |
7/15     |           713 |            0.99 |         713   |            1 |
7/16     |           648 |            0.99 |         648   |            2 |
7/17     |           503 |            1.99 |       1,006   |            2 |
7/18     |           339 |            1.99 |         678   |            2 |
7/19     |           373 |            1.99 |         746   |            2 |
7/20     |           432 |            1.99 |         864   |            2 |
7/21     |           321 |            1.99 |         642   |            2 |
7/22     |           246 |            1.99 |         492   |            2 |
7/23     |           241 |            1.99 |         482   |            3 |
7/24     |           230 |            1.99 |         460   |            3 |
7/25     |           221 |            1.99 |         442   |            3 |
7/26     |           195 |            2.99 |         585   |            3 |
7/27     |           275 |            2.99 |         825   |            4 |
7/28     |           237 |            2.99 |         711   |            4 |
7/29     |           142 |            3.99 |         568   |            4 |
7/30     |           145 |            3.99 |         580   |            6 |

_\*Revenue before Apple's cut and before taxes take out a huge chunk of the earnings (made the math easier)_

You'll notice that while revenue stayed about level, my rank dropped. This is in line with what I've seen in the past (download count is king). So here I am sitting at the #6 spot, exactly [where I was five months ago before the game ever went viral](#top6). Looking through my dev logs, [I decided to do exactly what I did back then](#freeagain): I made the game free to bring in "new blood".

Then, the impossible happened. On day one of being free, ADR received 36,831 downloads. Day two, A Dark Room sky rocketed to 111,209 downloads. In 48 hours, ADR went from being ranked as the 329th app overall to the 32th. I decided to see how far ADR could go. On the third day ADR had passed Candy Crush, Clash of Clans, Kim Kardashian, and pretty much everything else. By the 7th day, A Dark Room was the #3 app in the App Store overall, out ranked by the Facebook Messaging App (which everyone was forced to download), and Crazy Taxi (which was being promoted by Apple at the time). Here are the download numbers for those 7 days:

- 8/1: 36,831 (went free mid day)
- 8/2: 111,209
- 8/3: 203,882
- 8/4: 223,006
- 8/5: 213,379
- 8/6: 187,014
- 8/7: 43,307 (flipped back to paid mid day)
- Total: 1,018,628
- Total Reviews: Jumped from 7,800 to 11,914 (4,114 reviews)

As far as media coverage, Pocket Tactics, 148Apps, and Touch Arcade wrote about this sale. Extra Credits was kind enough to tweet about it too (they rock). It's hard to say how much of an impact they really had to the download numbers given that [media coverage in the past really hasn't helped ADR](#zoe) (but I may be wrong).

Now the big question, what happened to sales when I flipped it back to paid? Well... I'm still collecting data. Will post again soon ;-)

<a id="alternateuniverse"> </a>

**Aug 20, 2014: What if ADR Was Written Using Cordova and Was Ad Based?** <a href="#alternateuniverse"><small>permalink</small></a>

It's something I've always wondered. What kind of fate would A Dark Room have had if I took the original web version, made it mobile friendly, wrapped it using PhoneGap, and added ads? What problems would I have come across? What kind of revenue would I have experienced. Well great news, one of my colleagues happens to be _god like_ with JavaScript and has recently released a puzzle game written in PhoneGap. I asked him to do a guest entry about his experience and what kind of ad revenue he's bringing in. Here it is!

_About Casey Foster_

During the day I am a web developer. I'm a core contributor on [Backbone](https://github.com/jashkenas/backbone) and more recently a huge fan of Facebook's [React](https://github.com/facebook/react). I use those tools daily to build and improve user interfaces at [OrgSync](http://www.orgsync.com). But while I love what I do at work, I've always had a passion for games and an itch to build and release a game of my own as a mobile app.

A couple years ago I first heard about [Cordova](http://cordova.apache.org) / [PhoneGap](http://phonegap.com) and I just about cried I was so happy at the thought of not having to first learn Objective-C and Java, and then write the same game twice in separate languages to release on iOS and Android. Even better, the only thing I had to learn was a language I was already pretty adept at, JavaScript, and a bit of HTML and CSS. Say what you will about JS, but it's ubiquitous and definitely has, as Crockford would say, its good parts.

_Then I tried using Cordova_

The problem I found back then was that Cordova was just too young. The project was evolving rapidly and the documentation always seemed like it was lagging. At the time, the preferred method of using Cordova was downloading a zip file with the Cordova libraries for iOS, Android, etc. and then creating an Xcode project, Android/Eclipse project, etc. and manually linking those libraries to their respective projects.

This was probably a less frustrating task for iOS or Android developers, but not being a traditional iOS or Android developer, I was faced with many hurdles in this approach. I repeatedly ran into a plethora of build problems and error messages I wasn't prepared to debug. At that time, Cordova was not the solution I had hoped for and I wasn't willing to fight the framework until it cooperated.

I kept an eye on Cordova after that, but without a solid app idea I didn't have a reason to try it out again.

Then [2048](http://gabrielecirulli.github.io/2048/) came out and swept across the internet. It inspired me to create a puzzle game and with inspiration of other awesome puzzle games like [Trainyard](http://trainyard.ca), Gunoki was born.

> Fun Fact: The original name for Gunoki was Colorflick, but that name was already taken in the App Store. The second attempt at a name was Colorcraze, which was available in the App Store, but not in Google Play, so that was out.  After staring into space and churning through possible combinations of English words for what felt like days, I decided to take the make-up-your-own-word route. Gunoki was suggested by my wife and is derived from the names of our two dogs Gunner and Loki.

_PhoneGap Build_

Since JS, CSS, and HTML were still my weapons of choice for app development, I continued to have my mind set on Cordova. Given my previous frustrations with Cordova, I decided to give [PhoneGap Build](http://build.phonegap.com) (cordova app building as a service) a try. The goal of PhoneGap Build is to allow developers to upload their app assets (JS, CSS, HTML, images, etc.) and let their service run each platforms respective build process. The shared (and platform-specific) settings for each build are stored in a special `config.xml` file. This means you can define the name, description, bundle identifier, etc. of your app in one place and have it set in the correct spot for each platform automatically. After each build completes, the developer is given links to the final `.ipa`, `.apk`, etc. files that can be used for development or distribution. Even better, PhoneGap Build also has a sweet API that allows this whole processes to be handled programmatically.

Oh yea, and it's free (for one private project and infinite open source projects).

Being a big fan of automation (`make` can do wonders), I wrote a task to compile my game assets with [cogs](https://github.com/caseywebdev/cogs), zip and upload the assets to PhoneGap Build, download the finished `.ipa`, and then upload that to [TestFlight](https://testflightapp.com) so my testers and I could try it out.

I also have to highlight a huge advantage to building apps with Cordova is that you can test in the browser, no compilation necessary. This allows for a very fast development cycle since you're just a page refresh away from seeing your latest changes. This doesn't mean device/emulator testing isn't still crucial, but it does help.

PhoneGap Build worked great for me, but eventually I hit one of its limitations that I could not work around. PhoneGap Build allows developers to register plugins. Plugins create a bridge between platform-specific code and unify it with a single JavaScript API. One of the plugins I needed was for [AdMob](http://admob.com), but PhoneGap Build's policy only allows plugins that are 100% open source.  Unfortunately, parts of the AdMob SDK are shipped as a binary, which makes a plugin wrapping that SDK disqualified for use on PhoneGap Build.

This was where I parted ways with PhoneGap Build. It was time to figure out how to build these `.ipa` and `.apk` files locally on my machine.

_The New and Improved Cordova_

I was pleased to find that since the last time I used Cordova they had created an [npm](https://www.npmjs.org) package to distribute their new [CLI](https://cordova.apache.org/docs/en/3.5.0/guide_cli_index.md.html). After looking over the updated documentation, it appeared the entire process had been drastically simplified.  In fact, it had reached the point where there was no need to even open Xcode or the Android IDE and complete the entire build process with command line tools.

Heading back to my handy dandy `Makefile`, I added tasks to create the Cordova project, install my plugins, and build both debug and release versions of my app, all with the command line. This experience was much better than the one I had initially with Cordova. With the exception of me needing to update my provision profiles and certificates, the builds that the cordova command line interface output worked great.

One gripe I've had is that some of the properties I've added in `config.xml` seem to be ignored, at least in Cordova 3.5.0. For example, there is a property called `orientation` that accepts `portrait`, `landscape`, or `default` (both).  This is great in theory, except that this value never seemed to be respected in my builds and I ended up writing a script to manually edit the `.plist` for my Xcode project.

Other than the `config.xml` quirks, I've found Cordova to be a great tool for web developers to create *native* apps. JavaScript performance on the latest mobile operating systems is always improving and I believe it is a great option for apps that don't necessarily need top performance to succeed.

_The Numbers_

As of writing this, Gunoki has been available in the App Store and Google Play Store for about a week. Since Amir has been so transparent with his numbers, it seems only fitting to do the same (albeit these numbers are much smaller!).

Gunoki's first week numbers:

[ Platform ] | [ Downloads ] | [ Impressions ] | [ Clicks ] | [ Revenue ] |
:----------- | ------------: | --------------: | ---------: | ----------: |
iOS          | 444           | 7,877           |     111    | 15.34       |
Android      | 22            | 781             |       8    | 0.38        |
Total        | 466           | 8,658           |     119    | 15.72       |

If you're interested in playing it, **[Gunoki for iOS](https://itunes.apple.com/us/app/gunoki/id905840087)** and **[Gunoki for Android](https://play.google.com/store/apps/details?id=com.coderiety.gunoki)** are both free to download. Enjoy!

_So What About A Dark Room, Amir?_

There was definitely a part of me that considered making the original web version mobile friendly, but [I originally chose to go native for the experience](#pickingdevenvironment). As for cross platform support, I lucked out with Ruboto and the eventual release of RubyMotion 3 (details on that will be another entry).

Now to answer the big question: What would ADR have made if it were free and ad based? I've already proven that [A Dark Room can be a top free app](#million). I also have a [time frame for retaining a top spot](#newnormal). And now I have some ad revenue numbers (thank you Casey). _So here is a really, really rough estimate of what ADR could have made:_

- Casey's super addicting puzzle game (_which you should download by the way_), has a 25% click through rate (444 downloads divided by 111 clicks).
- Each click got him $0.13 (111 clicks divided by $15.34 in revenue).
- You get _zero_ dollars for impressions.

So now let's apply that to A Dark Room's numbers.

- At its peak, A Dark Room received 223,000 free downloads in one day.
- During the peak in the paid section, A Dark Room received 20,000 downloads in one day.
- That's 10x the number of downloads in the free section versus paid.
- ADR's total paid downloads to date is 747,000 with a gross revenue of $522,900.
- If ADR were free, the ad revenue would be $242,775 (747,000 downloads, multiplied by a factor of 10, multiplied by 28% clicks, multiplied by $0.13 per click).

So, the good news is A Dark Room _was_ better off being a paid app. This also shows that the real money isn't in ads. It looks like all the top grossing apps make their money off of In-App Purchases. Welp. There you have it :-)

<a id="afteronemillion"> </a>

**Sep 27, 2014: After 1 Million Free Downloads, What Happened to Paid Sales?** <a href="#afteronemillion"><small>permalink</small></a>

Back in the beginning of August. [I made A Dark Room free for a week](#million). During that time period, ADR became the #3 App Overall in the free category. The only two apps that were ahead of ADR were the Facebook Messaging App, and Crazy Taxi (which was being featured by Apple). It's an incredible feeling to out rank the likes of Candy Crush, Kim Kardashian, and Clash of Clans. For that brief seven day period, ADR proved that a small game with heart can out rank games specifically engineered for IAP's.

After that seven day period, I made ADR a $0.99 app again. True, we didn't make any money during that seven day period, but maybe the _1 million_ new people that downloaded the game would carry over to paid downloads in some way. Here are the results after 45 days of watching the numbers and comparing it to the averages from before the "free week":

- When ADR went free, we got coverage from Extra Credits, 148 Apps, Reddit (r/AppHookup), and Pocket Tactics.
- ADR was priced at $3.99 before I made it free (this was on purpose so that sale syndication sites would see a more drastic drop).
- ADR became the #3 app overall gaining 1 million downloads and 4,000+ 5 star reviews.
- The free week was in celebration of ADR's upcoming prequel, [The Ensign](https://itunes.apple.com/us/app/the-ensign/id908073488?mt=8) and Michael's new game [Gridland](http://gridland.doublespeakgames.com/).
- Around August 25th (after ADR was already back to paid), another media sweep happened on Gridland which trickled over to ADR.
- School went back in session. This is big deal because it looks like most of the people that play ADR are people in middle and high school. I have no concrete evidence outside of the decrease in sales I saw back when summer break started, and then the rise when school went back in session.
- We received no requests for interviews when ADR was the #3.
- The 45 day paid downloads for the week _before_ "free week" was **~907 per day**.
- The 45 day paid downloads for the week _after_ "free week" was **~1,022 per day**.
- The 45 day paid downloads for the week _including_ "free week" was **~901 per day**.

There you have it. After 1 million free downloads, 5 to 6 publications, school going back into session, and two new games; ADR's 45 day average remains unchanged. Maybe all the events that happened above helped _keep_ the 45 day average where it's at (which is also not great news).

Now what? Well. There are plenty of things I still want to talk about:

- iOS 8 has come out, what's the upgrade rate going to be?
- iPhone 6 and 6+ have come out, what's the sales distribution going to look like?
- The Ensign is in the App Store and is currently the #3 game under the RPG category and was actually featured as a "Best New Game".
- What kind of sales can you expect from a follow up title? How loyal are mobile gamers?
- What's the status of the Android port (tl;dr; it's not going well at all).

Until next time, take care... Oh, by the way. If you are a student in middle or high school, Michael and I would love to speak at your school about game development and coding (either over G+ or in person if your school is close to Ottawa, Canada or Dallas, TX). So don't hesitate to reach out to us if you're class room is interested.

<a id="oneyear"> </a>

**Dec 7, 2014: The Ensign and One Year of ADR** <a href="#oneyear"><small>permalink</small></a>

October was a quiet month. Nothing really changed with regards to download rates or rankings. [I took some time to reflect](http://amirrajan.net/rant/2014/11/30/id-give-anything/), knowing that ADR's one year anniversary was coming up. Has it really been a year since [one of the worst days of my life](#worstdayofmylife)? What did I really accomplish since [I decided to sell most of my worldly possesions and re-focus](http://amirrajan.net/meta/2014/03/16/rebooting-life-part-2/)? I'll have a Rebooting Life Part 3 blog entry coming soon to explore that. For now, let's talk about the prequel and what YTD earnings are for ADR.

_The Ensign_

A Dark Room's prequel (The Ensign) was released at the end of August. I wanted to make a brutally difficult [Soulsian Adventure](http://killscreendaily.com/articles/ensign/). I absolutely loved working on it. I stayed up the first night, burning the midnight oil. I simply couldn't sleep while there was this itch to scratch.

Given the following ADR had, I was able to actually get some beta testers to play the work in progress. It really helped to have others try the game out, give me feedback, and find spelling and grammar errors.

I released the game in August when I felt like _most_ of it was complete. I knew the game had some rough edges, and there were still story elements I wanted to expand on (that plus a nasty bug I have yet to track down). I took the same approach with releasing A Dark Room. It wasn't 100% done. iPad support wasn't there, some of the balancing and pacing wasn't perfect, and [story line progression left a few people stuck](#slaves2). But I released. A part of me was glad I took this approach, and the other part feels it was a mistake.

The first version of The Ensign received relatively lukewarm reviews from both [Kaijupop](http://kaijupop.com/2014/08/ios-quick-vid-ensign/) and [Touch Arcade](http://toucharcade.com/2014/08/22/the-ensign-review/). The Ensign was something I created on my own (the brilliant Michael Townsend was busy with [Gridland](http://gridland.doublespeakgames.com/)), so I was definitely struggling with imposter syndrome when those reviews came out.

**I really believe that game development is becoming more iterative. With digital media, it's incredibly easy for developers to fix problems and incorporate feedback. Given this, the current approach editors take to reviewing games is broken. While the game can improve, pivot, and grow, the lukewarm reviews are solidified in stone, rarely to be revisited.** I completely agree with Kaijupop and Touch Arcade, the _first_ version of The Ensign was not that great, but the _fourth_ version released over another _two_ months is consistently getting 5 star reviews. Here in lies my mistake, when you are a nobody like I was when I built ADR, it wasn't a big deal to iterate "live". But when you have a successful game out there, you're in the crosshairs, and have to execute _flawlessly_ (which is impossible).

That being said, when I released The Ensign, Apple featured it in their _Best New Games_, and _What We're Playing_ syndications. This led to The Ensign becoming the #8 game overall and pushed A Dark Room to the #7 spot. At first, I thought that download rates dictated if you were to be featured in _Best New Games_. **I thought it was an automated, software controlled syndication. Turns out it (probably) isn't.** There were two games that were also featured, and  sandwiched The Ensign in rankings. _The Firm_ sold for $0.99 and was ranked as the #1 game, and _PAC-MAN Friends_ selling for $2.99 was ranked #15 (The Ensign was #8 and sold for $0.99). For about a week, all three games were on the _Best New Games_ featured list. After that week, The Ensign was _removed_, but the other two games were still featured. I have no idea why this was done given that even the first version of The Ensign had higher ratings than the other two games (and was sandwiched in rankings... see now I want to have a yummy sammich).

I'm working on one more prequel. At one point, I wanted to just release a free blank app with an audio file stating my intent with the "pre-prequel". It would get a place holder out there, direct some App Store traffic to A Dark Room, and give me the opportunity to _iterate_ publicly on it. I don't think I'm brave enough to do that though. So for now, I'm operating under the unrealistic expectation of a flawless game being released, day one. That's all I have with regards to The Ensign, now lets talk about A Dark Room.

_A Dark Room After One Year_

Here is the (approximate) YTD revenue for A Dark Room, an app that took the #1 spot across the United States, United Kingdom, Australia, Germany, Canada, and Singapore.

[ Month ]    | [ Paid Downloads ] | [ Free Downloads ] | [ Apple Check ] |
:----------- | -----------------: | -----------------: | --------------: |
Nov 2013     | 403                |                    |           555   |
Dec 2013     | 698                |                    |           943   |
Jan 2014     | 986                |                    |         1,320   |
Feb 2014     | 2,288              | 8,612              |         1,760   |
Mar 2014     | 15,428             | 15,172             |        11,600   |
Apr 2014     | 305,000            |                    |       214,000   |
May 2014     | 237,000            |                    |       166,000   |
Jun 2014     | 101,000            |                    |        70,700   |
Jul 2014     | 29,526             | 5,110              |        22,200   |
Aug 2014     | 38,304             | 1,021,660          |        28,800   |
Sep 2014     | 28,400             |                    |        19,900   |
Oct 2014     | 14,900             |                    |        10,100   |
Nov 2014     | 5,040              | 134,959            |         3,790   |

The November 2014 paid downloads is not a typo. I made a mistake by making the game $1.99 again, and it destroyed our ranking in the RPG section. Lesson learned. I also made the game free for the first week of November in celebration of the one year anniversary (which I was happy to do, but that didn't help our rank either).

Total downloads (free and paid) is 1.96 million with a gross revenue of $553,000 (Apple has already taken it's 30% cut before issuing the checks). I started work on the app at the end of June. Here is the 16 month breakdown (4 months of development with no cash flow, and 12 months of income):

[ Month ]                                                 | [ Amount ] |
:-------------------------------------------------------- | ---------: |
Gross income (less Apple's share)                         |   553,000  |
My half of ADR (I happily give Michael his share)         |   276,500  |
33% income tax                                            |    91,245  |
12% self employment tax                                   |    33,120  |
Net                                                       |   152,135  |
Net per month (16 months from development to today)       |     9,508  |
Hourly (40 hrs, 48 weeks) doing ADR "full time"           |        59  |
Net hourly rate when I actually was working full time     |        51  |
16 month difference between ADR and 9-5                   |    14,280  |
Self employed medical insurance (wife was 1099 too)       |    10,880  |
*Grand total for making a #1 App*                         |    *3,400* |

There you go. You can either go to school, graduate from college, and (over a 7 year period) earn a pretty much guaranteed income. Or you can _try_ to team up with a friend, make a #1 app, and end up a _whopping_ $3,400 ahead (with no guarantee of future income)... I'm telling you now, ADR's success is a complete utter fluke, don't expect this for your app.

But, what have I learned about myself? I've learned that I have grit. I've done interviews with companies and they usually are unimpressed with my algorithmic/code related problem solving skills. But I have an endless reserve of sheer determination, intuition about software development, and the ability to _lead_... all of which is impossible to show in a couple of phone interviews and a one hour pairing session. I've learned that even though I can be _happy_, I will never, ever be _content_ (more on that in my Rebooting Life Part 3 entry).

As for what I've learned about the App Store... not a god damn thing. I still don't understand how [A Dark Room went viral in the UK](#minecraft). I don't understand how it became the [#1 app in the US](#number1us). I still don't understand how [A Dark Room got 1 million downloads when it went free](#million) (especially since I made it free again in the first week of November 2014, and didn't see that kind of download rate). I don't understand why A Dark Room is going viral _again_ in the UK _right now_ (yes, it's getting [one star reviews again](#topappday2)).

_What's Next_

This will be my last post here (unless something really amazing happens). I want nothing more than to be able to create worlds you can escape to. I don't think I'll stop building games anytime soon... nor will I stop writing and blogging. Subscribing below will be for my main blog. May the fire burn brightly for you. May it keep you warm.

<hr /> <!-- put next entry above this line -->

<link href="//cdn-images.mailchimp.com/embedcode/slim-081711.css" rel="stylesheet" type="text/css"/>

<div id="mc_embed_signup">
  <form action="http://amirrajan.us8.list-manage.com/subscribe/post?u=61936e0179df5da623ee7cdb7&amp;id=f44fb947df"
      method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" novalidate="novalidate">
    <label for="mce-EMAIL">Subscribe to Amir Rajan's Blog</label>

    <div>Subscribe to get high signal, low noise entries with regards to software development, doing what you love, and never being content with where you are.</div>

    <div><br/></div>

    <input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="email address" required="required" />
    <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button" /> <small>powered by MailChimp</small></div>
  </form>
</div>

<script src="/assets/themes/jquery.js"> </script>
<script src="/assets/themes/rank.js"> </script>
