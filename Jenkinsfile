node
{
stage('checkout')
{
  scm checkout
}
stage('deployDev')
{
  echo "Deploying to Dev after build"
  sh "HelloWorld.sh"
}
}
