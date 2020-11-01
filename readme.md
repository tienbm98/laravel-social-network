## Laravel 5 - Simple Location-Based Social Network 
It's location-based social network using the Laravel PHP framework.

### Installation
* git clone https://github.com/tienbm98/laravel-social-network.git projectname
* cd projectname
* composer install
* php artisan key:generate to regenerate secure key
* create new database and edit .env file for DB settings
* php artisan migrate —seed
* edit .env file for APP configuration and Google API Configuration
* storage, bootstrap/cache and public/cache directories should be writable
* php artisan storage:link
* php artisan serve


### Features
* Create a profile with a username, profile picture, cover picture, bio and personal information
* Share Posts, Images
* Find, follow your friends and send direct message to them
* Make comments on Posts, Images
* Like Posts, Images
* Follow new events with notifications
* Add hobbies
* Become a member of a hobby group automatically and interact with other people
* Hide your profile by sharing your location. Let only the people around you to have access to communicate with you
* Find people around you at the same location, having same hobby and become a member of an automatically created hobby group


### Pages 
There are 7 pages. which are Home Page for Login and Sign Up,  TimeLine, Direct Messages and Profile you know.
* Nearby page is for seeing people around you.  
* Groups are created automatically for people who share the same hobby.  You can see group posts in groups page if you added that specific hobby.  
* Following & Followers page shows the list of followers and people you are following.  


### Requirements
* PHP 5.6.4
* MySQL
