pipeline {
    agent any
	tools {
        maven "M2_HOME" 
    }

    stages {
        stage ('git clone') {

            steps {
                 
                    git branch:master url: https://github.com/mounika257/pip.git
                
            }
        }

        stage ('build') {

            steps {
                
                    sh "mvn install"
                
            }
        }



