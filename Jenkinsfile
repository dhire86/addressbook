pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "testmaven"
    }

    stages {
        stage('compile') {
            steps {
               echo "thi is test for compile"
            }
        }
         stage('unitest') {
            steps {
               echo "this is for unit test"
            }
        }
        stage('package') {
            steps {
               echo "this test for package"
            }
        }
    }
}
