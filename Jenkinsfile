pipeline {
    agent any
    stages {
       stage("Clone respository") {
          steps {
              git branch: "newjenkinsbranch", url: "https://github.com/chanchalKhatua/jenkins_test.git"
                   }
                          }
       stage('Run Script') {
           steps {
                 sh 'chmod +x script.sh'
                 sh './script.sh'
                 }
}
}
}

