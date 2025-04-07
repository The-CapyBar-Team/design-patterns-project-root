# design-patterns-project-root

## Prerequisites
1. Docker Engine
2. docker-compose

## Prepare the Repo

To clone and set up the repo you can choose ONE of the following options:

1. Recursively clone the repo
```bash
git clone --recursive <root_repo_url>
```
2. Simply clone the repo and initialize the submodules:
```bash
git clone <root_repo_url>
cd design-patterns-project-root
git submodule update --init
```

Note: `root_repo_url` in this context is either of these:
1. Https: https://github.com/The-CapyBar-Team/design-patterns-project-root.git
2. Ssh: git@github.com:The-CapyBar-Team/design-patterns-project-root.git

## Build & Run
1. To run all the containers, use the following command:
```bash
docker-compose up
```
2. To run and rebuild all the containers, use the following command:
```bash
docker-compose up --build
```
3. To shut all the containers down, use the following command:
```bash
docker-compose down -v
```
Note: `-v` flag is needed only if there exist the containers using some volumes.
