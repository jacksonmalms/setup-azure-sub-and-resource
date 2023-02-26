<p align="center">
<img src="https://www.imagar.com/wp-content/uploads/2018/06/azure.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>How to Setup a Subscription and a Resource in Azure</h1>
This tutorial is designed to teach absolute beginners that have never touched Azure before how to properly set up an Azure subscription so that they can learn and do labs to practice and gain experience with Azure. (This tutorial may be a bit redundant, I really just made it to practice showcasing my projects and/or tutorials on GitHub!)<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Step 1: Create an Azure account and open up the Azure portal
- Step 2: Within the Azure Portal, Create a Resource Group
- Step 3: Create a Storage Account within the Resource Group created in previous step
- Step 4: Create a file on your local desktop and upload it into the Storage Account
- Step 5: Edit the file within the Storage Account (within the Azure Portal)
- Step 6: Download the file and observe the changes
- Step 7: Delete the Resource Group created in step 2 (to make sure you don't incur any cost)
- Step 8: Verify that the Resource Group has been deleted


<h2>Azure Setup Steps and Resource Group Creation</h2>

<p>
<img src="https://i.imgur.com/LjRwydo.png"/>
</p>
<p>
First, you are obviously going to need to create an account. Go to https://azure.microsoft.com/en-us/free/ and click the green start free button. (Unfortunately you will need a credit/debit card to create your free account, there really isn't any way around this, it just is what it is)
</p>
<br />

<p>
<img src="https://i.imgur.com/ChmLLLV.png"/>
</p>
<p>
After your account setup and confirmation is complete (which may take a minute), you will get redircted to this page. From here, click the blue "Go to the Azure portal" button or you can go to https://portal.azure.com (<-- this is a good link to memorize) and it will sign you into the portal with whichever account that you are currently signed into.
</p>
<br />

<p>
<img src="https://i.imgur.com/6dleiQ2.png"/>
</p>
<p>
Once you get to the portal home page, type "subscriptions" in the search bar to make sure that your subscription is active and identify it.
In the next step, we are going to make our first resource group.
</p>
<br />

<p>
<img src="https://i.imgur.com/GgFY7AJ.png"/>
</p>
<p>
To get to the resource group page, simply search for it in the portal searchbar. Next, hit the blue "Create resource group" button.
</p>
<br />

<p>
<img src="https://i.imgur.com/MIw01SI.png"/>
</p>
<p>
Now lets start configuring our new resource group. Since you probably only have that one subscription, you probably won't need to touch that drop down menu, just make sure it's selected. For the group name I just named it "RG-Lab-1", but you can name it what ever you want. And you will probably want to set the region to your own region, select the region you want from the drop down menu. Hit the "Next: Tags >" button on the bottom left.
</p>
<br />

<p>
<img src="https://i.imgur.com/RH8d7Yt.png"/>
</p>
<p>
On this page you can assign tags to the resource group. Skip this as you don't have to assign any tags, but this is just for organizations to keep track of data pertaining to certain resources. Hit the "Next : Review + create >" button.
</p>
<br />

<p>
<img src="https://i.imgur.com/FIyOpk5.png"/>
</p>
<p>
On this page just make sure the information about the resource group is correct and hit create.
</p>
<br />

<p>
<img src="https://i.imgur.com/UqDWIKU.png"/>
</p>
<p>
Go back to the resource groups page and make sure the new resource group is there, you can get back to the page by searching for it again in the searchbar. Next we are going to test out this new resource group by adding an Azure Storage Account (it is basically like a robust google drive or dropbox).
</p>
<br />

<p>
<img src="https://i.imgur.com/NFs2IEf.png"/>
</p>
<p>
Search for storage accounts in the searchbar and click on it in the services section, it should be the first item in the search result. Once you get to the page, hit the blue "create storage account" button.
</p>
<br />

<p>
<img src="https://i.imgur.com/dLDQe5a.png"/>
</p>
<p>
Now select the subscription and resource group we just made in the first two drop down menus. Then create the name for your storage account, it needs to be globally unique. Now hit the blue review button in the bottom left, you might need to wait a minute for it to run final validation and then hit create!
</p>
<br />

<p>
<img src="https://i.imgur.com/PutNYrh.png"/>
</p>
<p>
Wait for it to complete deployment and hit "Go to resource".
</p>
<br />

<p>
<img src="https://i.imgur.com/hvoA7vJ.png"/>
</p>
<p>
Once you are in the storage account, click on containers.
</p>
<br />

<p>
<img src="https://i.imgur.com/fxeNC54.png"/>
</p>
<p>
Now create a new container, name it, and hit create.
</p>
<br />

<p>
<img src="https://i.imgur.com/DYJvYB6.png"/>
</p>
<p>
Now click on the new container you just made, and we are going to upload a basic text file into the container.
</p>
<br />

<p>
<img src="https://i.imgur.com/ysuSi5q.jpg"/>
</p>
<p>
Just make a new text document on your desktop, then name it and write what ever you want in it.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZuQHKzS.png"/>
</p>
<p>
Click the upload button and you can just drag and drop the file from your desktop or you can search for it in file explorer, and then upload it!
</p>
<br />

<p>
<img src="https://i.imgur.com/vwQkCp3.png"/>
</p>
<p>
Now that you have uploaded the file, you can edit, download it to your computer, or do whatever you want with it.
</p>
<br />

<p>
</p>
<p>
That just about concludes this tutorial/lab, for the final step we are now going to just delete the resource group entirely to ensure that we don't incur any cost. You can redo this tutorial/lab as many times as you'd like until you feel that you've got it down!
</p>
<br />

<p>
<img src="https://i.imgur.com/ZttsXKR.png"/>
</p>
<p>
To delete the resource group, just go back to the resource groups page, click on the resource group, click delete resource group, and type/copy paste the resource group's name to confirm, and then click delete.
