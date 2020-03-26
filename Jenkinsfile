node {
  try {
    stage('Checkout') {
//      checkout scm
      echo "checkout"
    }
/*    stage('Environment') {
      sh 'git --version'
      echo "Branch: ${env.BRANCH_NAME}"
      sh 'docker -v'
      sh 'printenv'
    } */
  }
  catch (err) {
    throw err
  }
}
