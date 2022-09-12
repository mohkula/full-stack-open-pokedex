Language chosen for this exercise: Python.
For linting I would use pylint since I have used it before in other projects.
The type of testing our application needs depends on the application that our team is working on, 
but most likely unit testing is needed. For that I would choose to use pythons PyUnit. If end to end testing is required in the project I would most likely choose cypress for those kinds of tests. For building purposes I think that I would use anvil, however I'm not too familiar with it but it seems like the best option.
Some other alternatives to Ci besides Jenkins and github actions: 
Buddy
TeamCity
GoCD
Bamboo
Gitlab CI
CircleCI
Codeship
Buildbot
Integrity
Strider
Autorabit
Final builder
Wecker
Buildkite
Semaphore
CruiseControl
Bitrise
Urbancode

I'm not familiar with these so more research is needed if I was to use some of these alternatives

Wether the application should be hosted in a self-hosted or a cloud-based environment again depends on the project in question. If the project is really small with a few users and is not expected to scale significally, then self-hosting could be enough. If the project is expected to scale however, then some cloud-based solutions should be considered.S
