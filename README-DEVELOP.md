# py-mongo-eve
Python project using MongoDB and Eve REST framework

## Friday 11/04 2:30-5 PM PST

### Decided on Initial Design

Python language selected because personal career goals focus on it.
MongoDb selected because job descriptions desire knowledge of product.
Eve selected because job descriptions unclear on which software used to create end points, and because Google search on "Mongo endpoints" list Eve as first choice for Python developers. Eve tools for utilizing new OpenAPI (Swagger) standard for RESTful, JSON API desing also significant.
Must use a basic Windows 10 laptop as development machine since normal Ubuntu, Redhat workstation in storage for eminent move to new job. Laptop needed several development environment tools installed, which will be done weekend of 11/5-6/2016. Some deatils are:
  Tried stackedit.io Markdown preview, but not consistent with GitHub Markdown (e.g., when ``` blocks needed, so install Grip.
  Install Python Grip and Nginx for Markdown previews.
  Install OpenSSL for Mongo and Nginx

### Install MongoDb on Windows 10

Read install guide, and did Google searches on Windows install best practices

```a
%HOME%\Software\MongoDb
%HOME%\Software\MongoDb\data\mongod.cfg
%HOME%\Software\MongoDb\data\log\mongod.log
%HOME%\Software\MongoDb\data\db\
```

### Create Git Project

Create repository py-mongo-eve on github.com/bradsturtevant
Clone repository on development machine
Create git branch develop in Git repository

```
git clone https://github.com/bradsturtevant/py-mongo-eve.git
git pull origin master
git checkout -b develop master
git push --set-upstream origin develop
```

git checkout -b feature develop
git merge --no-ff

### Install MongoDB on Windows 10

## Monday 11/07 2:30-5 PM PST

Create README-DEVELOP.md to track time spent on project, and highlight both behind the scenes work done and knowledge of Git, Systems Administration,
