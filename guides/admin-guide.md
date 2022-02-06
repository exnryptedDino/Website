---
layout: default
title: Admin Guide
parent: Guides
nav_order: 3
---

# BloxWorld Admin Guide
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

BloxWorld's administrative system is one of the features that help run the Park, custom developed by SimonNotSus. BloxWorld's administrative system takes the form of a Discord bot (Coming Soon), Roblox module, and administrative web panel (Coming soon).

### Commands
{: .text-red-300 }
#### 1A - Permission Levels
{: .text-grey-dk-000 }
{: .no_toc }
All members who are ranked Head Lifeguard+ will gain access to various commands. Ranks and their respective admin levels are shown below. 

| Rank        | Admin Level         | 
|:-------------|:------------------|
| Head Lifeguard          | Moderator | 
| Junior Manager | Moderator   | 
| Board of Lifeguards       | Moderator     | 
| Board Intern         | Admin | 
| Aquatic Board          | Admin | 
| Aquatic Director          | Admin | 
| Vice President        | Admin | 
| President           | Super Admin | 
| Administrative Assistant          | Super Admin | 
| Board of Administration           | Super Admin | 
| Junior Corporate          | Super Admin | 
| Corporate           | Super Admin | 
| Senior Corporate           | Super Admin | 
| Chief Corporate Officer           | Super Admin | 
| Group Manager           | Creator | 
| Engineering           | Creator | 
| Community Manager           | Creator | 
| Aquatic Council           | Creator | 
| Co-Founder           | Creator | 
| Founder           | Creator | 

Depending on the role, you will only be able to perform certain commands. For example, users with Moderator commands **cannot** run ;pban, but users with Super Admin commands can. 

#### 1B - Executing Commands
{: .text-grey-dk-000 }
{: .no_toc }
When executing commands, you must take care to ensure you are doing it correctly. 

* BloxWorld's administrative system allows you to run a command by typing "/e" in front of a command. 
  * To run a command privately with the "/e" method, you need to first open up the chat to run a command like you usually would. Before running the command, however, you need to type "/e."
    * EX:  **_/e :m Hello!_**
  * This will make the command private, and this hidden from the chat. 
* You may also use the console to carry out a command. 
  * To use the console, you need to first press ";" or "'" on your keyboard. This will cause a GUI to appear at the top of your screen. When using the console, the prefix is **not** required. 
    * EX: ; (Console Opens) 
      
      **_exploit logs_**

      ( Exploit logs GUI is then shown as expected) 
   

### Acceptable Usage
{: .text-red-300 }
This is the main section of the document. It will outline everything that you can and not do with your commands. 

All major admin abuse (running ;pban all etc.) is **logged** and will result in an instant punishment! The command will be immediately canceled, and developers are notified. 

#### 4A - All commands Usage
{: .text-grey-dk-000 }
{: .no_toc }

**Arguments** = What you need to supply to run the command. 

**Allowed** = What you may use this command for. 

**Not Allowed** = What you may not use this command for. 

**Punishment** = What happens if you use it inappropriately. 

**Logs All Attempts:** Whether or not doing all as a player logs.

Commands in _italic_ do not have any consequences/information to say about them. You may use them! Commands with a ~~strikethrough~~ must not be used AT ALL! Using them could lead to severe consequences.

| Command Name        | Arguments  | Allowed | Not Allowed | Punishment | Logs All Attempts |
|:-------------|:------------------|:------|:-------------|:------------|:------------------|
| :respawn / :res / :refresh / :ref          | A player | You can respawn yourself and anybody who may request it.  |  You may NOT do :respawn all, or respawn users who **do not** request a resapawn.           |  Ranges from a warning to permanent ban, depending on the severity.          |  No.                 |
| :kick (Board Intern+).           | A player, a reason. | Anyone with 3 or more warnings or for a valid reason.  |  Anyone with 3 or less warnings and for an invalid reason.  | Ranges from a blacklist to a permanent ban, depending on the severity.            |    Yes.               |
| :ban (Board Intern+).           | A player, a reason. | Anyone with a valid reason (read the Punishment Guide). | Anyone with an invalid reason.             |  Ranges from a warning to a permanent ban, depending on the severity.       |     Yes.              |
| :unban (Board Intern+).           | A player, a reason. | Anyone with a valid reason (read the Punishment Guide). | Anyone with an invalid reason.             |  Ranges from a warning to a permanent ban, depending on the severity.       |     No.   |
| :pban (Administrative Assistant+).           | A player, a reason. | Anyone with a valid reason (read the Punishment Guide).  |  Anyone with an invalid reason.            |  Ranges from a warning to a permanent ban, depending on the severity.           |   Yes.                |
| :sm / :m (Administrative Assistant + in-park ONLY).           | A message. | Announcements that everyone needs to see.  | Messages that are unimportant / do not need to be seen by anyone. | Ranges from a warning to a permanent ban, depending on the severity.          |  No.                 |
| :mod / :admin / :superadmin (ENG+).           | N/A.  | N/A.  |    N/A.          | N/A.            |    N/A.               |
| :unadmin (ENG+ ONLY.)           | A player. | Only users who are Head Moderator+ may use this command. This can be used for users who are undergoing admin abuse, but do not warrant for a ban.  |   Using this if you are not a Head Moderator+.           |     Permanent ban.        |        Yes.           |
| :s (ENG+ ONLY).           | N/A. | N/A.  |   N/A.           |     N/A.        |                   |
| :shutdown (Group Manager+ ONLY & Host/Co-Host in trainings).           | Only users who are Head Moderator+ may use this in-store. Use if there is a serious scripting bug & with authorization from Developers/Group Owner. | N/A.  |   Using it if you are not a Group Manager+ in-park.         |     N/A.       |    N/A.               |
| :slock / unslock (Not to be used at the store. May be used at trainings.        | N.A. | N/A.  |   N/A.           |     N/A.        |       N/A            |
| :time (ENG+ ONLY).           | N/A. | N/A.  |   N/A.           |     N/A.        |       N/A.            |
| :tp / :bring (Board Intern+). | Player(s) | Only if a player is stuck somewhere and needs to be freed. | Any other invalid reason. | Warning. If continued, may lead to a demotion. | Yes. 
| :to | Player. | Needing to be teleported to a certain situation, and any other valid reason. | Unnecessary reasons. | Demotion. | Yes. | 
| :btools (ENG+ ONLY). | Player. | N/A. | N/A. | Instant termination if used by a user who is not a Developer. | Yes. | 
| :view / :unview | Player. | To watch suspicious players (Ex: exploiters). | Stalking SHRs (Junior Moderator+). | Warning. | Yes. |
| :ff / :unff | Player. | To be used for Low Ranks at training. | Any other reason. | Warning. | Yes. | 
| :jump (Vice President+). | Player. | If a player is stuck in a seat and can not get out. | Any other reason. | Warning. | Yes. | 
| :fly (Vice President+). | Player. | If a Junior Moderator needs to supervise. | Any other player using the command. | Warning. | Yes. | 



| Command Names That Can Be Used (No information needed)       |
|:-------------|
| _:cmds_ |
| _:bans / pbans_           |
| _:info_         |
| _:pm (Board Intern+)._           |
| _:admins_           |
| _:chatlogs_           |
| _:logs_           |
| _:joinlogs_           | 
| _:shutdownlogs_           |
| _:viewtools_ | 


| Command Names that CAN NOT Be Used (No information needed)       |
|:-------------|
| ~~:crash~~           |
| ~~:h (SHOULD NOT BE USED BY ANYONE AT THE STORE, NON-HOSTS AND CO-HOSTS AT TRAINING)~~           | 
| ~~:change~~  |
| ~~:ws / :speed~~ |
| ~~:jumppower~~ | 
| ~~:god / :ungod / :heal~~ | 
| ~~:sit~~ | 
| ~~:team~~ | 
| ~~:insert~~ |
| ~~:clear / :clr~~ | 
| ~~:tools~~ | 
| ~~:removetools~~ | 
| ~~:startergear / :clearstartergear~~ |

### Conclusion
{: .text-red-300 }
You reached the end of the Admin Guide! Please ensure that you read **all** the information thoroughly before you use your commands. If you have any questions, please refer back to this guide or contact a Vice President+.
