node {
   currentBuild.result = "SUCCESS"
   stage('Printing hello world'){
       sh 'echo "Hello World"'
   }
   stage('unit test'){
       sh 'echo "unit test has started"'
   }
   stage('system test'){
       sh 'python -u session1_exercise1.py'
   }
   stage('integration test'){
       sh 'echo "integration test has started"'
   }
}
