# Environment Setup for DBMS using XAMPP

The easiest way to learn building DBMS is making a simple webapp using PHP and MySQL which is very easy and straight forward to use.

Firstly, to build a Database management Application in our local computer, we need to create the environment using XAMPP.
XAMPP stands for **X-operating system, Apache, Mysql, Php, Perl**
We are going to need **Apache** and **MySQL** to create a web application.

#### Let's go Step by Step,

## 1. Download XAMPP 

It is a development platform by [Apache Friends.](https://www.apachefriends.org/) 
Let's download XAMPP from [https://www.apachefriends.org/](https://www.apachefriends.org/)
</br>

<img src="https://user-images.githubusercontent.com/19222272/216757300-278e3604-9ec2-48ad-ad0d-897c42dd8908.png"  alt= “” width="500px"  height="">
</br>

For my windows machine, I'm going to download the **XAMPP for Windows** 

</br>

<img src="https://user-images.githubusercontent.com/19222272/216757484-7cbaa71d-3e87-4ef9-ac71-702811d5efbb.png"  alt= “” width="500px"  height="">




## 2. Install XAMPP on Operating System
As I've downloaded for windows, I'm going with the procedure for windows machine.
### i. Launch the Installer
Firstly, I'm going to launch the installer. 
</br>
![image](https://user-images.githubusercontent.com/19222272/216757707-e01569a6-91b9-4509-8654-a5f72fceaaab.png)


### ii. Launch the Installer
If the installer shows this error, just click **OK**. This is because in windows, an application installed from one user sometimes doesn't get all the permissions to operate perfectly on the system. 
</br>
![image](https://user-images.githubusercontent.com/19222272/216757918-615c916d-f979-43ab-a9a9-0de79633d863.png)

### iii. Select Components to Install
After clicking OK on previous screen, it will sequentially switch to this screen below. All the components should be selected by default. But if you want, you can unselect the ones you don't need.
</br>
![image](https://user-images.githubusercontent.com/19222272/216758190-3f67515f-2252-4b03-964d-a47f828fda9f.png)

### iv. Choose the installation folder
After selecting components, clicking **NEXT >**, the installer will ask you to select a folder to install XAMPP in.   
</br>
![image](https://user-images.githubusercontent.com/19222272/216758603-d4f010db-bfaf-4bf4-8136-f87f736e632b.png)

### v. Select Control Panel Language

![image](https://user-images.githubusercontent.com/19222272/216758700-c1d27199-64d2-4bc2-9356-3f448fb956f4.png)

### vi. Continue to Installation
After getting all the information's, the installer will ask you to proceed to final installation stage. After clicking **OK**, the installer will start to unpack itself at setup the components to the computer. 
</br>
![image](https://user-images.githubusercontent.com/19222272/216758754-59e19c3a-0d59-4055-8be0-9d915aff7857.png)


### vii. Allow on Firewall

Both Apache and MySQL will ask for Firewall permissions. As it is working as a server on our computer, this **Apache and MySQL** server will be accessible from all clients on our local network. So we will be able to access out web application from all our computers and devices on our home or local network. 
This is why It is asking for permission through windows firewall .
</br>
![image](https://user-images.githubusercontent.com/19222272/216759019-ad9c1762-77b6-4fe5-a8b2-df95a61f93fa.png)

### viii. Finish Installation
We are going to finish the installation and start the control panel now.
</br>
![image](https://user-images.githubusercontent.com/19222272/216759173-e514d089-2053-4264-aa39-c7bd6abb7ac7.png)



## 3. XAMPP Control Panel
Here is the XAMPP Control Panel. 
</br>
![image](https://user-images.githubusercontent.com/19222272/216759230-9349b4d7-0bc9-4678-b42f-d209d5c5f6af.png)

### Start the Modules
To check out development environment, we are going to **Start** the **Apache** and the **MySQL** modules.
</br>
![image](https://user-images.githubusercontent.com/19222272/216759315-c020fc3e-5dc5-4f30-a79d-5ba0476ddcec.png)

### ii. Allow MySQL module on firewall.
The **mysqld.exe** process is the MySQL module. It might ask for firewall access on running for the first time. I'll allow the **mysqld.exe** on my firewall for development purpose.
</br>
![image](https://user-images.githubusercontent.com/19222272/216759385-ee476fa1-4106-4227-8ca5-c573090b46a1.png)


### iii. Check "localhost" on browser
After launching all the modules required, now type **localhost** on browser and press enter. If the XAMPP works correctly, It will show the page below.
</br>
![image](https://user-images.githubusercontent.com/19222272/216759484-56b85b2a-5e07-4b98-99d5-91e9a54b3fd5.png)

Done. the installation is done. 
