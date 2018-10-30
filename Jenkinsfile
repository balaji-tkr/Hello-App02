@Library('jenkins-SL')_
import com.abc.demo
println demo.foo
pipeline {
        agent any
        stages {
         stage('Build') {  
            steps {
             sh  'mvn clean install'
          
            }
        }
}
}
