node {
   stage('Install node modules') {
       sh 'sudo npm install'
   }
   
   stage('Test') {
       sh 'sudo npm run test'
   }
   
   stage('Build') {
       sh 'sudo npm run-script build'
   }
}