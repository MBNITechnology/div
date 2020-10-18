pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        echo "build env"
      }
    }
    stage("test") {
      when {
        expression {
          BRANCH_NAME =="master"
          echo "-----------master branch ------------"
        }
      }
      steps {
        echo "test env "
      }
    }
    stage("deploy") {
      steps {
        echo "deploy env"
      }
    }




  }
}
