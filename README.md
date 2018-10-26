# hacktoberfest-oluaka
A curated list of Hacktoberfest Oluaka 2018 developers.

## Note:
*Information added to this repo shall be used for public display.*

## How to add a dev
Let start

#### First things first
Check out these articles on how to make your first PR
1. [GitHub](https://help.github.com/articles/creating-a-pull-request/)
2. [Medium](https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940)


#### Next
This is how you can add your profile

* `fork` this `repo` 
* `clone` it to you local machine `git clone "url you just copied"`

#### Create a branch
Change to the repository directory on your computer (if you are not already there):

```
cd hacktoberfest-oluaka
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name>
```

For example:
```
git checkout -b add-iroleh-vincent
```
(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

* open the [data](/data/devs.json) file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it at the bottom. Now, save the file.

* Add yours in the format below

```
  {
    "name": "Vincent Iroleh",
    "github": "vincentiroleh",
    "resident": "Nigeria",
    "country": "Nigeria",
    "gender": "Male",
    "stack": "JavaScript, python, html, css",
    "twitter": "irolehvincent",
    "url": "vincentiroleh.github.io",
    "profession": "Coding Entrepreneur"
  },
```

**Name**: Name of the Developer,<br/>
**GitHub**: GitHub profile name<br/>
**URL**: Your Web address if Any<br/>
**Profession**: What is the title of your Profession.<br/>
**Stack**: The dev stack you are most comfortable with.<br/>
**Twitter**: Your twitter Name.<br/>
**Gender**: This really have no importance, but feel free to add your<br/>
**Resident**: Your Country of residence<br/>
**Country**: Your Country of Origin


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add data/devs.json
```

Now commit those changes using the `git commit` command:
```
git commit -m "Add <your-name> to Developers list"
```
replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.


* Now Send a `pull request` 🎉


Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.




## Contributing

Thank you for taking the time to contribute! 👍🎉

Follow the steps above and you are done.


## Authors

* **Vincent Iroleh** - *Initial work* - [Iroleh](https://github.com/vincentiroleh)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

