# Midas-Gold-Plus-bot
A simple bot for grinding in Midas Gold Plus browser flash game


This is a bot to help griding in the Midas Gold Plus browser
  flash game.
              
  
  Roadmap:


                       
  
  Changelog:    
  
  v0.1.5:
  - add a feature to get Login bonus when it wears off (~12h): 
    refresh the browser page and set up casting the skills. 
    -- If book icon is found:
    -- If we can't find the "Blessing of Apollo" icon on the screen:
    -- Move mouse cursor close to it. If still can't find:
    -- press ctrl + R for refresing the browser tab
    -- wait for a minute
    -- find and press "Play muted" button
    -- press Lvl Up thingy for 25x multiplier
    -- set the skills:
      -- for Energy mode - press staff, press 3 skills, 
         press cross, move cursor to exit position    
  
  v0.1.4:
  - improved logging features: added time, ad info
  - added movement of a mouse cursor every 4 minutes 
    even if the game is not in focus
  - fixed the book BMP: it couldn't be found in some instances            
  
  v0.1.3:
  - add a feature not to move mouse cursor if a user moved it.
   (still needs testing!)
  
  v0.1.2: 
  - add a feature to watch an ad once an hour 
    -- after each hourly cycle of the main loop:
    -- Click the Store icon
    -- Click Free Gem icon
    -- Click Watch icon, wait for 1m
    -- Click Later icon
    -- Click Exit Store icon   
                                                 
  v0.1.1: 
  - Fixed a bug where moving the browser window broke 
  the focus of the bot 
  - Made game loops 4m instead of 5m
  
  v0.1: 
  - Bot can identify a book icon and click on the university
  researches and on the traids once in 5 minutes.
