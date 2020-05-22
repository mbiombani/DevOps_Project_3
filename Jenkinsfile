pipeline {
     agent any
     stages {
         stage('Upload to AWS') {
             steps {
                 sh 'echo "Hello World"'
                 sh '''
                     echo "Multiline shell steps works too"
                     ls -lah
               
withAWS(credentials:'IDofAwsCredentials') {
    // do something
}
s3Upload(file:'index.html', bucket:'my-bucket', path:'path/to/target/index.html')
s3Upload(file:'someFolder', bucket:'my-bucket', path:'path/to/targetFolder/')
             }
         }
       }
    }
