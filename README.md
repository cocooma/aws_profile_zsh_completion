# Aws Profile zsh completion

The script reads out the content of the ~/.aws/credential file and auto completes the awsprofile script.

## Installation

  1. cp -r zsh ~/
  2. cp -r usr /
  3. add the following lines to your ~/.zshrc file:

	```
	#aliases
	alias sap='. /usr/local/bin/awsprofile'
		
	# COMPLETION SETTINGS
	# add custom completion scripts
	fpath=(~/zsh/completion $fpath)
		
	# compsys initialization
	autoload -U compinit
	compinit
	```

