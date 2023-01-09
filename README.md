# La Mobilière Tech Radar

Based on the pioneering work of ThoughtWorks, our Tech Radar sets out the changes in technologies that are interesting in software development — changes that we think our engineering teams should pay attention to and use in their projects.

The Tech Radar is a tool to inspire and support Engineering teams at La Mobilière to pick the best technologies for new projects; it provides a platform to share knowledge and experience in technologies, to reflect on technology decisions and continuously evolve our technology landscape.

This Tech Radar is a list of technologies, complemented by an assessment result, called ring assignment. We use four rings to describe the various Tech stacks: 

* *ADOPT* — Technologies with broad adoption, in which La Mobilière is willing to invest long-term.
* *TRIAL* — Technologies that currently is experimented with in production. TRIAL technologies are more risky; some engineers in our organization walked this path and will share knowledge and experiences.
* *ASSESS* — Technologies that are promising and have clear potential value-add for us; technologies worth to invest some research and prototyping efforts in to see if it has impact. ASSESS technologies have higher risks; they are often brand new and highly unproven in our organisation. You will find some engineers that have knowledge in the technology and promote it, you may even find teams that have started a prototyping effort.
* *HOLD* — Technologies where the company is not willing to invest further and not recommended to be used for new projects; no new applications may use this technology but usually they can be continued for existing projects.
 
In this Techradar, we have added the source Links to all the tools on the stack so that when the Architect decides to use the certain tool he can have an idea about the tool in detail. These Links can be customised with internal CWIKI Links which is based on the decision from the Project Management. Currently we are going on with External Google source links of the tools. Hoep you got an idea of the Project, below you can find the steps for working with them in local machines and required details to Maintain the radar.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

1. Clone the repository to your local machine.
2. Relevant files are located in the _docs_ folder. To change assignements for technologies you will have to edit _entries.json_ accordingly.

Note: for better maintainability we separated the "entries.json" from the "radar.js" so that anyone can edit the content of the tech radar without causing any damage to the source code of the radar.

## Edit the Tech Radar content

### To change the color code or any sizes of the text the contributors can use the Project related files based on the requirements.

To add and remove technologies to different rings on the radar simply change the appropriate properties in "entries.json" according to the below mapping:

* Quadrant 0 - Languages & Frameworks
* Quadrant 1 - Platforms & Services
* Quadrant 2 - Tools
* Quadrant 3 - Methodologies
* Ring 0 - Adopt
* Ring 1 - Trial
* Ring 2 - Assess
* Ring 3 - Hold

Dont forget to add a link if applicable.

## How to run the Tech Radar in your local environment (Google chrome)

Step 1:
	Open cmd in chrome location:
	
	C:\ProgramData\Microsoft\Windows\Start Menu\Programs>

Step 2:
	Start chrome with allow file access using the below command
	
    COMMAND: "Google Chrome.lnk" --allow-file-access-from-files

Step 3:
	Run the edited index.html file using the opened chrome

## Deployment to Github pages. 

CONDITIONS:

1.The Repository should be Public.

2.Make sure the Team members are invited to the Repository so that they can validate or work in parallel when required (only the Repository Owner can do this activity).

    PATH: Settings/Access/Collborators/search through email and invite them.
    
  NOTE:They must have created an Github account using the official emaild before inviting them.

### Adding files to Techradar Repository in GitHub

STEP1: You can either Drag and drop the files by creating the folder setup in the mobiliar Repository.

           Note:Use Slash / after the name in the " Add file/create New file " for creating the folder.
	   
STEP2: You can even use the cloning option or adding directly from UI option based on user desicion.

### Hosting code in GitHub Pages

STEP1:Go to the following path in the Repository.

    PATH: Settings/Pages/Build and Deployement
    
STEP2:Here you can either host the pages from Main or Branches from the folder where the "index.html" file is available.

 NOTE: The hosted page link will be available in the top of the page after successful Deployement.There you can validate the final output in a hosted webpage.
    
    		Example: "https://prasannna-gunasekaran.github.io/T-Radar/"

### Hosting code using the custom Doamian of Mobiliar.

STEP1:In the same page you will find the custom domain where you can use the custom domain of Mobilair and the host the page.

     		   Example:"techradar.mobi.ch"

## Running the tests

After successful hosting of pages using custom domain of mobiliar you can validate the same by sending them to your others in mobiliar so that the goal is completed.

## Authors

* Prasanna Gunasekaran - TEAM DABBANG - La Mobilière

## License

This project is licensed under the MIT - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to all for helping us throughout the project.
