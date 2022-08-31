pipeline {
	agent any
	stages{
		stage('1-make a left'){
			steps{
				sh 'echo "walk..."'
                sh 'cat /etc/passwd'
			}
		}
		stage('2-make a right'){
			steps{
				sh 'echo "walk.."'
                sh 'lscpu'
			}
		}
		stage('3-make another left'){
			steps{
				sh 'echo "walk..."'
                sh 'cat /etc/passwd | grep ubuntu'
                
			}
		}
		stage('4-cross the street'){
			steps{
				sh 'echo "walk..."'
                sh 'whoami'
               
			}
		}
        stages {
            stage('5-Phil'){
                steps {
                    sh 'ps -ef'
                    sh 'sudo systemctl status jenkins'
                }
            }
            stage('6-processes running on the system-Abisola'){
			    steps{
				    sh 'ps -ef'
				    sh 'sudo systemctl status jenkins'
			    }
		    }
            stage ('7 christiane'){
                steps{
                    sh 'ps -ef'
                    sh 'sudo systemctl status jenkins'
                }
            }

       
        }
    }
}   
