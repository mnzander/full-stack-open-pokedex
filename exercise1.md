// EXERCISE 11.1

Asuming that the language will be Python, I found Pylint as a popular tool to detect errors, ensuring variable names and many more. For the testing stage, I've found Pytest Framework, which provides a compact and simple test suite. Finally, for "building" I've learned that Poetry is a good alternative to setuptools for managing dependencies and building packages in a simple way.

When we talk about alternatives for Jenkins and GitHub actions, the first thing that I thought was "GitLab CI / CD", which provides a platform for running pipelines directly alongside your GitLab repositories. GitLab replicates much of Jenkins' functionality with a different and more simple point of view.
But there is many more well known tools such as "Azure Dev Ops", "AWS Code Pipeline", "Travis CI", "Circle CI" etc.

For this team of 6 people, I would suggest a cloud-based enviroment due to its ease of setup and minimal maintenance. This enviroments offer a scalability for CI/CD pipelines during the development. I think that the cloud-based enviroment is a better tool for small teams. However, if we were managing other priorities such as "data sensitivity", "cost predictability" and "regulatory requirements", it would be worth considering a self-hosted enviroment.
