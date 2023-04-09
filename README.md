# Project template
<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]


<!-- Git commands -->
## Git commands
   ```sh
   git config --list --show-origin
   git config --global user.name <Your Name> # template
   git config --global user.name "Ivan K" # example
   git config --global user.email <dev@example.com> # template
   git config --global user.email "dev@example.com" # example
   git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"
   git clone https://github.com/IK-dev/project_template.git
   
# How to Ignore a Previously Committed File
# first need to update the .gitignore
git rm --cached trash
# The git rm command, along with the --cached option, deletes the file from the repository but does not delete the actual file. This means the file remains on your local system and in your working directory as an ignored file.
   ```


<!-- Console commands (Shell) -->
## Console commands (Shell)
```shell {cmd=true }
# pip freeze outputs a list of all installed Python modules with their versions
pip freeze > requirements.txt

# Installing Python Packages From a Requirements File
pip install -r requirements.txt

# Output a list of outdated packages
pip list --outdated
pip list

# Upgrade the required package
pip install -U fastapi
# pip install --force-reinstall fastapi

# If you need to check for missing dependencies, you can do so with the following command:
python -m pip check

pip uninstall fastapi
pip install fastapi
pip install fastapi --upgrade
```


<!-- Project layout -->
## Project layout
    mkdocs.yml		# The configuration file?
	requirements.txt # It is a simple text file that saves a list of the modules and packages required by your project.
	main.py			# some main file.
    docs/
        README.md	# The documentation homepage.
        ...			# Other file's, markdown pages, images and other files.
    var/
    src/			# source code


## Else
https://towardsdatascience.com/python-project-template-for-a-quick-setup-d3ba1821e853
https://github.com/MirYeh/PythonTemplate


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/ivan-klimchuk/
[contributors-shield]: https://img.shields.io/github/contributors/IK-dev/project_template.svg?style=for-the-badge
[contributors-url]: https://github.com/IK-dev/project_template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/IK-dev/project_template.svg?style=for-the-badge
[forks-url]: https://github.com/IK-dev/project_template/network/members
[stars-shield]: https://img.shields.io/github/stars/IK-dev/project_template.svg?style=for-the-badge
[stars-url]: https://github.com/IK-dev/project_template/stargazers
[issues-shield]: https://img.shields.io/github/issues/IK-dev/project_template.svg?style=for-the-badge
[issues-url]: https://github.com/IK-dev/project_template/issues

