pipeline
{
agent any
stages
{
stage('scm checkout')
{steps { git branch: 'main', url: 'https://github.com/deepalinewade/devops-july-jenkins.git'}}
 
stage('print your message')
 {steps { sh 'echo hello'  }}       //sh=execute shell

}
}
