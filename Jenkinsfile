node('test1') {
  // Mark the code checkout 'stage'....
  //stage 'Stage Checkout'

  // Checkout code from repository and update any submodules
 // checkout scm
  //sh 'git submodule update --init'  

  stage 'CheckOut'

  //branch name from Jenkins environment variables
  //echo "My branch is: ${env.BRANCH_NAME}"
   // stage 'test'

  //def flavor = flavor(env.BRANCH_NAME)
  git "https://github.com/anandchristal/test1.git"
  echo "Building flavor"
  //sh "mvn package"
  
  stage 'Build'
  def mvnHome = tool 'M3'
 //  sh "${mvnHome}/bin/mvn -B verify"
  sh "${mvnHome}/bin/mvn package"

 }
