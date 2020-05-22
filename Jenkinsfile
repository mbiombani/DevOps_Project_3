pipeline {
     agent any
     stages {
         stage('Upload to AWS') {
             steps {
                 sh 'echo "Hello World"'
                 sh '''
                     echo "Multiline shell steps works too"
                     ls -lah
                 '''
                  withAWS(region:'us-east-2') {
    // do something
}
                s3Upload(file:'file.txt', bucket:'my-bucket', path:'path/to/target/file.txt')
s3Upload(file:'someFolder', bucket:'my-bucket', path:'path/to/targetFolder/')
             }
         }
       }
    }
