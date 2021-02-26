# **PROJECT TEMPLATE**
This project uses the following: 
 - SASS (SCSS)
 - Parcel


---------------------------------------------------------------------------------
**NOTE**: This project uses a newer standard of SASS (Dart), so the way that sass is implemented is different. This project uses "@use" and "@forward" instead of "@import".
**NOTE**: YOU WILL NEED TO HAVE NODE.JS INSTALLED. TO CHECK IF YOU HAVE IT, TYPE "node -v" INTO TERMINAL AND IF IT SHOWS YOU A VERSION THEN GREAT. IF NOT, THEN INSTALLED IT FROM THE NODE.JS WEBSITE
---------------------------------------------------------------------------------
<br>

### **STARTING THE PROJECT**

To start this project, open terminal (Ctrl + ') and type "npm install". This will install all the dependencies needed for this project stated in the package.json file. You will have a newly created folder called "node_modules" with all the necessary files

If you look in "package.json", under "Scripts" you'll find "dev" and "build" scripts. They do the following:
 - Dev: Creates a development environment with quick auto-refresh
 - Build: This will be used when creating the final build to deploy the live site.

To start the project open terminal (Ctrl + ') and enter "npm run dev".  You will see something along the lines of: 

```
PS D:\Web Development\NewSass> npm run dev

> NewSass@1.0.0 dev D:\Web Development\NewSass<br>
> parcel src/index.html<br>

Server running at http://localhost:1234 
√  Built in 634ms.
```

Now you will have another newly created folder called "dist". This is where all the files will be saved. However, you still need to edit files within the "src" folder.

<br>

### **Using GITHUB** 
If using GitHub as version control then you will want to use a .gitignore file and write "node_modules" inside, without the quote marks. 

If you download this project to another computer then you will not have the "node_modules" folder included so this is where you start the project with "npm install" to download the "node_modules" folder.
