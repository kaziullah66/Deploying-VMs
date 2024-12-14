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
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462559416_427075810434687_7843140156711193483_n.png?_nc_cat=103&ccb=1-7&_nc_sid=9f807c&_nc_ohc=2vovHyYT8RoQ7kNvgFMIAVT&_nc_zt=23&_nc_ht=scontent-lga3-1.xx&_nc_gid=AVM3pYdqtggrT_Xyh5tjLOs&oh=03_Q7cD1QF3WvFt0i_2zZvIg-pJ2nFHyWKnvSFe9OnopUnBd7GxZQ&oe=67485719"/>
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462570519_3877120955851873_3871025402251609204_n.png?_nc_cat=111&ccb=1-7&_nc_sid=9f807c&_nc_ohc=HjghWuN17i4Q7kNvgG-eaaz&_nc_zt=23&_nc_ht=scontent-lga3-1.xx&_nc_gid=AJhkTUq_rRCRv1DKn8JEGGO&oh=03_Q7cD1QFOBYsGNzKS8G10nkZ1BSDWTJhcq2sJ7uuq2qeL2vx9OA&oe=67485727"/>
</p>
<p>
Click next on Disks and then on Networking. 
</p>
<br />
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462557270_1070135604302510_4645729013953760676_n.png?_nc_cat=108&ccb=1-7&_nc_sid=9f807c&_nc_ohc=flSDy1rAiPcQ7kNvgH6IZT-&_nc_zt=23&_nc_ht=scontent-lga3-1.xx&_nc_gid=A2cYa5dPr05u8DjacjV0QGy&oh=03_Q7cD1QFyEzd3Ia2u142T40Hhg7bEe5FiTVcTamXmMmHiXsrCVQ&oe=67488138"/>
<img src="https://scontent-lga3-2.xx.fbcdn.net/v/t1.15752-9/462547944_1223457248860526_4079091068965591722_n.png?_nc_cat=105&ccb=1-7&_nc_sid=9f807c&_nc_ohc=LVx9Rozr7e4Q7kNvgE6RqW9&_nc_zt=23&_nc_ht=scontent-lga3-2.xx&_nc_gid=ABTDPtZpIPxeVFhtaiv1edE&oh=03_Q7cD1QFLkkhGib_EbjaLmGzCqwxduV-SA8utcV1gsBUujQW_XA&oe=67486F03"/>
</p>
<p>
A virtual network is a private network that allows you to manage your network configurations. You can use the one they have for you or you can create a new one by clicking "Create new", putting in the name you desire for your virtual network, and pressing "OK". 
</p>
<br />
<br />
<p>
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462562604_1607937286819125_5729683410468730047_n.png?_nc_cat=103&ccb=1-7&_nc_sid=9f807c&_nc_ohc=9j0irTtELukQ7kNvgG-dVS_&_nc_zt=23&_nc_ht=scontent-lga3-1.xx&_nc_gid=AZMnglk4lqAVuvy9IuqBimR&oh=03_Q7cD1QF378fI1dE-4aRox6gQqYz97ALZfbAwYRRcOYd98-ATZQ&oe=67485C0E"/>
</p>
<p>
After that, you can click " Review + create". 
</p>

<br />
<p>
<img src="https://scontent-lga3-2.xx.fbcdn.net/v/t1.15752-9/462550773_1266952594328136_5553025988180877298_n.png?_nc_cat=100&ccb=1-7&_nc_sid=9f807c&_nc_ohc=xboAQCwnwlsQ7kNvgFtf-oT&_nc_zt=23&_nc_ht=scontent-lga3-2.xx&_nc_gid=ASaOGuV9H3Oj2SAkjPrCw4n&oh=03_Q7cD1QGarsSLo3oXqCc5r38H-Prh0fcGfW6Z4TYceCSZleFChw&oe=67486582"/>
</p>
<p>
Lastly, once you have passed the validation, you will click "create" and in a few minutes it will be complete. Congratulations on creating your virtual machine!
</p>
<br />



