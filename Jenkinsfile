node {
	ws('E:/Jenkins/utils/string_util') {
		stage "Initialization Process"
			echo "Pipeline Initiated for StringUtil"
		stage "Git Checkout"
			git url: "https://github.com/dineshdinch/string_util.git"
		stage "Compiling the Project"
			bat "ant jar"
		stage "Completion Process"    
			echo "StringUtil Pipeline Process Completed"
	}	
}