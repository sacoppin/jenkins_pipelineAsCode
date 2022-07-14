# jenkins_pipelineAsCode

- Install the necessary tools (JVM, gradle, jenkins...)
- Make a new Github repository with the content of the original [Repo](https://github.com/YoussF/caesar-cipher)
- Try to run the build and the tests manually to make sure everything is ok
- Create a Jenkinsfile, and write all the necessary steps, then push it to the remote repo.
- Create a pipeline in jenkins... 


entrer dans docker exec -it jenkins_jenkins_1 bash


- tuto gradle https://linuxize.com/post/how-to-install-gradle-on-debian-10/

- sudo apt update
- sudo apt install default-jdk
- sudo apt install zip unzip

- ./gradle build
- chmod -x caesar-cipher.jar 
- cd jenkins_pipeline_as_code/caesar-cipher/build/libs
- java -jar caesar-cipher.jar

----------------------------------