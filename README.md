# Agent-Hunt

### Sniper Enemy Feature
The sniper enemy feature I added to the game scans between two specified points by controlling the current point movement with MoveTowards. 
<br/><br/>If the laser touches the player during the scan, it waits for 2 seconds at the point where the laser touches the player's body and the alarm state is true (All enemies).
<br/><br/>When the alarm is raised, no matter where the laser is (even if another enemy sees the player and the laser is far away), we slowly aim the laser at the player's head.
I added vibration to the laser to make it more realistic when the sniper enemy aims the laser at the player's head and holds it steady.

[Gameplay](https://youtube.com/shorts/V0ldDtvo2dU)
