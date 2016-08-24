# CODE@HBS Official Homepage

This is the official website for CODE@HBS. 

**Your first challenge as a member of CODE**: add your name, photo and social media links to the "member" section of our open-source website. You must be a dues paying member of CODE for us to approve the pull request.

If you're an experienced developer, jump down to the "challenge accepted" section for details.

If you're relatively new to coding, come by the next CODE meeting and we can walk through this together. Or if you'd like, try doing this on your own first and we can do a code review together. 

## Challenge Accepted
Glad you're onboard. Let's add your details to our open-source website. 

First off, you'll need to have Ruby on your computer. To see your version, check the following in your terminal:
`ruby -v`. If you don't have Ruby, [you can install it on your computer](https://www.ruby-lang.org/en/documentation/installation/). CODE's open-source website uses a static webpage builder called [Jekyll](https://jekyllrb.com/). To style the websute, we used the [{Personal} template theme](https://panossakkos.github.io/personal-jekyll-theme/) designed by PanosSakkos.   

Once you have Ruby, you'll need to [fork this repository](https://help.github.com/articles/fork-a-repo/) to your own GitHub page. Then [clone the repository](https://help.github.com/articles/cloning-a-repository/) to your desktop. After cloning the repo, you'll need to install the Jekyll gem. In your command line enter the following commands

`gem install jekyll`

`gem install jekyll-paginate`

`gem install jemoji`

After cd'ing into the codehbs-official-homepage directory, start the Jekyll server:

`jekyll serve`

Look for your local server address. Most likely your Jekyll page will be hosted at localhost:4000. 

## Embrace good git hygene
To make updates, use your favorite text editor. Many CODE members like [Sublime Text](https://www.sublimetext.com/), [Atom](https://education.github.com/pack) and products from [JetBrains](https://www.jetbrains.com/). Always make a feature branch before submitting a pull request. Good feature branches are use the following format:

`your-initials/feature-you-are-adding` 

For example: `arc/add-coravos-photo-and-social-links`

Check out this repository for a [sample CODE@HBS git workflow](https://github.com/codehbs/git-workflow/blob/master/README.md) for working on team projects like this. 

Submit your pull request, and we'll merge your changes into the master branch in a few days! Challenge complete.
