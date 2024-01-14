node {
  stage('SCM Checkout') {
    git 'https://github.com/prio21/sprintdemo.git'
  }

  stage('Compile-Package') {
    bat 'mvn package'
  }
}
