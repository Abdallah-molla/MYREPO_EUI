node('dokcer-agent') {
   

         git branch: "main",url: "https://github.com/Abdallah-molla/MYREPO_EUI.git"
        stage('Build') {
            sh 'mvn clean package'
            // Add build commands here
        }

        stage('Test') {
            echo 'Running tests...'
            // Add test commands here
        }
     
   
    }
