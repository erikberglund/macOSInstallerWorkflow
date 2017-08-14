# macOSInstallerWorkflow

The script will automatically:

	* Download latest macOS Installer from the App Store
	* Create an OS Image using AutoDMG
	* Create a DeployStudio NBI
	* Upload both Image and NBI to the DeployStudio Server

## Setup
Download the script and edit the `CUSTOM VARIABLES` section at the top with your local settings.

You can also use the supplied configuration file and edit the line with `script_configuration=` and point it to the path of your ` macOSInstallerWorkflow.conf`
