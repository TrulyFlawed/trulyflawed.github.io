# My personal site

This is my personal, statically-generated site using Jekyll. At the moment, it does not have much going for it.

## Build & deployment

Because I'm using GitHub Pages, building and deploying the site is actually pretty straightforward.

### Building

As it uses Jekyll, you can build and run a local copy of the site that automatically refreshes using the following command:

```
bundle exec jekyll serve --livereload
```

If you want to access a preview from a different device (like a phone), you will have to run the following command:

```
bundle exec jekyll serve --host 0.0.0.0
```

Then, you can visit your site via `http://<your-local-ip>:4000`.

At the moment, I am unaware if you need to install Ruby and Jekyll yourself, or if having the Gemfiles and whatnot in the repository allows you to run the command as is. Either way, I'd just assume you have to download it, so follow the steps as outlined in [Jekyll's official documentation](https://jekyllrb.com/docs/installation/).

### Deployment

Deployment is very straightforward, just edit the source files and push it to GitHub. GitHub Pages will automatically build and deploy it for you.