<p align="center">
<img src="https://i.imgur.com/FrE0QAf.png"/>
</p>

<h1>Virtual Machine Remote Desktop Connection in Microsoft Azure</h1>
In this tutorial, we create a resource group, virtual machine and connect via Remote Desktop Connection in Microsoft Azure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Azure Portal
- Resource Group
- Windows 10 Virtual Machine
- Remote Desktop Connection
- Confirmation

<h2>Azure Portal</h2>

<p>
<img src="https://i.imgur.com/xylOPQX.png"/>
</p>
<p>
Go to: Portal. Azure.com. <br /> <br />
Log In Azure Portal if not already logged in. <br /> <br />
Select "Resource groups" icon. <br /> <br /> <br /> <br />
</p>
<br />


<h2> Resource Group </h2>

<p>
<img src="https://i.imgur.com/4vii2Bn.png"/>
</p>
<p>
Select "Create" button in the middle of the page.
</p>
<br />

<p>
<img src="https://i.imgur.com/MrNi9xH.png"/>
</p>
<p>
For the Subscription select the approriate subscription if you have more than one Azure subscription. <br /> <br />
If you only have one subscription skip this step and proceed to the next step. <br /> <br />
For the Resource Group type the desired name for the resource group, for this tutorial we will be using "RGLab2". <br /> <br />
For the Region select the desired region, for this tutorial we will be using "(US) East US". <br /> <br />
Select the "Review + create" button to proceed with the creation of the Resource group. <br /> <br />
</p>
<br />


<p>
<img src="https://i.imgur.com/DAnWsrs.png"/>
</p>
<p>
Once all the steps have been completed correctly you will see a green check mark and the words "Validation passed". <br /> <br />
Select the "Create" button to proceed with the creation of the Resource Group. <br /> <br />
</p>
<br />


<p>
<img src="https://i.imgur.com/5IdDhot.png"/>
</p>
<p>
Our newly created Resource group is completed and displayed in the Resource group Home Page.
</p>
<br />



<h2>Windows 10 Virtual Machine </h2>

<p>
<img src="https://i.imgur.com/3Eppu0i.png"/>
</p>
<p>
Go to Portal.Azure.com. <br /> <br />
Type "Virtual Machines" in the search bar. <br /> <br />
Select "Virtual Machines" from the search results. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/J8RlpJb.png"/>
</p>
<p>
Select "+ Create" button. <br /> <br />
From the drop down menu select "Azure virtual machine". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/PCMMH4k.png"/>
</p>
<p>

For the Subscription select the approriate subscription if you have more than one Azure subscription. <br /> <br />
If you only have one subscription skip this step and proceed to the next step. <br /> <br />
For the Resource Group select the desired Resource Group, for this tutorial we will be using "RGLab2". <br /> <br />
For the Region select the desired region, for this tutorial we will be using "(US) East US". <br /> <br />
For the Availabilty Zone select the desired availability zone, for this tutorial we will be using "Zone 2". <br /> <br />
Please be sure to deselect "Zone 1" so that 2 zones are not selected in the same region for the same virtual machine. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/wS17vr4.png"/>
</p>
<p>
For the Image select "Windows 10 Pro".
</p>
<br />


<p>
<img src="https://i.imgur.com/BdIyfEQ.png"/>
</p>
<p>
For the Size select "Standard- 2 vcpus". <br /> <br />
For the Username type "labuser". <br /> <br />
For the Password create something that you can easily remember or write down and easily retrieve. <br /> <br />
For the Confirm Password repeat the same password you previously created. <br /> <br />
</p>
<br />


<p>
<img src="https://i.imgur.com/VLSFGfX.png"/>
</p>
<p>
Acknowledge Licensing Confirmation a blue box should appear. <br /> <br />
Select "Review + create" to proceed with the creation of the virtual machine. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/SnoYnNO.png"/>
</p>
<p>
Once all the steps have been completed correctly a green check mark shoudl apprear and the words "Validation passed". <br /> <br />
Select "Create" to proceed with the creation of the virtual machine. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/puecVtv.png"/>
</p>
<p>
The virtual machine is currecntly being deployed (created).
</p>
<br />

<p>
<img src="https://i.imgur.com/mH0mkEm.png"/>
</p>
<p>
The virtual machine has been deployed and is ready to be resourceful as a newly created resource.
</p>
<br />


<h2>Remote Desktop Connection</h2>

<p>
<img src="https://i.imgur.com/3Eppu0i.png"/>
</p>
<p>
Go to: Portal.Azure.com. <br /> <br />
Type "Virtual Machines" in the search bar. <br /> <br />
Select "Virtual Machines" from the search results. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/IMJA7CL.png"/>
</p>
<p>
Select VM1.
</p>
<br />

<p>
<img src="https://i.imgur.com/mBuLL3M.png"/>
</p>
<p>
Copy the Public IP Address for VM1.
</p>
<br />

<p>
<img src="https://i.imgur.com/Xmho7HL.png"/>
</p>
<p>
Go to the Windows Pane at the bottom of the screen, in the search bar type "Remote Desktop" and press the Enter button.
</p>
<br />

<p>
<img src="https://i.imgur.com/FIeULC9.png"/>
</p>
<p>
Paste the Public IP Address for VM1. <br /> <br />
Press "Connect" to proceed with accessing Remote Desktop Connection for VM1. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/HT2WDcA.png"/>
<img src="https://i.imgur.com/wFCCLv1.png"/>

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/sXDpRnx.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/PUcdRKD.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<h2>Confirmation </h2>

<p>
<img src="https://i.imgur.com/2DsSqnz.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/xC20aHM.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


