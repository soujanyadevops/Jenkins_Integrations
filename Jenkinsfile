pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is BhavaniShekhar from VybhavaTechnologies'
                        echo 'We are exploring Jenkins pipeline with groovy DSL scripting'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy_qa') {
                  steps {
                        echo "Deploy the Java application into Tomcat QA Environment"
                  }
            }
            stage('Deploy_stage') {
                  steps {
                        echo "Deploy the Java application into Tomcat Stage Environment"
                  }
            }
      }
}
