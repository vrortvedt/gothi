# gothi
Code for strategy game Gothi

A stakable multiplayer simultaneously-reconciling turn-based strategy conquest game and blockchain based ecosystem

April 2018
sagadapps.io

TLDR 
Gothi is a conquest strategy game set in 9th Century Iceland, where players develop alliances and utilize information warfare, with successful players earning cryptotokens that form the basis of the Gothi ecosystem 

GAME PREMISE

It is the year 874.  Iceland’s settlement has begun.  There is no king and no central government.  
Powerful gothi, or chieftains, vie with one another for power and justice.  Alliances among the gothi must be formed to survive this dangerous world, but within every apparent ally lurks the possibility of treachery, with fatal consequences.  

You control one of seven Gothi.  Each gothi commands two units - a company of Kinsmen who wield the sword and the shield to protect your interests, and a Skald, or poet, who wields information as a potentially game changing weapon in your arsenal.

The seven Gothi all have the same resources and positioning - distance matters not, nor does the luck of the draw or the roll of the dice.

The Gothi’s choices are all that matter for survival - how to deploy Bannerman to assault, defend or reinforce - how to deploy the Skald to gain allies, undermine foes or plot grand betrayals - who to trust among the other Gothi - what to disclose about your knowledge and your plans and what to keep secret - whether to pursue victory through honest and lasting alliances or whether to betray another Gothi’s trust at the moment of maximum consequence.  Survivors earn GothiCoins from those that are vanquished.

Welcome to the world of Gothi.

BACKGROUND

The Quest for the Perfect Game 

My gaming life has been rich, but I’ve always believed that a more perfect game was out there.  In a sense, games are about a balance between the rigidity of rules and the freedom to choose.  In the simplest children’s games, this balance is heavily weighted to the former.  

The freedom in Candy Land or Chutes and Ladders is basically limited to choosing which physical avatar to use in the game.  From then on, it is an inexorable march to the finish line, controlled by the roll of the dice and the distribution of arbitrary rewards and penalties.  Strategy and player choices are non-factors.

On the other hand, too much freedom in gaming can erode a sense of purpose or consequence.  A poorly conceived DnD mission or an open sandbox game that feels too open can devolve into unfocused purposelessness.  The sweet spot is a game design that maximizes choices while keeping the players sharply focused on their goals within the universe of the game.  

Everyone’s sweet spot is different, but Gothi is my attempt to create a gaming protocol that is rigid enough to be easily playable but which encouraged the type of imaginative engagement with its possibilities that leads to a state of flow.  

Source Material

The game theory basis of Gothi comes from the board game Diplomacy.  Diplomacy is a multiplayer WWI conquest board game with no dice, very simple combat rules and a simultaneous turn reconciliation.  However, the real genius of the game is the negotiation phase  where subgroups of players are encouraged to find private corridors to plot and strategize before entering orders for their units to execute.  Basically you exchange in-game gossip, trade promises and try to get other players to support your goals by convincing them you will support theirs.  Orders about troop movements are submitted in secret, and then reconciled all at once to determine how the board had changed.  At reconciliation, betrayals are revealed, conquests achieved while other efforts fizzle out.

I played Diplomacy only once, in 2003, and didn’t come close to finishing the game after 7 hours of play.  Yet to this day, that incomplete session remains one of the most immersive gaming experiences of my life.  While the actual pledges as to future actions could get complex, the game boiled down to the simple, pure beating heart of game theory - whether to cooperate or defect, and under what circumstances.

But as anyone who has played Diplomacy can attest, it is not without substantial flaws.  First, getting seven people to commit to a 10 hour plus board game session is impractical for all but a very few of us at very specific times in our lives.  Second, reconciling each players’ orders every turn to figure out what happened was time consuming and complicated.  Third, the preexisting information and impressions friends had about one another could make the game more intriguing, but it also could be hazardous to relationships.  Beyond just the in-game betrayals, which were harrowing enough, a disclosure to friend B that you think you can trap friend C because of his unthinking rashness might make it back to friend C, and then there’s an IRL breach that could wreck a friendship. The game appears to be most immersive when it skirts just above the line where it will have IRL consequences.

In the years since, I’ve thought about ways to keep the immersive flow of Diplomacy while minimizing its flaws.  The popularity of Settlers of Catan reignited my interest in game design - while it could be a great game, I sometimes felt that it could fall into the Monopoly trap where luck (via dice or card draws) could play an outsized role in determining victory among competent players.  

Further, it’s my view that most games that allow cooperation between players (e.g. trading resources in Catan), selling don’t have sufficient incentives to overcome the inertia towards non-cooperation.  Fantasy football allows trading rostered players, and a robust trading market among would make for a more engaging experience.  But the effects of the waiver wire (allowing attempts to bolster one’s team without the appearance of aiding any other teams), and the endowment effect where players overvalue the players on their own roster.  The solution is a game design that makes it nearly impossible to win without cooperating with other players.

The final inspiration came from a story about an innovative use case at an Ethereum meetup in Washington DC in early 2018.  Consensys’ John Wolpert told the story of the development of MeThree by a young coder who wanted to address the plague of sexual harassment and abuse that had become part of the zeitgeist in 2017.  Recognizing the disincentives to a victim being the first to come forward, but also the liberating power of numbers, MeThree allows a victim to record details about the abuser and the nature of the misconduct to the blockchain and through control of the private key, be able to have a timestamped record of the event that he or she alone could access.  Yet if three separate people record misconduct by the same person, MeThree automatically places them in an anonymous chat to signal that they are not alone and give them a safe forum to discuss what they would like to do about the situation.

While a compelling case for a blockchain-aided more just future, MeThree’s recognition that semi-private communication channels, even among anonymous strangers, could overcome the inertia against action.  It got me thinking about an environment with competing communication channels and the game theoretic potential of asymmetric access to information.  But the conception of a system where every communication channel connects a player to both a competitor and a potential ally seemed to cause the game theory gods to nod in approval. 

Why Settlement-era Iceland?

As for the name and the setting, the settlement of Iceland in the late 9th century to early 10th century is a fascinating period that we know about through the Sagas - the literature of the bloodfeuds and disputes and codes of justice of that era.  Written in an unsparing way, the Sagas are infused with an existential worldview that has more in common with noir detective fiction than with medieval tales of chivalry.  

I am indebted to Professor William Miller of the University of Michigan Law School for sharing this wonderful literature with me through his class Bloodfeuds.  Professor's Miller's appreciation for this wondrous period of human civilization was contagious.  Here's the cliff notes explanation as to why.

Iceland, throughout its thousand year history, has never had a king that ruled over the island.  Yet it was not in a state of anarchy.  The Gothi had a law code, and met every year on neutral territory at the Althing - an annual fair, market, forum and convention - to resolve disputes and seek justice for wrongs committed in the past year.  Both physical power and clever utilization of the law were necessary to prevail in disputes - neither was sufficient on its own.  While this system was not perfect by any means, it worked better than one familiar with governance by a strong central authority might imagine.

Hybrid Warfare

Gothi’s combat design is dead simple.  There are seven Kinsmen units in the game - when they clash,  1 beats none, 2 beats 1, while equal numbers result in a draw.  Every player begins with a single Kinsmen unit, so a single player can’t conquer anything without help.

In contrast to the simple combat rules, the information war aspect of Gothi has limitless permutations. Gothi allows players to make one-on-one contact with other Gothi, and communicate via chat program.  At the start of the game, no Gothi are in contact with each other.  By deploying the Skald Contact order, a Gothi will open a line of communication with a random uncontacted Gothi and will then be able to chat with that Gothi for the remainder of the game. 

The design goal is that the elementary combat mechanics will generate deep diplomatic intrigue in a world of limited information and uncertainty about the trustworthiness of the other players.  It’s hybrid warfare where information, wielded expertly, becomes much more deadly than the sword.  

GOTHI GAME DESIGN

Goal

The goal of Gothi is to survive to the end of the game.  Surviving Gothi earn GothiCoins (an ERC20 token or successor standard), which may be traded on exchanges or used to buy into higher stakes games of Gothi.  Vanquished Gothi earn nothing.  Seven new GothiCoins are generated in a standard game of Gothi.  A sole survivor who wins a domination victory earns all seven GothiCoins.  If two Gothi survive and agree to a negotiated peace to end the game, they may agree to split the coins evenly at 3.5 apiece, or may agree to an unequal split of 4/3, 5/2 or however they both agree to split the proceeds.  Any number of Gothi may agree to end the game at any time, but may do so only when all Gothi are unanimous about the allocation of the GothiCoins.

Game Overview

Gothi is a turn based game, but players do not take turns sequentially.  Instead all players secretly submit their Orders for two types of units that they control (Kinsmen and Skalds) by a specified deadline, which occurs after a negotiation period where Gothis that have established contact with one another may communicate. After the Orders are submitted, they are processed and reconciled against each other and put into effect simultaneously, generating a Report for all players to review.  Then the next turn begins.

Kinsmen are able to capture territory and vanquish Gothi from the game, and they are able to defend against attacks.  Skalds are information warriors, and may engage in a wide variety of acts of surveillance, concealment, disruption, revelation and other dark arts.  

The game ends when either a Gothi vanquishes the other six players, or when all remaining players reach an agreement as to the terms for peace.

Turn Structure

Each turn in Gothi comprises four phases.
Open Comms - players may communicate with other contacted Gothi via one-on-one chat windows or Comms - typically this phase will comprise about 75% of the time of each turn
Order Entry - After Open Comms closes, Orders for Kinsmen and Skalds must submitted before the Order deadline - while Orders may be submitted and changed during Open Comms, there will be a short period after Open Comms for Order Entry that accounts for approximately 5% of the time of each turn 
Reconciliation and Report - each Gothi’s Orders are processed and reconciled - a Report in the form of an auto-published mock newspaper that describes the turn’s events and each Gothi’s Orders is published to each player - this is typically instantaneous, but may be delayed 
Solitary Analysis - Subsequent to the issuance of the Report, there is a period of time prior to Open Comms when players have time to digest the Report and strategize their next moves.  

Turn Formats

While the length of each turn could be customized for different game formats, we posit two initial game formats: 

IMMERSION - One turn per hour - 45 minutes of Open Comms, 5 minutes for Order Entry, instantaneous Reconciliation and Report, and 10 minutes of Solitary Analysis
SERIAL - One turn per day - 10 hours of Open Comms, from say 10AM UTC to 8PM UTC, 15 minutes Order Entry, a nighttime buffer prior to Reconciliation and Report at 8AM UTC, and then two hours of Solitary Analysis before Open Comms resumes

Units

Gothi
Gothi are the avatars of the players.  They command Kinsmen and Skald units through Orders.  Gothi names are randomly assigned from a set of prominent names from the Icelandic Sagas, and do not carry over from game to game.  In one game, a player may control the Gothi Njal and in another, he or she would control Gudrud.  The names do not carry any different traits.  At the end of the game, a Gothi either survives or is vanquished.  

Longhouses 
Longhouses represent the seven territories controlled by the Gothi and are named after their original Gothi.  At the start of the game, each Gothi controls one Longhouse and one Kinsmen company is quartered in that Longhouse.  

Longhouses have a strength that can sustain one but not two successful standard assaults.  A Longhouse that has been successfully assaulted one time is compromised and will fall to the next successful assault.  However if an assaulting party has a strength that is two or more greater than the defending party (e.g. one assaulting Gothi with two supporting Gothi vs. a lone defending Gothi - 3 on 1), a full strength Longhouse can be conquered in a single turn.
 
As the game unfolds, conquerors control the Longhouses of vanquished Gothi as well as their Kinsmen.   For instance, a player controlling the Gothi Gunnar who vanquishes the Gothis Thord and Hallgerd would then control three Longhouse territories (Gunnar Longhouse, Thord Longhouse and Hallgerd Longhouse) as well as three companies of Kinsmen, but just one Skald (see Skald section below).

Kinsmen
The soldiers of Gothi, Kinsmen are loyal, strong and dumb.  They are capable of executing three Orders, each of which is available from the start of the game.

Gothi who control multiple Kinsmen may gift extra companies to other Gothi, either as signs of trust or as rewards for supporting a successful Assault, or for any other reason. Gothi must keep at least one Kinsmen company. 

The Skald
The Skald’s realm is information.  Obtaining it, publishing it, manipulating it and using it in a wide array of other ways. 

The Skald’s Orders are grouped into three skill trees 

Successfully executed Skald Orders impact three different areas:
Intel received only by the Gothi, such as intercepted Comms transcripts or identification of Open Comms between other Gothi
Active Measures that affect other Gothi, such as by disrupting their Comms or planting false messages in Comms
Report manipulation that affects what all Gothi see about the previous turn, such as by concealing the Gothi’s Orders or planting misinformation about what actually transpired

Additionally, certain Skald Orders can affect the actions of Kinsmen, such as the Hedge Order.

Combat Rules

Gothi’s combat rules are as simple as can be - greater numbers of Kinsmen conquer fewer numbers, while equal numbers have no effect.  Kinsmen cannot be lost or destroyed even if they attack with fewer numbers than the number of defenders.  There are seven companies of Kinsmen throughout each game of Gothi, through which Gothi submits their Orders may change over the game.  Each Kinsmen company has a permanent strength of 1 and may not be divided - it exerts its entire strength at one location on each turn.

Whenever a Gothi orders Kinsmen to Assault a Longhouse, the Combat Rules apply.  First, the strength of each Assaulting Party and Defending Party is calculated.  An Assaulting Party’s strength is equal to the number of Supporting Kinsmen plus the Assaulting Kinsmen they are supporting.  Similarly, a Defending Party’s strength is equal to the number of Rallying Bannerman plus the rallied Defending Kinsmen.

A failed Support or Rally (either because the target Kinsmen supposedly leading the Assault or Defense is not at the designated Location, or is not carrying out the designated Assault or Defend Order) does not affect the Assaulting Party or Defending Party strength calculation, and otherwise has no combat effect.  

In the event that more than one Assaulting Party assaults the same Longhouse in a turn, the combat rules are as follows:
If the total strength of all Assaulting Parties is less than or equal to the strength of the Defending Party, there is no effect
If the total strength of all Assaulting Parties exceeds the strength of the Defending Party, the Defending Party is expelled from the Longhouse, and if that is the Gothi’s only Longhouse, the Gothi is vanquished - in that scenario:
The Assaulting Party with the greatest strength captures the Longhouse and its Kinsmen
If there are two or more Assaulting Parties that have the same strength and no Assaulting Party has a greater strength, no one captures it and the Longhouse remains vacant until a subsequent Assaulting Party captures it with a greater strength than any other Assaulting Party - in the situation of a vacant Longhouse, its Kinsmen company automatically deploys Defend on each turn

Information and Communication in Gothi

There are two types of information in Gothi - that which is broadcast to all players and that which is communicated only between two of the seven Gothi (at least initially).  Learning how to strategically exploit the gap between everyone’s knowledge and your own asymmetric knowledge will make you a master of Gothi.

Players learn about the state of things in Gothi through three different means of communication 
Secret Intel that is gathered about other Gothi and revealed only to one player
Binary, semi-confidential Comms with other contacted Gothi
Broadcast Reports that reveal to all players what has unfolded on the prior turn

For reasons explained more fully in the Prohibited Conduct section below, it is important that Gothi only communicate and receive information about the game in progress within the game itself.  This means that exchanging phone numbers or email addresses to communicate outside the game framework is strictly prohibited.

Intel
Intel is the result of Skald activity to probe and steal information about what the other Gothi are up to.  It is delivered only to the Gothi who successfully ordered the Skald to obtain the Intel at the same time that the Report is published.

Comms
Comms are the precious lifeblood of Gothi.  They constitute the one-on-one text messaging chats between connected Gothi that allow for planning, scheming and misleading. They are the springhead from which flows the asymmetric information that makes every game of Gothi unique.

 In a standard Gothi game, the players use randomly assigned pseudonyms names from Icelandic sagas that are unique to that single game.  So although my Gothi username may be GCHoarder, I might be assigned to play as Njal in one game, Gudrid in the next.  The Comms will display these one time use Gothi names.

To start the game, no Gothi are in contact with one another.  The Skald order Contact will likley be a popular first order, as it randomly establishes a communication channel or Comm, with another Gothi, allowing the players to communicate with each other.  Once established, Comms stay open throughout the game or until a Gothi is vanquished, barring interference such as through the Skald’s Disrupt order.  Some players may wish to deploy Contact until they have established Comms with all other Gothi while others may prefer to develop only one or two relationships in the early stages of the game. 

Comms are unique to each Gothi, and do not transfer to new owners when a Gothi is vanquished (except in the case of the Puppeth Skald order below).

Reports
Reports are published accounts of the events of the previous turn.  They are generated automatically and are distributed to each Gothi player at the same moment.  Reports take the form of a mock newspaper - The Saga Times.  Articles in the Report are auto-written by software that creates a narrative account of what happened.  It will automatically weight the events of the prior turn, and give headline status to the most significant outcomes (e.g., a Gothi has been vanquished), and will fill the front page with additional accounts of what has transpired.  At the bottom of each report will be an explicit readout of the orders entered by each Gothi along with whether it was successful, and possible some statistics about the Gothi’s choices (e.g. Most Common Kinsmen Order - Assault (65%)).  

It could be useful to include trend analysis styled as op-eds written by a fictional personality, perhaps one who tends to criticize whatever behavior has emerged.  So one day’s column following a defensive-oriented turn may lament the evident cowardice and risk aversion, while on another day we may find a plea for nonviolence.  The goal would be for this perspective to reflect a fickle public, never satisfied but happy to offer its own conventional wisdom as to how things should be done.

Making Moves in Gothi

Orders
Orders are the actions of the Gothi about what they wish their Kinsmen and Skald to accomplish in the turn.  They are scarce commodities and should be deployed with strategic intent.  Before each turn’s Order Deadline, a Gothi submits one Order for each Kinsmen company that he or she controls and one Order for his or her Skald.  In the event that a Gothi fails to enter an Order before the deadline, the default is that the Kinsmen will Defend and the Skald will do nothing. 

Suborders
Suborders are additional requirements that apply to particular Orders and that must be satisfied in order to be executed.  Some Suborders are simple directions about where to carry out an Order, while others require greater tactical precision to take effect.  

Kinsmen Suborders can involve the coordination of forces to achieve certain ends.  The Support Order requires the specification of which Assaulting Kinsmen are to be supported, and where the Assault will occur.  Getting either Suborder wrong wastes the Kinsmen’s turn.  While it may sound simple to coordinate Suborders like these in theory, it may be that another player wants to neutralize a Kinsmen company for a turn by tricking a Gothi into sending it to a phantom battle. 

Skalds, as the information warriors, have the potential to impact the game in powerful ways, but with these additional powers come additional challenges.  Skald Suborders can be predictions about one or more Orders by other Gothi, and depend on being able to clearly see what other Gothi will do in order to work.  The more powerful the Skald Order, the more complex and difficult the Suborders required.  

For example, the simple Disrupt Order only requires the Order Enjoin is designed to try to foil an impending attack, even when the Attacking Party has superior numbers, so it is a very powerful Order if executed. Enjoin’s Suborders require accurate predictions as to 1) which Gothi will Assault, 2) which Gothi(s) will Support the Assault, and 3) which Longhouse will be the target.  The Order will only execute if all three Suborders are completely satisfied, and will fail if any Suborder is incorrect.

Kinsmen Orders and Suborders

Assault
(Suborder: Target Longhouse)
-attempt to capture a Longhouse
-if successful, the Assaulting Gothi gains control over the Longhouse’s Kinsmen
-if the captured Longhouse is the only Longhouse controlled by a Gothi, the Gothi is vanquished

Defend
(Suborder: Target Longhouse)
-hunker down and defend a Longhouse
-if a Gothi controls more than one Kinsmen company, he may Order two or more Kinsmen to defend the same Longhouse
-this is the automatic Order if a Gothi does not submit a Kinsmen Order or if the Longhouse is vacant
 
Support
(Suborders: Support Target; Supported Action; Target Longhouse)
-assist another Kinsmen (belonging either to you or to another Gothi) in an Assault or Defend
-if the Assault or Defend is successful, the Supporting Kinsmen does not claim anything 
-if one of the Suborders is incorrect, the Order fails
-unlike Assault or Defend Orders, which will be carried out no matter what, a Support Order may be rendered contingent by certain successful Skald Orders
-e.g., the Hedge Skald Order will pull Supporting Kinsmen back to a designated Longhouse if it comes under attack on that turn

Skald Orders and Suborders

Contact - DIPLOMAT
(No Suborders)
- open comms with a random uncontacted Gothi
- comms remain open for the duration of the game, unless disrupted
1 Veteran Point earned on successful execution

Survey - DIPLOMAT
(No Suborders)
-obtain Intel identifying two additional Comms between other Gothi
-Trace will not disclose Comms that have been formally disclosed already, through previous Trace orders or through identifying Comms published in the Report
1 Veteran Point earned on successful execution 

Mask - SPY
(No Suborders)
-conceals the Gothi’s Orders in the upcoming Report
-also blocks all attempts by other Gothi to obtain Intel about you
1 Veteran Point earned on successful execution

Disrupt - SPY
(Suborders: Target both Gothi whose Comms you wish to disrupt)
-severs the Comms between a pair of Gothi during the next turn
-if the target Gothis did not have Comms established prior to Reconciliation, this Order has no effect, even if they established Comms on that turn
2 Veteran Points earned on successful execution

Denounce - DIPLOMAT
(No Suborders)
-if the Gothi successfully defends against a supported assault on the turn, the Comms transcript between the Assaulting and Supporting Gothi will be published in the Report
-if there is more than one Supporting Gothi, each Comms transcript between the Assaulting Gothi and the Supporting Gothi will be published
2 Veteran Points earned on successful execution

Hedge - BATTLELORD
(Suborders: Target Contingent Longhouse)
-if the Gothi’s Kinsmen are ordered to Support an Assault, and if the target Contingent Longhouse is attacked on the turn, the Kinsmen are called back to defend the Contingent Longhouse instead of playing a role in the battle at the primary Longhouse to which they were ordered
-this is an effective Skald Order when Supporting an Assault, as it allows a Gothi to hedge his or her bets against the chance of a sneak attack 
1 Veteran Point earned on successful execution

Stretch - BATTLELORD
(Suborders: 1) Assault or Support; 2) Target Secondary Longhouse)
-if the Gothi’s Kinsmen are ordered to Support an Assault that will be successful without the Support strength (e.g. Defending Party strength = 0), the Kinsmen will be redirected to either Assault or Support an Assault on a Secondary Longhouse
2 Veteran Point earned on successful execution

Recon - SPY
(Suborders: Target Gothi)
-obtain Intel about the target Gothi’s Comms distribution, with identities attached where the Gothi had prior knowledge of specific Comms connections  (e.g. “Target Gothi has 4 Comms - 45% with Gothi A, 30% with Unknown Gothi, 25% with Gothi D, 0% with Unknown Gothi”)
1 Veteran Point earned on successful execution

Intercept  - SPY
(No Suborders)
-obtain Intel comprised of a random, partially redacted Comms transcript from the prior turn
-all Gothi and Longhouse names are redacted, including the names of the Gothi writing the Comms
-one-third of the transcript lines are also redacted
1 Veteran Point earned on successful execution
If Ordered by GHOST SPY, obtain complete unredacted transcript between 2 Gothi from prior turn

Tap - GHOST SPY
(Suborders: 1) Target both Gothi; 2) Specify Relationship (Contact/Allies/Mutual Defense Pact))
Tap and access live transcript between two specified Gothi for subsequent turn 

Enjoin - PEACEMAKER DIPLOMAT
(Suborders: Target Assaulting Gothi; Target Supporting Gothi(s); Target Longhouse)
-if successful, prevents capture of a Longhouse by an Assaulting Party with +1 strength advantage over the Defending Party
-cannot prevent capture of a Longhouse by an Assaulting Party with +2 strength advantage
-any deviation from the Suborders results in failure, including:
Naming a Supporting Gothi when the Assault is unsupported (even if the reason it is unsupported is due to a contingency such as through a Hedge Order)
Failing to identify which Gothi will Assault and which will Support 
Omission of an additional Supporting Gothi
-note: if a Gothi controls multiple Kinsmen, the Suborder need not specify which specific company is used for the Assault or Support

Harvest - SPY
(No Suborders)
-when combined with a successfully executed Assault Order by the same Gothi, Harvest results in the conquering Gothi obtaining Intel comprised of one of the vanquished Gothi’s Comms transcripts from the prior turn - if the vanquished Gothi had multiple Open Comms, one is chosen at random

Bind - PEACEMAKER DIPLOMAT
(Suborders: Target Ally)
-prevents a betrayal by an ally and any Assaulting Party that the ally is a part of that tries to Assault the Gothi’s Longhouse will have a strength of 0

Berserker - HERO BATTLELORD
If Kinsmen Order is successful in battle (excludes unchallenged Defenses), will randomly Assault two additional non-allied Longhouses

Leak - DIPLOMAT
(Suborders: Target 2 Gothi; Requires Matching Order from Second Skald)
-if successful, targeted Gothis’ Comms from prior turn are published in Report
- 3 Veteran Points earned for successful execution

Puppeth - HERO BATTLELORD
(Suborders: Target Gothi)
-this is a sophisticated attack akin to a body snatchers maneuver that is coupled with a coordinated Assault by two Gothi
-it can only work against a Gothi who is vanquished on the turn
- can only be executed by Supporting Gothi
-if successful, Puppeth hides from other players that the Gothi has been vanquished in the following Report, and the Supporting Gothi takes over the vanquished Gothi’s existing Comms, while the Assaulting Gothi takes over the Longhouse and the associated Kinsmen

Sue For Peace - DIPLOMAT
(Suborders: GothiCoin Allocation to Survivors)
-ends the game with multiple surviving Gothi only if on the same turn:
All Skalds deploy Sue For Peace 
All Kinsmen deploy Defend
All Skalds specify matching GothiCoin Allocations to the survivors
-e.g., if three Gothi remain, and each enters matching Orders to Defend/Sue For Peace and that the Allocation should be 2.5 GothiCoins each to Gothi A and Gothi B and 2 GothiCoins to Gothi C, the game ends and the GothiCoins are distributed to each survivor per the Allocation
-if the Allocations do not match, the game continues

GOTHI ECOSYSTEM

GothiCoins

GothiCoins act as the incentive in Gothi and serve as a token to interact with the Gothi ecosystem.  

GothiCoin Creation
GothiCoins (GTH) are generated through people playing Gothi.  At the start of a standard seven person game, eight GothiCoins are created.  Seven of these coins are to be awarded to the surviving Gothi at the game’s conclusion, and one GothiCoin is awarded to the developers.  There will be no ICO, no premining and no market price peg.  There is no cost to players for joining a standard seven player game.  Therefore, the supply of GothiCoins will directly track the adoption of the Gothi game. 

Developer Use of GothiCoins
In the early stages of the Gothi ecosystem’s growth, the developers’ GothiCoins will be used for the following purposes:
Paying gas fees to enable the Gothi network to run
Paying developers for past or future work
Creating liquidity on token exchanges that list GothiCoin
Establishing a fund to pay part or all of the initial Jury Fees
Investing in the health of the Gothi ecosystem (with specifics provided whenever any such project is launched)

GothiCoin Markets
Some players may wish to trade the GothiCoins they earned for another digital asset like ETH.  Other players may wish to purchase GothiCoins to play higher stakes games.

The Althing

Beginning in 930, the Althing was annual assembly of Iceland's most powerful leaders - the Gothi - who met on neutral territory to decide on legislation and dispense justice.  

Here, the Althing is the hub of the Gothi Ecosystem.  It is where players create Gothi profiles, join games of Gothi, discuss strategy and proposed game improvements or modifications, track GothiCoin balances, and even remedy disputes relating to Gothi.  

Gothi Player Profiles

While within the game of Gothi, each player’s identity is randomly assigned from a database of Icelandic saga names, they must first create a player profile, which will store earned GothiCoins and track the player’s statistics.  

Because it would hurt the network for bots to flood the Gothi ecosystem solely to “earn” GothiCoins, it is proposed to require that Gothi player profiles be connected to real world identity verification in some fashion, such as through a uPort identity or something similar.  Players who appear to let bots run games on their behalf may have their accounts suspended or may be penalized in some way to discourage such behavior.

So while the real person John Doe may be required to use his uPort identity to create a Gothi player profile, he may choose the profile name GothiBerries71.  When he joins a standard Gothi game, he may be randomly assigned the name Njal in one game, and Aud in the next game.  Should he survive the game as Njal as a sole survivor (earning seven GothiCoins), and earn two GothiCoins as Aud by surviving with two other players, those nine GothiCoins would be deposited in the account of GothiBerries71, as well as other statistical information about his game performance.

Trophies and Record Books

Joining a Game of Gothi
Players can always join a standard game of Gothi at no cost.  Standard games consist of seven randomly chosen players, each of whom will use an Icelandic saga codename within the game.

It is anticipated that players may have differing levels of time commitment they wish to devote to a game of Gothi, and so two initial formats are proposed.

One turn per hour - this format fits a more engaged player who wishes to play an immersive game that begins and concludes on the same day
One turn per day - this format is intended to fit players who may not have the interest or time to play the game semi-continuously, but enjoy the strategic value afforded by a slower pace and more time to plan and execute one’s strategy

There may be other game formats that have wide appeal that may be offered.  Additionally, given that Gothi may be played by people living in every time zone, games will be offered that are convenient for different clocks.  For instance, one turn per day games will be offered with Order deadlines at each hour of the day and Reports published approximately 10 hours later to accommodate sleep.  Hourly turn games may similarly provide 10 hour breaks. 

Higher Stakes Games
The Althing will allow players will GothiCoin balances to commit multiple GothiCoins in higher stakes games and tournaments.  Players that wish to enter higher stakes games without earning GothiCoins through standard game play may purchase them on exchanges.

From time to time, the top players will be invited to compete in special tournaments with their actual profile identities revealed.  Special prizes and certainly bragging rights will accompany such special events, and arrangements may be made to increase spectator enjoyment of these events.        

Forums and Discussion Boards

Prohibited Conduct
Within a Gothi game, offline communication between players is prohibited.  The anonymized naming process is designed to help prevent this from occurring, but there may also be AI based tools to detect and expose sharing of external contact information, which would compromise the game balance by excluding player communications from being surveilled or exposed, which are crucial aspects to the game strategy.  

If discovered, offline communication may result in forfeited GothiCoins, temporary or permanent bans or other penalties.

Abusive conduct is also prohibited, and players are encouraged to refrain from sharing personal information, including gender, sexual orientation, nationality, religion, etc., but encouraged to use pronouns corresponding with their randomly assigned names within each game.

Disputes and Dispute Resolution

Juries and Jury Fees

PLASMA DEPLOYMENT

CRYPTOECONOMIC ANALYSIS




