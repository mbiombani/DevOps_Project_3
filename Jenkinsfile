pipeline {
     agent any
     stages {
         stage('Upload to AWS') {
             steps {
                 sh 'echo "Hello World"'
                 sh '''
                     echo "Multiline shell steps works too"
                     ls -lah
                     
                      stage('Upload to S3') {
                    withAWS(endpointUrl:'<endpoint>', credentials:'<s3 credentials>') {
                        s3Upload acl: 'Public', bucket: '<bucket>', file: "/foo/", path: 'bar/'
                    }

             }
         }
       }
    }
