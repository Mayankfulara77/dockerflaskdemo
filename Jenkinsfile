stage('Docker Nexus Auth'){
    docker login -u admin -p admin http://44.201.118.101:9001/
}

stage('Push Docker Images to Nexus Registry'){
    sh 'docker push http://44.201.118.101:8081/repository/demorep/
echo "hh"
}
