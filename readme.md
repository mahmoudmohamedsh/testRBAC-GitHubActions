# How run the project locally

this app run monge database inside container

1. change the link of db in index.js to the link of local 
2. run docker 
3. run docker compose command to run the image of db
```shell
$ docker-compose --project-name test-project -f docker-compose.yml up -d

$ npm run dev
```


## remove the docker images
```shell
$ docker-compose --project-name test-project -f docker-compose.yml down
```


- users
- courses
- lessons (videos, documents)
- enrollments
- progress tracking (completed lessons, quizzes, certificates)
- payment
- BLOG

Press Ctrl + Shift + F  -> search for todo


- user
  - progress
- course
  - category
  - lesson
- enroll 
- payment
- blog