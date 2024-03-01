pipeline
{
  agent {
	  label 'slave'
  }
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/Nagaraju118/Jenkins_26.git"
      }
    }
    stage("Run")
    {
      steps
      {
        sh "java Demo.java"
	sh "python Main.py"
      }
    }
  }
}
