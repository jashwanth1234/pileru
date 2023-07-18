pipeline {
    agent any
    stages {
        stage ('stage1') {
            steps {
                script {
                    myvar = 1
                    while (myvar <= 10) {
                        println "my var1 value is ${myvar}"
                        myvar=myvar+1
                    }
                }
            }
        }
    }
}
