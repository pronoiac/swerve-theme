# Swerve LimeSurvey template / theme

## What is it?
This modifies the Default [LimeSurvey](https://www.limesurvey.org/) layout a bit.

### What's different from the Default theme?
The questions with rankings have a new layout: your selections at the top, with the choices below, in columns.

## What does it look like?
![swerve screenshot](https://user-images.githubusercontent.com/171153/35495018-77b82b48-0473-11e8-9a81-c3bc1871dbee.png)

## Installation
One could use the LimeSurvey interface or put the files into place.

### Requirements
It was written and tested on LimeSurvey 2.73.

### Config file changes
This template has custom views, so the config file requires an additional setting: `allow_templates_to_overwrite_views` in `application/config/config.php`, within the `config` array.

For more info, see [this section on the LimeSurvey Theme editor page.](https://manual.limesurvey.org/Theme_editor#Custom_Question_Views_.28version_2.5.29)

### LimeSurvey interface
*This isn't available yet.*

Download the zip file from the GitHub releases page.
In LimeSurvey, select Configuration, Template Editor, then Import.
Select the downloaded zip file.

### Put the files into place
The path for files is `upload/templates/`.
Unzip the zip file or clone the git repo or whatever.

## Creators
Blame: James Young wrote this mod.
Credit: The original theme is by Louis-Sébastien Gac Artigas <louis.gac@limesurvey.org>.

## License
This is based on the Default theme in LimeSurvey.
Following that, this is released under GNU General Public License version 2 or later.