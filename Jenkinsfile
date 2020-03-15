pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

// node('node') {
//     try {
//         stage('Print env variables'){
//             sh 'printenv'
//         }
//     }

//     catch (err) {
//         throw err
//     }
// }
