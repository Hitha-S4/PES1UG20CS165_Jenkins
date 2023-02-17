pipeline{
    agent any
    stages{
      stage('Build'){
        steps{
          sh 'g++ -c PES1UG20CS165.cpp'
          sh 'g++ -o PES1UG20CS165 PES1UG20CS165.cpp'
          echo 'build stage successfull'
        }
      }
      stage('Test'){
        steps{
          sh './PES1UG20CS165'
          echo 'Test stage executed successfully'
        }
      }
      stage('Deploy'){
        ste{
          echo 'Deployed successfully'
        }
      }
    }
  post{
    failure{
        echo 'Pipeline Failed'
    }
  }
}
