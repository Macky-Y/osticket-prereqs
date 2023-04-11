<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Azure Subscription
- Resource Group
- Virtual Machine

<h2>Installation Steps</h2>

<p>
1. Login to your Microsoft Azure Account.
</p>
<br />
2. Go to <ins>portal.azure.com</ins> and create a resource group in Microsoft Azure by doing these following steps.
</p>
<p>
<img src="https://i.imgur.com/E4aihrd.png" height="80%" width="80%" alt=""/>
</p>

<p>
<img src="https://i.imgur.com/MQq5Wgq.png" height="80%" width="80%" alt=""/>
</p>

<p>
<img src="https://i.imgur.com/21I7aJq.png" height="80%" width="80%" alt=""/>
</p>

<p>
<img src="https://i.imgur.com/ecgunwc.png" height="80%" width="80%" alt=""/>
</p>

<p>
<img src="https://i.imgur.com/jZdNEGl.png" height="80%" width="80%" alt=""/>
</p>

<p>
<img src="https://i.imgur.com/Bgomd73.png" height="80%" width="80%" alt=""/>
</p>

<p>
<img src="https://i.imgur.com/ZnkxePv.png" height="80%" width="80%" alt=""/>
</p>

<p>
<img src="blob:https://imgur.com/2a51b8dd-9e52-40d5-868b-d1159f66a624" height="80%" width="80%" alt=""/>
</p>

<p>
3. Now let's create our Virtual Machine in Microsoft Azure. Follow these steps.
</p>

<p>
<img src="https://i.imgur.com/JdZ9IWw.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/xojxgGR.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/xk1M1lE.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/A9pvgJN.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/oiYOqCU.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/O7Q5lTr.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/f9edjg9.png" height="80%" width="80%" alt="" />
</p>

- Once we clicked <ins>Review + Create</ins> let's wait for the VM to finish deployment

<p>
<img src="https://i.imgur.com/Nevweih.png" height="80%" width="80%" alt="" />
</p>

- Once it says <ins>Your deployment is complete</ins>, do these steps.

<p>
<img src="https://i.imgur.com/XNaJmXA.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/Kn93TF0.png" height="80%" width="80%" alt="" />
</p>

- Our deployed VM will appear in this page.

<p>
<img src="https://i.imgur.com/G94BL6r.png" height="80%" width="80%" alt="" />
</p>

<p>
4. For macOS users, download <ins>Microsoft Remote Desktop</ins>. We will use this to connect to our VM. If you're using Windows, use <ins>Remote Desktop Connection</ins>, the steps are the same.
</p>

<p>
<img src="https://i.imgur.com/2a8lxLn.png" height="80%" width="80%" alt="" />
</p>

<p>
5. Let's connect to our VM by following these steps.
</p>

<p>
<img src="https://i.imgur.com/hgWCVmt.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/ZgV6B3V.png" height="80%" width="80%" alt="" />
</p>

- Now open <ins>Microsoft Remote Desktop</ins> application.
- Once the application is open, you will see this screen.

<p>
<img src="https://i.imgur.com/yJKcOc8.png" height="80%" width="80%" alt="" />
</p>

- Follow these steps to connect to our VM.

<p>
<img src="https://i.imgur.com/rsidiIf.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/6OeiM8c.png" height="80%" width="80%" alt="" />
</p>

- Once we added our VM, you will be taken to this page. Double click it to connect.

<p>
<img src="https://i.imgur.com/NWtaoN7.png" height="80%" width="80%" alt="" />
</p>

- You will be asked for your credentials to connect to our VM. Input the username and password we created earlier and click <ins>Continue</ins>.

<p>
<img src="https://i.imgur.com/E33Dtdn.png" height="80%" width="80%" alt="" />
</p>

- Click <ins>Continue</ins>.

<p>
<img src="https://i.imgur.com/sCdGfCO.png" height="80%" width="80%" alt="" />
</p>

- Now we will wait for the application to connect to the VM.

<p>
<img src="https://i.imgur.com/LRfJBAI.png" height="80%" width="80%" alt="" />
</p>

- Select <ins>No</ins> to everything and click <ins>Accept</ins>.

<p>
<img src="https://i.imgur.com/D8eKCVb.png" height="80%" width="80%" alt="" />
</p>

<p>
Click <ins>Yes</ins> and now we're connected to our Windows VM.

<p>
<img src="https://i.imgur.com/g5Yxe4p.png" height="80%" width="80%" alt="" />
</p>

<p>
6. Now we will install and set up our osTicket. Open your internet browser inside the VM and download all these files <a href="https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6">here</a>.
</p>
<p>
<img src="https://i.imgur.com/mGqBR6P.png" height="80%" width="80%" alt=""/>
</p>

<p>
7. After downloading the files, we will install and enable <ins>Internet Information Services</ins>. Follow these steps.
</p>

- Click the <ins>start</ins> button and go to <ins>Control Panel</ins>

<p>
<img src="https://i.imgur.com/AU2EVba.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/W7uGBtm.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/HWaOoDC.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/WTLiG2Y.png" height="80%" width="80%" alt="" />
</p>


<p>
<img src="https://i.imgur.com/QuMz87e.png" height="80%" width="80%" alt="" />
</p>


<p>
<img src="https://i.imgur.com/AndxO1H.png" height="80%" width="80%" alt="" />
</p>

- Wait for this to finish.

<p>
<img src="https://i.imgur.com/5JVnC9l.png" height="80%" width="80%" alt="" />
</p>

- Once it finished downloading and installing, let's check if IIS is working by going to the browser and typing our loopback address <ins>127.0.0.1</ins> and we should see this page.

<p>
<img src="https://i.imgur.com/YcKQ6nP.png" height="80%" width="80%" alt="" />
</p>

<p>
8. From the downloaded file, install <ins>PHPManagerForIIS_V1.5.0</ins>.
</p>

<p>
9. From the downloaded file, install <ins>rewrite_amd64_en-US</ins>.
</p>

<p>
  10. Open your File Explorer inside your VM, go to <ins>This PC</ins>, double click <ins>Windows (C:)</ins>, and create a folder and name it <ins>PHP</ins>.
</p>

<p>
<img src="https://i.imgur.com/l9V8Za2.png" height="80%" width="80%" alt="" />
</p>

<p>
11. From the downloaded file, extract <ins>php-7.3.8-nts-Win32-VC15-x86</ins> to your PHP folder.
</p>

<p>
<img src="https://i.imgur.com/xxSfA0o.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/uPVEeCT.png" height="80%" width="80%" alt="" />
</p>

<p>
12. Go to <ins>This PC</ins>, double click <ins>Windows (C:)</ins> and select your PHP folder.
</p>

<p>
<img src="https://i.imgur.com/Es1Nda7.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/UGC9CAT.png" height="80%" width="80%" alt="" />
</p>

- Now our <ins>PHP</ins> folder should look like this.

<p>
<img src="https://i.imgur.com/7tSADa1.png" height="80%" width="80%" alt="" />
</p>

<p>
13. From the downloaded file, install <ins>VC_redist.x86</ins>.
</p>

<p>
14. From the downloaded file, install <ins>mysql-5.5.62-win32</ins>. Follow these steps.
</p>

<p>
<img src="https://i.imgur.com/OqcZbq4.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/nR5c0HO.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/qz2SyOg.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/qj3rIFA.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/GY4O84Z.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/14vpjP1.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/YwteoTk.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/bRm5MT5.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/wgm1Z91.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/3YY9uuC.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/zJuDUSq.png" height="80%" width="80%" alt="" />
</p>

<p>
15. Open <ins>IIS</ins> as an admin and follow these steps.
</p>

<p>
<img src="https://i.imgur.com/FZKdsxu.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/MyHKz65.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/GRmw6F6.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/sL9rseI.png" height="80%" width="80%" alt="" />
</p>

- Go to <ins>This PC</ins>, double click <ins>Windows (C:)</ins>, go to your <ins>PHP</ins> folder.

<p>
<img src="https://i.imgur.com/2tHxQmm.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/gbVAagt.png" height="80%" width="80%" alt="" />
</p>

- Now it should look like this.

<p>
<img src="https://i.imgur.com/CT0jlOW.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/6dorvyQ.png" height="80%" width="80%" alt="" />
</p>

<p>
16. Now we will install osTicket. Go to <ins>File Explorer, This PC, Windows (C:), inetpub, and wwwroot</ins>.
</p>

<p>
17. Open a new <ins>File Explorer</ins> tab and from the downloaded file open <ins>osTicket-v1.15.8</ins>. Drag the <ins>upload</ins> file from osTicket to <ins>wwwroot</ins> folder and wait for it to finish.
</p>


<p>
<img src="https://i.imgur.com/7W1H0kU.png" height="80%" width="80%" alt="" />
</p>

<p>
18. Restart <ins>IIS</ins> again.
</p>

<p>
19. Follow these steps to configure osTicket.
</p>

<p>
<img src="https://i.imgur.com/UF1WowJ.png" height="80%" width="80%" alt="" />
</p>

- Note some of the extensions are not enabled.
<p>
<img src="https://i.imgur.com/6Yh734Q.png" height="80%" width="80%" alt="" />
</p>

- Follow these steps to enable the extensions we need for osTicket.

<p>
<img src="https://i.imgur.com/taxgaLD.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/LasaWTX.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/Rrjboyo.png" height="80%" width="80%" alt="" />
</p>

- Refresh your browser and osTicket should now look like this.

<p>
<img src="https://i.imgur.com/qcvxdkN.png" height="80%" width="80%" alt="" />
</p>

<p>
20. We need to do a few more steps to configure our osTicket. Follow these steps.
</p>

- Go to <ins>File Explorer</ins> and go to this path: <ins>C:\inetpub\wwwroot\osTicket</ins>

<p>
<img src="https://i.imgur.com/tI0TAxt.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/DE5pgp6.png" height="80%" width="80%" alt="" />
</p>


<p>
<img src="https://i.imgur.com/3Dd84UN.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/lViupfH.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/UHp6eiY.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/xJBD6bc.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/qf8XW78.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/JQYiFV7.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/gk0Z7Oc.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/KXN6lL5.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/ZaUKCiJ.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/efupyZQ.png" height="80%" width="80%" alt="" />
</p>

<p>
21. Now we will setup osTicket in our browser. Follow these steps.
</p>

<p>
<img src="https://i.imgur.com/wLofggc.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/e7rMX31.png" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/T42XPSJ.png" height="80%" width="80%" alt="" />
</p>

- From the downloaded file, open and install <ins>HeidiSQL_12.3.0.6589_Setup.exe</ins>. Once it finished downloading open it.

<p>
<img src="" height="80%" width="80%" alt="" />
</p>

<p>
<img src="" height="80%" width="80%" alt="" />
</p>

<p>
<img src="" height="80%" width="80%" alt="" />
</p>

<p>
<img src="" height="80%" width="80%" alt="" />
</p>

<p>
<img src="" height="80%" width="80%" alt="" />
</p>

<p>
<img src="" height="80%" width="80%" alt="" />
</p>

<p>
<img src="" height="80%" width="80%" alt="" />
</p>

<p>
<img src="" height="80%" width="80%" alt="" />
</p>




<p>
<img src="" height="80%" width="80%" alt="" />
</p>




















<p>
<img src="" height="80%" width="80%" alt="" />
</p>

<p>
<img src="" height="80%" width="80%" alt="" />
</p>















<p>
<img src="" height="80%" width="80%" alt="" />
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>






<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>

<br />



<br />



<br />
