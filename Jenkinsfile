pipleline{
  agent any 
    stages{
      stage("Build"){
        steps{
          echo "Its Build From GitHub Repo"
          start file1.txt
		  }
		 }
      stage("Test"){
        steps{
          echo "Its Build From GitHub Repo"
          start file2.txt
      }
    }
      stage("Package"){
      	steps{
        	echo "Its Wrap the Entire file to artifact"
        	start file3.txt
      }
    }
	stage("Deploy"){
		steps{
			echo "This File Sends a Artifacts to the tomcat server"
		}
		
	 }
}
}
