# JENKINS
This jenkins readme is located only on the 'home' branch, we learnt how to switch between the dev and master branch and had Jenkins listen to only the dev branch and build when changes have been committed to that branch.

## What is it and what is it for?
Jenkins is an open-source continuous integration software tool written in the Java programming language for testing and reporting on isolated changes in a larger code base in real time. The software enables developers to find and solve defects in a code base rapidly and to automate testing of their builds.

Say you develop a software. You might have unit tests bundled in your software. A Jenkins job could watch your software's git repository and run these tests for you, like you would do manually, whenever a new commit is pushed.

If the tests are successful, you might want Jenkins to package/bundle/compile your software to produce an artefact you can install or deploy.

When you have that artefact ready, you might even want Jenkins to deploy it for you in production.

It has the tools and plugins to help you do that but really you can do what you want using, for example, the shell provisioner to run bash/python/ruby/whatever scripts and commands.

# What is a pull request
When a pull request is created in github, Webhook to Jenkins will send pull request references(/from) as well as the branch name. If the pull request is from a fork, the app will only send the pull request reference. This should allow users to setup the plugin to just build from pull requests.

# What is a webhook?
Sometimes people call webhooks reverse APIs, but perhaps more accurately a webhook lets you skip a step. With most APIs there’s a request followed by a response. No request is required for a webhook, it just sends the data when it’s available.

To use a webhook, you register a URL with the company providing the service. That URL is a place within your application that will accept the data and do something with it. In some cases, you can tell the provider the situations when you’d like to receive data. Whenever there’s something new, the webhook will send it to your URL.

# What is ngrok?
Ngrok is a multiplatform tunnelling, reverse proxy software that establishes secure tunnels from a public endpoint such as internet to a locally running network service while capturing all traffic for detailed inspection and replay.

Enter ngrok, a very cool, lightweight tool that creates a secure tunnel on your local machine along with a public URL you can use for browsing your local site. When ngrok is running, it listens on the same port that you're local web server is running on and proxies external requests to your local machine.


# CI-CD-CD

Remember the 4 pillars:
  ease of use
  flexibility
  robustness
  cost

## What is SDLC
1. What is it?
2. Problems with LDLC
3. How DevOps helps SDLC
  - Automation and Collaboration

1. SDLC:
  - Plan/Design
  - Develop
  - Test
  - Deploy

2. Problems:
  - Scale and complexity:
    - Functions
    - Architecture
    - Infrastructure
    - Developers
    - Operations

  - Manual and slow process
  - Broken and fractured communication
  - Human errors
  - Large volume of testing
  - Long deployment window
  - High cost

3. DevOps in SDLC:
- DevOps came to help modern SDLC as then we can achieve agile style development:
  - Automation (automate all we can as they can be easily repeated without human error)
  - Collaboration

- DevOps lifecycle stages:
  - Continuous development
  - Continuous testing
  - Continuous integration
  - Continuous delivery/deployment
  - Continuous monitoring

1. CI
````
              /--Dev1\
          /---------testing--->
        /      \Dev2/           \
git---------------------------------->Production
````
We should have a test for every merge point.

2. CD - Software engineering approach in which teams produce software in short cycles,
ensuring that the software can be reliably released at any time and when releasing the Software
, doing it MANUALLY.

CD - is a software engineering approach in which software functionalities are
delivered frequently through AUTOMATED deployments.

both deploy code into production, but do it in manual and automated ways.

Pipeline phases:
1. commit
2. build
3. automates tests
4. deploy
