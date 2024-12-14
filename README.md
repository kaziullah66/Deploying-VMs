<p align="center">
<img src="https://i.imgur.com/LN04E6D.jpeg" width="550" height="300"/>
</p>

  <h1 align="center">Deploying Azure Virtual Machines</h1>
  In this tutorial, we will go through the steps needed to create virtual machines on Azure. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Resource Group Environment
- Region
- Virtual Network(VNet)
- Operating Systems
- Storage
- Authentication



<h2>Steps</h2>

<p>
<img src="https://i.imgur.com/cxmL9oz.png"/>
</p>
<p>
Go to virtual machines, click the "+ Create" button, and click Azure virtual machine. 
</p>
<br />
<br />
<p>
<img src="https://i.imgur.com/NkBMnCB.png"/>
</p>
<p>
Now you can choose a subscription.
</p>
<br />
<br />
<p>
<img src="https://i.imgur.com/Pjy6278.png"/>
</p>
<p>
Next, we will create a resource group by clicking "Create new", putting a name, and pressing "OK". A resource group holds all our resources in one place making it easy to manage. 
</p>
<br />
<br />
<p>
<img src="https://i.imgur.com/9QyAwpM.png"/>
</p>

<p>
Here you will think of a name for your virtual machine. Make sure to keep it short and meaningful. 
</p>
<br />
<br />
<p>
<img src="https://i.imgur.com/6FkaNIU.png"/>
</p>
<p>
In this part, we will choose where our virtual machine will be located. A virtual machine is a software-based computer and they are stored in servers all around the world. Here you will choose where you would like to have your virtual machine.
</p>
<br />
<br />
<p>
<img src="https://i.imgur.com/xtFz6Hn.png"/>
</p>
<p>
Image is simpily the operating system you wish to use. Your options to choose from include Windows and Linux-based virtual machines.
</p>
<br />
<br />
<p>
<img src="https://i.imgur.com/1LTdbWc.png"/>
</p>
<p>
After we have chosen the image, we have to choose the size. You will choose the size based on what you will use the virtual machine for, also taking into account the cost and scalability. However, you can scale up and down based on your needs later. For example, if you are just testing on small tasks, you may be able to get away with 2 VCPs (2 cores), which will allow for a much lower cost.
</p>
<br />
<img src="https://i.imgur.com/A5Htbma.png"/>
</p>
<p>
For "authentication type" we will select, password. Now take out a sheet of paper or open notepad on the computer, to note down your credentials (username and password) so you never forget it.
</p>
<br />
<br />
<p>
<img src="https://i.imgur.com/v6kXhyn.png"/>
<img src="https://i.imgur.com/N7WUsZW.png"/>
</p>
<p>
Click next on Disks and then on Networking. 
</p>
<br />

<img src="https://i.imgur.com/Kr7ox3u.png"/>
</p>
<p>
A virtual network is a private network that allows you to manage your network configurations. You can use the one they have for you or you can create a new one by clicking "Create new", putting in the name you desire for your virtual network, and pressing "OK". 
</p>
<br />
<br />
<p>
<img src="https://i.imgur.com/ThgAzJ0.png"/>
</p>
<p>
After that, you can click " Review + create". 
</p>

<br />
<p>
<img src="https://i.imgur.com/37W4eD6.png"/>
</p>
<p>
Lastly, once you have passed the validation, you will click "create" and in a few minutes, it will be complete. Congratulations on creating your virtual machine!
</p>
<br />



