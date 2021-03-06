# HACKTOBER FIESTA - 21

## Prerequisites
- Sign up to [hacktoberfest](https://hacktoberfest.digitalocean.com/)
- Have python and pip installed on your system



<br>

## Setup

### Step 1 - Fork
As the first step, you have to `fork` this repository to your own github account. 
For that please click on the fork button on the top right corner of your window.  
You will now have the forked repository among your own repositories.    
![Fork](https://github.com/dkowsikpai/card/blob/main/Screenshots/fork.png)
<br>

### Step 2 - Clone 
Clone the repository to your local machine using the git command.
```
git clone <url_to_forked_repository>
```

<br>

### Step 3 - Install Flask
Use pip to install flask. 
```
  pip install flask
```

<br>

### Step 4 - Run the application
The application can be run using the command. The application will be running at `localhost:5000` by default.
```
python app.py
```



<br>

## Tasks

### PR 1 - feature on home page
Open the file _namelist.html within templates folder, where the names of all the participants seen on the homepage of the website is given.
Copy the relevant section of code as shown below and insert another record with your own details.
```
<a class="participant" href="/<github-username>">
  <div>
    <div class="name"> <your name> </div>
    <div class="college"> <your college> </div>
  </div>
</a>
```

<br>

### Your Initial Pull Request(PR)
- Push your changes to the github repository.
- Go To Pull requests tab on github
- Click on `New Pull Request` button. 
- Make sure that head repository is your repository
![Pull Request Head](https://github.com/dkowsikpai/card/blob/main/Screenshots/PR%20Head.png)
- Make sure it is showing green tick mark
- Press on `Create Pull Request` Button
![Create PR](https://github.com/dkowsikpai/card/blob/main/Screenshots/Create%20PR.png)
- Add necessary title and description
- Hit `Create Pull Request` Button

<br>

### PR 2 - create card at "/github-username"
- Within templates folder create a copy of sample.html and change the name to `<your_github_username>.html` 
 If your username is `abc` then change the new file's name to `abc.html`.
- Going to the url `localhost:5000/<github-username>` will now give you the sample card.
- Make another pull request using the above given steps.

<br>
  
### PR 3 - modify primary details about yourself in the card
- Within static folder, create a copy of "sample" folder and modify its name to your "github-username"
- Within this newly created folder replace existing image with your own image. 
- Open the earlier created html file in a text editor of your choice. Change the name inside `<title>` tag.    
![title](https://github.com/dkowsikpai/card/blob/main/Screenshots/title.png)
- Now, replace the path to the css file with the path to the css file in your newly created folder in static.
- Modify the src attribute of the image with the path to where your image was added.
- Edit Your name and college name in the same html file.    
![div](https://github.com/dkowsikpai/card/blob/main/Screenshots/details%20div.png)
- Opening `localhost:5000/<github-username>` will now show the modified card with your details and image.
- Make your next pull request.
 
<br>

### PR 4 - design your card as you wish
- You can change the css file within the your newly created folder in static. New CSS styles or even animations can be included.
- The dimensions of the card must remain the same. 
- Copying another participants code is strictly prohibited.
- Once the design is ready, make your final pull request. This will make you eligible to receive Hacktoberfest goodies.
- The best card will be selected as part of our event and he/she stands a chance to win exciting prizes.
