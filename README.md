Open up a terminal
Run the following command to copy the code
git clone https://github.com/viveks-13/router.git
To make changes for a new feature:
  Create a new branch using: git checkout -b branch_name
  Saving changes: git add .
  Commiting changes: git commit -m "your message here"
  Pushing changes: git push origin branch_name
  Pulling down new changes: git pull origin branch_name
Once you push your changes up to save progress, you can create a pull request by going to github website and creating one through the UI here
Lowk ask chat for any questions it's goated with github stuff, but just make sure you don't push changes directly to main branch since that should stay stable
First time you try to pull the code/push it might ask you to set credentials if you haven't, the password isn't a password but instead a personal access token (PAT)
  Create the PAT by going to settings -> developer settings -> access tokens -> create new classic -> give it a name, no expiration, and access to all the fields


Project vision:

App opens up with a prompt box that the user types into
  Sample prompts could be something like: "Create me a route from Seattle to California stopping every 150 miles for gas and every 5 hours for food"
Submit the prompt
User then gets a list of different routes that they can select from with key features highlighted (total time, mileage, etc.)
User selects the route they want/can fine-tune a specific route more by clicking on it and then adding in another prompt (can add this in later tho and just start with creating one route and forcing user to use that)
Route opens up in google maps or maybe even in the app itself not sure what the google maps API looks like yet

Frameworks:
UI is set-up to be run through Storyboard, plenty of documentation online and on chat for how to use it

