node {
   
    stage('building a docker image'){
        echo "Building a Docker Image"
        sh 'docker image build -t customngix ./Dockerfile'
        sh 'docker image tag customnginx rakskash/customnginx'
    }
}
