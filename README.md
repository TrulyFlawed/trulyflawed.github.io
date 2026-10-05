# duskfall.dev

My personal website built with Jekyll. Developed with the goal of minimal JavaScript use, modern HTML & CSS, and few dependencies.

Live site: https://duskfall.dev/

## Setup

1. Install Ruby (see [Jekyll’s install docs](https://jekyllrb.com/docs/installation/)).
2. From the repo root:
   ```bash
   bundle install
   ```

## Local development

Serve with live reload:

```bash
bundle exec jekyll serve --livereload
```

Then open http://127.0.0.1:4000.

To preview from another device on your network:

```bash
bundle exec jekyll serve --host 0.0.0.0 --livereload
```

Visit `http://<your-local-ip>:4000`.

## Deployment

Edit the source, commit, and push to `main`. GitHub Pages builds and publishes automatically. After deploy, check https://duskfall.dev/.

## License

Source code is licensed under MIT, original content is licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/), and third-party material remains under its own terms.