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
                                          sh "java Demo.java"
                                          sh "python3 Main.py"
                                         }
                                   }
                            }
              }
       }
