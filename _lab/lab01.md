---
layout: lab
num: lab01
ready: true
desc: "Setting up your CSIL and Binary Arithmetic 1"
assigned: 2019-10-02 14:00:00.00-7
due: 2019-10-09 23:59:59.00-7
---
<p><b>NOTE: Due Wednesday, October 9th at 11:59 PM</b></p>

<h2>Goals for This Week</h2>
<p>By the time you have completed this work, you should be able to:</p>
<ul>
  <li>Have your CSIL account requested or received</li>
  <li>Monitor class announcements with <a href="http://www.piazza.com/ucsb/fall2019/cs64" target="_blank">Piazza</a></li>
  <li>Have your account activated on <a href="https://www.gradescope.com/courses/65312" target="_blank">Gradescope</a></li>
  <li>Learn how to get files related to your assignments</li>
  <li>Use the <b>Gradescope</b> tool for submitting assignments</li>
</ul>
<b>Provided files:</b>
<ul>
  <li><a href="{{'/lab/lab01/lab01.pdf' | relative_url }}"><code>lab01.pdf</code></a></li>
</ul>
<hr>
<h1>Step by Step Instructions</h1>

<h2>Step 1: Log Into a Computer</h2>
If you are unable to log in, make sure you join someone whose works.
<p>
  If you need to request an account, <a href="https://accounts.engr.ucsb.edu/invites/login">click here.</a>
</p>

<h2>Step 2: Sign up for Piazza (If You Have Not Already)</h2>
<p>
  See link on top of this page.
  All course announcements will be through Piazza, so it is very important that you sign up!
</p>
    
<h2>Step 3: Sign up for Gradescope (If You Have Not Already)</h2>
<p>
  See link on top of this page. Use this Entry Code: <b>MVE855</b>.
  All course assignments will be done through Gradescope.
</p>
    
<h2>Step 3: Create a Directory for This Work</h2>
<p>Back in your <code>CSIL</code> account, first create a directory for this course, if you have not already:</p>
<pre>
mkdir cs64
</pre>
<p>Then, if you want to confirm that it worked, list the contents of this directory</p>
<pre>
ls
</pre>
<p>That should show <code>cs64</code> as one of the contents of the current directory.</p>
<p>Now go into the <code>cs64</code> directory, create a <code>lab1</code> directory inside it, and enter the <code>lab1</code> directory:</p>
<pre>
cd cs64
mkdir lab1
cd lab1
</pre>
<p>Confirm that you are in the proper directory by checking the current path:</p>
<pre>
pwd
</pre>
<p>It should say your home directory's path, followed by <code>cs64/lab1</code>.</p>

<b>
  Note: You are expected to learn the unix commands presented in assignments.
  After today, I will expect that you know what <code>mkdir</code>, <code>cd</code>, and <code>pwd</code> do.
  If you forget them, you may refer back to these instructions.
</b>
<p>You may not do much with this directory FOR THIS PARTICULAR assignment, but it's good practice and you will be using more UNIX features/commands in future assignments</p>

<h2>Step 4: Get the Provided File Into Your Work Directory</h2>
<p>
  The provided <a href="{{'/lab/lab01/lab01.pdf' | relative_url }}"><code>lab01.pdf</code></a> file is need to make its way into the directory you just created. There are a number of ways to do this (but you likely know how to do this... ask your TA for help if not)
</p>

<h2>Step 5: Change the File Permissions Appropriately</h2>
<p>
  Depending on some factors, it may still be possible for others to read the contents of the files you just copied.
  This can lead to problems if you then put your answers in the files (as the rest of this assignment asks you to do), as someone else could potential read your answers.
  We can fix this problem by tightening up the permissions on the files so that only you can read them, like so:
</p>
<pre>
chmod 600 lab1.pdf
</pre>
<p>
  The <code>chmod</code> command is used to change the permissions on files.
  The <code>600</code> in the command stipulates that you are giving yourself read and write access, while taking away any access to anyone else.
</p>
    
<h2>Step 6: Do the Assignment, then Turn in Your File Using Gradescope</h2>
<p>
  <b>If you partnered with someone (it's OPTIONAL - and NO MORE THAN TWO people can work on one assignment together), record the email address they are using for the class at the top of the assignment. EACH person needs to submit their own assignment!</b> 
</p>

<p>Your assignment file is a PDF with the questions and blank spaces for the answers. The easiest way to proceed is to (a) print the original PDF, (b) write your answers on the paper <b><i>USING DARK INK</i></b> (so it shows up in a scan), (c) scan your print outs into a NEW PDF file (you can still give it the same name), and finally, (d) upload/submit the NEW PDF file to Gradescope. It should go without saying that neatness counts: if your scan is unreadable or your handwriting is very
bad, your assignment may not get graded (i.e. you'd get a zero score).</p>

<p>If you have software that allows you to directly edit a PDF file, you can use that instead of steps (a), (b), and (c) above. This is not usually software we have for students to use, so if you want to go this route, you may have to purchase this PDF-editing software yourself. Again, this is OPTIONAL. It's perfectly fine to go the print-then-scan route described above.</p>

<p>PLEASE NOTE: Not ALL of your assignments will be done this way - some of your assignments will have you submitting actual programs instead of questions. I will give you detailed instructions with programming assignments when that time comes.</p>

<p>Your final step will be to go to Gradescope, select the <b>lab01</b> entry, and upload/submit your NEW PDF. Please call your submitted PDF file <b>lab01.pdf</b>.

<h2>(Optional) Step 7: Sign Up for CS Department Announcements</h2>
<p>
  The CS department has a mailing list to tell you about department events specifically targeted towards undergrads.
  Many students are unaware of this, so I want to let you know about it.
  You should (but are not required to) subscribe to this so that you can find out about all of these opportunities.
  To do so, go to <a href="http://lists.cs.ucsb.edu/mailman/listinfo/ugrads/">http://lists.cs.ucsb.edu/mailman/listinfo/ugrads/</a>.
</p>
<p>
  There is also a jobs list where you can find out about internship opportunities: <a href="http://lists.cs.ucsb.edu/mailman/listinfo/jobs/">http://lists.cs.ucsb.edu/mailman/listinfo/jobs/</a>.
</p>

<hr>
 <p>Copyright 2019, Ziad Matni, CS Dept, UC Santa Barbara. 
 Permission to copy for non-commercial, non-profit, educational purposes granted, provided appropriate
  credit is given; all other rights reserved.</p>
