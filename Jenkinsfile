pipeline{
agent any 
stages {
	stage("checkout"){
		steps{
			git branch: 'branch1', url: 'https://github.com/patil2624/taskjenkins.git'
		}
	}
	stage("permistion"){
		steps{
			sh ' chmod u+x file.sh'
			sh ' chmod u+x file_dir.sh'
		}
		}
	stage("exicute"){
		steps{
			sh './file.sh'
			sh './file_dir.sh'
		}
	}
	stage("show"){
		steps{
			sh 'cat file.sh'
			sh 'cat file_dir.sh'
		}
	}
}
}

