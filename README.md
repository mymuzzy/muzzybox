# muzzybox

Hey, I am muzzy !!!

I have created this amazing CTF for pentester. However, This is not like other CTF which has been using common exploits and tools. Instead, you will learn about Real-world website testing methodology, advance injections and more.

Google Drive URL : https://drive.google.com/file/d/1yFKVD_bDvzMp66ewOmyihXZ-_RZ8yGOs/view?usp=sharing


### Direction To Use
Import into VirtualBox or VirtualMachine and start playing.

# Configuration

### $ 1. Download the zip file from the Google Drive URL.

![1](https://user-images.githubusercontent.com/61471222/75571333-f6ba3900-5a7e-11ea-9209-295b96ab4416.png)

-> Now, extract the zip file as shown below.
![1](https://user-images.githubusercontent.com/61471222/75571703-b7d8b300-5a7f-11ea-8793-21fae880b7e9.png)


### $ 2. Now you can import in .ova file in VirtualBox.(You can also use VMWare)
-> Open VirtualBox, go to "File" option and click on "Import Appliance..."
![1](https://user-images.githubusercontent.com/61471222/75571882-169e2c80-5a80-11ea-92a0-02afdbd1b989.png)

-> Now Select the full path of .ova file as shown below.
![1](https://user-images.githubusercontent.com/61471222/75572029-64b33000-5a80-11ea-96a4-e65d79bcca38.png)

-> Now leave all setting as it is and click on "Import Button"
![1](https://user-images.githubusercontent.com/61471222/75572225-ac39bc00-5a80-11ea-8d61-d90178325a3f.png)

-> After successfully import we can ready to start our machine.
-> Click on Start button
![1](https://user-images.githubusercontent.com/61471222/75572711-4bf74a00-5a81-11ea-8cf4-14ab97d4e4ec.png)

-> Set "Network Setting as "Bridged Adapter" (In case of any network issues)
![1](https://user-images.githubusercontent.com/61471222/75572874-a85a6980-5a81-11ea-8092-aa51dbcdc2e7.png)

-> Now we can Able to see the login panel

![1](https://user-images.githubusercontent.com/61471222/75573080-17d05900-5a82-11ea-96cb-b2d71ff1ca5a.png)


### $ 3. Open your attacker machine with same network setting as "muzzybox" machine has. 
-> (Network Setting as "Bridged Adapter")
-> Now enter a command "ifconfig" for observe your machine's IP.
![1](https://user-images.githubusercontent.com/61471222/75573505-fcb21900-5a82-11ea-82bd-fec494ee31a1.png)

-> Now enter a command "netdiscover -r 192.168.0.0/16" as a root user for scan the entire network
![1](https://user-images.githubusercontent.com/61471222/75573921-d9d43480-5a83-11ea-974b-a11f8713b140.png)

-> Then we can able to get the "MuzzyBox" machine's IP.
![1](https://user-images.githubusercontent.com/61471222/75574121-143dd180-5a84-11ea-8031-3de691a4d635.png)

-> and IP is "192.168.0.122"
-> Open your browser and visit the page
![1](https://user-images.githubusercontent.com/61471222/75574499-6da60080-5a84-11ea-89f8-4836cc983801.png)

-> Now, Open text file and you will get all information about the challenges.
![1](https://user-images.githubusercontent.com/61471222/75574915-2a985d00-5a85-11ea-9297-de0f8dc03d12.png)



# Feedback and Queries

If you want to share about issues and problem, feel free to share with me on LinkedIn
"https://www.linkedin.com/in/hussenimuzkkir/" 

Thanks For Reading.

