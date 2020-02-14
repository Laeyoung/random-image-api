[![Run on Ainize](https://ainize.ai/static/images/run_on_ainize_button.svg)](https://ainize.web.app/redirect?git_repo=github.com/Laeyoung/random-pengsu-jjal)


> A simple random-pengsu-jjal written in PHP.

## Getting started

**Live Version:** https://random-pengsu-jjal.laeyoung.endpoint.ainize.ai/

#### 1. Clone git repo

`git clone https://github.com/Laeyoung/random-pengsu-jjal.git`

#### 2. Update random-pengsu-jjal images.

> Img Path: **./assets/images/**

#### 3. Build new docker image

`docker build -t random-pengsu-jjal .`

#### 4. Run new random-pengsu-jjal

`docker run -p 8080:80 -d random-pengsu-jjal`

#### 5. Open [localhost:8080](http://localhost:8080)


## Deploy on Ainize

#### 1. Build docker image for dockerhub

`docker build -t ${YOUR_DOCKER_HUB_ID}/${DOCKER_HUB_REPO_NAME} .`

#### 2. Push docker image to dockerhub

`docker push ${YOUR_DOCKER_HUB_ID}/${DOCKER_HUB_REPO_NAME}`

#### 3. Deploy on Ainize.ai

Open [ainize.ai](https://ainize.ai), and deploy.


### Original Repo Author
- **OblivionSan** - [@OblivionSan](https://twitter.com/OblivionSan) | [Discord Server](https://discord.gg/kxNeGRC) | [Website](https://oblivionsan.tk)
