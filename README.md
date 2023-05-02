Download Link: https://assignmentchef.com/product/solved-cop-2800-java-programming-i-project-6-gui-text-encryption
<br>
5/5 - (3 votes)

Using the <a style="font-size: 16px;" href="https://wpollock.com/Java/TxtCrypt/TxtCrypt.jar">TxtCrypt</a><span style="font-size: 16px;"> application as an example, create a Java </span><abbr style="font-size: 16px;" title="Graphic User Interface">GUI</abbr><span style="font-size: 16px;"> stand-alone application that allows a user to encrypt any text as Pig Latin.  For example, the string “</span><code style="font-size: 16px;">Java is very simple!</code><span style="font-size: 16px;">” should be converted to the string “</span><code style="font-size: 16px;">Avajay isway eryvay implesay!</code><span style="font-size: 16px;">“.  You may use either </span><abbr style="font-size: 16px;" title="Abstract Windowing Toolkit">AWT</abbr><span style="font-size: 16px;"> or </span><abbr style="font-size: 16px;" title="Swing toolkit">swing</abbr><span style="font-size: 16px;">.</span>

<h2>Requirements:</h2>

Write a stand-alone Java <abbr>GUI</abbr> application called <code>TxtCrypt</code>.  Use either <abbr>AWT</abbr> or swing.  This application should allow anyone to convert any text into Pig Latin.  Your application <strong class="big">must</strong> provide a pair of<code>TextArea</code> (or <code>JTextArea</code>) components where the user can type in any text into the first, and see the encrypted results in the second.  The input text is called the <em>plaintext</em>, and the resulting Pig Latin is called the <em>ciphertext</em>.  You must provide the basic <abbr>GUI</abbr> and event handling.  This <strong class="big">must</strong> include a button, which when pressed displays the ciphertext for the currently displayed plaintext.  (You may add additional <abbr>GUI</abbr> components as you see fit.)

I have provided class <code>utils.PigLatin</code> (<a href="https://wpollock.com/Java/TxtCrypt/api/">view <code>utils.PigLatin</code> <abbr>API</abbr></a>), which is a class with a public static method called <code>encrypt</code>.  (See below for the download link.)  This method takes a <code>String</code> as an argument, and returns an encrypted, “Pig-Latin-ized” version of the argument as another <code>String</code>.  The method signature is:

<pre>    package utils;    public class PigLatin    {        public static String encrypt ( String plainText )        { ...        }        ...    }</pre>

You only need the <a href="https://wpollock.com/Java/TxtCrypt/utils.jar">utils.jar</a> file (right-click this link to save), which should be put into the same directory as your Java class file(s).  (If you place your application into its own Jar file, both Jars should be in the same directory.)

<span class="highlight">To compile your application</span>, don’t forget you will need <code>util.PigLatin</code> to be found on your <code>CLASSPATH</code>.  The simplest way to do that is to have your Java source file (say <code>Proj6.java</code>) and <code>utils.jar</code> in the same folder, say on your Desktop.  Then you can compile your program like this on Windows:

<pre class="Indent">C:Users<em>yourname</em>Desktop&gt;<strong>javac -cp .;utils.jar Proj6.java</strong></pre>