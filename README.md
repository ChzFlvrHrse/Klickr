Welcome to the Klickr_Clone!

Klickr Project is a clone of Flickr that is centered around sharing images and looking at images relatable to you. Users can browse images to find inspiration for themselves or to use images for personal projects.

Link to test out website: https://klickr-group.herokuapp.com/

## Tech Stack
 Frontend:
* React
* Redux
* JS
* HTML
* CSS

DB:
* SQLAlchemy  



## How to run Klickr Locally

* Clone/download the repo https://github.com/ChzFlvrHrse/Klickr-Group.git

* cd into Klickr-group folder and ``` run pipenv install ```

* Open two terminal paths for both Klickr-group and react-app.
* Under Klickr ``` run pipenv shell  then flask run, for react-app run npm install```
* Create a .env file under the root of the backend folder with the following contents:

  ``` REACT_APP_BASE_URL=http://localhost:5000 ```


## Getting started
Clone the repository then install dependencies

using ```pipenv install -r requirements.txt ```
Create a .env file based on the example with proper settings for your development environment


 ``` Get into your pipenv run pipenv shell,flask db upgrade, flask seed all, flask run```



# Environment Info
```
DATABASE_URL=sqlite:///dev.db
FLASK_DEBUG=True
SECRET_KEY=«generate_strong_secret_here» 
```

``` 
Inside react-app create another .env and add     REACT_APP_BASE_URL=http://localhost:5000 

```



## Explore / AllImages Page

![Screen Shot 2022-10-21 at 5 47 21 PM](https://user-images.githubusercontent.com/99216902/197294477-12efc6c4-4b72-4aa6-9c66-2e6a18d64e85.png)

* We managed to get the images to fit inside the container without compromising on quality, but have different sizes.




## SearchBar
![Screen Shot 2022-10-21 at 6 00 14 PM](https://user-images.githubusercontent.com/99216902/197294922-f9e10978-e979-444e-9dfa-78b0602b9e75.png)

* Search Bar was a major victory! It will display by both title and owner name, and you can hide undesired results by category.






## Carousel Images on Details

![Screen Shot 2022-10-21 at 6 02 31 PM](https://user-images.githubusercontent.com/99216902/197295213-f5a2d2bb-0b48-42df-8323-6426cb659e61.png)

* On our details page, we have a carousel that users can scroll through, if they wish to checkout another image details.



# Klickr
