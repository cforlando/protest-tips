# protest-tips
Info site for protecting your irl and online identity during a protest

## Setup

This site uses `mkdocs` as the static site generator. Use `pip` to install it.

```bash
python3 -m pip install -r requirements.txt
```

## Writing

We use Markdown to create the content and layout of the site. `mkdocs` provides a preview which generates every time a file is saved.

```bash
mkdocs serve
```

## Deploy

`mkdocs` makes it simple to update the live site on GitHub pages.

```bash
mkdocs gh-deploy
```