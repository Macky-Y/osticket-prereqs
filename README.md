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
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>

<br />

<p>
Download all these files <a href="https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6">here</a>.
</p>
<p>
<img src="https://i.imgur.com/mGqBR6P.png" height="80%" width="80%" alt=""/>
</p>

<br />



<br />
