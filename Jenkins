pipeline{
    agent any 

    stages{
        stage('Build-system details'){
            steps{
                sh '''
                echo "system details"
                uname -a
                '''
            }
        }
        stage('Memory-details'){
            steps{
                sh '''
                echo "Memory-details"
                free -h
                '''
            }
        }
        stage('cpu details'){
            steps{
                sh '''
                echo "cpu details"
                lscpu
                '''
            }
        } 
        stage('date'){
            steps{
                sh '''
                echo "todays"
                date
                '''
            }
        }
        stage('current process'){
            steps{
                sh '''
                echo "current process"
                ps -eaf | head
                '''
            }
        }                        
    }
}
