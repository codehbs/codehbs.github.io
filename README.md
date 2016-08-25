# CODE@HBS Official Homepage

This is the official website for CODE@HBS. Check out [a demo](http://codehbs.github.io/codehbs-official-homepage) of the site.

![screenshot](/img/code-website-screenshot.png)

**Your first challenge as a member of CODE**: add your name, photo and social media links to the "member" section of our open-source website. You must be a dues paying member of CODE for us to approve the pull request.

If you're an experienced developer, jump down to the "challenge accepted" section.

If you're relatively new to coding, come by the next CODE meeting and we can walk through this together. Or if you'd like, try doing this on your own first, and we can do a code review together. 

## Challenge Accepted
Glad you're onboard. CODE's open-source website uses a static webpage builder called [Jekyll](https://jekyllrb.com/). To style the website, we used the [{Personal} template theme](https://panossakkos.github.io/personal-jekyll-theme/) designed by PanosSakkos. Let's add your details to the CODE site.

First off, you'll need to have Ruby on your computer. Check your Ruby version (`ruby -v`) in your terminal. If you don't have Ruby, [you'll need to install it](https://www.ruby-lang.org/en/documentation/installation/). 

Once you have Ruby, you'll need to [fork the codehbs-official-homepage repository](https://help.github.com/articles/fork-a-repo/) to your own GitHub page. From your GitHub profile page, [clone the repository](https://help.github.com/articles/cloning-a-repository/) to your desktop. After cloning the repo, you'll need to install the Jekyll gem. In your command line enter the following commands:

`gem install jekyll`

`gem install jekyll-paginate`

`gem install jemoji`

After cd'ing into the codehbs-official-homepage directory, start the Jekyll server:

`jekyll serve`

Look for your local server address. Most likely your Jekyll page will be hosted at localhost:4000. 

## Embrace good git hygene
To make updates, use your favorite text editor. Many CODE members like [Sublime Text](https://www.sublimetext.com/), [Atom](https://education.github.com/pack) and products from [JetBrains](https://www.jetbrains.com/). Always make a feature branch before submitting a pull request. Good feature branches use the following format:

`your-initials/feature-you-are-adding` 

For example: `arc/add-coravos-photo-and-social-links`

We drafted for you a [sample CODE@HBS git workflow](https://github.com/codehbs/git-workflow/blob/master/README.md) for working on team projects like this. 

Submit your pull request, and we'll merge your changes into the master branch in a few days! Challenge complete. #shipit
