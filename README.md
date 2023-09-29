# Agent-Hunt

### Developer Tool
The tool I developed to greatly increase the speed of the game development process and provide a great benefit in specific testing and in the next stages, adding innovations to the game faster and solving bugs faster.
<br/>
<li> <b>Credit :</b>        It gives 10k coin for each click on the button.
<li> <b>Diamond :</b>          It gives 10k diamonds for each click on the button.
<li> <b>Revive Kit :</b> It gives 1 revive kit for each click on the button.
<li> <b>Clear :</b> Whenever the button is clicked, all values are reset to zero.
  <br/><br/>
  
<li> <b>Play :</b> After selecting the desired level using the buttons on the right and left sides of the 'Level' and 'Chapter' values, clicking the 'Play' button will start the chosen section.
<li> <b>End Level :</b> When a level is being played, pressing the 'End Level' button completes the current level. The 'End Level' button does not function while in the menu.
<br/><br/>
  
<li> <b>New Bounty :</b> Bounty levels are designed for players to earn extra rewards and the loading time for each bounty level is one hour.When the 'New Bounty' button is clicked, the bounty level loads without the need to wait for this duration.
<li> <b>End Bounty :</b> When a bounty level is being played, pressing the 'End Bounty' button completes the current bounty level.
  <br/><br/>
<li> <b>Die :</b> While playing a level, pressing the 'Die' button will kill the player.
<li> <b>Unlock Guns :</b> Unlocks all weapons locked in the weapon store
<li> <b>Next Weapon :</b> It shows which weapon will be unlocked at the end of the next level and what percentage the weapon will be unlocked in that level.
<br/><br/> 
  
![Developer Tool In Menu](https://github.com/huseyinkaraaslan/Agent-Hunt/assets/108534143/428e8321-638d-4170-b7f9-0cbb9633e8ac)
  
### Aim System
The aim system I developed using Animation Rigging.<br/>
The character's designated joint point(left hand, right hand) is directed towards the player's aiming point

[Gameplay](https://youtube.com/shorts/W_alZdidL84?feature=share)
<br/><br/>


### Sniper Enemy
The sniper enemy feature I added to the game scans between two specified points by controlling the current point movement with MoveTowards. 
<br/><br/>If the laser touches the player during the scan, the laser waits for 2 seconds at the point of contact with the player's body and goes into alarm (All enemies).
<br/><br/>When the alarm is raised, no matter where the laser is (even if another enemy sees the player and the laser is far away), we slowly aim the laser at the player's head.
I added vibration to the laser to make it more realistic when the sniper enemy aims the laser at the player's head and holds it steady.

[Gameplay](https://youtube.com/shorts/V0ldDtvo2dU)
