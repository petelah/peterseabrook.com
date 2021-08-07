# PeterSeabrook.com

### About
This is my personal site server. The idea is for it to be constantly evolving to one day be a full web app that will act as a blog and API server for my personal needs.

#### Tech Stack
- Golang
- - Go Fiber framework for serving http traffic
- Docker, containerised by docker
- AWS, hosted via EC2
- CI/CD:
- - Github actions for our pipeline
- - Terraform for managing and deploying infrastructure
- Nginx, reverse proxy to serve SSL traffic
- Postgres, local database

### ToDo
- Basic site with static content MVP
- Connect to DB
- Template content
- Develop CRUD capabilities for adding/removing content
- Create API
- Decouple into react app & API server