# Arcturus Morningstar 3.5.1

## Release README.md

This Release of Arcturus Morningstar was compiled at 06:00:34 on 29/04/2022 and it's build hash is: 
**[c8254e2eb60dae63c2b6bbf0c3718fee](https://git.krews.org/morningstar/Arcturus-Community/-/pipelines/3804)**

This version will be the final 3.x build of Arcturus Morningstar, as such we have decided now is the time to release a stable build.

The next version of Morningstar will have major fundamental changes to the core of the emulator, which will break a lot of current 3.x plugins, but don't worry! We'll be releasing documentation as these changes arise, and we'll be sure to publish how to update your plugins for full 4.0 compatibility.

To prepare your hotel for 3.5.1, ensure you have ran the updates in the updates SQL folder. Please remember these are all the database changes for 3.0.0 -> 3.5.0

Official Documentation for Developers is coming soon to the 4.x branch, so please keep an eye out!

**Changelog:**

1.  Fixed Homeroom Forwarding (No more double room bug) (Skeletor)
2.  Multiple Composers have been updated with their actual names (UnknownComposer5 > MysteryBoxKeysComposer etc) (Skeletor)
3.  Fixed NPE in HC Payday (Snaiker)
4.  Added check to gift messages max length (brenoepic)
5.  When a habbo receives a handitem, they now turn towards the habbo (Senpaidipper)
6.  Fixed Exception on answering polls if they have no answer (brenoepic)
7.  User furniture is now ejected if their rights are removed (brenoepic)
8.  Pressure plates now work as intended (brenoepic)
9.  Fix ticks in crackable furni interaction (Snaiker)
10.  SupportTicketEvent is no longer fired twice (Snaiker)
11.  Code for Redeem Voucher in catalogue has been cleaned up (Snaiker)
12.  Youtube TV now works again & uses the official method (Brenoepic)
13.  MySQL Connector has been updated (Fixes confidential issue #889) (Skeletor)
14.  Sticky notes now lets anyone with rights edit them (dap)
15.  Crackable items can now give wall items correctly (Snaiker)
16.  Offer ID fix for catalogue page highlights (ArpyAge)
17.   Fixed NPE in SubscriptionCommand when a user is not online (brenoepic)
18.  Fixed issue when buying furniture with a badge attached (brenoepic)
19.  Fixed ColorWheel interaction (brenoepic)
20.  Fixed possible NPEs and fixed softkick issue where it kicked anyone 
21.  Beds now work properly from FurniBuilder (Mike)
22.  Trap Interaction Fixed (Kitt Mustang)
23.  Small Custom Wired Fix (ArpyAge)
24.  Rewritten Calendar System (brenoepic)
25.  Fixed NPE With adding friends who are offline (ArpyAge)
26.  New Interaction: InteractionBuildArea (brenoepic)
27.  Fixed RoomDataComposer to give the correct score (Snaiker)
28.  Fixed Football Valid moves (Remco)
29.  Fixed busted inventory fragments (Bill)
30. Fixed SQL Exceptions (after updating the sql connector)  Snaiker
31. Fixed Summon Commands (brenoepic)
32. Fixed black screen on doorbell (brenoepic)
33. Add bot motto max length (Bill)
34. Add moodlight color config (Skeletor)
35. Fixed empty gifts being possible to send (ArpyAge)
36. Fixed football valid moves (Remco)
37. Fixed Calendar Timestamp (brenoepic)
38. Fixed users not being able to pick up their pets in other peoples rooms once place(brenoepic)

39. Custom Stacking setting to stack bigger items on top of smaller ones (ArpyAge)
40. Fixed Floor Plan Editor (brenoepic)
41. Added new RCON command 'ChangeUsername' (snaiker)
42. Changed order of operations so Buildheight event can override max/min height of tiles (ArpyAge)
43. Fixed Empty Inventories bug (brenoepic)
44. Fixed items with lay for wired.place.under
45. Fix duplicate badge bug (Snaiker)
46. Fixed Mannequin Naming (brenoepic)
47. Fixed Group Forums so guild admins can now moderate forum threads (Harmonic)
48. Fixed Groups so guild admins can now accept members (Harmonic)
49. Updated Catalog Layouts (Tenshie)
50. Fix Room Change during teleport (brenoepic)
51. Fix teleports on floorplaneditor (brenoepic)
52. Fix Invisible rooms in "my friends" without rights. (AlfreviD)
53.  Added "Atcg" Achievement on crafting (Harmonic)
54. Fixed daily respects and scratches not showing up without reloading (nttzx)
55. Fixed Users should not be able to enable effects/use effects when they have a helmet on from team wired. (AlfreviD)
56. Updated Vouchers to select from voucher history WHERE voucher_id = ? (oshawott)
57.  Added effect_vendingmachine_no_sides (Oliver)



-- And probably many more I missed!
Cheers, Krews.org