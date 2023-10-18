# Automate-Application-Testing-Using-AWS-CodeBuild
Automated testing into your DevOps pipelines is crucial to increase speed and efficiency by ensuring that your application functions properly after every update. 
Enforcing adequate test coverage will make sure that your entire application works. When you fix one area you will know if you have accidentally broken another. 
Finally, all of these tests are more efficient if your Developers have useful reporting to show where they need to troubleshoot any potential failures.
This project demonstrates how I use AWS CodeBuild as a part of Continuous Integration pipelines to test and build code. Test techniques included:
•	Functional unit tests
•	Isolated component tests with mocked dependencies


I cloned a mini tic-tac-toe react application. The manual process of fixing bugs creates problems with updates and patches. As the requirement is moving to an automated infrastructure-as-code style of deployment for any new applications. I want to install as many workloads as possible on scalable, ephemeral, environments. This requires the creation of deployments that are repeatable and do not require manual changes after installation. If an application has issues, I can replace the problem component. And the most important, each deployment package must be tested for bugs before being deployed. When issues are found, a new version will have to be released to address the issues in a new deployment without manual intervention. Technologies used:
-	AWS CodePipeline for automation and AWS CodeBuild to build the code. After a successful build, the deployment package is uploaded to Amazon S3
-	Cloud9 IDE because it is accessible from anywhere in the world, from any compatible device, via remote access.

SAMPLE APP:
![image](https://github.com/cacaogun/Automate-Application-Testing-Using-AWS-CodeBuild/assets/103553102/aa6aae8b-5d51-4a5a-8030-39479f487eee)

