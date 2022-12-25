# What is CI/CD?
<br/>
<img
  src="./img/devops.svg"
  alt="DevOps cycle"
  style="display: block; margin: 0 auto; max-width: 300px">
<br/>
<p align="justify">CI/CD (Continuous Integration and Continuous Delivery) refers to 2 best practices in the software development world. Continuous Integration involves frequent merges to the main branch of a Git repository, and then automatically running unit tests when that code is pushed. Since multiple people are working on the same project and each working on different features, CI helps these changes merge into the mainstream to ensure that these incremental changes can happen. In addition, another key idea of CI is automated unit testing, where each little part of our program is tested to behave the way it is supposed to. Continuous Delivery refers to shorter release schedules that allow new features to get out to users much more quickly instead of releasing something at the end of the long cycle.</p>
<br/>

# GitHub Action
<p align="justify">There are plenty of CI/CD tools such as Jenkins, GitLab..., but one of them produced by GitHub more recently is known as GitHub Actions. This tool allows us to create these workflows so that when someone pushes code to a Git repository, certain steps defined by a developer take place automatically. So, for example, we can use GitHub Actions to automate the process of running tests; every time anyone pushes to a repository, we'll automatically run some GitHub action that is going to take care of the process of running tests on that program. And we will know immediately as a particular test fails every pushes occurs.</p>

## Sources
https://en.wikipedia.org/wiki/CI/CD<br>
https://youtu.be/WbRDkJ4lPdY

