# CentOS-9-LAMP

Objective: This repository will document the process of creating a CentOS Stream 9 Linux server and how to install and configure LAMP stack. This project is for practice purposes and should NOT be used in production environments. 

Part one: 
- You will need to create an a CentOS-9 server. I used the Akamai Cloud platform to create my free Linode with this link https://www.linode.com/
  - You can follow NetworkChuck on YouTube for deals and specials to get a free $100 code to get started with your linode https://www.youtube.com/@NetworkChuck/search?query=linode
- For your CentOS 9 server, you will want to build the one using the least amount of resources. We are not going to need a lof of space for this demo project and you will more than likely delete the project once you have completed it. This project is inteded for you to learn and practice completing the LAMP set up for furture projects.
- More step by step details can found in this project https://github.com/users/Juanita-Aaron/projects/5
<img width="1178" alt="image" src="https://github.com/user-attachments/assets/f2548d42-efdc-40a3-86e1-5e32a79818fe" />


Part Two: 
- You are ready to SSH into your environment once the set up is complete. You can access your environment using hte terminal on your computer or codespce using the documentation in the following link https://www.linode.com/docs/guides/use-public-key-authentication-with-ssh/
- For this demo, we used the "ROOT" user because we destroyed the resources promptly after createion. This is NOT recommended for long term use, only for the time used to create the project (1 day). Ensure that you are using a password generator to create a secure password at least 40-60 charatcers including numbers, letters and symbols. This will help to keep it secure for the time being.


Part Three: 
- Follow the guide and steps outlined in project Apache to download and configure Apache. https://github.com/users/Juanita-Aaron/projects/6/views/1?pane=issue&itemId=98978800&issue=Juanita-Aaron%7CCentOS-9-LAMP%7C5

- Follow the guide and steps outlined in project Maria DB to dowload and configure MariaDB. https://github.com/users/Juanita-Aaron/projects/6/views/1?pane=issue&itemId=98978820&issue=Juanita-Aaron%7CCentOS-9-LAMP%7C6

- Follow the guide and steps in project PHP to download, configure and test the version of PHP you have chosen. https://github.com/users/Juanita-Aaron/projects/6/views/1?pane=issue&itemId=98978830&issue=Juanita-Aaron%7CCentOS-9-LAMP%7C7

- Each one of those projects has the needed code for your terminal in the order that you need to run the commands. There is also supporting documentation linked in each one. Do not skip any steps. By skipping steps you will begin to get errors and will need to start over inorder to have the propper packages and dependancies. installed in the correct order.


If you are able to see the PHP Version page in your browser, you have compelted the project! Make sure you disconnect from your terminal and destory the resources after. This project is ONLY for practice to master using the terminal to configure your Linux linode with the LAMP stack for future projects. Once you have mastered these skills, you can move onto more complex configurations and Cloud options for hosting web applications. 


