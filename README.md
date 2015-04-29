# flshb0t
A bot for Magic streaming

-----------------------------------------------------------------------------------
 FISHBOT COMMANDS LIST
 
 For bug reports, questions, suggestions, etc.. contact  Overvoltage
 You can also report problems or make suggestions by typing this in chat: !contact <message>
------------------------------------------------------------------------------------
 
!commands - displays this link

!leave  - fishbot leaves your stream permanently (usable by streamer only)
 
!raffle start - starts a raffle that can only be won by a follower (streamer only)

!raffle - joins a raffle if there is one going on

!modsonly - commands become usable for mods only (on/off, usable by mods only)
 
!shutup - disables/enables AI (usable by mods only)

!odds  - calculates probability given 4 parameters: cards left, cards drawn, outs in deck, outs required (example: !odds 60 7 4 1    ---> 39.95%)
 
!legacy/modern/standard/vintage PlayerName - looks up decks by player
 
!card <card>   - looks up card
 
!price <card>  - looks up price of card from www.cardhoarder.com
 
!addquote - adds a quote for the stream

!quote - shows random quote

!delquote - deletes last quote. If number is specified, deletes Nth quote (mods only)

!uptime - shows uptime of stream
 
!punt - adds punt to punt counter of stream (mods only)
 
!removepunt - removes latest punt (usable by mods only)
 
!dic <word>  - looks up word in dictionary
 
!ud <word>   - looks up word in Urban Dictionary (mods only)
 
!catfact - looks up random fact about cats.
 
!imdb <title>   - looks up movie title on IMDB
 
!contact <message> - sends bug report, suggestions, etc

----------------------------------------------
        BETTING SYSTEM    
---------------------------------------------
!match - starts a bet on match. Betting lasts 60 seconds (only usable by mods, disables all other functions for the duration)
 
!bet w/l points - places a bet on the match (if the betting timer is running)
 
!win - reports match as a win (usable by streamer only)  
 
!loss - reports match as a loss (usable by streamer only)
 
!void - voids the match and all bets made on it (usable by mods only)

!top5 - displays the top 5 points holders

!points - displays your points
 

Viewers will not be given the 2500 starting points before either making a bet or typing !points. Everyone receives 100 points every day.

--------------------------------------------
        Magic Trivia

---------------------------------------------
!trivia <number of rounds>   - starts trivia (mods only)

!strivia    - stops trivia (mods only)

!addtrivia Question*Answer   - adds question to trivia database (after confirmation)


-------------------------------------------------
Administrator commands:

!join <stream name>  (e.g. bahra_)       --- bot will enable all scripts for this stream, and add it to autojoin

-----------------------------------------------------


Change log:
    23/03/15 - Added !raffle start , !raffle  and !join  commands
    06/03/15 - Added !addquote, !quote and !delquote
    05/03/15 - Fixed bugs
    15/02/15 - Added odds to betting, added trivia
    14/02/15 - Added !shutup command to disable AI.
    13/02/15  - Added !top5 command and !void command, removed randomized greeting messages (annoying)
    12/02/15 - Improved betting system. Added command to report problems, make suggestions, etc: !contact
    12/02/15 - Added betting system
