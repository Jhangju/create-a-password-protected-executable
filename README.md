# create-a-password-protected-executable in c#
This programs is designed for some malware developing purpose you can check wether a legitimate process trying to open the executable.

<b>How it works?</b>
<p>
  <ol>
    <li>First you create a exe if you dont know how to create exe in c# download and install visual studio installer and install .net development.</li>
    <li>You exe can found in your project name folder /bin/debug/project.exe</li>
    <li>Now since you have exe if you direct execute it, it might say not valid user because you did not give password.</li>
    <li>Now open CMD and goto the path of your exe write "yourexename.exe 123" it would might open a new cmd which proves ypu give correct password.</li>
    <li>You can change password and rebuild it to create new exe</li>
    <li>The code that you want to execute after correct password you can write it in where condition is true. <i>We open a new cmd process</i></li>
</ol>
</p>
