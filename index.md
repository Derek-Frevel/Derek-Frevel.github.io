## About Me
Hello! My name is Derek Frevel, and I'm a passionate game developer with a strong foundation in both programming and design. I graduated with distinction from the University of Alberta in 2024 with a degree in Computing Science, complemented by a Certificate in Computer Game Development.

I specialize in gameplay programming, where I bring ideas to life by creating engaging and interactive experiences through games. I have some experience working on and creating a variety of AI entities, exploring how they can make game worlds more dynamic. Additionally, I’ve contributed to various UI implementations, enhancing the overall user experience.

I'm always eager to push the boundaries of what's possible in game development, and I'm excited about any opportunity that allows me to bring my skills to new and exciting projects.

## My Projects
### [The Drawnjuring](https://store.steampowered.com/app/3048510/The_Drawnjuring/) (2024-Present)
#### **Overview**
The Drawnjuring began as a university capstone project with a team of six, but thanks to the support from the [Edmonton Screen Industries Office](https://edmontonscreen.com) and their Trailhead Program, we continued development beyond the term.

The game embraces absurdism and features contrasting art styles to create a humorous and unique experience. In The Drawnjuring, you play as G'lich, a Lich competing against a giant disembodied hand known as The Oodler, to see who can escape a space prison first. As G'lich, you battle through hordes of oodles—creatures drawn by The Oodler—while making your way out of the prison, culminating in a climactic final battle in The Oodler's home dimension.

The core gameplay blends classic dungeon-crawler elements with a unique twist: you can revive defeated enemies to fight on your behalf.

#### **My Role and Experience**
As one of three programmers on the team, my primary contributions were designing the majority of enemy behaviors and implementing the Revive ability.

We aimed for a diverse array of enemies with distinct behaviors and abilities. To achieve this, I created an enemy base class that handled logic common to all types, such as target selection and a simple Finite State Machine with states like attacking, chasing, and idling. This approach allowed us to easily extend the base class, modifying specific behaviors for each enemy type to achieve the variety we desired.

The Revive mechanic is a standout feature that distinguishes our game from typical dungeon crawlers. From the start, we built our enemy class around the concept of **Targets**, which are game objects the AI seeks to attack. This allowed for straightforward implementation of the Revive mechanic: upon revival, the AI state changes from dead to alive, and the team affiliation switches from enemy to player. With a simple adjustment to the targeting logic, revived enemies now attack the opposing team. This system is what enabled direct combat between player-affiliated AI and enemy AI. This mechanic creates a dynamic where AI combat becomes a key feature of gameplay, enabling direct confrontations between player-affiliated AI and enemy AI. Through this dynamic, the game achieves its intended aesthetic of commanding your own undead army, giving players a unique and enjoyable experience.

### [To Bake a Cake](https://derek-frevel.itch.io/to-bake-a-cake) (2024)
#### **Overview**
As part of a team of three, I participated in the 2024 Alberta Game Jam where we had 48 hours to create a game using the theme "Out of Order". Our game, To Bake a Cake, creatively explored this theme through both its gameplay and narrative.

In each level, players experience a unique twist in game mechanics—starting with normal gameplay then introducing level unique mechanics such as: a one-minute survival challenge, inverted controls, and inverted shooting. The game also features a humorous story where the chapters are intentionally "Out Of Order." The narrative follows a personified star attempting to bake a cake at the end of the universe, leading to a playful disruption of time and physics that mirrors both the game’s narrative and mechanics.

#### **My Role and Experience**
As the sole programmer on the team, I was responsible for all aspects of programming and level design for To Bake a Cake. This included creating the core gameplay mechanics, implementing various level-specific twists, and designing the levels to align with the theme "Out of Order."

I began by developing a basic top-down shooter with standard mechanics, such as levers to open doors and simple enemies that chase and attack the player. From this foundation, I introduced unique twists for each level to distort core mechanics in creative ways.

For the second level, instead of the player fighting through a level to reach a gate, they must defend an oven for one minute before progressing. A key feature here is that the player's movement speed decreases the further they move from the oven, adding a strategic layer to the defense.

In the third level, I implemented inverted movement controls, complemented by a maze-like environment where players navigate to find ingredients. This level required players to adapt to the new control scheme while dealing with the maze layout.

For the fourth level, I inverted the speed of the player’s projectiles to challenge aiming. This twist was notably difficult, so I designed the level to help players understand and adjust to the difficulty curve before facing more intense challenges.
