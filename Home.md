## Upcoming

- [ ] Sold pets global history
- [ ] More evolutions
- [ ] Better staggered rewards

## The Main Menu
Yay! you're in pixel pets. Now what's all this stuff about?
I will go over each element and explain what it does, so you can start hatching eggs and fighting in no time.

### Adding pixel tokens
![image](https://user-images.githubusercontent.com/12151584/135686980-1cda999b-90dd-4acc-9e87-fc04fe0caa6a.png)

To get started, you will want to add some pixel tokens. To do that, simply click that "+" button right next to your account name.

You will be taken to Ref Finance, where you can swap Near for PXT, which you have to wrap into wNear first

![image](https://user-images.githubusercontent.com/12151584/143616035-81063542-b615-4fe1-bf37-83bdffeb6220.png)

Once confirmed, you can now swap it into PXT

![image](https://user-images.githubusercontent.com/12151584/143615909-9fdd09f3-061f-4c12-9039-9b33cfcd6c42.png)

Refreshing the game page should display your newly acquired PXT! Congratulations :)

### Your pets
![image](https://user-images.githubusercontent.com/12151584/135687231-95a4a27e-9dcd-488f-9b24-a41f30e5a7d8.png)

This is where you will find all the pets you have! You always start with these 3, so you can check out how the game works.
Speaking of which, let's try and do that, shall we?

### Starter Pets
Each player starts with 3 starter pets: Phybo, Clin and Snock.
These pets are very weak, but good enough to get your start into the game!
Phybo, Clin and Snock can't hatch from eggs, since they are just weak starter pets.

## Fighting
Select your 3 pets on the right by either right clicking them, or pressing the "Select Pet" button.

![image](https://user-images.githubusercontent.com/12151584/135687399-6cc92364-4933-420c-b963-9c180a430a42.png)

Once they're all selected, just press the "Search Match" button and wait a little bit!

![image](https://user-images.githubusercontent.com/12151584/135687493-26c07869-f93e-48aa-8912-b3cea6f4fee2.png)

### Combat System
The combat is automatic, and the way it works is very simple. 
Each player attacks within the order of their creatures in crescent order. 
Being Pet #1 the first attacker on each side, and up to Pet #3. 
This sequence loops until one of the players has lost all of his pets in combat and the winner is decided. 

![image](https://user-images.githubusercontent.com/12151584/135687748-cf5a145d-0dd8-460d-8b16-a64938174fcf.png)

You can speed up the fight by clicking the buttons on the bottom!
At the end of the match, each pet gets up to 50 experience based on enemy strength and pets that fainted will be injured for a period that is equivalent to its level.
You also get or lose some ranking, depending if you've won!

Now, what exactly decides who won? Let's look at the stats each pet has, shall we?
To do so, simply click in one of your pets on the right tab!

![image](https://user-images.githubusercontent.com/12151584/135688086-c8d85dcb-e42c-464b-9b52-c6030f46dee2.png)

Once in here, you can see your pet stats, but there's not a lot of info about them, so, let me tell you how each one works.

![image](https://user-images.githubusercontent.com/12151584/135688269-15bdda8f-6c1f-43f4-b9b9-c2a637a089be.png)

### Level
![image](https://user-images.githubusercontent.com/12151584/135688347-0c058ba4-b4c1-4e2e-9365-7b86567358ff.png)

The level of the pet. Each level increases the stats of the pet by 2%. Also the injured duration raises with each level.
You can also check the progress of the level on the experience bar right next to it. The formula applied is: `baseStat * level / 33`

### Power Level
![image](https://user-images.githubusercontent.com/12151584/135688556-bf1f94e3-637c-4c23-9dfe-9549497ddf86.png)

The power level is a random number between 30 and 100 and affects the stats of the pet based on it's value. 30 decreases the stats by 20%, 100 increases the base stats by 60%. The formula applied is: `baseStat * (powerlevel - 65) / 50`

### Attack Type
![image](https://user-images.githubusercontent.com/12151584/135700952-e0707a19-edc8-484d-807a-7847c04d0799.png)

The Element type the creature will inflict when attacking. This element reacts with other elements, having a stronger effect against some elements and weaker against others. For more information go to: https://github.com/pixeldapps/pixelpets-wiki/wiki/Pets-Overview#pet-type-calculation

### Body Type
![image](https://user-images.githubusercontent.com/12151584/135700942-18dbf96f-3ca5-4abd-8796-755f6a8ad2c6.png)

The Element type of the creature. When received damage from another element, the creature will take more damage from some elements and less from others.
For more information go to: https://github.com/pixeldapps/pixelpets-wiki/wiki/Pets-Overview#pet-type-calculation

### Damage
![image](https://user-images.githubusercontent.com/12151584/135700967-bb940ce8-8af8-472a-aaa9-c67e7a6aa84d.png)

Damage is the raw amount of damage a creature can cause, this by-passes the element synergy, but can be dodged.

### Armor
![image](https://user-images.githubusercontent.com/12151584/135700985-86e44aaf-159c-488d-8b5a-7ec1f2ad0195.png)

Armor is how much raw damage a creature can soak, this does not apply for magical damage.

### Magic
![image](https://user-images.githubusercontent.com/12151584/135700981-233d0296-2a8e-4ba2-b4cc-3bfecda9b4e1.png)

Magical damage is the element damage a creature can inflict, it can by-pass defense but can also be dodged.

### Speed
![image](https://user-images.githubusercontent.com/12151584/135700971-2c3777e2-a475-4c86-8e74-8915c6a28949.png)

Speed increases the chance that your creature will dodge an attack.

### Rarity
![image](https://user-images.githubusercontent.com/12151584/135701023-36afbf81-d3d4-4718-bf1c-082c12290b3e.png)

The creature's rarity is tied to the egg from which it hatched from. The rarity of a creature will increase its base stats.
Being Common: 0%, Rare: 10%, Epic: 17%, Legendary 26%

### Drop chance
Some pets get hatched more often then others pets, currently there are 3 categories:
Common: 85%
Rare: 19%
Very Rare: 1%

Depending on drop chance pets are a bit stronger.

### Merging Pets
![image](https://user-images.githubusercontent.com/12151584/143616782-4288fc3b-baad-40ff-b5c8-951b3be1f58e.png)

It's possible to merge two pets of the same type and rarity to enhance the power level of the primary pet and also increase the rarity if the power level is already at 100.

The improvement of the power level is calculated by primary pet `power level + secondary pet power level / 30 + 1`

The improvement of the rarity is calculated by `78 + secondary pet power level / 30 + 1 * 2`

For the final pet the train level of the primary pet is taken.

## Some other information

### Starting Tips
Here are some good starting tips if you're new to Pixel Pets!

1. Buy a bunch of really weak pets

Buying several pets allow you to play the game more often, making your pets simultaneously stronger faster. You should aim for a full roster (28/28) but half of that will already ensure that you can play matches without having to constantly wait for units to stop being injured.

2. Train and Hatch while Offline

Training is better when you're about to leave the game untouched for several hours, this will ensure that once you get back in, you have eggs to hatch and trained creatures ready to fight

3. Balance out your creature types

Having a variety of different creatures can ensure that you won't get knocked down by someone who has a creature type that is stronger than yours! Make it varied

4. Keep an eye on the market

A lot of players just want to make a quick buck, take advantage of that! You can find really good and strong pets in the market every now and then, and those will guarantee that you can climb rank like no one other.

### Evolving Pets
At certain levels, creatures can evolve. Which are in two stages: Level 40 and Level 80 - Once your creature reaches that level, you can pay a small fee to evolve it.

![image](https://user-images.githubusercontent.com/12151584/143607167-ad60395c-a730-40eb-8b6a-ffcf8d37e81a.png)

Each evolution increases the pet overall stats by 10%

![image](https://user-images.githubusercontent.com/12151584/143607100-92e26632-ba1a-4324-9a67-bfd58f2b5d03.png)

Some creatures, however, do not evolve. They're usually a bit stronger for that reason.

### Training Pets
![image](https://user-images.githubusercontent.com/12151584/135688447-3a45899c-b319-4f7b-b3f1-33cb81f826d6.png)

It's possible to raise the training level of the creature to up to level 10. Each training raises the pet base stats by 4%. The formula applied: `baseStat * trainLevel * .04f`

![image](https://user-images.githubusercontent.com/12151584/143607533-b130eb11-e788-4a49-96d0-8f375508d6b7.png)

While training, the creature is unable to fight or to be sold. It will remain training with the following formula: 
(3 hours * current train level) So, if you train a creature from train level 2 to train level 3, it will take 6 hours until it is done.

![image](https://user-images.githubusercontent.com/12151584/143612832-acbc4ae9-8b6c-4af6-938d-72413b8a3b8a.png)

### Fighting Points
![image](https://user-images.githubusercontent.com/12151584/135701088-4c1ef8ad-bdb9-4d57-87fc-7a1ea6e324b4.png)

Fighting points are a currency used to fight other players. Whenever you fight, you spend 1 fight point. When it reaches 0, you can spend 0.25N to add an additional 100 fighting points to your balance. Additionally you receive an egg when refilling your fight balance with a chance of 97% getting a common egg and 3% getting a rare egg. This costs are used to cover the gas and storage costs of the fighting system.
