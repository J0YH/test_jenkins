pipeline {
    agent any

    stages {
        
    stage('Initiate') {
        steps {
            echo 'I am initiating'
        }
    }

    try {

        stage('Print env variables') {
            sh 'printenv'
        }

    } catch (err) {
        throw err
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
