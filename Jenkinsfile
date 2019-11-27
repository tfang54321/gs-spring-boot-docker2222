

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



bat  'gradle  build'

}

}

}

}
