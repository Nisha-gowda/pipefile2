pipeline {
        agent any
        stages {
                stage ('build') {
                        steps {
                                sh '''
                                                echo "this is build stage"
                                                sleep 2
                                   '''
                        }
                }

         stage ('deploy') {
                parallel{

                stage ('deploy1') {
                        steps {
                                sh '''
                                                echo "this is deploy stage"
                                                sleep 2
                                   '''
                        }
                }

               stage ('deploy2') {
                        steps {
                                sh '''
                                                echo "this is deploy stage"
                                                sleep 2
                                   '''
                        }
                }
             }

}

                stage ('test') {
                        steps {
                                sh '''
                                                echo "this is test stage"
                                                sleep 2
                                   '''
                        }
                }
        }
}
