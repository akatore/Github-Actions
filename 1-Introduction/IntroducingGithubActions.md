Github Actions is a powerful and flexible platform provided by GitHub, It allows developers to automate tasks directly from their repositories.
We can quickly create workflows to impliment CI/CD pipeline that build test on every pull request and deploy merge pull request to the production right beside our codebase.

Out of the box the code can be executed in different operating systems, like ubuntu, Windows and Macs.

And few advantages of Github actions are that, Github manages the infrastructure for us, which includes :
* Setting up the servers
* Scaling resources
* Managing execution environment for the Workloads
> ![image](https://github.com/user-attachments/assets/47533db0-7bcc-4c08-a86d-66a327159324)

Our task is write workflow configuration in YAML files and github actions handles the rst of the tasks which includes:
* Executing the tasks in virtual machines
* caching necessary dependencies
* providing reports on the outcomes.
![image](https://github.com/user-attachments/assets/7465a0c1-2ed9-4f53-983f-e94b8113b970)

Finally the (workflow) Automation also helps us:
* streamline development,
* reduce manual errors,
* Increase the efficiency for software development workflow

SO the **actions** solely used for automating CI/CD pipelines building testing and releasing the code, NO!

![image](https://github.com/user-attachments/assets/29572b42-cfc1-45b3-89b8-31916ba1e9be)

GitHub actions goes beyond just CI/CD,

![image](https://github.com/user-attachments/assets/ea89832a-85fb-4ecf-b571-af6befd431fa)

It lets ypu run workflows when other events happen in the repository it can be used for automating all kind of repository actions by listening to event such as push events issues, pull request, GitHub registry package events, or whenever a issue or a pull request gets updated. (these are just few, more are their)

