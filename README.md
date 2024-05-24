<p align="center">
<img src="https://imgur.com/6jyO94C.png" height="20%" width="40%">
</p>

<h1>Virtual Private Networks</h1>
This tutorial outlines setting up a VPN and exploring its use.<br />
<p></p>



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- www.whatismyipaddress.com
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Creating a Virtual Machine in Azure</h2>
<p></p>
To start we will go to "www.whatismyipaddress.com" to find out our computer's IP address. Take note of this. Next, we will create a Resource Group (RG-VPN) and a Windows 10 Virtual Machine (VM-VPN) in a different geographical location, I chose Japan.
<p>
<img src="https://imgur.com/AEsXKHx.png" height="40%" width="80%">
<p></p>
Login to VM-VPN and go to "www.whatismyipaddress.com" to get the VM's IP Address.
<p>
<img src="https://imgur.com/AFYRUFv.png" height="40%" width="80%">
<p></p>

<h2>Signing Up for ProtonVPN and Testing Connection</h2>
<p></p>
Back on our computer, we will sign up for ProtonVPN. Once we are signed up we will download the ProtonVPN client on VM-VPN.
<p>
<img src="https://imgur.com/z47PphN.png" height="40%" width="80%">
<p></p>
Now we will connect to the VPN server in a different country, I chose The Netherlands.
<p>
<img src=".png" height="40%" width="80%">
<p></p>
Open a browser and go to "www.whatismyipaddress.com" again and we can observe our IP address has changed to a location in The Netherlands.
<p>
<img src=".png" height="40%" width="80%">
<p></p>
Now when we go to websites such as "www.google.com", "www.youtube.com", and "www.disney.com" the computer assumes we are in The Netherlands and shows us the content for that country.
