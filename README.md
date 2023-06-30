# Jenkins

 ## The aim of the above project is to create and configure a pipeline that will handle the unit testing and deployment process. 

The project involves automating these processes, which contributes to improving code quality and the efficiency of the development team. Additionally, the project includes scheduled pipeline builds, allowing for regular checks of application functionality through periodic test runs and software deployments. The activity diagram in the UML standard serves as a tool to better understand the individual stages and structure of the pipeline.


1. Preparation of a pipeline to run unit tests (manual invocation):

-> Cloning the code:
![7](https://github.com/Ulania/Jenkins/assets/96245511/ad9c5625-c4ec-45b6-8604-9da8c48acba1)

-> Initializing the environment:
![8](https://github.com/Ulania/Jenkins/assets/96245511/9dd35fef-f335-407a-8a4a-cf194d7d9f93)

-> Running the tests:
![9](https://github.com/Ulania/Jenkins/assets/96245511/0c39e8b0-9aa7-4301-ab80-7199a76c3d77)

-> Deploying (only invoking the "echo I'm in the deployment section" function):
![10](https://github.com/Ulania/Jenkins/assets/96245511/ddb82e7e-1daa-49aa-a1d3-9eb3948c541e)

2. Adding periodic builds (every hour):

To add periodic builds to the pipeline, you can use the "triggers" section and set the execution time of the pipeline using the "cron" function. The pipeline will be triggered every hour.

![11](https://github.com/Ulania/Jenkins/assets/96245511/10fb55cd-f04e-44b2-9a19-730c5becef62)

3. An activity diagram in the UML standard has been prepared, describing individual stages and invocations of the pipeline.

![uml](https://github.com/Ulania/Jenkins/assets/96245511/00024141-6ae2-4ef5-8dac-746b5adbca44)

4. Adding a Deployment stage that will display a message indicating that deployment will occur at that point.

![Screenshot 10]



