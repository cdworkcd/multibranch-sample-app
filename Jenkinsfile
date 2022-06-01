pipeline{
    agent { label "linux" }
    options{ 
        buildDiscarder logRotator (artifactDaysToKeepStr: '', artifactNumToKeepStr:'5',daysToKeepStr: '',numToKeepStr: '5')
        disableConcurrentbuilds()
    }
    stages{ 
        stage('Hello'){
            step echo 'Hello'
        }
    }

}
