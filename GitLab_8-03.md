# Домашнее задание к занятию "`GitLab`" - `Букин Даниил`

### Задание 1

Вот скриншоты работоспособности моего runner-а:

1. ![image](https://img.inmyroom.ru/inmyroom/resize/700x700/jpg:85/uploads/photo/file/66/66a5/jpg_1000_66a54503-3af6-4ff2-840f-85e6b640b9c5.jpg?sign=92b4b224d95aa02a4c1c9e29e0c3c8fb4aa20a97eab1c3681a45ab0fcea079c3)

2. ![image](https://krasivosti.pro/uploads/posts/2021-04/1617983816_2-p-kot-na-stule-3.jpg)

### Задание 2

1. ![image](https://github.com/Llyffy/Homework/assets/53367937/90e4a86f-c8b6-4d61-88a3-cf1a67733fc9)

2. ![image](https://github.com/Llyffy/Homework/assets/53367937/ee741e05-7c40-4e03-a2bc-385ac74ac95f)

Вот так выглядит мой .gitlab-ci.yml
```
stages:
  - build
  - test
  - deploy

build:
  stage: build
  script:
    - echo "Building the project..."

test:
  stage: test
  script:
    - echo "Running tests..."

deploy:
  stage: deploy
  script:
    - echo "Deploying the project..."

```
