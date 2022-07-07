・Welcome to guide for using stand creator!

・I heavily advise you to read through the entire guide for the full understanding of the project.

```
DOCUMENTATION OF THE FUNCTIONS :

1. Create('COMMANDNAMEHERE', function() --/ This will create an chat command / replace COMMANDNAME inside the brackets with your desired command name.
2. CreateAction('LOOPNAMEHERE', function() --/ This will create an action this should be placed before (1).
3. CreateKeybind('KEYBINDHERE', function() --/ This will create a keybind command, it'll only work on the stand (Refer to "https://developer.roblox.com/en-us/api-reference/enum/KeyCode") for keybinds.
4. CreateTargetAbility("COMMANDNAMEHERE", function() --/ This will use an command on a target you choose / eg..(Attack! Bacon)
5. CreateLoop("LOOPNAMEHERE", function() --/  This will begin looping the arguments specified until stopped (5).
6. StopLoop("LOOPNAMEHERE") --/ This will stop the specified loop (4).
7. Stand.Action = "LOOPNAMEHERE" --/ This will begin the specified loop/action that you have created (Refer to 2). Stand.Action = "" will essentially stop the action.
8. Play(ID, true) --/ This will begin playing the specified audio in the first argument, The second argument true/false + If the second argument is set to false it'll begin looping the audio.
9. Stop() --/ This will stop any audios from playing.
10. AnimPlay(ID,SPEED) --/ This will begin playing the specified animation (ONLY DH / ROBLOX ANIMATIONS), SPEED will control the animationspeed (Default is 1).
11. AnimStop(ID,SPEED) --/ This will stop playing the specified animation, SPEED will control the stopping speed (Default is 1).
12. Chat("TEXTGOESHERE") --/ Will chat the specified text in the first argument (stand cry / eg.. following you master).
13. Buy.Item() --/ Will buy the specified melee (make sure you have enough cash). eg.. Buy.Knife(), Buy.Bat(), Buy.StopSign(), Buy.Shovel(), Buy.Pencil(), Buy.Nunchucks(), Buy.SledgeHammer(), Buy.Grenade(), Buy.Flashbang(), Buy.Boxing(), Buy.Default().
14. Hit(true) --/ If the first argument is set to true it'll do a charge attack + If the first argument is set to false it'll do a quick punch.
15. Crew(true,ID) --/ If the first argument is set true it'll join the crew specified(ID) + If the first argument is set to false it'll leave any current crew.
16. DropMoney(Amount) --/ This will drop the amount of money specified.
17. GetNearest() --/ This will get the nearest enemy player.
18. Equip(Tool) --/ This will equip the specific tool eg.. "Combat", "Wallet", [Knife], [Bat], [StopSign], [Shovel], [Pencil], [Nunchucks], [SledgeHammer], [Grenade], [Flashbang] --/ In-case your item is not on this list use darkdex.
19. Unequip() --/ This will unequip any currently equipped tools.
```
・All the above functions can & should be utilized on Stand-Creator abilities.
```
DOCUMENTATION OF ABILITY CREATING :

Create("Hello!", function() --/ Inside the " " we have named this ability Hello!, So if we were to type Hello! in-game the command would run utilizing function (1), You can rename the Hello! to anything you want.
    Chat("Hello!") --/ We will make the STAND say Hello!, Utilizing function (13).
end) --/ Always remember end) on any ability you created.

Create("Crew!", function() --/ Inside the " " we have named this ability Crew!, So if we were to type Crew! in-game the command would run utilizing function (1)
    Crew(true,2) --/ 2 Is the crew ID that the stand will join to utilizing function (15), You need to be in the roblox group of it in-order to join crew.
end) --/ Still remember end) on any ability you created.

CreateAction("Summoned", function() --/ Inside the " " we have named this action Summoned utilizing function (2), The action wont begin by itself you need to create an ability seperately to use it.
    STAND.Character.HumanoidRootPart.CFrame = OWNER.Character.HumanoidRootPart.CFrame*CFrame.new(1,1.85,2.5) --/ This will control the stand position while the action is running.
end) --/ Still remember end)

Create("Summon!", function() --/ Inside the " " we have named this ability Summon!, So if we were to type Summon! in-game the command would run utilizing function (1)
    Stand.Action = "Summoned" --/ We can change the action to the one that we previously created & named Summoned.
end) --/ Still remember end)
```
・All of the above examples will explain simple ability creating & should be read throughout.
```
STAND NAME & ABILITY IDEAS :
・https://jojowiki.com/List_of_Stands

STAND OUTFIT IDEAS :
・https://www.roblox.com/games/9714571746/JoJos-Bizarre-Collection 

JOJO SOUND EFFECTS :
・https://www.roblox.com/develop/library?CatalogContext=2&Subcategory=16&CreatorName=jojoaudio&SortAggregation=5&LegendExpanded=true&Category=9
・https://www.roblox.com/develop/library?CatalogContext=2&Subcategory=16&CreatorName=Tsuagon&SortAggregation=5&LegendExpanded=true&Category=9

USEFUL SOURCES FOR BEGINNERS :
・https://developer.roblox.com/en-us/articles/Understanding-CFrame
・https://developer.roblox.com/en-us/learn-roblox/coding-scripts
・https://scriptinghelpers.org/
・https://developer.roblox.com/en-us/onboarding
・https://youtube.com/playlist?list=PLw1uWqQBDcgjKqFjPNgtVtBNx3xTGz-l7

HOW TO USE MULTIPLE ROBLOX INSTANCES :
・https://wearedevs.net/d/Multiple%20Games
・https://github.com/ic3w0lf22/Roblox-Account-Manager

HOW TO USE THE STAND CREATOR :
・https://www.youtube.com/watch?v=FA7TLi7KxhE
・https://www.youtube.com/watch?v=Pg-jc7XTCSg
```
・Each of the helpful links provided will provide you some information on how to use utilize the script to it's full effect & how to make it work correctly.
```
FAQ :

The stand script isn't executing or doing anything?
・Make sure to execute on the correct account & This only occurs if you have incorrect usernames or incorrect username order.

The stand is damaging you?
・Make sure to be in the same crew as your stand.

The stand stand is getting kicked when executing?
・Make sure to have a good ping under 200.

Reach bugging or other things bugging?
・Make to use any of the following exploits: KRNL, Synapse X, Fluxus.
```
・It's truly been an incredible journey creating this project, I remember the first day when i was scared of even uploading this project, I've learned alot.. If you're curious about something or genuinely want something, You shouldn't be scared of it, Appreciate the opportunity and the chance of taking action on it, Approach & explore it because you'll never know where it leads you to.
