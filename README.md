# Deploying-VMs


<p align="center">
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462546323_2601541603570069_6929602243085794007_n.jpg?stp=dst-jpg_s2048x2048&_nc_cat=103&ccb=1-7&_nc_sid=9f807c&_nc_ohc=B7W_dorxipYQ7kNvgF_BWq1&_nc_zt=23&_nc_ht=scontent-lga3-1.xx&_nc_gid=AcqTjbfsoSvIAhbNGuwPZWD&oh=03_Q7cD1QFgv50kgJDFjkoqS1AJ6j6V_j-I2Zz-icBMsw1LNbIbQQ&oe=6742F978" width="550" height="300"/>
</p>

<h1>Deploying Azure Virtual Machines</h1>
In this tutorial, we will go through the steps needed to create virtual machines on Azure. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Resource Group Environment
- Region
- Virtual Network(VNet)
- Subnet
- Operating Systems
- Storage
- Network Security Groups(NSGs)



<h2>Steps</h2>

<p>
<img src="https://scontent-lga3-2.xx.fbcdn.net/v/t1.15752-9/462535692_1057394996127071_1273292413106901476_n.png?_nc_cat=101&ccb=1-7&_nc_sid=9f807c&_nc_ohc=i4GFQ3JnzeYQ7kNvgEZa4-O&_nc_zt=23&_nc_ht=scontent-lga3-2.xx&_nc_gid=AuKfCNWZjujMrIacc4Nqn56&oh=03_Q7cD1QFbdqjeQzlzw2CKDxMfoOkLAEYftOgeNJFRTGMH_i064g&oe=6743C3F8"/>
</p>
<p>
Go to virtual machines, click the "+ Create" button, and click Azure virtual machine. 
</p>
<br />
<br />
<p>
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462551411_1959053414520918_4385247132022562839_n.png?_nc_cat=110&ccb=1-7&_nc_sid=9f807c&_nc_ohc=c2k6ZK4QO3gQ7kNvgGB9vuW&_nc_zt=23&_nc_ht=scontent-lga3-1.xx&_nc_gid=AUr0V-nsWZigJduxQQ4_VmO&oh=03_Q7cD1QEVgq9K8GEYvmxH3PIWNWDdw8x0EqNGCF1tD51jxG1eoA&oe=6745AB94"/>
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
Next we will create a resource group. A resource group holds all of our resources in one place making it easy to manage. 
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
In this part we will choose where our virtual machine will be located. A virtual machine is a software based computer and they are stored in servers all around the world. Here yo will choose where you would like to have your virtual machine.
</p>
<br />
<br />
<p>
<img src="https://scontent-lga3-2.xx.fbcdn.net/v/t1.15752-9/462547921_3523912771248600_2757100729062954209_n.png?_nc_cat=100&ccb=1-7&_nc_sid=9f807c&_nc_ohc=eQbXbDUofnMQ7kNvgFgPBmI&_nc_zt=23&_nc_ht=scontent-lga3-2.xx&_nc_gid=ARSu9sOtCdfuxPVcN3FGaXf&oh=03_Q7cD1QECcsuRkexx26seI2uV7yImprujVsPX-8Nqk8sfDJ25LQ&oe=67483F1ED"/>
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
After we have chosen your image we have to choose the size. You will choose the size based on what you will use the virtual machine for, also taking into account the cost and scalability but you are able to scale up and down based on your needs later. For example if you are just testing on small tasks you may be able to get away with 2 vcpus(2 cores) which will allow for a much lower cost.
</p>
<br />
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462539840_1050355300170841_2499457334563325859_n.png?_nc_cat=102&ccb=1-7&_nc_sid=9f807c&_nc_ohc=NdhcGkN1veQQ7kNvgGLSg5u&_nc_ht=scontent-lga3-1.xx&_nc_gid=AaAaEIdQiNam4YE_ZM3ed0M&oh=03_Q7cD1QFayGGyexi3A9APUGfAnsVJBpzC7uCo_rHE2Bkm7kHkwQ&oe=6735227D"/>
</p>
<p>
We filtered for DNS. 
</p>
<br />
<br />
<p>
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462540281_556518583724149_4773454699472645203_n.png?_nc_cat=103&ccb=1-7&_nc_sid=9f807c&_nc_ohc=FKDA7piLw2sQ7kNvgG2F7n7&_nc_ht=scontent-lga3-1.xx&_nc_gid=A-36XImvw4MaPyR_7jzt4RD&oh=03_Q7cD1QGIKzQ4U6j34kGtetV0bcb3DmyjqBuQKVtKsM5dDkUAXA&oe=673528F1"/>
</p>
<p>
We filtered for RDP. 
</p>
<br />
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462539840_1050355300170841_2499457334563325859_n.png?_nc_cat=102&ccb=1-7&_nc_sid=9f807c&_nc_ohc=NdhcGkN1veQQ7kNvgGLSg5u&_nc_ht=scontent-lga3-1.xx&_nc_gid=AaAaEIdQiNam4YE_ZM3ed0M&oh=03_Q7cD1QFayGGyexi3A9APUGfAnsVJBpzC7uCo_rHE2Bkm7kHkwQ&oe=6735227D"/>
</p>
<p>
We filtered for DNS. 
</p>
<br />
<br />
<p>
<img src="https://scontent-lga3-1.xx.fbcdn.net/v/t1.15752-9/462540281_556518583724149_4773454699472645203_n.png?_nc_cat=103&ccb=1-7&_nc_sid=9f807c&_nc_ohc=FKDA7piLw2sQ7kNvgG2F7n7&_nc_ht=scontent-lga3-1.xx&_nc_gid=A-36XImvw4MaPyR_7jzt4RD&oh=03_Q7cD1QGIKzQ4U6j34kGtetV0bcb3DmyjqBuQKVtKsM5dDkUAXA&oe=673528F1"/>
</p>
<p>
We filtered for RDP. 
</p>
<br />




