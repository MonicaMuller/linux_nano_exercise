<p align="center">
<img src="https://i.imgur.com/TES6KV4.png" height="40%" width="60%" alt="Linux"/>
</p>
<h1>Linux Exercise: Nano</h1>

In this exercise, I...

Credit to Colt Steele’s Udemy course, **The Linux Command Line Bootcamp: Beginner to Power User**, for providing both the exercise and the knowledge needed to complete it.
<br />

<h2>The Commands</h2>

- A
  - B

## The Exercise

### Part 1

1. Open up the `recipe.txt` file using `nano`
2. On line 3, add your own name after `Author:` so that it says `Author: Stevie Wonder` or whatever your name is
3. Whoever wrote this recipe didn't know how to spell "parmesan", so instead they wrote "parm". Please update the two instances of "Parm" to "Parmesan". You can do this manually or by using nano's replace feature.
4. Write out your changes! Close the file.

### Part 2

1. Open up the `website.html` file with `nano`
2. This HTML file contains a simple website for a fictional restaurant called "Ristorante Colt". You recently purchased the restaurant and have decided to change its name! Please replace all instances of "Ristorante Colt" with your new restaurant's name. Do this using a nano shortcut, rather than manually replacing each one.
3. Save your changes and close the file!

### Part 3

1. The `country-data.json` file contains a large country dataset, with over 39,000 lines of JSON!
2. Unfortunately, there is a typo on line **15399**. It says "Honrdras" but it should say "Honduras". Please fix this! Rather than scrolling for a decade, use a nano shortcut to jump to line **15399**.
3. **Bonus:** Figure out how to tell `nano` to open the file at exactly **15399**.

### Bonus

1. The `review.txt` file contains a text review of the Cacio E Pepe recipe from `recipe.txt`. Open up the `recipe.txt` file using `nano` and scroll to the bottom. 
2. Using a nano shortcut we have not covered, insert the contents of `review.txt` at the bottom of `recipe.txt`.

<h2>What I Did</h2>

**1. Create a new folder called `my-app`**
<p>
<img src="https://i.imgur.com/OmTD8rX.png" height="100%" width="100%"/>
</p>

To get started, I used `mkdir my-app` to create a new directory called `my-app`.

<br />
<br />

**2. Navigate to `my-app`, and inside, create two new empty files called `README.md` and `package.json`**
<p>
<img src="https://i.imgur.com/5lA4q9x.png" height="100%" width="100%"/>
</p>

After navigating into `my-app`, I used the `touch` command to create two files: `README.md` and `package.json`.

<br />
<br />

**3. Still inside `my-app`, create a new folder called `public`. Without `cd`-ing into `public`, create an `index.html` file inside it.**
<p>
<img src="https://i.imgur.com/G5kBofb.png" height="100%" width="100%"/>
</p>

Next, I created a new directory called `public`, then used `touch public/index.html` to create the `index.html` file inside it without navigating into the `public` directory.

<br />
<br />

**4. Create a new folder called `src` inside `my-app`.  Navigate into it.**
<p>
<img src="https://i.imgur.com/D5u05rh.png" height="100%" width="100%"/>
</p>

I created a new directory called `src` inside `my-app`, then navigated into it using `cd src/`.

<br />
<br />

**5. Using a single line, create the following four files inside `src`: `App.css`, `App.js`, `index.css`, and `index.js`**
<p>
<img src="https://i.imgur.com/ZUIwwzy.png" height="100%" width="100%"/>
</p>

While inside `src`, I used a single `touch` command to create four files at once: `App.css`, `App.js`, `index.css`, and `index.js`.

<br />
<br />

**Folder Structure Confirmation**
<p>
<img src="https://i.imgur.com/XDabC2M.png" height="100%" width="100%"/>
</p>

I then used `ls` to confirm that the files and directories I created matched the expected folder structure, including `ls` with relative paths to check the contents of the `public` and `src` subdirectories from the parent `my-app` directory.

<br />
<br />

**BONUS: Using a single command, create a new directory inside `src` called `components`, and inside that new `components` directory, create a new directory called `Navbar`. Do this using a single command, without first creating the `components` directory.**
<p>
<img src="https://i.imgur.com/LAuDNTn.png" height="100%" width="100%"/>
</p>

For the bonus, I used `mkdir -p src/components/Navbar` to create both the `components` directory and its nested `Navbar` directory with a single command. I then used `ls` along with relative paths from the `my-app` directory to confirm that the new nested folder structure was correct.

(Edit to add: Apparently, "ls -R" would have listed the folder structure with one command. At least now I know 😅)

<br />
<br />

<p>
✨ I’m really enjoying learning more Linux commands and seeing how they build on each other! Now I’m getting more comfortable not only moving around the Linux file system from the terminal, but also creating files and directories in it.
</p>
<br />
