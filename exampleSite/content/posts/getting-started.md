+++
title = 'Getting Started'
date = '2025-03-24T23:00:00-03:00'
tags = ['starter','guide']
topics = ['documentation']
featured = true
weight = 1
+++

This post will guide you in setting up your very own Hugo site with this theme. It covers the essential parts: [installation](#Installation), [basic usage](#usage) and recommended [next steps](#next-steps). After setting up the basics, feel free to also take a look at other [posts]({{< ref "/posts" >}})!

## Installation

This guide is a shorter version of [Hugo's quick start](https://gohugo.io/getting-started/quick-start/) (you may even say it's a quicker start). If you face any problems or want more comprehensive content, make sure to check it out!

### Requirements

- A basic understanding of Hugo (aka. [read the docs](https://gohugo.io/documentation/))
- [Hugo CLI installed](https://gohugo.io/installation/)
- [git installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Setup Locally

1. Create a new Hugo site

```sh
hugo new site my-blog
```

2. Change the working dir to the newly created one

```sh
cd my-blog
```

3. Install the theme by cloning the GIT repository

```sh
git clone https://github.com/math-queiroz/rusty-typewriter themes/rusty-typewriter
```

4. Create some pages with the desired content

```sh
hugo new content content/posts/first-post.md
```

5. Test your site locally

```sh
hugo server -D
```

6. Congrats! You just got your site up and running locally. Now get to configure and customize it!

### Going Public

Since after build you get just plain static site files (HTML, CSS and JS), there are plenty of pipelines to deploy, places to host and ways to publish your site. If you're interested in the most common ones for Hugo, you can find them listed and documented in [here](https://gohugo.io/hosting-and-deployment/).

## Basic Usage

Now that you have a site, the standard workflow for managing content is simply given by:

1. Create the content page with `hugo new content content/posts/post-name.md`
2. Edit the created file with the intended content
3. Update the repository and publish the alterations

Also, make sure to give the [content management docs](https://gohugo.io/content-management/) a read.

## Next Steps

At last, if you need directions as to where to go next:

- Tweak the `hugo.toml` config file based on [the boilerplate one]({{< ref "/posts/configuration" >}});
- Get ~ricing~ styling your themed site from with CSS;
- Make sure to leave a star at the theme repo and support my work if you enjoy it!

