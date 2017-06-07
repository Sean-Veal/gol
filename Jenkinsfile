//Start of Jenkins Pipeline

pipeline {

//Where pipeline will run
agent any

//start stages: build, test, deploy
stages {

//start of stage: build
stage('build') {

//Runnning steps inside the build stage 
steps {

//Invoke command
bat 'mvn clean install'
}

}

}

}
