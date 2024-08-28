<p align="center">
  
![image](https://github.com/user-attachments/assets/5ae4ae45-a988-4468-8cb1-9a4b61f82eca)

</p>

<h1>RDP To Another Desktop</h1>
</p>
This is a demonstration on how to RDP to another Desktop  .<br />

<p>
<h1>Technologies and Environments Include</h1>
  -Microsoft Azure(Virtual Machines)
  
  -RDP(Remote Desktop Protocol)
</p>
<h1>Operating Systems Used</h1>
-Windows 11

-Windows 10(For Virtual Machine)

<h1>Prerequisites Include</h1>
-Azure Subscription(Free Subscription)

-RDP Software(Using Windows Version is this demonstration)
</p>
<p>
Alrighty, To start things off your going to head to your desktops broswer and search "portal.azure.com" From here you are going to select "Resource Group" or type it into the provided search bar.Go ahead an select "Create" and give your group a name.(For this example im naming mine RG-01) select your region, and then select "review and create.Once Finished, it should look something close to this as shown below.
</p>

![image](https://github.com/user-attachments/assets/88a24e9f-c54f-4fda-b243-13713b9bd46e)


</p>
<br />
<p>
</p>
<p>
From this page, Use the search bar and type "Virtual Machine", select create virtual machine. Select the Resource Group you have just created and give your new machine a new(im using the name VM-01), use a region that works with your system and a size that is avaliable for your subscription
  
![image](https://github.com/user-attachments/assets/544b8309-a289-4a6b-ac20-2dbeae12d88e)

  Now your going to want to create a username and password(this is an important step in using RDP) checkmark the licensing box at the bottom and select "review and create" If done correctly, validation should pass and just click create.
  
  ![image](https://github.com/user-attachments/assets/b921494b-6f00-426a-94dd-84815638e7eb)

  Watch the magic happen while your Virtual Machine is being created.
  
  ![image](https://github.com/user-attachments/assets/af111941-36ed-49f4-b53d-247d0b08e9b2)

</p>
<br />
<p>

</p>
<p>
Once created, refresh the page and head over to your resource group you created earlier. Inside will be your new VM. Select your VM and copy the "Public IP Address"(we will be using this as our main way to remote into the newly created VM). 
  
  ![image](https://github.com/user-attachments/assets/fc1c7745-8319-4b8f-b6f1-ddea61924030)

</p>
<br />
<p>
Next, Head down to your Windows "start" button and type "Remote Desktop". Open the app and paste your created VM's Public IP Address in the search bar.
  
  ![image](https://github.com/user-attachments/assets/3a90dc2b-7f78-4a4d-a5a0-163eddd9a8c3)

</p>
<p>
Now, press connect and sign in using your created username and password from your VM,select okay to the popup box that appears and now you should be loading into your VM you have just created. Once evrything loads in, you should be on the start screen of your VM
  
![image](https://github.com/user-attachments/assets/0eb5228b-3bba-4f05-9ba9-83beb52f7dcb)


</p>
<br />
From here, the ball is in your court and you may do as you please. *IMPORTANT NOTE* once you have finished with your experimenting inside of your VM, Make sure to exit out of your Remote Desktop and head back to "portal.azure.com" and shutdown and remove your VM and your resource group. you dont want to leave these go on in the backround because Microsoft Azure is a "pay-as-you-go" and you dont want to use up all your free credits inc. Have fun and hope this helped you in understanding how to RDP into another Desktop!

![image](https://github.com/user-attachments/assets/b317ea1a-b6ef-4be3-89f9-d190742df8f5)


![image](https://github.com/user-attachments/assets/38a2b49a-282a-481f-adaf-de8c7b3907bd)

