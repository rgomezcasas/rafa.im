# My personal website

## Build & Deploy
* If it's the first time after cloning, execute `git submodule update --init --recursive`
* To build local: `make start`
* To deploy:
  1. Do all the changes
  2. `make build`
  3. Commit and push inside the `public` submodule
  4. Commit and push this project
  
  
## To Do
* Automate deploy with GH Actions
