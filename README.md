# Alexa
Steps

For building a skill in the developer portal check --> https://developer.amazon.com/docs/custom-skills/steps-to-build-a-custom-skill.html

Follow Lambda setup from here --> https://github.com/alexa/skill-samples-java/tree/master/helloworld - Go to Readme - AWS lambda setup.

Unzip the folder and extract the folder. Go to the folder containing pom.xml. 
C:\Users\test\fundingskill\alexa-skills-kit-java-master\alexa-skills-kit-java-master\samples or 
C:\Users\test\internalskill\alexa-skills-kit-java-master\alexa-skills-kit-java-master\samples

Run the command 'mvn assembly:assembly -DdescriptorId=jar-with-dependencies package'.
This will create a jar file in the target folder. Use the jar with dependencies and upload it to Lambda.

