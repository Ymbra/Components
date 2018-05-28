## Pull docker
docker pull digitallyseamless/nodejs-bower-grunt

## Run docker
docker run -it --rm -v $PWD:/data digitallyseamless/nodejs-bower-grunt bash

## install npm
root@029df569180f:/data# npm install

## Run gulp
root@029df569180f:/data# grunt
