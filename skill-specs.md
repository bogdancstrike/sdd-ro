Create a skill that activates at /spec <message> - it should create in docs/ directory three files: prd.md (product requirements document, designed for humans - scope of project, features, problem it solved), arf (architectural reference framework, designed for technical team - technologies, dependencies, deployment strategies, main flows, async vs sync, etc), specs.md (specifications, intent, tasks, how to test each task, acceptance criteria for each task, file that is designed for the ai agent that will implement the code)

All three should start from a template (one for each) of .md format of 10-15 keypoints for each

When i will trigger /spec <message> (in message i explain what i want from system, features, technologies etc) the skill activates so the three files should be created in docs/ dir of current working dir.

First give me the three files to review (the templates that will be used in the skill)

The skill should be installed and accesible in any new session after i review the three template files
