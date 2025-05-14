# Aetheric Imagery Magic system
### A lightweight SillyTavern lorebook magic system to weave worlds together in a compelling manner.

Designed with fantasy settings in mind except the actual core system doesn't contain any content. You could theoretically apply this lorebook to any ruleset. 

Has some core concepts that encourage visceral storytelling, but might not be appealing for every (or many a) universe:

- **Magic is everywhere, and everything is magical.**
  > Universal system that gives plausibility to human spellcasters, viscious monsters, and wonderful items. Allows for a consistent scale and detailed spectacle with less AI jargon.

- **No teleportation.**
  > Currently a Basilisk feature: Instant traversal is impossible, but you can get close by using intradimensional shortcuts. And theres also what lurks beyond, if you're interested in that.

- **Visceral imagery over damage numbers.**
  > Mana as a concept has been entirely rebuked, and replaced with metabolic spellcasting. Damage numbers dropped in favour of brutal fight choreography - this system encourages fast paced combat scenes about wrestling for control. 

- **Never forget to emphasise human frailty.**
  > For as long as humans age, people will seek to improve their own lives and defy expectations. Not explicitly dystopian, but the overcoming nature inspires people to cheat death and exploit the land with unique design.

- **Iteratively optimizing tokens across multiple formats.**
  > I use Deepseek to test the lorebook, but one lorebook mightn't fit every SillyTavern instance. Refer to formats for a description of each.

---

# The Magic System

This system runs on aether, a magic potential energy that permeates through roots and crevices of the world. You can't see it, but you will likely be made aware of a lack or abundance of it.

Aether operates with its own physics rules that inform the rest of the world. Individual aether charges have a charge polarity that string together to encode an attribute, something like an element. Every physical material can accumulate Aether up to a capacitance (Æc), and also has a throttle goverened by a flux (ΦÆ). Aether can also interact with the world given an attribute, reagent, and a medium to effect a reaction called a Spell.

When a novice pyromancer wishes to use fire attribute magic, they cast a spell by invoking ambient aether to react with their body in a metabolic process. A novice pyromancer's first spell is usually some form of self-immolation as magic has an immediate effect. Fortunately for pyromancers, there is the study of 'Metamagic' which allows aether to read, displace, project or bind other aether charges. Our pyromancer could collect the fire into a mote and launch it with extreme concentration, though making fire motes requires you study metamagic - or does it?

People don't have to cast spells by themselves either. Delicate glyphs can be inscribed on objects (like a wand) to automatically rewrite aether attributes to any type as a spell is cast, which inclues metamagic and all its consequences. Now our pyromancer can more easily hurl fireballs given a bit of human ingenuity. Spellcasting peripherals like wands and grimoires can be tailored to specific spellcasters by automating the metamagic, encapsulating fires in motes, and launch to a single action.

That's the gist of it, but creating the aether rules lead to emergent explanation for many things like dragon breath and guilds/parties, as well as exploration of novel 'magic' ideas: implicit information warfare and spell automation being my favourites.

---

## Todo:

- [X] Core ruleset functional
- - [ ] Improve entry keying over time with feedback

- [ ] Extension content: spell attributes

- [ ] Extension content: alchemy formulae

- [ ] Extension content: material aether characteristics
---

# Formats

- [Catnip](https://github.com/thaalesalves/ai-games-research/wiki/CAT-nip--SFW-guide-by-Covalent-and-Curious-Nekomimi)
	> The first format which I wrote in. Something like xml tags used as entity components, wrapped in tables to prevent format leaking.

- Basilisk
	> Work-in-progress, being designed with Discord teaching to supercede Catnip. Programmatic like pseudo-python, high quality of response with less implication nudging.
 	> Now dictionary compression, as well as citations that tell you which rules have been invoked. You can tell if a definition has been compressed via `summary/...` vs `dictionary/...`
 	> ![image](https://github.com/user-attachments/assets/a244e2dc-8453-43cd-8458-29b5869fe5ca)
 	> ![image](https://github.com/user-attachments/assets/12f3417b-ac0b-4bbe-8aea-8b63d364e803)



---

# Installation

- Download or copy files of your choosing from this repository.

- Manually insert the file into a worlds folder: `SillyTavern/data/%some username%/worlds/` or `SillyTavern/public/worlds/`

When you import it, all the entries will appear out of order. You can change it to sort by order to fix this.

---

# Contribution

Feedback is much appreciated, feel free to raise issues on the Github or dm me on Discord (@warmechanic)

I'm happy for people to fork and pull request additional content for this system, particularly looking for lorebooks in different formats to work with different models or characters.
