## dog sitting site:

# Setup
- DO NOT USE THIS FILE CREATE A BRAND NEW APP ON YOUR LOCAL COMPUTER USE THIS READ ME AS A GUIDE FOR THE CHALLENGE.
- make a new corneal app called code_challenge

- run bundle / change active record / change migration  statement in spec_file and config.ru 

- go to GitHub and create a new repository 

- connect your code challenge to the repository and upload to GitHub.

- use corneal gem to make models and tables for 

Dog: name, age, img_url, (belongs to a user)

User: name, (has many dogs)

- make seed data (create a seeds.rb file/ fill it with 5 dogs and 5 owners)

# Seed File:

DOGS:
{name:"Trixie Pawtell", age:2, img_url:"https://prettypup.co.uk/wp-content/uploads/2020/05/french-bulldog.jpeg"}
{name:"McFly", age: 5, img_url:"https://www.loveyourdog.com/wp-content/uploads/2019/08/Pitbull-Terrier-Mixes-900x500.jpg"}
{name:"Ursula", age: 10, img_url:"https://i.insider.com/5dfe62a2954bda02a25cfd52?width=700"}
{name:"Mashed Potato", age: 2, img_url:"https://i.pinimg.com/originals/65/8f/89/658f89216f56deae9660ebba09cf5de1.jpg"}
{name:"Gumdrop", age: 6, img_url:"https://hips.hearstapps.com/vader-prod.s3.amazonaws.com/1565637384-51DuxaRPXPL.jpg?crop=1xw:1xh;center,top&resize=480%3A%2A"}

USERS:
{name:"Dev Patel"}
{name:"Jennifer Lopez"}
{name:"Janelle Monae"}

# Relationships 

- assign random dogs to user in your terminal so every dog has a user. 

# Controller/Views
- in the controller make a route for seeing all the dogs called /dogs

- in the controller make a route to show all the users called /users

- set up your views for both your routes(erb files)

# HTML:

Dogs:
- in your dogs views display a title of "Available Dogs" in an h1 tag. 
- after that have all the dog names in an h2 header
- ages in a h3 header
- display the dogs image in an img tag
- all of the above should be contained in a div with an id of dog_container. 

Users:
- in your users views display all the users names in an h2 header and underneath list the dogs names that belong to them in an unordered list.

# CSS: 
/dogs
- make a border around your dog_container box. 
- change the background color to whatever color you want 
- change the image size to 400px
- display flex and justify content space between. 

/users 
- change the background color 
- change the text color of the dogs names
- underline the names of the users 
