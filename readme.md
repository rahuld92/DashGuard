# git-redate
### Made by [Potato Labs](http://taterlabs.com)

Change the dates of several git commits with a single command.

![alt tag](https://raw.githubusercontent.com/almokhtarbr/Complete_blog_CMS_laravel/master2/A-Screenshot/account.png)
![alt tag](https://github.com/almokhtarbr/Complete_blog_CMS_laravel/blob/master2/A-Screenshot/all_posts.png?raw=true)
![alt tag](https://github.com/almokhtarbr/Complete_blog_CMS_laravel/blob/master2/A-Screenshot/categories.png?raw=true)
![alt tag]()
![alt tag]()
![alt tag]()
![alt tag]()

# Installation

For homebrew users, you need to run `brew tap PotatoLabs/homebrew-git-redate` and then `brew install git-redate`.

If you're not using homebrew, you can clone this repo and move the `git-redate` file into any folders in your $PATH. Restart your terminal afterwards and you're good to go!

# Usage

Simply run: `git redate --commits [[number of commits to view]]`.  You'll have to force push in order for your commit history to be rewritten.

To be able to edit all the commits at once add the --all option: `git redate --all`

**Make sure to run this on a clean working directory otherwise it won't work.**

The `--commits` (a.k.a. `-c`) argument is optional, and defaults to 5 if not provided.
