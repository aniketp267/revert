pipeline {

             agent {

                    label {
                         
                         label "qa"
                         customWorkspace "/mnt/pipeline"
                                 }   
  
                           }

                    stages {

                      stage ("stage-1") {
 
                        steps {

                              sh "sudo systemctl start httpd" 
                               sh "sudo cp -r index.html /var/www/html"
                               sh "sudo chmod -R 777 /var/www/html/index.html"  

                                                           }  

                                                     }

                                               }
}
