pileline{
agent any 
stages {
	stage("checkout"){
		steps{
			git branch: 'branch1', url: 'https://github.com/patil2624/taskjenkins.git'
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

