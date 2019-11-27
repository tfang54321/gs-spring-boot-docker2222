

pipeline {

agent any

stages {

stage('Checkout') {

steps {



 git 'https://github.com/tfang54321/gs-spring-boot-docker2222.git'

}

}





stage('buildimage') {

steps {



bat  'gradle  build docker'

}

}
 
 
 stage('rundocker') {

steps {



bat  'docker run -p 8089:8088 springio/gs-spring-boot-docker1127'

}

}
 

}

}
