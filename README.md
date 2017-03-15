# Ansible Syntax Highlighting Extension

This extension implements syntax highlighting for Ansible in VScode. 
It's based on the [Ansible Sublime-text package](https://github.com/clifford-github/sublime-ansible) with my own fixes.

## Setup File associations

Settings for VScode to automatically assign Ansible syntax to files.

```
    "files.associations": {
        "**/defaults/**/*": "ansible",
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
