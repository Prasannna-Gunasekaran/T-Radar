# _TechRadar_

The Tech Radar is a list of technologies, complemented by an assessment result, called ring assignment. 
The Tech Radar is a tool to inspire and support Engineering teams at Mobilair to pick the best technologies for new projects; it provides a platform to share knowledge and experience in technologies, to reflect on technology decisions and continuously evolve our technology landscape.

We use four rings to describe the various Tech stacks.

ADOPT — Technologies we have high confidence in to serve our purpose, also in large scale. Technologies with a usage culture in our Zalando production environment, low risk and recommended to be widely used.

TRIAL — Technologies that we have seen work with success in project work to solve a real problem; first serious usage experience that confirm benefits and can uncover limitations. TRIAL technologies are slightly more risky; some engineers in our organization walked this path and will share knowledge and experiences.

ASSESS — Technologies that are promising and have clear potential value-add for us; technologies worth to invest some research and prototyping efforts in to see if it has impact. ASSESS technologies have higher risks; they are often brand new and highly unproven in our organisation. You will find some engineers that have knowledge in the technology and promote it, you may even find teams that have started a prototyping effort.

HOLD — Technologies not recommended to be used for new projects. Technologies that we think are not (yet) worth to (further) invest in. HOLD technologies should not be used for new projects, but usually can be continued for existing projects.

In this Techradar, we have added the source Links to all the tools on the stack so that when the Architect decides to use the certain tool he can have an idea about the tool in detail. These Links can be customised with internal CWIKI Links which is based on the decision from the Project Management. Currently we are going on with External Google source links of the tools. Hoep you got an idea of the Project, below you can find the steps for working with them in local machines and required detais to Maintain the radar.



## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

STEP 1: Download the copy and save in your Local Machine.

STEP 2: Work on the JSON files and updations in your Local Machine.

STEP 3: Project related Files 
        1.index.html
        2.entries.json
        3.radar.js
	
PATH: diemobilar/JAP Techradar/docs

## Here from the source code we have separated the "entries.json" so that in future anyone can edit the hosted techstack based on the requirements. This will not cause any damage to the source code file "radar.js".

## Files to Edit 

## To change the color code or any sizes of the text the contributors can use the Project related files based on the requirements.

1. entries.json
      For any new addition of tools in dieMobiliar and to add links for those applications in the stack. In this we can decide the quadrants and rings of the applications.

### How to run the file in local browser(Google chrome)

For Example:

Step 1:
	Open cmd in chrome location:
C:\ProgramData\Microsoft\Windows\Start Menu\Programs>

Step 2:
	Start chrome with allow file access using the below command
    COMMAND: "Google Chrome.lnk" --allow-file-access-from-files

Step 3:
	Run the edited index.html file using the opened chrome

## After successful validations in Local machine you can then use the GitHub for hosting them. 

CONDITIONS:

1.The Repository should be Public.
2.Make sure the Team members are invited to the Repository so that they can validate or work in parallel when required.(Only the Repository Owner can do this activity)
    PATH: Settings/Access/Collborators/search through email and invite them.
        NOTE:They must have created an Github account using the official emaild before inviting them.

### Adding files to Techradar Repository in GitHub

STEP1: You can either Drag and drop the files by creating the folder setup in the mobiliar Repository.
           Note:Use Slash / after the name in the " Add file/create New file " for creating the folder.
STEP2: You can even use the cloning option or adding directly from UI option based on user desicion.
Say what the step will be

## Deployment
### Hosting code in GitHub Pages

STEP1:Go to the following path in the Repository.
    PATH: Settings/Pages/Build and Deployement
STEP2:Here you can either host the pages from Main or Branches from the folder where the "index.html" file is available.
    NOTE: The hosted page link will be available in the top of the page after successful Deployement.There you can validate the final output in a hosted webpage.

### Hosting code using the custom Doamian of Mobiliar.

STEP1:In the same page you will find the custom domain where you can use the custom domain of Mobilair and the host the page.
        Example:"techradar.mobi.ch"

## Running the tests

After successful hosting of pages using custom domain of mobiliar you can validate the same by sending them to your others in mobiliar so that the goal is completed.

## Authors

* Prasanna Gunasekaran - TEAM DABBANG - Diemobiliar 

## License

This project is licensed under the MIT - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
Acknowledge People helping you build this project.
* Thanks to the [zalando](https://github.com/zalando) project for helping throughout the project.


