<h1>Creating Hash Values in Linux </h1>

 

<h2>Description</h2>
In this scenario, I created and evaluated the hash values for two files, using Linux commands to calculate the hash of two files and then observe any differences in the hashes produced to determine if the files are the same or different.
<br /> .


<h2>Languages and Utilities Used</h2>

- <b>Bash shell</b>
- <b>Linux</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program Walk-through:</h2>

<p align="center">
Listing the contents of the directory and displaying them: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/HV1.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generating hashes of the contents of the two files to see the difference between them: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/HV2.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Writing the hashes to two separate files and then displaying them to compare the difference: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/HV3.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using the 'cmp' function to compare the two files byte by byte: <br/>
<img src="https://github.com/RyanSNCyberSec/RyanSNCyberSec/blob/main/HV4.JPG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
