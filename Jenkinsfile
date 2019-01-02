node
{
stage('checkout')
{
  checkout scm
}
stage('deployDev')
{
  echo "Deploying to Dev after build"
  sh """chmod +x HelloWorld.sh 
  ./HelloWorld.sh"""
}
}
