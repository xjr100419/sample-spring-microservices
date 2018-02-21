node {

    withMaven(maven:'M3') {

        stage('Checkout') {
            git url: 'https://github.com/xjr100419/sample-spring-microservices.git', credentialsId: 'github-piomin', branch: 'master'

            sh 'echo $DEMO_PARMS '

             sh 'echo  ${DEMO_PARMS} '

        }



    }

}