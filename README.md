[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [your name]
### Student number: [your student number] 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 


I wanted to make the intensity curve rise steadily as the player traverses between sections 2 and 3. 

I used risk as a way to moderate tension in a section. F

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

The main challenge comes from the precise manuvers needed to traverse certain sections, combined with carefu

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

I employed heavy use of pass-through platforms to facilitate backtracking, and intentionally made the task of backtracking much easier. This is to lighten the load on players with exploring areas that they may have missed, and not make it tedious and mundane.

Some areas showed "sneak peeks" of another area with the camera. While this does defeat the purpose of being hidden from the player, it plays on their curiousity to check out the shown area and encourages them to explore. 

Some subsections of a level were given distinct stand-out qualities to make the memorable. For instance, one level uses a mini-gauntlet that requires the player to clear 2 mini sections to open up a room that leads to a key. Later sections of the level use the game's sunset background to make the challenging parts something valuable to remember.

While 

I added some sections using health pickups to encourage the player to try them out. I was inspired by other game's method for testing skill expression. This method , and rewarding them their success.

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

// In this section, I tried to make the first section linear.

### 2.1. Acid

### 2.2. Checkpoints
Checkpoints are given generously, at least one within each subsection of the map so exploration is not exhausting for the player. They are placed before an obstacle, sometimes during one to add challenge to some sections of the level..

### 2.3. Chompers
Chompers are introduced as a peon enemy initially. Later, they serve as an incentive for the player to platform patiently, or with caution as they are placed on smaller platforms or serve as obstacles during exploration. 
### 2.4. Health Pickups
Health pickups are introduced via alternate path in Section 1. I designed them to be items you can find as reward for exploration/completing an optional challenging section. They were also introduced to reward the player for completing a section of the level. Health packs used this way reward the player's demonstration of skill, or serve as moments of relief in the dramatic tension.

### 2.5. Keys

### 2.6. Moving Platforms
Moving platforms were n

### 2.7. Passthrough Platforms
Passthrough platforms are introduced during Section 1. It was essential for the player to grasp their mechanics as most platforming in the level was based on these platforms. I taught them both to descend and ascend a platform, then reinforced it by allowing them to use the platforms before Section 2.

### 2.8. Spikes
Spikes are introduced as a constraint on the player's movement in platforming. These teach the player on movement in Section 1, and are later used to test their skill via precision platforming.

### 2.9. Spitters

### 2.10. Weapon Pickup (Gun)
The gun is significantly stronger than the Staff, so I introduced it later mid-way through Section 2. The gun serves as the player's primary option for dealing with Spitters, out of reach enemies or for clearing sections that would otherwise be normally impossible to clear with just the staff.  The player should have some grasp of the movement mechanics, so they can apply what they know to maxmize the gun.


### 2.11. Weapon Pickup (Staff)
I decided to introduce the Staff early into the game, as the player would not have any agency against the encounters I put in without it. 

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

Originally, Section 1 was made to be much shorter, but I decided to add more platforming and teaching moments to ensure the player had the ropes with controls. This was essential before they were given the non-linear sections of the level.  

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


