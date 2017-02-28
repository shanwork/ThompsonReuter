Basic coin conversion single page app
=====================================

Notes:
=======

1. Including the styling, I took about two hours to get the state of the application to what it is (Wednesday Feb 22 morning)

2. The code is not a lot, so I've included the style and script blocks within the HTML:
If I were to separate out these as their own files: 
STYLING
=======
 would be a folder at the same level as index.html calls styles and the css file would be called something like <name>.css which would contain everything within and NOT including the '<style>' '</style>' tags
reference would be something like <link rel="stylesheet" href="styles/main.css">

JAVASCRIPt/ANGULAR
===================
Again, depends on how extensive the code is. I would create a folder called scripts and put all the code between and not including <script> </script> tage
into a file called app.js
this would be access in the html as <script src='scripts/app.js> 
Again, for multiple MV* flows the way I structure my scripts folder is
scripts/app.js
scripts/controllers/ - all controllers go here
scripts/globals/ - all service or factory classes go here
Maybe add the following
scripts/directives
scripts/misc
scripts/config

The following notes below are because I didnt have the bandwidth to do so

3. I haven't been able to search for the currency pound symbol. I'm using '#' I havent done any research in this, but I'm assuming it would have to be some glyphicon

4. The app is tested only on IE, chrome and firefox.  

5. Validation is incomplete - I havent been able to implement validation of '#3.45p' or '7.8p'