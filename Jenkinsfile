pipeline {

        agent any
        environment{


                staging_Server="54.204.204.251"

        }

        stages {

                stage('Deploy to Remote Server'){

                    steps{

                        sh ' sudo scp -r  ${WORKSPACE}/*  root@${staging_Server}:/var/www/html/jenkinsdemoproject'

                    }
                
                
                }


        }



}
