pipeline
{
  agent any
   stages
  {
    stage('build')
    {
      steps
      {
        script
        {
          bat 'docker build -t getting-started-app:latest .'
        }
      }
    }
    stage('test')
    {
      steps
      {
        script
        {
          echo 'running tests'
        }
      }
    }
     stage('deploy')
    {
      steps
      {
        script
        {
          echo 'deploying'
        }
      }
    }
  }
}
