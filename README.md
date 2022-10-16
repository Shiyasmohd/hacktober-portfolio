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

## Tasks

### PR 1 - feature on home page
Open the file &namelist.html within templates folder, where the names of all the participants seen on the homepage of the website is given.
Copy the relevant section of code as shown below and insert another record with your own details.
```
<a class="participant" href="/<github-username>">
  <div>
    <div class="name"> <your name> </div>
    <div class="college"> <your college> </div>
  </div>
</a>
```

<br>

### Intial Commit 
You can check your change using the following command

```
 git status
```
this command will show you the changes that you have made and left untracked, you have to add these changes to the staging area.

<br> 
Now, you should add it to the staging area using the following command.

```
  git add .
```
`.` specifies to add all the chnges to the staging area.
<br>
Now that the changes are tracked or added to the staging area you should make a commit regarding that particular change using the following command in the terminal. 

```
  git commit -m "<commit message>" 
```
The `commit message` message should specify what is the change made for, it will result in well documentation of the project

<br><br>

### Pushing the commit

Now that you have commited your changes you should push the changes to the remote git repository for that you can use the following command, given below

```
  git push -u origin main
```
This will automatically push your commit to the remote repository, it may ask your password / passphrase for authentication.


<br><br>

### Your Initial Pull Request(PR)
- Push your changes to the github repository.
- Go To Pull requests tab on github
- Click on `New Pull Request` button. 
- Make sure that head repository is your repository
![Pull Request Head](https://github.com/dkowsikpai/card/blob/main/Screenshots/PR%20Head.png)
- Make sure it is showing green tick mark
- Press on `Create Pull Request` Button
![Create PR](https://github.com/dkowsikpai/card/blob/main/Screenshots/Create%20PR.png)
- Add necessary title and description
- Hit `Create Pull Request` Button

<br>

### PR 3 - Customize your Portfolio
- Create a copy of the Template folder inside the component folder and rename it as `<your_github_username>`
- Inside the pages folder, create a copy of the `index.js` file and rename it as `<your_github_username>.js`
- Rename your image as `<your_github_username>` and add to the public folder
- Open ```/components/<your_github_username>/Navbar/Navbar.js```
- Goto line no:50, replace the image with ```src=/<your_image_file_name>```
- Goto `pages/<your_github_username>.js`, replace the Template folder name with `<your_github_username>`
<br/>
  ```
  import SampleEntryComponent from "../components/<your_github_username>/EntryComponent";
  ```
- Goto `component/<your_github_username>/EntryComponent.js`
- Replace image file name with your `<your_image_file_name>` 
<br/>
  ```
  import ProfileImg from '../../public/<your_image_file_name>'
  ```
- Goto line 34, Customize the Hero section 
- Within templates folder create a copy of sample.html and change the name to `<your_github_username>.html` 
 If your username is `abc` then change the new file's name to `abc.html`.
- Going to the url `localhost:5000/<github-username>` will now give you the sample card.
- Make another pull request using the above given steps.

<br>

### PR 4 - Add Projects
- Within templates folder create a copy of sample.html and change the name to `<your_github_username>.html` 
 If your username is `abc` then change the new file's name to `abc.html`.
- Going to the url `localhost:5000/<github-username>` will now give you the sample card.
- Make another pull request using the above given steps.

<br>

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
