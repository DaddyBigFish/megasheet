![image](https://github.com/user-attachments/assets/93f730e7-da58-4f64-8e0a-027a0d2c8b80)

# How to
Simply create interactive cheatsheets / notes that will automatically adapt to the variables below using the input fields. The project MegaSheet is a single simple HTML page with JavaScript controlling the interactivity. You can feed the MegaSheet with an offline .txt file known as a 'sheet', or alternatively you can add the sheet to the 'sheets' directory in GitHub and it will automatically recognise it using the dynamic file loading via GitHub's public API.
## Variables
```
$TARGET   $DC   $DOM   $MYIP  $USERNAME  $PASSWORD  $HASH
```
## Structure
```
#     (Single hash to create a new collapsable box)
##    (Double hash to create a heading inside the box)
[*]   (Enclosed asterix to create tabs within the box)
[###] (Enclosed triple hash to create header inside a tab [*])
```
