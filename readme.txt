To use on your server, you'll need to do a couple things

1.Define PC_Warden
I don't know how this is done since I tested using Primalist as a placeholder/dummy, but according to my understanding, the AT needs to be defined in the server source somehow. Same way all the other ATs are presumably
 Then you'll need to change any files that include the line PC_Primalist with PC_Warden. This should only be the PC_Primalist.def file and the classes.def

2. If you've made any changes to the files I have, You'll need to merge the changes. I've tried to make this as simple as possible
a list of files you'll likely need to edit

in Powers:
Inherent.powersets (search Rally)
Inherent_Inherent.powers (search Rally)
Temporary_Powers.powersets (search Rally)
Temporary_Powers_Temporary_Powers.powers (search Rally)

in texts
menuMessages.ms (search Class_Warden)
the other translations are handled in their own translation files (Warden_info.ms and Warden_powers.ms) so you won't need to worry about them

also it's an astronomically low chance we ended up making identical pstrings, but if you want to be safe go ahead and search my files with the pstrings you created and see if any redundancies show up

If you have any issues with the AT, message me on discord Yikes#8008 and I'll see how I can help, but I kinda bumbled my way through this anyways lol
