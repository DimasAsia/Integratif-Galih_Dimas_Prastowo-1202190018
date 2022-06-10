Galih Dimas Prastowo

1202190018

IT 02-01

# **Laravel on windows**

## **Required Requirements**
- Installed XAMPP for windows
- Installed Composer for windows

## How To Install 
- Enter Command Prompt is the first step to install laravel. The trick is to click Win+R then type cmd and click OK

  ![cmd](https://user-images.githubusercontent.com/92965284/173079844-13f39aac-7279-4169-a250-6d2e069a9ad8.png)
  
- Navigate Command Prompt or terminal to the file server directory. The file server location on XAMPP by default is in the xampp/htdocs directory. Enter this command in the Command Prompt window to enter the htdocs directory

  ```bash
  cd \xampp\htdocs
  ```
  
  ![navigate](https://user-images.githubusercontent.com/92965284/173082118-ebb67000-51cd-495a-a45b-3e1f4b5340c3.png)

- if you have entered the htdocs directory, you must make a project request to retrieve (and install) the Laravel files that have been provided in the Github repository to the specified directory. Use this command to make a request:
  
  ```bash
  composer create-project --prefer-dist laravel/laravel ga_dimas
  ```
  
  from the command above the project created with the name **ga_dimas**
  
  If the command has been successfully entered, Composer will begin the process of fetching data and installing Laravel into the directory you specified
  
  ![project](https://user-images.githubusercontent.com/92965284/173085185-8888aa0a-d9c7-4cc1-93b9-10162c0522d9.png)
  
- After the Laravel file download process is complete, there will be a new folder in the file server directory with a name according to the project name that you previously specified in the /xampp/htdocs folder
  
  ![directory](https://user-images.githubusercontent.com/92965284/173085674-81eb8a13-b506-4282-9508-75b93286a810.png)

- To ensure that Laravel is successfully installed and ready to use, navigate to Command Prompt or Terminal to the directory you created earlier. Then, enter the following command into Command Prompt or Terminal:
  
  ```bash
  php artisan serve
  ```
  
  ![phpartisan](https://user-images.githubusercontent.com/92965284/173086327-161b7700-1c87-4f5b-ad87-07845676b697.png)
  
- If it says Laravel development server started in the Command Prompt or Terminal, the next step is to open the link provided by Laravel. By default, you will be directed to the server address, which is 127.0.0.1:8000. Later, a homepage will appear with Laravel writing in the middle as shown in the image below:

  ![result](https://user-images.githubusercontent.com/92965284/173086760-938890a8-35a8-4d5b-b7bd-fae7b706bf2f.png)

  If the homepage is visible, then the Laravel installation on Windows is successful
