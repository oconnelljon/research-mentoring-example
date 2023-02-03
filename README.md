# research-mentoring-example
Presentation for how to setup a python specific development environment using modern tooling.


The problem with camel case is that there are often different interpretations of words - for example, checkinService vs checkInService.
https://stackoverflow.com/questions/11947587/is-there-a-naming-convention-for-git-repositories


# pytest
https://code.visualstudio.com/docs/python/testing

To discover tests:
  tests dir needs __init__
  
"Configure Python Tests"
Creates the following in settings.json
    "python.testing.pytestArgs": [
        "tests"
    ],
    "python.testing.unittestEnabled": false,
    "python.testing.pytestEnabled": true
