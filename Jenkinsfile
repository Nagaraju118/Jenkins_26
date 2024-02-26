Pipeline
{
  agent any
  stages
  {
    stage("git")
    {
      steps
      {
        git "https://github.com/Nagaraju118/Jenkins_26.git"
      }
      stage("run")
      {
        steps
        {
          sh "Demo.java"
          sh "Main.py"
        }
      }
    }
  }
}
