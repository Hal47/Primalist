# Primalist
Greetings all!

This is my first content "release" for any game, so learning pains are to be expected.  Any questions, do not hesitate to reach out:

u/brw316 on reddit

@brw316#5375 on Discord

/////////////////////////////////////////////////

Introducing the cut Special Archetype, Primalist.

Melee attacks, Defensive Powers, and Ally Buffs

The Primalist Special Archetype is a competent melee combatant. This is enhanced by its ability to shapeshift into a Hunter or a Prowler.  While in primal form, the Primalist will deal good damage and heal nearby allies.  In Hunter form, you can attack foes with tooth and claw and weaken nearby foes.  In Prowler form, you can shred enemies and stun them.

Primary:  Feral Might (melee)
Secondary: Primal Gifts (defense/support) 

//////////////////////////////////////////

Note1: At this time, this archetype is only available to server owners that run Ouroboros V2I1.  I will post an update to this repo if and when I can post bins for I25/I26 versions.

Note2: These instructions assume that you have a server set-up for  binning in order to incorporate custom content into your server environment.  If you do not, instructions to set-up a binning server can be found at:  

https://corps.ouro-comdev.com/index.php?title=Server_Setup_for_Making_Bins

/////////////////////////////////////////

To Install:

1. BACKUP YOUR FILES!!!  You never know when something can go horribly awry, so ensure your data\bin and data\server\bin are backed up to revert if necessary.

2. Place the files in the Primalist\data and Primalist\serverdata folders into the respective "YourServerName"\data and "YourServerName"\serverdata folders.

3. Place the executables from Primalist\Executables into your ROOT directory and overwrite.  If you have compiled changes to the code in any capacity, you will need to merge the uiStatus.c file that is included in Primalist\Executables\Source.  Instructions to do so can be found here:  https://ourowiki.ouro-comdev.com/index.php?title=Volume_2_Build

4. Bin the server using: 
  - mapserver.exe -createbins -verbose 2
  - Ouroboros.exe -createbins -verbose 2 -project cov

6. Create your templates
  - mapserver.exe -productionmode -templates

5. Start your server.

6. The Primalist Special Archetype will now show beneath Warshades.

//////////////////////////////////////////

To reiterate, this is the first release I have ever done, so have patience while I try to navigate this process. Play and leave feedback!!!

//////////////////////////////////////////

To Do: 

Provide a cleaner texture for AT icon
 
Add screenshots to Archetype selection page.

Get bins for i25/i26

//////////////////////////////////////////

Special thanks to:

Zach_little, darwinasm86, malonkey1, Bubblewrap and Fuzzy_c for assistance in navigating the technical side as well as testing.


SilverAgeFan and OrangeBlueHue for the design of the archetype icon.

