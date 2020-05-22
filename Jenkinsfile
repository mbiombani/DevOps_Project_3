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
}s3Upload( 
  bucket: 'BUCKET', 
  path: "PATH_TO_FOLDER", // no trailing slash 
  file: "FOLDER", 
  workingDir: "PARENT_OF_FOLDER" 
)
             }
         }
       }
    }
