# Deploying
## Cloud computing is a general term for the delivery of hosted services over the internet.
#### Types of cloud computing services
1. infrastructure as a service (IaaS),
2. platform as a service (PaaS) ,
3. software as a service (SaaS).

## What is PaaS?
Platform as a service (PaaS) is a cloud computing model that delivers applications over the Internet ,such as:Google App Engine and Heroku.

In a PaaS model, a cloud provider delivers hardware and software tools -- usually those needed for application development -- to its users as a service. A PaaS provider hosts the hardware and software on its own infrastructure. As a result, PaaS frees users from having to install in-house hardware and software to develop or run a new application.

### PaaS consists of three main components:
1. the layers of software that your application runs on—“the stack”.
2.  the deployment machinery that instantiates virtual servers.
3. the user interface and the overall user experience (UX).

### Paas Advantages:
1. allows developers to frequently change or upgrade operating system features.
2. It also helps development teams collaborate on projects.

## Environment Variables
Are the best way of storing sensitive data like API Keys, Login Credentials and Database Passwords.
(Printenv) to view all environment variables

### Command example to list and create an environment variables:

1. create file called printenv.js
2. write this command in the file console.log(process.env);
3. then run the file node printenv.js… so that you will find all of the environmental variables.
4. to define an environment variable export HELLO=WORLD
5. inside the file write console.log("Hello", process.env.HELLO);
6. then run the file.
