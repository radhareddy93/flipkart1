pipeline
{
agent any
stages
{
  stage('Checkout')
  {
    steps
    {
      Checkout SCM
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

