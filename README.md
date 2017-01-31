# Ansible Syntax Highligting Extension

This extension is trying to make syntax highliting for Ansible better on VScode. 
It's based on [original Ansible Sublime-text package](https://github.com/clifford-github/sublime-ansible) with my own fixes.

## Setup File associations

Settings for VScode to automatically assign ansible syntax to files.

```
    "files.associations": {
        "**/defautls/**/*": "ansible",
        "**/tasks/**/*.yml" : "ansible",
        "**/handler/*.yml" : "ansible",
        "**/*_vars/**/*.yml" : "ansible",
        "**/roles/**/*.yml" : "ansible",
        "**/playbooks/**/*.yml" : "ansible",
        "**/*ansible*/**/*.yml" : "ansible",
        "**/vars/**/*.yml": "ansible",
        "**/inventory/*/*": "ansible"
    }
```
