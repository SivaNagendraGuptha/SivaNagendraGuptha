- 👋 Hi, I’m @SivaNagendraGuptha
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
SivaNagendraGuptha/SivaNagendraGuptha is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
sonar.projectKey=2104450_DevOps-CaseStudy
sonar.projectName=2104450_DevOps-CaseStudy
sonar.projectVersion=1.0
sonar.language=java
sonar.sources=src
sonar.host.url=http://localhost:9000
sonar.login=my_auth_token

Error: LinkageError occurred while loading main class org.sonarsource.scanner.cli.Main
	java.lang.UnsupportedClassVersionError: org/sonarsource/scanner/cli/Main has been compiled by a more recent version of the Java Runtime (class file version 61.0), this version of the Java Runtime only recognizes class file versions up to 55.0


sonar.projectKey=siva-simple-java
sonar.projectName=siva-simple-java
sonar.java.binaries=target/classes
sonar.exclusions=**/*.java


https://github.com/jenkins-docs/simple-java-maven-app.git




ERROR: Step ‘Deploy war/ear to a container’ aborted due to exception: 
java.lang.InterruptedException: [DeployPublisher][WARN] No wars found. Deploy aborted. %n
	at hudson.plugins.deploy.DeployPublisher.perform(DeployPublisher.java:107)
	at jenkins.tasks.SimpleBuildStep.perform(SimpleBuildStep.java:123)
	at hudson.tasks.BuildStepCompatibilityLayer.perform(BuildStepCompatibilityLayer.java:80)
	at hudson.tasks.BuildStepMonitor$3.perform(BuildStepMonitor.java:47)
	at hudson.model.AbstractBuild$AbstractBuildExecution.perform(AbstractBuild.java:818)
	at hudson.model.AbstractBuild$AbstractBuildExecution.performAllBuildSteps(AbstractBuild.java:767)
	at hudson.model.Build$BuildExecution.post2(Build.java:179)
	at hudson.model.AbstractBuild$AbstractBuildExecution.post(AbstractBuild.java:711)
	at hudson.model.Run.execute(Run.java:1917)
	at hudson.model.FreeStyleBuild.run(FreeStyleBuild.java:44)
	at hudson.model.ResourceController.execute(ResourceController.java:101)
	at hudson.model.Executor.run(Executor.java:442)
Finished: FAILURE
