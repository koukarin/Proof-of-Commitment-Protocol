# Proof-of-Commitment-Protocol

First of all, let’s consider the Proof-of-Work (PoW) and Proof-of-Stake (PoS). These consensus play
two key roles :</br>
• Secure the blockchain </br>
• Participate to the emission and distribution of the coins / tokens.

Of course, we, the ErgOne team, don’t have the pretension to beat the perfection of Ergo and its
Autolykosv2 in terms of security and efficiency. But we have thought of an innovative way to mint
and distribute tokens far away from hashrate (energy power) or staking (financial power).

As a Community Fan Token, we believe that commitment in a project or ideals is a new kind of
power mixing time, personal energy and creativity. It was therefore normal for us to try to create a
protocol based on this power.

We have therefore designed the Proof-of-Commitment Protocol (PoCoP) to issue and distribute the ErgOne
tokens in order to reward the most active and committed into the promotion and support of Ergo.

Because we are confident that Ergo will establish itself in the blockchain ecosystem, we think the
mission of ErgOne is intended to be evolving. That’s why we plan a way, in the long run, to permit
the community to vote for one or more other projects to support.

But it’s time now, to clarify what is the Proof-of-Commitment Protocol precisely.

## Genesis of the Proof-of-Commitment
As we’ve just said, supporting a project involve time, creativity and energy. And unfortunately, this
commitment is based on the passion of just a few mainly because there are no incentives to spend
efforts on it.

In parallel, we can observe that a lot of passionate content creators commit on the long term on
different niche markets. Of course, they are excited by their sharing but they can keep faith also
because of advertising revenues and partnerships with companies. We can observe this trend on
platforms like Youtube but also in all kinds of social media. And there’s sometimes a gap between
what the content creator is preaching and the products he promotes.

In view of this observation, we have decided to incentive the commitment of the community in the
promotion of a project that will change the entire world : Ergo.

The ErgOne token is dedicated to push the community members to highlight Ergo but, in a few
years, other projects nominated in a total decentralized way.

## Incentives
First of all, we plan to reward the active members on Twitter and Youtube. We will allocate these
rewards monthly and on the basis of a virality score of each content creator.
On both platforms, we will share 5000 ErgOne every month and we will divide this amount
by 2 every two years. So, halving happens every two years.
December 2022: 5000 ErgOne shared per month and per platform
December 2024: 2500 ErgOne shared per month and per platform
December 2026: 1250 ErgOne shared per month and per platform
…
until there’s no more ErgOne to distribute.

In parallel, transaction fees will replace gradually and partially the rewards decreasing. These fees
will come from different services like the ability to tip your best influencer or content creator and
many other ways to support the protocol.

The rewards will be directly linked to the virality score.

## Virality Score and Individual Maximum Rewards.
### Virality Score Calculation
During the first years, the target will be to promote the cryptocurrency Ergo all around the world.
So, only content from members community and with the hashtag Ergo (#ergo, #Ergo, #ERGO…)
will be integrated to the virality score.

On Twitter, the virality score is the sum of retweets and likes divided by 10 for all the tweets
published with #ergo during the previous month.
<p align="center">viralityScore = retweets + (likes / 10)</p>
On Youtube, the virality score is equal to the sum of likes and views divided by 5 for all the content
published with #ergo during the previous month.
<p align="center">viralityScore = likes + (views / 5)</p>
We decided to NOT reward the members proportionally to their virality score. Indeed, on most
social media platforms, 0.5% of content creators grab 99% of the revenues.

We have decided to create 4 groups ; each composed by 25% of the members.
The first group with the highest virality score will share 60% of the rewards.
The second group with the virality score just underneath will share 25% of the rewards.
The third group will share 10% of the rewards.
The last group will share 5% of the rewards.

Decreasing the rewards to the most famous influencers and sharing them by quarters, prevent
everyone to think about earning ErgOne Tokens for a living. So, this kind of distribution permits to
avoid cheaters who could be tempted to buy false views, likes… ErgOne aims to become an
incentive for the community members and create organic growth.

We don’t want content creators to shill Ergo (or other projects) for the rewards only but because
they believe in it on the long run. ErgOne is owned by the community for the community.

In the same time, we want to express an eternal gratitude to the 2 members who will have obtained
the best virality score on Twitter and YouTube during the month. That’s why, we plan to engrave
their commitment on the blockchain. So, in addition to their rewards, each of these 2 members will
receive one priceless NFT. Through this gift, they will have a place in the history of Ergo… and
soon, in the history of the other community projects.

But, because we want a fair distribution of the rewards, only to people who really care about the supported project, we have to face two obstacles : Spammers and bots.

### Tackle Spammers
We really want to avoid the community being encouraged to over-tweetwith the hashtag supported (e.g. #ergo).

For this reason, we’ve decided to count tweets which author presents a normal activity. So if he/she tweets more than 28 times a day, it will be considered as a spam.

Obviously, we know that hardcore tweeters naturally exist. That’s why we won’t punish people who tweet more than 28 times a day. But some of these tweets may not be counted.

### Tackle Bots
Twitter and YouTube host some bots that can produce misleading results. Some technical tools already exist to detect bots.

Unfortunately, they’re not absolutely perfect and the Proof-of-Commitment Protocol can’t be at the mercy of a company that finds a way to develop undetectable bots.

Because we don’t want to enter a technological race, we have decided to design the protocol in order to make bots unprofitable.
Firstly, the distribution is not proportional to the virality score. For e.g.: the 25% most active on twitter will share 60% of the monthly rewards (the first year: 5000 ErgOne).

Then, users have no idea how many likes, retweets or views are needed to be present in this group. If they underestimate the required engagements, they can take place in the second group that share 25% of the monthly rewards. If they overestimate the required engagements, they will overpay a social media bot company.

Now, let’s imagine ErgOne become rare and precious, and its value makes profitable to overpay a bot company.

We have added a mechanism to avoid that phenomenon.

Indeed, we plan to share 5000 ErgOne during the first two years. Therefore, the 25% most active users will share 3000 ErgOne (60% of 5000). Cheaters could take profit just using bots if the individual rewards are important.

So we have implemented a limit: the Individual Maximum Rewards.

Here is the calculation of this limit:

PPE = pay per engagement *(average price of bot companies / 2 => today: 0.01$ / engagement)*

ErgOnePrice = ErgOne price *(ErgOne / $: value from Spectrum)*

VS = the virality score minimum for being in the first group (25% most active). We consider the worst case: the cheater had a maximum of luck and paid a bot company to have exactly the minimum amount of engagement for a maximum amount of reward. If he is profitable, all other cheaters could also be profitable.

<p align="center">Individual Maximum Rewards = VSm * PPE * ErgOnePrice</p>

Then, the Individual Maximum Rewards represents the individual rewards acceptable for being sure that no cheater could have been profitable.

- if the Natural Rewards of the 25% most active < Individual Maximum Rewards: rewards will be distributed following the process explain in the “Incentives” paragraph.

- if the Natural Rewards of the 25% most active > Maximum Rewards:
	- The first group (the 25% most active people) will earn: the Individual Maximum Rewards.
	- The second group will earn: 42% of the Individual Maximum Rewards.
	- The thirds group will earn: 25% of the Individual Maximum Rewards.
	- The last group will earn: 8% of the Individual Maximum Rewards.
  
With this mechanisms, bot use will never be profitable.

## The Architects
The challenge will be tough to keep cheaters and spammers away from the community because
incentives can also attract bad intentions.

Indeed, even with a fair distribution and a community spirit, some people will try to divert the
project for their own profit.

This threat will be hampered by the algorithm design. But in reality, it can only be prevented by a group of passionate members involved in the community.

This group has to build and protect the pillars and the core values of the projects that the members
have decided to support *(Ergo during the first years)*.

### Who will be the Architects ?
We won’t be able to rely on them at the beginning of ErgOne. So, during the first months, the
founders will be the architects.

And month after month, the community members who will obtain the best virality score during a
month and will receive an NFT will be part of the Architects.

We should also involve the most committed members in the ErgOne economy. So the most
important hodlers and those who bought rare NFTs will be part of the Architect Team.

In this way, we will create an eclectic group culturally and economically staked. Such diversity will
provide solid foundations for ErgOne in a long-term perspective.

### Roles of the Architects
Being an Architect involves wide responsibilities. As just said before, they are in charge of
protecting the core values of the community and tackling the cheaters and spammers.

So, each of them will have to inspect some content that the ErgOne algorithm suspects of being
spam.

Indeed, the temptation could be important to cheat. And we have no doubt that some malicious
members will try to insert #Ergo even if their content deals with angling.

The members tagged as spammers will be banned from the reward
mechanism.

### Incentives for the Architects
As a key role in the Proof-of-Commitment protocol, the Architects have to be also rewarded. When
the decentralization of this kind of moderation will be effective, Architects will receive a part of the
rewards.

This portion of the monthly rewards will be defined later by the community.

## Long Term Governance
Because we are confident in the Ergo’s capacity to become a Top 10 cryptocurrency, we think that,
one day, Ergo won’t need ErgOne anymore. And then, the ErgOne Community will be willing to
face new challenges supporting projects chosen through a democratic path thanks to the Proof-ofCommitment Protocol (PoCoP)
