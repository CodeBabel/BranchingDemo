node
{
stage('checkout')
{
  checkout scm
  echo 'branch name ' + env.BRANCH_NAME
}
stage('deployDev')
{
  echo "Deploying to Dev after build"
  sh """chmod +x HelloWorld.sh 
  ./HelloWorld.sh"""
}
}
