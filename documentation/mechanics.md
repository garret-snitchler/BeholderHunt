# Stats
There's a general conflict here between simulationist and making things convenient. I think the compromise is that some armor will come with inherent element resistance.
Here are ideas for base stats:
	Strength: Increases damage done by physical attacks.
	Vitality: Increases max HP, increases resistance to physical ailments such as poison or paralysis.
	Mind: Increases magic damage, increases resistance to magical ailments such as charm or confusion. Increases success of applying magical ailments.
	Agility: Determines turn order. Slightly increases critical hit chance, accuracy, and evasion. (Slightly is to emphasize that this is not supposed to be gamebreaking on its own)
	Charm: Chance to distract enemies in combat. The highest charm in the party will modify your buy and sell prices. Certain skills are powered by charm. 
		Can be directly increased by certain equipment.
	
Certain stats are calculated by factoring in both equipment and stats. They can also be buffed and debuffed mid-combat. These are:
	Physical Attack - Combination of strength and weapon bonus.
	Magical Attack - Determined by a combination of Mind and the spell being used. 
	Physical Defense - Reduces damage taken from physical harm. Defense is only provided by armor. Some armor also provides additional magical/elemental resistance. 
	Magical Defense - Defense against magical attacks. Harder to gain than physical defense. 
		(Elemental resistance is also relevant to reducing magical damage - make this easier to see than how it is in DQ.)
	Critical Hit Rate: This stat is normally low, and receives slight modifiers from Agility. Can be boosted by certain weapons that sacrifice physical attack.
		Critical hits increase damage and bypass defense.
	Evasion - This stat is normally low, and receives slight modifiers from Agility. Can be boosted by certain equipment that sacrifices defense. Effective against both physical and magical damage.
	Elemental Resistance - Resistance to each of the magical elements, gained from equipment both mundane and magical.
		Fire
		Ice
		Wind
		Earth
		Light
		Darkness

# Combat Mechanics

# Jobs
Warrior - Or something along those lines, the intention with this class is to make a simple attack bot. Warriors are notable not for their abilities but for two traits:
	1. Warriors are the class that can wield the most equipment. All the heaviest weapons and armor that most classes couldn't use are a wonderful find for any warriors in your party
	2. Durability. While other classes are reliant upon an MP stat, the warriors will perform as well in the first combat of the adventure as they will in the thirtieth. 

Weirdly I'm not super feeling the classic mage/cleric right now. If I did do a priest I'd distinctly go for a cleric though I like that more than "wizard but in white clothes". 
We'd for sure enforce the blunt weapons only policy. It's also important to me that this is not a required character to have in the party - I'd want there to be other options
in the form of Staffs of Multiheal, consumables that heal multiple people at once, 

I like Thieves. I think a thief's main quirks would be going fast, getting crits/sneak attacks, and using status ailments. DQ nails it, for the most part. Obviously make sure
that monsters are actually vulnerable to most status ailments, especially including bosses. I think this kind of also overlaps with my ideas of an alchemist. 

I like monks/martial artists. I subscribe to the theory that one of a martial artist's benefits is not relying upon regular equipment upgrades. Glass cannons.

I like paladins. The concern is too much overlap with warrior or priest. This is a warrior with a divine flair to their abilities. Smites, defensive party buffs, etc.

I'm considering a warlord. This might replace the warrior, and it also feels like it has overlap with the paladin. The rough concept here is a martial character who does
"leadership" and through that makes the rest of the party stronger. Stuff like offensive buffs, giving a character a second action, having more control over the turn order, etc.

I feel obligated to include some sort of dedicated magic character. If we wanna make things more sexy than your standard priest/mage, then get creative. A warlock that operates
off of explicitly sinister, demonic energy would be fun. Inspiration would be DD's occultist. 
Healer variants could be something like a literal healbot, which feels both like a cute joke and an attempt at providing something more flavorful than your usual white mage

Face - This job has a high charm stat, making it skilled at bartering with merchants and distracting foes in battle. 
	The flavoring here is intentionally vague. I think there are two main directions we go with it, and I think there's some overlap in utility:
		The Merchant. An amiable, well connected tradesman. Has abilities related to using items without consuming them (had a second in his bag). Passives that increase gold
			acquired after battle. Could "charm" some combatants with gold.
		The Tease. A flirty, seductive character. Has abilities related to making enemies lose turns in battle, charming enemies, powering up party members, etc.

NO beastmasters I don't really like those. HOWEVER, I think maybe a class that's part-beast would be cool. I think a dragon-person is my favorite so far?
This is pretty clearly Souls inspired but no shutting ideas down this early! There's also some Darkest Dungeon inspiration from the Abomination, but that's challenging to 
transport into this since that class's big downside is the damage it does to your party's morale. It's a similar candidate for a berserker character.

A character who's gimmick is being undead would be funny. Maybe a decent idea for a "berserker" reflavoring? No control over them, they don't die, but they don't take direct orders

In a similar vein I think a robot class would be cool. The challenge with both of these non-traditional ones is making it clear to a new player what this class does that sets it 
apart from others. This could be funny as a Blue Mage type situation.

# Level Ups

# Job System?
1. No job changing system. Characters start as the classes you pick for them. This is the least interesting and the most restrcitve, but in a short game it's not necessarily inappropriate.
	You would likely also just pick the player's party for them at this point, like a more traditional RPG, though you could take an Etrian approach and let them choose their party
	What I'd really be taking inspiration from with this is Cthulhu Saves Christmas, as I think it does an excellent job of both establishing roles for party members while still
		giving you a fair amount of flexibility when it comes to figuring out what you want the character to be specializing in combat. No need for full subclasses, just give
		a limited number of skill slots or specific choices of equipment that benefit one playstyle more than the other and you should be good enough to allow for strategizing.
2. Standard Job System - You have a pool of jobs that party members can change between. Certain thinsg are carried over from one job to another, such as spells, abilities, stat gains
	This is a system that would encourage depth and careful design
	Let's think about versions we've experienced:
		DQ3's resetting you to level 1 but giving you a significant amount of stats carried over, as well as spells and abilities.
			You can only change jobs after achieving level 20, which is hard to reach in the early game and fairly easy to reach in the late game.
			There is a single "hidden job" called Sage, though the game itself does a poor job of both communicating that Gadabout transforms into this or that
				its ability to transform into Sage is notable if it's your first time looking at the job change screen
			It's also notable that DQ3 has a unique job that only the main character gets, but I think I wouldn't want that and I wouldn't want the MC to be unchangable either
		DQ9 in comparison doesn't reset you at all and is overall lenient when it comes to job switching. It makes use of a visualization to make clear what equipment is only
		usable by certain classes, and this is good as it also lets you know what classes will work even if none of that class is represented in your party. I think this is more
		player friendly than DQ3's version. 
			Similar to XC3, half of this game's jobs are unlocked by doing specific quests. These quests are marked the same way as any other quest is, making them somewhat easily missed.
				I don't think it's a problem if optional jobs are easily missed by blind players, but I don't think they should be permanently missable. 
				It's notable that in DQ9, the job unlock quests also serve as indirect prereq requirements, as they all require you to use skills learned from a base job first. This
				means that for example, if you've gone through the game with no thieves, you won't be able to get the Ranger job unless you take the time to raise a thief. However, this
				isn't much of a hurdle if someone is willing to put a small amount of time down to raising a thief, and then afterwards you could pivot to Ranger with no problems.
		XC3's system of starting with 6 jobs (or one per party member) across 3 different roles and then slowly rolling out more over the course of the game when you do specifc quests
			I think this system had a lot of potential but it had the biggest problem in job systems for me which is that it just homogenized everybody by the mid-game
			I would also say that some jobs struggle to differentiate themselves from others, both in terms of flavor and in gameplay. 
		Stranger of Paradise - Each job has a skill tree and an amount of weapons it can use. Every skill tree gives you unique moves and also ends with unlocking one or more
			other jobs, which was great for doing a prestige-like system. But it must be remembered that this skill tree approach was for when you only had one party member - it
			could easily fall prey to the homogenization issue discussed earlier, and it might also be too much micromanagement to do across multiple party members. If there's
			anything we could take from it it's that giving each job a nonlinear growth track controlled by the player might be fun, as well as the idea that certain jobs could
			serve as prerequisites for other jobs. Also, that while moves carry over across jobs, the idea that every job has a unique ability (of varying complexity) is good for
			making them all feel different
		Metaphor - I haven't finished 'researching' this game's systems yet but I like what it's doing. Jobs fill different roles, there's a limited ability to use one job's skills
			from another job, the game gives you suggestions on which jobs to bring into a given boss fight, job unlocking is through money but otherwise you can change them instantly,
			there are combo skills between jobs, really good stuff across the board here. It also has prestige jobs unlocked by maxing out other jobs, though this is where my research
			lacks because I haven't actually unlocked any of these yet myself. The only issue is that I do think there are some cases where it's hard to really note what makes a given
			class special. Like, seeker VS warrior VS brawler, they do different things but flavor wise it's not super easy to tell compared to the obvious distinctions in something like DQ.
The conflict here is largely between what I think is interesting and what I think is reasonable to do within the scope of this game. I'm more excited about a job system but I'm
still uncertain about the actual length of this game. If this ends up being large I'd spring for a job system, but if we're going for something compact I'd probably say to not.
With that in mind I'm unfortunately going to table the discussion of the specific job changing mechanics until the vision is more clear.

# Differentiation from a dungeon crawler
The main thing that sets a dungeon crawler apart from a more typical classic RPG, at least in my eyes, is a combination of three things:
	1. How much focus is on resource management
	2. How long are the dungeons
	3. How confusing are the dungeon layouts (teleporter mazes, regular mazes, etc.)
The reason we do this is because, while I like dungeon crawlers, I don't think the intent with Beholder Hunt is to make a dungeon crawler. So maybe avoid doing these things too much 
unless we decide we want to make a dungeon crawler
