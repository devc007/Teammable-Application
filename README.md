## In this project i have used localstorage to persist data instead of Databases like mongodb or postgress SQL
When I open index.html it shows a page where a user profile and image with below a name field which shows the name of user but currently
it shows nothing just blank
![Screenshot from 2024-09-25 16-51-53](https://github.com/user-attachments/assets/47d387a1-fc79-4360-8b75-ad72df083d9a)


## explaination of different section
so first is display view-- It first show a heading "User Profile" after that there is a dog image and below it a inline element of html span, below it a edit button is given if user want to edit name-- now if website is displaying you any name so this name is fetched from local storage of browser i will tell it later that how this names are set and how they are fetched and where are they stored
So after clicking on the edit button it blocks the dislay view and open or show the edit view edit view consists simmiliar things except in name span it have an active block where user can provide the input name so if your provide the input name and clicked on save profile button what will happen is 
on click to save profile button a function will be triggered which will set the name value in local storage what user is provided and after edit view is blocked and display view will be shown and in display view name span fetch the data from localstorage so that how all things works.
