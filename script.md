Clone app

--- show repo while others are cloning...


Install deps
Run the app locally -> node required, not needed if they don't want to run locally
Run the tests locally

-- create CircleCI app (create account if need be)

CircleCI basic config:


jobs: build
docker image circleci/node:12

checkout 
install npm deps
npm run test

One job, one executor
Run test only
Store tests artifacts


--- 

show orb instead...
//TODO

---

Assemble docker image

DOCKER_LOGIN - as environment vas
DOCKER_PWD 

---

Deploy docker image to Docker Hub

---

make deploy depend on successful tests

---

Run vulnerability scan

---

manual accept

---

Summary