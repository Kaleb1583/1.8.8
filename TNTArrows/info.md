Arrows that blow up (spawns tnt) on contact with the ground, a mob or player.  

TntArrow.java: EntityArrow.java but with tnt on hit.  (replace entityarrow's code with this to use)
EntityArrow.java: Default class for arrows without tnt.  

Configuration: Line 55 & 56 (tntSpawned boolean & tntCount int)  

line number is at where spawnTNT is at (if -> for -> spawnTNT)  
(line numbers below are off by a few, need to fix but dont got time currently)  
  
Arrow Hits Mob/Animal/Player: Line 359  
Arrow Hits Another Player: Line 373 (i removed the code here since the one above handles player hits too)  
Arrow Hits Ground: Line 411  
