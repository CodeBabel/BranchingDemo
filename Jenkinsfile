node
{
stage('checkout')
{
  checkout scm
}
stage('deployST')
{
  echo "Deploying to ST after build and deployment to Dev"
  sh """chmod +x HelloWorld.sh 
  ./HelloWorld.sh"""
}
}
