---
layout: page
subheadline: "Twitter Bot (Genny) and Discord Bot (Rebecca)"
title: "FEH Gauntlet Bot V2: Electric Boogaloo"
teaser: "A bot for Fire Emblem Heroes that sends notifications when your team is losing during Voting Gauntlets!."
header:
    image_fullwidth: "header_fell_star.jpg"
    caption: An Ancient Being of Unlimited Knowledge
    caption_url: "https://fireemblem.fandom.com/wiki/Sothis"
image:
    thumb:  projects/fell-star-archives/icon_fell_star_archives.jpg
    homepage: projects/fell-star-archives/icon_fell_star_archives.jpg
categories:
    - projects
tags:
    - projects
author: OhKairos
show_meta: true
---

Hey you, glad you could make it! Now, where have we been since our last post?  

[Original Blog Post Here on Old Website](https://ohkairos.github.io/projects/feh-gauntlet-bot/)

## Did You Set It to Wumpus? (Discord Integration)  
The main reason for this post is to explain why FEH-Gauntlet-Bot has moved from Twitter to Discord for all future updates. The reasoning is simple: there was once upon a time that the bot got suspended with no justification from Twitter support. When we sent a case to appeal, it was approved without any context as to why. Subpar Twitter experience aside aside, it was then I realized I had no means of communicating to my users that the bot was unusable! To remediate that, I make a decision to open up a discord server with the same functionality as the original twitter bot, but with two key differentiators:  
* On the Twitter Bot, you received alerts for ALL TEAMS, ALL THE TIME. Most people only have one FEH account, so it was generally annoying receving those alerts. Discord has roles you can ping individually, so this solved one problem. Discord is also a highly mature appplication with LOTS of customization for bot developers, which we will talk about a bit below.
* The community around FEH-Gauntlet-Bot is LOVELY :heart: . The bot and by extension us running it isn't always smooth, but we've received several lifetimes worth of support and forgiveness. It was nice, and we was wanted to put a face to us at Atemosta for an even more familial experience. 

## No More Birbs? (Will You Still Be on Twitter?)  
The Twitter Bot will continue to run as normal, but will no longer receive any updates. Discord has proven itself to be a better platform overall for us, but we don't want to burn all the OG users who don't want to install additional applications or create additional accounts if they don't want to. 
  
## Future Genny (Upcoming Features)  
This is the fun part! Remember that community bit we was preaching about earlier? There are lots of things we at Atemosta want to do so we can reward those members who want *more* out of the FEH-Gauntlet-Bot experience, so we have a couple of features on the burner (in no particular order of importance): 
* Integrating or creating a score prediction feature for users who are on teams who rarely get multipliers (Looking at you, Team Ike)
* Creating a more streamlined way of recruiting allies for the VG to ensure your victory in these crucial battles. Users who have AWESOME units can be nominated for community rewards known as Tempest Tokens (more below).
* Betting on Voting Gauntlet outcomes with Tempest Tokens 
* Replicating the whole VG experience via Discord! This will give a chance to see how you fare had you been on another team within the true FEH VG (Tempest Tokens up for grab here too!).

## Joshua and the Tempest Treasures (Tempest Tokens)
[Full Article Here: Tempest Tokens]({{site.url}}{{site.baseurl}}/tempest-crossing/tempest-tokens/)
Atemosta is a bootstrapped entity focused on creating solutions for people like us (hyper-JRPG nerds). Our premise is simple: create simple and elegant solutions using existing technologies, and flourish a community around these solutions. Since we LOVE  you all so much :heart: , we decided to create a community reward known as Tempest Tokens. 

A preview into the future, Atemosta hopes to create enough passive-revenue streams so we can focus on our true desire: to build out a [fully-fledged VR JMMORG]({{site.url}}{{site.baseurl}}/tempest-crossing/) with homages to our favorite games. To reward early users of our solutions, we have created a cryptocurrency known as Tempest Tokens. It runs on XLM (more details in our white paper [TODO: LINK HERE]), but what's neat about this blockchain is two things: how fast it runs, and how easy it is to swap tokens on-chain. Through this amazing technology, we plan to create a myriad of tokens and prize redemptions for our early users in order to make an even more polished and streamlined experience for future users!

Now Joshua... why Joshua? Joshua is known as a notorious gambler and Tempest King of FEH 8: Sacred Stones. For those willing to play his games, we distributes Tempest Tokens to community members participating in FEH-Gauntlet-Bot related events, and as of now these Tempest Tokens can be redeemed for [Discord Rewards]({{site.url}}{{site.baseurl}}/tempest-crossing/tempest-tokens/atos-vg-rewards) and physical items in our [ATOS Secret Shop]({{site.url}}{{site.baseurl}}/tempest-crossing/tempest-tokens/atos-secret-shop). 

## Can I Haz Tempest Tokens?
Most will be given out for free as a thank you to our community, but for the more passionate of the bunch, we are willing to sell them too. **Note**: it is ***HIGHLY INADVISABLE*** to buy these as the value created by our solutions is pretty small at this moment in time, but if you are still intrgued beyond that, send a direct message to `OhKairos#4545` on discord or send an email to ohaiyo+atos@atemosta.com for more details. 

## Back to Work, Techie (What's Under the Hood)
This bot has come a LONG way since it was first coded up in college. A lot of improvements have already been implemented, such as:
* A Docker container that contains all the bot code and dependencies (minus API credentials), ready to deploy anytime and anywhere!
* A Travis CI integration for automatically unit testing changes to code and ensuring that they (probably) won't break anything  
* A Discord bot! 

On our tech backlog are more mature integrations as well:
*  Convert FEH-Gauntlet-Bot to a web service via Docker Containers 
*  Migrate the bot architecture to run off Kubernetes
* Create an ELK stack as a Docker container for logging bot functions and health monitoring   
* Secrets Integration via HashiCorp Vault

## Here's to You, Kid
Wow! You read the whole thing! You must really like us! :blush:
Thank you as always for supporting us, and we look forward to our future adventures together! 