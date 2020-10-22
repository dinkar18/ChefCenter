# ChefCenter

Chef center is a dynamic android app where a user can find plenty of recipes. 
user have to log in to access the recipes.
user can register aswell using his name, username(unique) and password.
the login is managed by firebase authentication.
user once logged in land to homepage where he/she can have access to recipes.
the recipes are viewed with a image, recipe name, time required to make the recipe and category of recipe.
if a user press on a recipe, he/she will land to description page where he can see the enlarged image of recipe along with full description on how to make it.
To make the app dynamic, thers's a option for the user to upload a recipe
any user can upload the recipe by pressing the upload button located on the bottom right of home page.
user need to enter the fields and a image to upload.
recipe will not be uploaded in case of a missing field.
the uploaded recipe will get uploaded to realtime database in it fields and image will be saved to firebase storage.
all the recipes which we saw on homepage are coming from same realtime database and storage.
so when a user upload a recipe, a new recipe will be added to the list of recipes.
a user can search for a specific recipe using its name or category

----only admin-----

users can upload a recipe but once uploaded, user can not delete the recipe from the database.
the uploaded recipe will be shown to all the users in the home page.
if someone wants to delete a uploaded recipe he/she need to have the admin login id.
only admin have the key to delete a reciepe.
a specic username /password is required to do so.
in the description page, if u long press the image, there will be a popup.
only a specific username and passsword will do the job and can delete the recipe
if someone enters the wrong email or pasword, a popup will come saying "Only Admin are authorized to delete the recipe"

the right credentials are

username: dinkar
password: 123456d

REQUEST : if u access anything, please dont delete the recipes as app will look dull without any recipe. if u want to try, first upload a recipe and then try deleting it

THANK YOU
