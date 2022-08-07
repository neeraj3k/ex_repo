pipeline
{
  agent
  {
    node
    {
    label "QA"
    customWorkspace('/new_project')  
    }
    }
  stages
  {
  stage('cp')
    {
      steps
      {
       sh 'sudo cp index.html /var/www/html'
      }
        }
  }
  
  
  
}
