# web-scraper-text-review
It is a web scrapper for text review

Live Heroku link:
https://thawing-spire-36643.herokuapp.com/review

*NOTE: In Heroku I haven't used mongodb to store result but i have upload a file flask_app.py in which i have used mongodb so you can use it in local machine. It will fasten ypur query.


![20200914_171301](https://user-images.githubusercontent.com/51397434/93081966-b97d6780-f6ad-11ea-82e1-ea9d6cc5dc0b.gif)

>steps for deployment

Make sure git is installed.
(for testing purpose type in cmd ------>git)

#now move to project directory
#and run following command:
git init
#create .gitignore file and add file you dont want to upload
git add .
git commit -m "initial commit"

Make sure heroku cli in installed
(for testing purpose type in cmd ------>heroku)

#now run following cmd:
heroku login
heroku create
git remote  -v
git push heroku master
