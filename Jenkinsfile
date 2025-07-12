pipeline{
    agent ary
    stages{
      stage 'Build' {
        steps {
          echo 'Building...'
          sh 'echo "Build step executed"'
        }
      }
        stage 'Test' {
            steps {
            echo 'Testing...'
            sh 'echo "Test step executed"'
            }
        }
        stage 'Deploy' {
            steps {
            echo 'Deploying...'
            sh 'echo "Deploy step executed"'
            }
        }

      
    }
}