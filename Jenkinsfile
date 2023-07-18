pipeline {
    agent any
    stages {
        stage ('stage1') {
            steps {
                script {
                    myvar 1 = 1
                    while (myvar 1 <= 10) {
                        println "my var1 value is ${myvar1}"
                        myvar1=myvar1+1
                    }
                }
            }
        }
    }
}
