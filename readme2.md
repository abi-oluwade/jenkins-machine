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
