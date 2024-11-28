pipeline {
    agent {
      node {
        label 'slave_1'
      }
    }
    stages {
          stage ('Docker Push') {
                 steps {
                     sh '''
                       docker push goudsagar/httpd-my:latest
                    '''
                 }
                }
    }
}
