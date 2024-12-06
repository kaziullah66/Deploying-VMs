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
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462542831_1295424718537201_8759737473628678491_n.png?_nc_cat=111&ccb=1-7&_nc_sid=9f807c&_nc_ohc=00t9Yfd4i0MQ7kNvgGBcJ9v&_nc_zt=23&_nc_ht=scontent-lga3-1.xx&_nc_gid=AZ3S1PydjAvAFWbSr-oX_Rf&oh=03_Q7cD1QHrjc1cVlP1u4rYA0jtLLFb72Fd5n-_b1-IGyEozvnAIA&oe=67484CA6"/>
</p>
<p>
Next, we will create a resource group by clicking "Create new", putting a name, and pressing "OK". A resource group holds all our resources in one place making it easy to manage. 
</p>
<br />
<br />
<p>
<img src="https://scontent-lga3-2.xx.fbcdn.net/v/t1.15752-9/462559019_1882273395594663_1246778324972284439_n.png?_nc_cat=109&ccb=1-7&_nc_sid=9f807c&_nc_ohc=55tCh2IllLsQ7kNvgERqkze&_nc_zt=23&_nc_ht=scontent-lga3-2.xx&_nc_gid=ADcKHZ4NZKSDgGl4wvNQ23A&oh=03_Q7cD1QF4uMFUdtqwI3ypAJygsXOgTiAYMtJG1fOVoira-7Luyg&oe=67484135"/>
</p>

<p>
Here you will think of a name for your virtual machine. Make sure to keep it short and meaningful. 
</p>
<br />
<br />
<p>
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462554620_931057108886008_5070631755048768871_n.png?_nc_cat=108&ccb=1-7&_nc_sid=9f807c&_nc_ohc=mjo1e4DrUUsQ7kNvgEvN3Be&_nc_zt=23&_nc_ht=scontent-lga3-1.xx&_nc_gid=AzHicXKjquL-qnG3Lc2ttgE&oh=03_Q7cD1QFakdojOx-ftG6AgPWhIUEorQ3fLk4Xl30tFbTH-wcIcg&oe=674834D9"/>
</p>
<p>
In this part, we will choose where our virtual machine will be located. A virtual machine is a software-based computer and they are stored in servers all around the world. Here you will choose where you would like to have your virtual machine.
</p>
<br />
<br />
<p>
<img src="https://scontent-lga3-2.xx.fbcdn.net/v/t1.15752-9/462547921_3523912771248600_2757100729062954209_n.png?_nc_cat=100&ccb=1-7&_nc_sid=9f807c&_nc_ohc=eQbXbDUofnMQ7kNvgFgPBmI&_nc_zt=23&_nc_ht=scontent-lga3-2.xx&_nc_gid=A9yP-NXrluf0TChW0VAlSTC&oh=03_Q7cD1QGqCCMnEDafo1Jd6JVEBJ9JEffB45GtgGkZ1Lkc_bMQhg&oe=67483F1E"/>
</p>
<p>
Image simpily is the operating system you wish to use. Your options to choose from include Windows and Linux based virtual machines.
</p>
<br />
<br />
<p>
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462553997_502399422802145_4953393159092313798_n.png?_nc_cat=111&ccb=1-7&_nc_sid=9f807c&_nc_ohc=9dg9iPl34goQ7kNvgENqyjX&_nc_zt=23&_nc_ht=scontent-lga3-1.xx&_nc_gid=A5evCHFN0zq_LioqLVOLA68&oh=03_Q7cD1QEBjGqT7gModbQJ5rZOimhl3FdsPJaeMJC9ivPJv5in_w&oe=6748436C"/>
</p>
<p>
After we have chosen your image we have to choose the size. You will choose the size based on what you will use the virtual machine for, also taking into account the cost and scalability but you are able to scale up and down based on your needs later. For example, if you are just testing on small tasks you may be able to get away with 2 vcpus(2 cores) which will allow for a much lower cost.
</p>
<br />
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462637782_595077726284457_935809349317951669_n.png?_nc_cat=102&ccb=1-7&_nc_sid=9f807c&_nc_ohc=V5vznWpKjM8Q7kNvgFwbwlm&_nc_zt=23&_nc_ht=scontent-lga3-1.xx&_nc_gid=A34kRGjwkhD60NTFLMcFZOT&oh=03_Q7cD1QGaHaucq6sikBNk8psfYdD0QpoDdUgM46kfwGp5SwLfWQ&oe=67484803"/>
</p>
<p>
For "authentication type" we will select password. Take out something, physical paper or notepad of the computer, to note down your credentials (username and password) so you never forget it.
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



