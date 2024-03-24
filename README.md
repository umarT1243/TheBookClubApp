# TheBookClubApp

the homepage has a login and a signup button

on the home page you cancan click on the profile button to change details of the logged in user

the search button allows you to go to the search page which is not fully fuctioning at the momment but maybe in a future update

you can add book to library by entering the book title , author , publisher and isbn10, and then continue to add book this will add a book in the library which
you can view the added books in the library  if you click on the book . all books show up in the recycler view . as you add more books the id number on the side of the display will increase so you will always know how many books youve had inn your library , even if you choose to delete some to free upp space. you are also able to delete books that you dont want to have in your library anymore.

you can also visit the reviews page and click the plus to write a review , or write a review straught from the book you are viewing.
when writing a review just click the green plus, and type in the details .
once you have given it a rating out of 5 you sign off your name at the bottom and then submit the review .
on your reviews page you can click on a review and view in on a bigger screen.

we have the navbar at the bottom which has 3 fragments , home , events and notifications. you can navigate between each page using the nav bar at the bottom.

when there are new events it would get listed and yiu can register by clicking the green button. closer to the time of event you would get a notification to remind you.
( this feature was functioning but didnt make it past testing ) deffinently somthing we can look to improve on.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

TESTING
for testing i used esspresso testing and used it to help the view actions in my application when dealing with the adapters and database. i also have the correct dependency files in the gradle.

i also tested the device on an emulator and a physical device and realised that the positioning of the ui was changing between emulator and physical so this had to be fixed.

overall i think the use of unittests emulator testing and physical device tesing really benefitted me and helped improve my application in more ways than one.
