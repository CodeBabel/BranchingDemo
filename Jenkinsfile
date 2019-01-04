node
{
stage('checkout')
{
  checkout scm
}
stage('deploy')
{
  echo 'branch name ' + env.BRANCH_NAME
  if (env.BRANCH_NAME.startsWith("Feature_"))
    {
    echo "Deploying to Dev after build"
    }
  
  sh """chmod +x HelloWorld.sh 
  ./HelloWorld.sh"""
 
}
}
