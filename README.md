## Overview
This CLI app is designed to assist me with recurring projects. Using Todoist with the GTD paradigm I often want to set in mortion the same set of tasks for a systematic process. Templatizing those tasks was difficult so I made a simple CLI program ot do it for me. Tudu becuase my last name is Dugan and I thought it was funny.

## Usage
Ideadlly we would do the following:
`tudu init`
this would create a .tudu dir with a .config file or something, that config file would have the users API key.
Then we would need to a way to easily build out a templatized projects/todo lists
`tudu create ` - Maybe a way to create YAML Files with vars? 
`tudu new ` - new project or set of tasks based upon defined Yaml? 
`tudu delete` - delete project or set of tasks based up defined yamls?
`tudu get` - Get all tasks related to the Yaml file ?
`tudu help` - Help


## Yaml File structure
{{Project Name}:
  -  {{ Project Task }}
  {{ Sub Project Name }}:
    - {{ Sub Project Task}}

## Update
Trying Jira Integration
