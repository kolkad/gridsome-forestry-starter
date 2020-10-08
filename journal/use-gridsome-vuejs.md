---
date: 2020-10-09
title: Creating documents for Naija
author: Nichlas W. Andersen
excerpt: Documents made available are very important.

---
Creating a new site on Netlify is simple. Once you’ve logged in, you’ll be taken to [https://app.netlify.com](https://app.netlify.com "Coming up with something"). If you’re just starting out, there’s only one option, Click the **Add A New Project** button shown above.

## Step 2: Link to Your GitHub (or supported version-control tool of choice)

Clicking “Add A New Project” brings you to this screen:

![step 2 - link with git provider like GitHub or Gitlab](https://cdn.netlify.com/0a36819500c2254f84301d10e6ecbd1e0f20f143/c7374/img/blog/create-new-site.png)

Be sure to push your repo to GitHub, so that all we’ll need to do is link Netlify to GitHub. Click the **GitHub** button as illustrated in the screenshot above.

## Step 3: Authorize Netlify

![step 3 - authorize auth Netlify app](https://cdn.netlify.com/0acaae3eeca45e37481187030ffc0c981ec2172e/e4fb0/img/blog/authorize-github.png)

It’s time to allow Netlify and GitHub to talk to each other. Clicking the **Authorize Application** button will do just that. Like it says in the image below, Netlify doesn’t store your GitHub access token on our servers. If you’d like to know more about the permissions Netlify requests and why we need them, you can visit our [documentation on Git provider permissions](https://docs.netlify.com/configure-builds/repo-permissions-linking/).

## Step 4: Select Your Repo

![step 4 - selecting project repo to connect to Netlify](https://cdn.netlify.com/b429c96d703c49639ef0d78a789af4a656bb06dc/97b2e/img/blog/choose-repo.png)

Now that you’ve connected Netlify and GitHub, you can see a list of your Git repos. Choose the repo you’d like to deploy from the list.

## Step 5: Configure Your Settings

![step 5 - configure site settings in Netlify app](https://cdn.netlify.com/47f0bbb70a0dcafb0340f296296df43d21d68366/dd351/img/blog/config-your-repo.png)

Here you can configure your options. Make sure your publish directory is where your public site files are placed after building the site (e.g. `dist`) and your build command is whatever you run to build the site (e.g. `npm run build`). Then click the **Deploy site** button to continue.

## Step 6: Build Your Site

![step 6 - building your site in Netlify](https://cdn.netlify.com/6830c2e391603fdb9c058bf35e7856f246023c16/2cb44/img/blog/building-site.png)

Now it’s time to sit back and relax. You did your part; let Netlify take care of the rest. It’ll only take a minute.

## Step 7: All Done

Once the build completes, your site is live! Head to the overview and you can see the URL of your newly published site.

![step 7 - Netlify app site deploys overview](https://cdn.netlify.com/3b0f4ebe3a738e26695408e2ad541cf45d3d2a0a/75a0f/img/blog/done-1.png)

Netlify automatically generated a name for your site. Let’s update that by visiting the settings tab and clicking “Change site name”:

![step 8 - updating site name and url in Netlify app](https://cdn.netlify.com/eb124a66134af5ebe3cd37ce794e03a12368151a/22db2/img/blog/done-2.png)

There, that’s better. Looks pretty good, huh? Wasn’t that easy? To take it a step further, [set up your custom domain](https://www.netlify.com/blog/2016/03/14/setting-up-your-custom-domain/).

Congratulations on your new site, and thanks for using Netlify!

[deploy](https://www.netlify.com/tags/deploy) [tutorial](https://www.netlify.com/tags/tutorial)

[![Eli Williamson](https://cdn.netlify.com/85ff2f213dce17352fc0bb4e1baa78801bb8ddce/4fed9/img/blog/authors/thumbnails/eli-williamson.jpg =40x40) ](https://www.netlify.com/authors/eli-williamson)[![Jason Lengstorf](https://cdn.netlify.com/17e068f7793790060945713f91c14284aecbce86/5024e/img/blog/authors/thumbnails/jason-lengstorf.jpg =40x40) ](https://www.netlify.com/authors/jason-lengstorf)Written by [Eli Williamson](https://www.netlify.com/authors/eli-williamson) & [Jason Lengstorf](https://www.netlify.com/authors/jason-lengstorf) Published in [Guides & Tutorials](https://www.netlify.com/topics/tutorials) on September 29, 2016

Let’s have a conversation! Visit the Netlify Community for discussion about this blog post.

[Visit the Community](https://community.netlify.com/c/connect/)

## Subscribe to the newsletter

Exploring the Jamstack, static sites, and the future of web development. Subscribe to our newsletter to make sure you don't miss anything.

Email address