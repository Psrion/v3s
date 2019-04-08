Compile information

step 1. Configure environment
	1) Configure JDK
		a) jdk1.6 or jdk 1.7
		b) configure one of them if ~/.bashrc or /etc/profile
		c) check whether configuration is effective, execute as follow command 
			
				java -version

		   if it comes out 1.6 or 1.7, it illustrates configuration successfully.
  
    2) Configure Makefile
    	this project needs to use make version 3.81 or 3.82, so you should download
    	and configure it, then, copy directly to the camdroid project

step 2. Compile project
	1) make sure you are in "root" permission
	2) execute "./compile_v3s.sh"
	3) enter "1" to select compiling chip structure
	4) enter "1" to select compiling output video format structure
	5) while finishing, you can find it output a image, which can do
	   for step 3.


step 3. Burning and transplanting
	1) using windowns software "Phoenixsuit.exe" to burn image
	2) select step 2 output image and transplant



