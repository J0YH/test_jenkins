pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('print env vars') {
            steps {
                sh 'printenv'
            }
        }
    }
}


// pipeline {
//     agent any

//     stages {
        
//     stage('Initiate') {
//         steps {
//             echo 'I am initiating'
//         }
//     }

//     stage('Print env variables') {
//             sh 'printenv'
//     }
    
//     }
// }

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
