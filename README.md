# The Riot-Beggar-Bot

A simple and straight-forward Python script that autoruns every 24 hours to send a direct message to the [@PlayValorant](https://twitter.com/PlayVALORANT?s=20&t=VSGxu2r_sdnxOfU-v3gxXw) account and annoy the **ever-living shit** out of their social media team (for a good cause).

## What and why the hell?

> valarante child game.... look to cartoon grapfix to make kid player happy like children show.. valarante cartoon world with rainbow unlike counter strike with dark corridorr and raelistic gun.. valarante like playhouse. valarant playor run from csgo fear of dark world and realism so need child game to relax

[Valorant](https://playvalorant.com/en-us/) is a popular 5v5 free-to-play first person shooter with a timed rotating shop that cycles through new bundles of skins for in-game weapons. For real-world money, users are able to purchase skins for their own weapons, either individually or in themed packs of five. However, there are a total of 18 weapons available, so users will typically have multiple themes and weapons that do not go together if they decide to purchase skins for each weapon in their library.

![The most beautiful skin bundle](https://static.wikia.nocookie.net/valorant/images/f/fa/Bundle_Nunca_Olvidados.png/revision/latest/scale-to-width-down/1000?cb=20211019170213)

> The Nunca Olvidados Collection is a collection of cosmetics in VALORANT. Its contents were initially available to be obtained when the collection was first released as a bundle in the Store. After this, only its weapon skins can be obtained whenever they become available in a player's daily offers from the Store.

> The collection is inspired by the Mexican holiday "Día de los Muertos" (Day of the Dead) and its name translates to "Never Forgotten" from Mexican-Spanish.

For patch 3.08, the [***Nunca Olvidados***](https://playvalorant.com/en-us/news/game-updates/the-origins-of-valorant-s-nunca-olvidados/) skin bundle was released for five weapons: the Vandal, Ares, Frenzy, Bulldog, and Knife. Given that there's eighteen weapons and only five of those weapons actually have the ***best skin in the game***, it's only morally and ethically correct for them to release skins for the remaining eighteen weapons (especially for Viper mains who use the Phantom) (_that's me_).

After days of trying to figure out how to get in contact with a $21 Billion dollar company in order to communicate my absolute need for another _Nunca Olvidados_ bundle, I arrived at my final conclusion: It is most likely impossible to do so **legally**. Therefore, I opted to do the next best thing: repeatedly ~~harass~~ direct message the very ~~unfortunate~~ understanding Valorant Social Media managers/interns via Twitter.

## How?

First, I purchased a Raspberry Pi Zero W for $10, installed RaspberryOS on it, and connected to it via SSH and VNC. Next, I created a Twitter Developer account, and utilized the Twitter API to obtain Keys, Tokens, and Secrets to allow my personal account to connect to the bot and directly message other users on Twitter with their user ID. Finally, I created a Python script that cycles through a massive list of direct messages to send everyday at 12:30PM CST. The whole thing took less than a day, surprisingly. It's easier than you think and that's kind of **scary**.

## What's the goal?

To get Riot to add more weapons with the _Nunca Olvidados_ theme or to get blocked from all of Riot's social media accounts. Whichever comes first.

### Disclaimer

I did not purely create this bot to annoy the Valorant Twitter account and get more _Nunca Olvidados_ weapons (although that was a large chunk of it), but I also wanted to create a tiny single-function bot in order to become more familiar with the Raspberry Pi and the Twitter API.
