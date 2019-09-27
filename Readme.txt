Introduction: 
Welcome to 1999, the start of the dot.com boom!

The MarTech team have provided you with the analytics code for tracking sales on your website. 
Please follow the following instructions:

2) Add the analytics code to your app
- Go to the AnalyticsCode.txt
- Change the "event_category" value from "team ?" to your team name
- Copy the text and paste it into public/team-#.html
- Go to the desktop, and open the Marvinsoft.com/public folder, and double click on team-#.html
- Click the button
- Check that you see an event in the Google analytics

3) Copy in these commands into the command prompt to submit your code to the build process
- git add .
- git commit -m "feat: adding new analytics tracking code"
- git push origin feat/team-4

4) go to CircleCI tab on the browser to view the build process in action

5) Go to your freshly deployed website: http://35.189.188.125/team-4.html

6) Click on the "Make new order" button

7) Watch your sales roll in on our Analytics dashboard