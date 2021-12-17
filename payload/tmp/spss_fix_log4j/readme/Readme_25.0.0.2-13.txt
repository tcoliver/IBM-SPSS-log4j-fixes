BY DOWNLOADING, INSTALLING, COPYING, ACCESSING, OR OTHERWISE USING THE SOFTWARE, YOU AGREE TO 
THE TERMS OF THE SPSS LICENSE AGREEMENT UNDER WHICH YOU ACQUIRED IBM SPSS Statistics 25.0 FP2.
BY AGREEING, YOU REPRESENT AND WARRANT THAT YOU HAVE FULL AUTHORITY TO ACCEPT THESE TERMS. 
IF YOU DO NOT AGREE TO THESE TERMS,
- DO NOT DOWNLOAD, INSTALL, COPY, ACCESS, OR USE THE SOFTWARE; AND
- PROMPTLY RETURN THE UNUSED MEDIA AND DOCUMENTATION TO THE PARTY FROM WHOM IT WAS OBTAINED. 
IF THE SOFTWARE WAS DOWNLOADED, DESTROY ALL COPIES OF THE SOFTWARE.


Installation instructions 
========================= 
1.  Products affected:  Statistics Desktop & Server 25.0 FP2
Platforms affected:	ALL

2. The related defect id(s):
#5282 Upgrade Log4j to 2.15.0 because high security riks 

3. Affected Files: 
The attached interim fix zip file contains the following:
	log4j-core-2.15.0.jar
	log4j-api-2.15.0.jar
	log4j-1.2-api-2.15.0.jar
	readme.txt (this file) 

4. How to apply the hot fix: 
	Win64 & UNIX
		(1) Close the Statistics 25.0 FP2 application. 
		(2) Navigate to the Statistics 25.0 FP2 installation directory. 
		(3) Locate the file log4j-1.2.16.jar which under installed directory and subfolder(/common/ext/bin/spss.tm1.8), and then backup it to other folder, such as your Desktop, and then copy the interim fix file log4j-core-2.15.0.jar, log4j-api-2.15.0.jar, log4j-1.2-api-2.15.0.jar to the folder.
		(4) Locate the file log4j-1.2.17.jar which under installed directory and subfolder(/common/ext/bin/spss.cognos.8), and then backup it to other folder, such as your Desktop, and then copy the interim fix file log4j-core-2.15.0.jar, log4j-api-2.15.0.jar, log4j-1.2-api-2.15.0.jar to the folder.
		(5) Locate the file com.springsource.org.apache.log4j-1.2.16.jar which under subfolder(/as-3.1.0.0/lib, /as-3.1.0.0/3rdparty), and then backup it to other folder, such as your Desktop, and then copy the interim fix file log4j-core-2.15.0.jar, log4j-api-2.15.0.jar, log4j-1.2-api-2.15.0.jar to the folder.
		
	MacOS
		(1) Close the Statistics 25.0 FP2 application. 
		(2) Navigate to the Statistics 25.0 FP2 installation directory. 
		(3) Locate the file log4j-1.2.16.jar which under installed directory and subfolder( SPSS Statistics.app/Contents/common/ext/bin/spss.tm1.8), and then backup it to other folder, such as your Desktop, and then copy the interim fix file log4j-core-2.15.0.jar, log4j-api-2.15.0.jar, log4j-1.2-api-2.15.0.jar to the folder.
		(4) Locate the file log4j-1.2.17.jar which under installed directory and subfolder(SPSS Statistics.app/Contents/common/ext/bin/spss.cognos.8), and then backup it to other folder, such as your Desktop, and then copy the interim fix file log4j-core-2.15.0.jar, log4j-api-2.15.0.jar, log4j-1.2-api-2.15.0.jar to the folder.
		(5) Locate the file com.springsource.org.apache.log4j-1.2.16.jar which under subfolder(SPSS Statistics.app/Contents/bin/as-3.1.0.0/lib, SPSS Statistics.app/Contents/bin/as-3.1.0.0/3rdparty), and then backup it to other folder, such as your Desktop, and then copy the interim fix file log4j-core-2.15.0.jar, log4j-api-2.15.0.jar, log4j-1.2-api-2.15.0.jar to the folder.
		
5. IBM SPSS Statistics 25.0 FP2 is now ready to be used.
