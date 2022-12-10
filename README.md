<p align="center">
<img src="https://imgur.com/IDf9K3v.png" height="40%" width="40%" alt="Microsoft Azure Logo"/>
</p>

<h1>Azure Storage Account</h1>
This tutorial teaches how to deploy a cloud storage account via Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Storage Account)
- Notepad (For Test Files)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Create Azure Account
- Step 2: Deploy Resource Group
- Step 3: Deploy Storage Account
- Step 4: Deploy Container
- Step 5: Upload to Storage Account

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://imgur.com/1kHoC6I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Search and download "Microsoft Azure" to create an account. Once the account is created, a "subscription" will be auto deployed for you (if not then proceed to create one) please view above picture and follow the prompts. This subscription is where the future storage account will reside once made. 
</p>
<br />

<p>
<img src="https://imgur.com/NQ0WqAC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For this step search "resource group" in the Azure search bar --> create a resource group titled "RG-Storage-Account". Make sure to use your desired region and place the RG into the correct subscription. For the subscription box, since we only have one subscription, the RG will default to that location. Click "create".
</p>
<br />

<p>
<img src="https://imgur.com/b2fFmWW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, search "storage account" in the Azure search bar --> Click "create storage account". Make sure you place this account in the subscription and resource group created in the previous steps. As a side note, the storage account title must be globally unique. 
</p>
<br />

<p>
<img src="https://imgur.com/UXQMBUX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
A "container" is similar to a folder. You can have multiple containers with different files and permissions attached to them. Deploy a container within the created storage account to prepare for file uploads. Select storage Account --> your storage account --> containers --> create new container. Name the container and adjust the access level to private or public depending on your needs. 
</p>
<br />

<p>
<img src="https://imgur.com/RKwGsJn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/tPyNtMw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is the final step. Open "Notepad" on your PC --> Create a new random note (titled test) --> save it --> click your storage account container --> upload the note into your cloud storage account. You can also edit the file while it is in your cloud account if need be. That concludes this lesson.
</p>
<br />
