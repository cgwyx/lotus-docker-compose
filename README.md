# docker-compose for project lotus 

Lotus is an experimental implementation of the Filecoin Distributed Storage Network. For more details about Filecoin, check out the [Filecoin Spec](https://github.com/filecoin-project/specs).

## Background

1There is no docker and docker-compose supports in official project yet, so I forked a [repo](https://github.com/ldoublewood/lotus.git) for lotus with docker suppport etc. And meanwhile added this repo for docker-compose

## Usage


``` bash
git clone https://github.com/ldoublewood/lotus.git
cd  lotus
git submodule update --init --recursive
docker build  . -t registry.example.com/lotus

cd ..
git clone https://github.com/ldoublewood/lotus-docker-compose.git
cd lotus-docker-compose
docker-compose up

```
