 pipeline{
 	agent any 
 	stages{
 		stage('clonecode'){
			steps{
				sh 'ps -ef'
				checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'team7-git-id', url: 'https://github.com/Kondji237/Project3Group6.git']])
 			}
 		}
				stage('Divine'){
			steps{
				sh 'ps -ef'
				sh 'lsblk'
				sh 'sudo systemctl status jenkins'
			}
		}
 		stage('Steeve'){
			steps{
				sh 'ps -ef'
				sh 'lscpu'
				sh 'du -h'
				sh 'sudo systemctl status jenkins'
 			}
 		}
 	}
 }
