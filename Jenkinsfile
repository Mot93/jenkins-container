pipeline {

    agent {
        dockerfile {

            filename 'Dockerfile'

        }
    }

    stages {

        stage ('hello world'){
            steps {
                
                // Proof that we are working inside the container
                sh 'cat /etc/os-release'
                sh 'ls -l'

                // Executing the python script
                sh 'python3 main.py'

            }
        }

    }    

}