# Simplinfo Installation

## Dependencies
As of version 1.42, you do not need ANY dependencies as far as I'm aware.

## Install Command

Run the following command in your terminal to automatically install **simplinfo Linux Edition**
```bash
sudo curl -L "https://raw.githubusercontent.com/justaguy1091-bit/simplinfo/refs/heads/main/simplinfo%20LE" -o /usr/local/bin/simplinfo && sudo chmod +x /usr/local/bin/simplinfo
```

## Manual Install

Manual install for both Simplinfo (BSD) and Simplinfo LE has been moved to the docs folder.

[Click here to view the manual install instructions](https://github.com/justaguy1091-bit/simplinfo/blob/main/docs/installation/manual.md)

# How to set your favorite Anime (Optional)

## Step 1
Create a file to set your own favorite Anime (Blasphemy if not Ganbare Nakamura-kun!!)

sudo [text editor] ~/.bestanime
or
touch ~/.bestanime

## Step 2
Add your favorite Anime either directly into your file
“Your Favorite Anime”

Or if you did “touch”, run this command:
echo “Your Favorite Anime” > ~/.bestanime

## Step 3
Run ./simplinfo again, it should be there.

## Step 4
Congratulations!
