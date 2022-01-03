BY DOWNLOADING, INSTALLING, COPYING, ACCESSING, OR OTHERWISE USING THE SOFTWARE, YOU AGREE TO 
THE TERMS OF THE SPSS LICENSE AGREEMENT UNDER WHICH YOU ACQUIRED IBM SPSS Statistics 26.0 FP1.
BY AGREEING, YOU REPRESENT AND WARRANT THAT YOU HAVE FULL AUTHORITY TO ACCEPT THESE TERMS. 
IF YOU DO NOT AGREE TO THESE TERMS,
- DO NOT DOWNLOAD, INSTALL, COPY, ACCESS, OR USE THE SOFTWARE; AND
- PROMPTLY RETURN THE UNUSED MEDIA AND DOCUMENTATION TO THE PARTY FROM WHOM IT WAS OBTAINED. 
IF THE SOFTWARE WAS DOWNLOADED, DESTROY ALL COPIES OF THE SOFTWARE.


Installation instructions 
========================= 
1.  Products affected:  Statistics Desktop & Server 26.0 FP1 (Windows and Unix) or 26.0 FP2 (macOS)
Platforms affected:	ALL

2. The related defect id(s):
#5282 Upgrade Log4j to 2.17.0 because high security risk 

3. Affected Files: 
The attached interim fix zip file contains the following:
	log4j-core-2.17.0.jar
	log4j-api-2.17.0.jar
	log4j-1.2-api-2.17.0.jar
	readme.txt (this file) 

4. How to apply the hot fix: 
	Win64 & UNIX
		(1) Close the Statistics 26.0 application. 
		(2) Navigate to the Statistics 26.0 installation directory (e.g. $SPSS_HOME or 'C:\Program Files\IBM\SPSS\Statistics\26').
		(3) Locate the following files and remove them to a backup location outside of the Statistics install path:
			$SPSS_HOME/common/ext/bin/spss.tm1.9/log4j-1.2.16.jar
			$SPSS_HOME/common/ext/bin/spss.cognos.9/log4j-1.2.17.jar
			$SPSS_HOME/as-3.1.1.0/lib/com.springsource.org.apache.log4j-1.2.16.jar
		(4) Copy the interim fix files (log4j-core-2.17.0.jar, log4j-api-2.17.0.jar, log4j-1.2-api-2.17.0.jar) to these locations:
			$SPSS_HOME/common/ext/bin/spss.tm1.9/
			$SPSS_HOME/common/ext/bin/spss.cognos.9/
			$SPSS_HOME/as-3.1.1.0/lib/
		
	MacOS
		(1) Close the Statistics 26.0 application. 
		(2) Navigate to the Statistics 26.0 installation directory (e.g. $SPSS_HOME or '/Applications/IBM/SPSS/Statistics/26').
		(3) Locate the following files and remove them to a backup location outside of the Statistics install path:
			$SPSS_HOME/SPSSStatistics.app/Contents/common/ext/bin/spss.tm1.9/log4j-1.2.16.jar
			$SPSS_HOME/SPSSStatistics.app/Contents/common/ext/bin/spss.cognos.9/log4j-1.2.17.jar
			$SPSS_HOME/SPSSStatistics.app/Contents/as-3.1.1.0/lib/com.springsource.org.apache.log4j-1.2.16.jar
		(4) Copy the interim fix files (log4j-core-2.17.0.jar, log4j-api-2.17.0.jar, log4j-1.2-api-2.17.0.jar) to these locations:
			$SPSS_HOME/SPSSStatistics.app/Contents/common/ext/bin/spss.tm1.9/
			$SPSS_HOME/SPSSStatistics.app/Contents/common/ext/bin/spss.cognos.9/
			$SPSS_HOME/SPSSStatistics.app/Contents/as-3.1.1.0/lib/
		
5. IBM SPSS Statistics 26.0 is now ready to be used.
