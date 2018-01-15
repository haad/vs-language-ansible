# Ansible Syntax Highlighting Extension

- `Ansible`: It's based on the [original Ansible Sublime-text package](https://github.com/clifford-github/sublime-ansible) with my own fixes.
- `Ansible (advanced)` : It's based on YAML language of 2015 FichteFoll <fichtefoll2@googlemail.com> with modifications to support :
    - Jinja language
    - Jinja expressions for ansible conditions (`when`, `changed_when`, `failed_when`, `check_mode`)
    - Some YAML block scalar
    
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
