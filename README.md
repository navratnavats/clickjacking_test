
<h1>Clickjacking Tester</h1>

<p>This script test if websites are vulnerable to clickjacking attack and creates a POC</p>

<h3>Setup</h3>
<ol>
<li>Copy the URL from the code button above</li>
<li>In command line terminal use : git clone [paste the url copied]</li>
</ol>

<h3>Usage</h3>
<em>Make sure you copy the websites into the file and then check. Copy the file into the clickjacking_test folder</em>
<pre> python3 clickjacking_test.py [filename] </pre>

<h3>Example</h3>
<pre> python3 clickjacking_test.py test.txt </pre>

<h3>Output</h3>
<pre>root@root:~# python3 clickjacking_test.py test.txt

[*] Checking www.google.com

   [-] Website is not vulnerable!

[*] Checking www.facebook.com

   [-] Website is not vulnerable!

[*] Checking www.amazon.com

   [-] Website is not vulnerable!

[*] Checking www.cobaltstrike.com

   [+] Website is vulnerable!
   [*] Created a poc and saved to <URL>.html
</pre>



