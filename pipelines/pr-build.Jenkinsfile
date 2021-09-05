/***************************************************************
 Name       : pr-build.Jenkinsfile
 Description: This Jenkins job triggers on commit into repository
 Author     : Andrii Shylin <anderwerty@gmail.com>
 ***************************************************************/

pipeline {
    agent {
        node {
            label any
        }
    }

    options {
        timestamps()
    }

    stages {
        stage('Build') {

            steps {
                script {
                    echo 'Hello, World'
                }
            }
        }

    }

}
