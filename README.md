<p align="center">
<img src="https://i.imgur.com/r2cytOp.png" height="40%" width="60%" alt="Linux"/>
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

1. Open up the `recipe.txt` file using `nano`.
2. On line 3, add your own name after `Author:` so that it says `Author: Stevie Wonder` or whatever your name is.
3. Whoever wrote this recipe didn't know how to spell "parmesan", so instead they wrote "parm". Please update the two instances of "Parm" to "Parmesan". You can do this manually or by using nano's replace feature.
4. Save your changes and close the file!

### Part 2

1. Open up the `website.html` file with `nano`.
2. This HTML file contains a simple website for a fictional restaurant called "Ristorante Colt". You recently purchased the restaurant and have decided to change its name! Please replace all instances of "Ristorante Colt" with your new restaurant's name. Use a nano shortcut rather than manually replacing each one.
3. Write out your changes! Close the file.

### Part 3

1. The `country-data.json` file contains a large country dataset, with over 39,000 lines of JSON!
2. Unfortunately, there is a typo on line **15399**. It says "Honrdras" but it should say "Honduras". Please fix this! Rather than scrolling for a decade, use a nano shortcut to jump to line 15399.
3. **Bonus:** Figure out how to tell `nano` to open the file at exactly line 15399.

### Bonus

1. The `review.txt` file contains a text review of the Cacio E Pepe recipe from `recipe.txt`. Open up the `recipe.txt` file using `nano` and scroll to the bottom. 
2. Using a nano shortcut we have not covered, insert the contents of `review.txt` at the bottom of `recipe.txt`.

<h2>What I Did</h2>

### Part 1

**1. Open up the `recipe.txt` file using `nano`.**
<p>
<img src="https://i.imgur.com/KYIxazS.png" height="100%" width="100%"/>
</p>

I navigated to the `NanoExercise` directory and used `nano recipe.txt` to open the file.

<br />
<br />

**2. On line 3, add your own name after `Author:` so that it says `Author: Stevie Wonder` or whatever your name is.**
<p>
<img src="https://i.imgur.com/gqA33zs.png" height="100%" width="100%"/>
</p>

I moved the cursor to `Author:` and typed my name.

<br />
<br />

**3. Whoever wrote this recipe didn't know how to spell "parmesan", so instead they wrote "parm". Please update the two instances of "Parm" to "Parmesan". You can do this manually or by using nano's replace feature.**
<p>
<img src="https://i.imgur.com/PRc3bp2.png" height="100%" width="100%"/>
</p>

Since the replace feature is used later in this exercise and the word that needs to be replaced only occurs twice in a small file, I chose to manually change each instance of "Parm" to "Parmesan". However, if it would have been more time-consuming to do this, the replace feature would have been better.

<br />
<br />

**4. Save your changes and close the file!**
<p>
<img src="https://i.imgur.com/mmph5Je.png" height="100%" width="100%"/>
</p>

I used `Ctrl+S` to save the file.

<br />
<br />

### Part 2

**1. Open up the `website.html` file with `nano`.**
<p>
<img src="https://i.imgur.com/Dt4BYFP.png" height="100%" width="100%"/>
</p>

I used the `nano website.html` command to open the `website.html` file in nano.

<br />
<br />

**2. This HTML file contains a simple website for a fictional restaurant called "Ristorante Colt". You recently purchased the restaurant and have decided to change its name! Please replace all instances of "Ristorante Colt" with your new restaurant's name. Use a nano shortcut rather than manually replacing each one.**
<p>
<img src="https://i.imgur.com/IOKJD6T.png" height="100%" width="100%"/>
</p>

I used `Ctrl+\` `(^\)` to open the replace feature and typed the words I wanted to replace.

<br />
<br />

<p>
<img src="https://i.imgur.com/BmzuKtO.png" height="100%" width="100%"/>
</p>

I pressed `Enter` and typed the new words to use in place of the words I wanted to replace.

<br />
<br />

<p>
<img src="https://i.imgur.com/7DWJP9y.png" height="100%" width="100%"/>
</p>

After pressing `Enter`, the replace feature selects the first instance of the words I want to replace and asks whether or not I want to replace it or all instances.

<br />
<br />

<p>
<img src="https://i.imgur.com/CgD95we.png" height="100%" width="100%"/>
</p>

I pressed `A`, so all instances were replaced at the same time.

<br />
<br />

**3. Write out your changes! Close the file.**
<p>
<img src="https://i.imgur.com/29O9fPa.png" height="100%" width="100%"/>
</p>

I used `Ctrl+O` and `Enter` to save the file, then `Ctrl+X` to exit the file.

<br />
<br />

### Part 3

**1. The `country-data.json` file contains a large country dataset, with over 39,000 lines of JSON!**
<p>
<img src="https://i.imgur.com/xigqKkZ.png" height="100%" width="100%"/>
</p>

I used the `nano country-data.json` command, and at the bottom, ` [Read 39073 lines] ` verifies that there are over 39,000 lines in the file.

<br />
<br />

**2. Unfortunately, there is a typo on line **15399**. It says "Honrdras" but it should say "Honduras". Please fix this! Rather than scrolling for a decade, use a nano shortcut to jump to line 15399.**
<p>
<img src="https://i.imgur.com/gqTG9Ej.png" height="100%" width="100%"/>
</p>

I used the nano shortcut `^/` (`Ctrl+/`) to go to a specific line, then I typed `15399` and pressed `Enter`. (I also changed the color theme to better see the text)

<br />
<br />

<p>
<img src="https://i.imgur.com/jJBSS4O.png" height="100%" width="100%"/>
</p>

I looked to the right of the cursor and confirmed that `Honrdras` was there.

<br />
<br />

<p>
<img src="https://i.imgur.com/GsGkqE6.png" height="100%" width="100%"/>
</p>

I moved the cursor to the right and manually corrected the word, then saved the file.

<br />
<br />

**3. Bonus: Figure out how to tell `nano` to open the file at exactly line 15399.**
<p>
<img src="https://i.imgur.com/7oAiFw0.png" height="100%" width="100%"/>
</p>

I used the `man nano` command to go to the man page for the `nano` command. In the man page, I found that putting `+` and the line number between `nano` and the file name would open the file with the cursor on the stated line.

<br />
<br />

<p>
<img src="https://i.imgur.com/dbdX92z.png" height="100%" width="100%"/>
</p>

I typed the `nano +15399 country-data.json` command, then pressed `Enter`.

<br />
<br />

<p>
<img src="https://i.imgur.com/qDkjH60.png" height="100%" width="100%"/>
</p>

As expected, the file opened to line 15,399, with the edit I made in Part 3, Step 2 being on the line with the cursor.

<br />
<br />

### Bonus

**1. The `review.txt` file contains a text review of the Cacio E Pepe recipe from `recipe.txt`. Open up the `recipe.txt` file using `nano` and scroll to the bottom.**
<p>
<img src="https://i.imgur.com/oFFwILJ.png" height="100%" width="100%"/>
</p>

I used the `nano recipe.txt` command, then manually scrolled to the last line.

<br />
<br />

**2. Using a nano shortcut we have not covered, insert the contents of `review.txt` at the bottom of `recipe.txt`.**
<p>
<img src="https://i.imgur.com/XX5d8Gt.png" height="100%" width="100%"/>
</p>

I pressed `Ctrl+G` to get to the Help page of nano, then searched for the word "Insert"; I found that `^R` would insert another file into the file I was in.

<br />
<br />

<p>
<img src="https://i.imgur.com/IBDzTR2.png" height="100%" width="100%"/>
</p>

I exited the Help page by pressing `Ctrl+X`, then pressed `Ctrl+R`. `./` means that the available files I can insert will be from the current directory, which is `NanoExercise`. I began typing the name of the file and used `Tab` to autocomplete, then pressed `Enter`.

<br />
<br />

<p>
<img src="https://i.imgur.com/zOkiS5Q.png" height="100%" width="100%"/>
</p>

I confirmed that the text from `review.txt` was present at the bottom of `recipe.txt`, then saved the file.

<br />
<br />

<p>
✨ Lorem ipsum
</p>
<br />
