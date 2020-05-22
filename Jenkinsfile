pipeline {
     agent any
     stages {
         stage('Upload to AWS') {
             steps {
                 sh 'echo "Hello World"'
                 sh '''
                     echo "Multiline shell steps works too"
                     ls -lah
               
withAWS(region:'us-east-2') {
    // do something
}
s3Upload bucket: 'public-assets',path:'public/',file:'index.html',contentType:"text/html"

             }
         }
       }
    }
