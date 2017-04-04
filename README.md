# Export-facebook-friends-mail-addresses-
Facebook prevents users from exporting contacs directly to other social media web sites like Google+ or Linkedin. Consequently you can't directly import facebook friends to your google contacts. This is a manual for a workaround and takes about 5 minutes.

## 1. login to Yahoo or create an account
## 2. Go to contacts

https://github.com/christianreiser/export-facebook-friends-mail-addresses-/blob/master/images/1.jpg

## 3. Import facebook friends

https://github.com/christianreiser/export-facebook-friends-mail-addresses-/blob/master/images/2.jpg

## 4. export contacts as Yahoo CSV 
(actions -> Export...-> mark: Yahoo CSV)
this file will be empty but we will use it as a template later on

## 5. Print all contacts

https://github.com/christianreiser/export-facebook-friends-mail-addresses-/blob/master/images/3.jpg

## 6. Basic view

https://github.com/christianreiser/export-facebook-friends-mail-addresses-/blob/master/images/4.jpg

## 7. Cancel

https://github.com/christianreiser/export-facebook-friends-mail-addresses-/blob/master/images/5.jpg

how it should look like:

https://github.com/christianreiser/export-facebook-friends-mail-addresses-/blob/master/images/6.jpg

## 8. mark and copy all contacts (IMPORTANT: only copy contct and mail adress, don't mark and copy heading and copyrights on the bottom)

## 9. Paste all in the first columb of a .csv file (i.e. excel or LibreOffice Calc). Save file.

## 10. open the (IPython file)[https://github.com/christianreiser/export-facebook-friends-mail-addresses-/blob/master/export%20and%20sort%20name%20and%20mail%20from%20facebook%20friends.ipynb] from the github repository.

## 11. Change the filepath in the 3. line to your saved .csv filepath

## 12. Run code and copy & paste into the Yahoo CSV template fro step 4
copy&paste the names in the columb First
copy&paste the email adresses in the columb Email

## 13. import this file in google contacts

