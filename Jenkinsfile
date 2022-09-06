pipeline{
    agent{
        node{
            label 'master'
        }
    }
stages{
    stage('install-httpd')
    {
        steps{
            sh 'sudo yum install httpd -y'
        }
    }
    stage('index.html'){
        steps{
            sh 'cp index.html /var/www/html/'
            sh 'service httpd start'
        }
    }
}

}
