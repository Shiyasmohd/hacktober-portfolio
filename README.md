# HACKTOBER FIESTA - 22

## Prerequisites
- Sign up to [Hacktoberfest 2022](https://hacktoberfest.digitalocean.com/)
- Have a photo of yours ready in 1:1 ratio. To make it in 1:1 ratio edit the photo and select the crop icon. From there select the square icon, this ensures your photo is in 1:1 ratio.
-  Install [VsCode](https://code.visualstudio.com/download), [NodeJs](https://nodejs.org/en/download/), [Git](https://git-scm.com/downloads) and have an account in [Github](https://github.com/)

<br>

## Note
- Create a new pull request, only after the previous one is accepted

<br>

## Setup

### Step 1 - Fork
As the first step, you have to `fork` this repository to your own github account. 
For that please click on the fork button on the top right corner of your window.  
You will now have the forked repository among your own repositories.    
![Fork](https://github.com/dkowsikpai/card/blob/main/Screenshots/fork.png)
<br>

### Step 2 - Clone 
Clone the repository to your local machine using the git command.
```
git clone <url_to_forked_repository>
```

<br>

### Step 3 - Changing working directory
This will change the working directory to the newly cloned repository. 
```
  cd HACKTOBER-FIESTA22/
```

<br>

### Step 4 - Install Node Modules
Use npm to install flask. 
```
  npm install
```

<br>

### Step 5 - Run the application
The application can be run using the command. The application will be running at `localhost:3000` by default.
```
npm run dev
```



<br>

# HACTOBER FIESTA 2022 PORTFOLIO SETUP

## Initial Setup
-  Sign up to 
-  Have a photo of yours ready in 1:1 ratio. To make it in 1:1 ratio edit the photo and select the crop icon. From there select the square icon, this ensures your photo is in 1:1 ratio.
-  Install [VsCode](https://code.visualstudio.com/download), [NodeJs](https://nodejs.org/en/download/), [Git](https://git-scm.com/downloads) and have an account in [Github](https://github.com/)

## Cloning
- Create a folder wherever you wish.
- Open VsCode and open a new terminal and open the folder you have created .
- Type in the next set of commands. You can copy paste them for your convenience.
- # commands
-  ```git clone https://github.com/Shiyasmohd/hacktober-portfolio```
-  ```cd hacktober-portfolio```
-  ```npm install``` 
-  ```npm run dev```
-  After the above command your portfolio will be loaded in the browser. Type [https://localhost:3000](https://localhost:3000) in your browser.
- 5. Voila!! You can see your portfolio.

# WORKING YOUR PORTFOLIO
- Once you have cloned the repository in VsCode, open the files icon on the left side in VsCode.
- Click the "components" folder and copy paste the file "templete.js". You will see that another file "templete copy.js" has been created alongside the original file.
- Rename "templete copy.js" to your "your name.js".
- Now go ahead and copy paste your photo in the folder public of your already created folder. Also remember to rename your photo with your name. This is for ease of working
- Back to VsCode. Click the folder in your name and select the script EntryComponent.js.
- Now edit the line of code " import ProfileImg from '../../public/put the name of your image here.jpg' ".
- Once this part is done reload [https://localhost:3000](https://localhost:3000) . You'll notice that the photo on the top right side is yours..
- Now select the pages folder and select the SampleEntryComponent and rename the file to your name.
- Edit this line " import SampleEntryComponent from "../components/your name(Name of the file in components folder)/EntryComponent"; "
- And you're all done.
