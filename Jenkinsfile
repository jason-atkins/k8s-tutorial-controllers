pipeline {
    agent any
 
        stage('Deploy') {
            steps {
                sh '''
    	    kubectl apply -f frontend.yaml
            kubectl apply -f backend.yaml
            sleep 60
            kubectl get services
                '''
            }

        }

    }


