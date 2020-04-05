pipeline{
agent any
stages{
stage('getting source code'){
steps{
 git 'git@github.com:jaya5939/jenkinsfiles.git'
}
}
 stage('creating a file'){
    steps{
         echo "this is helloworld pipeline"
}
}
//stage('ctreating a doirectory'){
//   steps{
//  sh 'mkdir /tmp/jenkins-pipeline'
//}
//}
stage('os version'){
 steps{
  sh 'cat /etc/*release*'
}
}
}
}



