# docker-jenkins

## Run jenkins inside docker

```
docker-compose up
```

Then [setup project with github repository](https://jenkins.io/doc/tutorials/build-a-node-js-and-react-app-with-npm/#setup-wizard)

## Unlocking Jenkins

When you first access a new Jenkins instance, you are asked to unlock it using an automatically-generated password.

1. After the 2 sets of asterisks appear in the terminal/command prompt window, browse to http://localhost:8038 and wait until the Unlock Jenkins page appears.
![Unlock Jenkins](https://jenkins.io/doc/book/resources/tutorials/setup-jenkins-01-unlock-jenkins-page.jpg)

2. From your terminal/command prompt window again, copy the automatically-generated alphanumeric password (between the 2 sets of asterisks).
![copy admin password](https://jenkins.io/doc/book/resources/tutorials/setup-jenkins-02-copying-initial-admin-password.png)

3. On the Unlock Jenkins page, paste this password into the Administrator password field and click Continue.

## Customizing Jenkins with plugins

After unlocking Jenkins, the Customize Jenkins page appears.

On this page, click Install suggested plugins.

The setup wizard shows the progression of Jenkins being configured and the suggested plugins being installed. This process may take a few minutes.

## Creating the first administrator user

Finally, Jenkins asks you to create your first administrator user with username and password are `jenkins/jenkins`

1. When the Create First Admin User page appears, specify your details in the respective fields and click Save and Finish.

2. When the Jenkins is ready page appears, click Start using Jenkins.
Notes:
    This page may indicate Jenkins is almost ready! instead and if so, click Restart.
    If the page doesn’t automatically refresh after a minute, use your web browser to refresh the page manually.

3. If required, log in to Jenkins with the credentials of the user you just created and you’re ready to start using Jenkins!

## Setup Repository
