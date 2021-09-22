#### DISCLAIMER: Yes, there may be a way to shorten this javascript and make it more readable, but you know what? Stick it up your butt and make your own if you know better! Otherwise, please enjoy :3

```------------------------------WHAT THIS IS:------------------------------
If you are using luckperms and the placeholder for expiration time of either of the two options given by luckperms, 
you might also find it annoying that you cannot shorten the time nor translate hours, minutes etc into your language. 
This javascript does exactly that!
----------------------------------CREDITS----------------------------------
Requested by: SilverCore#6666
Made by: MidnightCore#6666
------------------------------THINGS YOU NEED:------------------------------
1.) Placeholder API plugin
2.) PAPI Javascript expansion (/papi ecloud download javascript & /papi reload)
3.) PAPI Luckperms expansion (/papi ecloud download luckperms & /papi reload)
        Do NOT use /reload or plugman to enable Placeholder API!
------------------------------HOW TO EDIT:------------------------------
The only 2 things you need to edit here is the middle word of each row and if you want this piece to show or not.
Do not, under any circumstances, edit the first variable, that will make the javascript not work properly.
    1. Variable is fixed, do not change!
    2. Is the translation used when parsing the placeholder in your game.
    3. Sets the placeholder to be shown at all or not
------------------------------INSTALLATION:------------------------------
1.) Drag and drop this whole document as is into the following folder of your server: 
plugins -> PlaceholderAPI -> javascripts and edit the format as described above in HOW TO EDIT.
2.) Now you need to register this javascript in plugins -> PlaceholderAPI -> javascript_placeholders.yml
Into that file, add the following AS IS, both lines:
time:
  file: lptime.js
3.Ingame, do /papi reload.
4.) Now you can use the placeholder as follows:
  To convert %luckperms_expiry_time_<permission>% USE %javascript_time_expiry_time,<permission>%
  To convert %luckperms_inherited_expiry_time% USE %javascript_time_inherited_expiry_time,<permission>% 
  ```
  
#### !!!!!!!!!!!!!!!! ATTENTION: Do not replace the comma in front of the <permission> with an underscore! 
#### We really want you to use the comma, don't try to be a hero and use an underscore, haha.
