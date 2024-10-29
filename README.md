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
Now we will create a resource group. A resource group holds all of your resources in one place making it easy to manage. 
</p>
<br />
<br />
<p>
<img src="https://scontent-lga3-2.xx.fbcdn.net/v/t1.15752-9/462543021_1616316085945696_4570867840570373192_n.png?_nc_cat=105&ccb=1-7&_nc_sid=9f807c&_nc_ohc=NdPEFi3Z3lgQ7kNvgEvuYk2&_nc_ht=scontent-lga3-2.xx&_nc_gid=ASJlsmJFniigreI5skKyyu4&oh=03_Q7cD1QHMGnZgzPk5upi7CD57GTN4HbDy2m0Jgs4VnajorX0Bcg&oe=67333DBA"/>

<img src="https://scontent-lga3-2.xx.fbcdn.net/v/t1.15752-9/462567831_552622970489830_6102310246806097682_n.png?_nc_cat=101&ccb=1-7&_nc_sid=9f807c&_nc_ohc=YnHwbvvURNMQ7kNvgHFW9dU&_nc_ht=scontent-lga3-2.xx&_nc_gid=AX4KhUkcdsIG868Ji_ZAveV&oh=03_Q7cD1QG2RLf7ygG7ygNDcSTOeZpE7AohK5uUUpY9E444y_i2dg&oe=67334B05"/>

</p>
<p>
We created an inbound port rule for our Linux virtual machine in Azure to deny incoming requests. We see that the requests are now timing out and being ignored.
</p>
<br />
<br />
<p>
<img src="https://scontent-lga3-2.xx.fbcdn.net/v/t1.15752-9/462639026_1085569749852165_3156622879168093775_n.png?_nc_cat=101&ccb=1-7&_nc_sid=9f807c&_nc_ohc=EJtMqOO3mB0Q7kNvgFLqBnQ&_nc_ht=scontent-lga3-2.xx&_nc_gid=ANZkkAN6lGuj11HiKzAubIr&oh=03_Q7cD1QHDWVPHHlU8QhnMe56rfaLfLWdXLGkfYdO9FK64dcu7NA&oe=6734FBAA"/>
</p>
<p>
We connected to our Linux virtual machine and filtered for SSH. 
</p>
<br />
<br />
<p>
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




