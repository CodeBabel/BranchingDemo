node
{
stage('checkout')
{
  checkout scm
}
stage('deployDev')
{
  echo "Deploying to Dev after build"
  sh "HelloWorld.sh"
}
}
