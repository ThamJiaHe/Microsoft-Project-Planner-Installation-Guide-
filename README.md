<h1 style="color:blue;" align="center" >Microsft Project Professional 2024 Installtion Guide.</h1>
<h3 align="center">For only School Course uses only as they dont give us but it tested in the test lol!</h3>
<h2>Step 1: Downloading the file:</h2>
<p>Click on the Green button <Code> Download as .zip or clone repo it to your local decive location using the git clone link.</p>
<h2>Step 2: Unzip the folder:</h2>
<ul>
  <li>Unzip the File</li>
  <li>Save the folder to desktop</li>
</ul>
<h2>Step 3: Open the Folder:</h2>
<ol>
  <li>Open the folder in File Explorer</li>
  <li><strong>The folder contains two essential files for installing Microsoft Office:</strong></li>
  <b>1. config.xml</b>
  This file defines the installation settings for Office, such as:
  Which Office products and apps to install.
  <b>2. setup.exe</b> 
  This is the Office installation launcher. It reads the instructions from the config.xml file and carries out the installation accordingly.
  </li>
  <li style="color:red;">Right-Click on empty space and select Open in Command Prompt</li>
</ol>
<h2>In Command Prommpt:</h2>
<ol>
  <li><b>Enter this command to run and Download the script: <br> setup /download config.xml</b>b></li>
  <p><strong>Open Task Manager and in the Performance Tab under WiFi, u will see youe network spike mean it working.</strong></p>
  <p><strong>To tell is done your network graph will go all the way down <br>* Make Sure you are not downloading others things in the background</strong></p>
  <li><b>Enter this command to configure the scripts to Office: setup /configure config.xml</b></li>
  <p><strong>Coffee Time! Let Office install. Try not to use your computer in the mean time if can.</strong></p>
  <p>Once Office is Installed. Run this script below:</p>
  <li><b>cd C:\Program Files\Microsoft Office\Office16
  cscript ospp.vbs /sethst:kms.03k.org</br>
  cscript ospp.vbs /act
  </b></li>
  <p><strong>Once done, It will shown Successfully activated in your command prompt / terminal.</strong></p>
</ol>

<h3><strong>If u cannot activate, Solution to resolve it.</strong></h3>
<ul>
  <li>Connect to Personal Hotspot</li>
  <li>Disable Firewall just for this installtion only.</li>
  <li>Disable any Custom DNS been used</li>
  <li>Restsrt your machine</li>
  <li>Using Geek uninstaller to fully uninstall Office and any remainding files. Free Version works fine.
https://geekuninstaller.com/download</li>
</ul>

<p><b>NYP Student&copy; 2025</b></p>
