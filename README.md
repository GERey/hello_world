# hello_world


```
  version: 2.1
  jobs:
    build:
      docker: 
        - image: circleci/node:4.8.2 # the primary container, where your job's commands are run
      steps:
        - checkout # check out the code in the project directory
        - run: echo "hello world" # run the `echo` command
```
