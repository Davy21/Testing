pipeline {
   agent any
   
   stages {
      stage('build'){
         steps{
           sh '''
             git version
             echo $BUILD_NUMBER
             echo $TAG_NAME
           '''
           echo 'build'
         }
      }

      stage('test'){
         steps{
           echo 'test'
         }
      }

      stage('deploy'){
         steps{
           echo 'deploy'
         }
      }
   }
}
