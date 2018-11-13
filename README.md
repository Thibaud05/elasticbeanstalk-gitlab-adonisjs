# elasticbeanstalk-gitlab-adonisjs

ADD AWS var to gitlab in `Settings -> CI/CD -> Variables`: 
 - $AWS_ACCESS_KEY_ID
 - $AWS_SECRET_ACCESS_KEY

Set the app name in `.elasticbeanstalk/config.yml`

Set the aws-app-env in `.gitlab-ci.yml`
