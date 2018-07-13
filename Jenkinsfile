pipeline
{
agent any
stages
{
  stage('Checkout')
  {
    steps
    {
      checkout SCM
    }
  }
  stage('Build')
  {
    steps
    {
       sh 'mvn install'
    }
  }
}
}

