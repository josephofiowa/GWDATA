# Deploying Bootstrap

We'll learn the basics of the [French Embassy Hackathon Series: Ed Hack 2017 site](http://www.frenchedhack.com/). 

## Bootstrap

The above site is _probably_ the closest one could come to making a website with as few of edits to a Bootstrap template as possible. The site is a near clone of Bootstrap's [Landing Page Theme](https://startbootstrap.com/template-overviews/landing-page/).

Credits and thanks to the creators of the template [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat). Thanks to [David Miller](http://davidmiller.io/) of [Blackrock Digital](http://blackrockdigital.io/) for maintaining [Start Bootstrap](http://getbootstrap.com/).

## Updating your live page

To update your live page, you need to tell git to track your files, and push them up to your remote repository. This requires being in the working directory where your site exists on your local machine. In other words, navigate in the terminal to the folder containing all of your site's work.

First, tell Github to track the files you have in your repository.

```bash
git add .
```

Add your commit message for those specific changes.

Then:

```
git commit -m "this is my commit message; you should write your own"
```

Push those changes up to Github!

Then:

```
git push
```

You may be prompted to enter your password. I recommend [setting up SSH keys](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/).




## Useful Getting Started Resources

I'm an educator. I found these resources useful when creating a Bootstrap page using Github Pages. You will too:

- High level Github Pages overview [link](http://jmcglone.com/guides/github-pages/)
- Video walkthrough creating a static site without even using the terminal (but you should learn git in the terminal) [link](http://dougbelshaw.com/blog/2015/01/04/github-pages/)
- Configuring your DNS for your custom domain, Namecheap specific [link](http://abdelraoof.com/blog/2014/09/20/configuring-namecheap-dns-for-github/)
- Troubleshooting custom domains from Github help [link](https://help.github.com/articles/troubleshooting-custom-domains/)
- Getting free stock photos for your site on Pixabay [link](https://pixabay.com/) and 13 others [link](https://www.entrepreneur.com/article/238646)
