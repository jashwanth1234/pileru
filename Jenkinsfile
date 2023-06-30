/* groovylint-disable NglParseError */
pipeline {
    agent any
    parameters {
        choice choices: ['dev', 'prod', 'sit'], description: 'Select Environment', name: 'ENV'
    } 
}
    stages {
        stage(Working with variables) {
            steps {
                script {
                    val1 = 20
                    println "my val1 is ${val1}"
                    // parameters values
                    println "my parameter valaue is ${params.EN}"
                }
            }
        }
    }
}
