# Phenocam Batch Rename
This is a renaming tool written in python for Professor Patty Oikawa's Improved GHG measurement and modeling of tidal wetland project at CSU East Bay. The tool uses RegEx to rename all the .jpg files in the designated folder so that they are compatible with the data processing tools. It is designed with a simple GUI for nontechnical users.

## Prerequisites

- Python3

## Install

- Download the phenocam_batch_rename.py file.

## Usage
- **Always have a backup of the images before proceeding!**
- Double click the phenocam_batch_rename.py file or run it with python in terminal.
- Select the folder where the pictures are located.
- Select the location the photos were taken.
- Confirm settings.
- Click the "Rename Files" button.

## For Students At Other Universities

- If you need to change the location names, edit the LocationList in the python file.

- For example, if my study sites were Oakland, Berkeley, and San Jose, I would change 
	`locationList = [
	    "Location",
	    "Concord",
	    "EdenLanding"
  	]`
  To:
  	`locationList = [
	    "Location",
	    "Oakland",
	    "Berkeley",
	    "SanJose"
	]`
