# Resume

My resume is written in **LaTeX** and automatically built and deployed using **GitHub Actions** and **GitHub Pages**.

Every time I push changes to this repository:

1. The LaTeX source is compiled into a PDF.
2. The latest resume is deployed via GitHub Pages.
3. My portfolio redirects **https://vatsal.live/resume** to the newest version automatically.

This ensures that every shared resume link always points to the latest version.

## Tech Stack

* LaTeX
* GitHub Actions
* GitHub Pages

## Local Development

Compile the resume locally:

```bash
make
```

Clean generated files:

```bash
make clean
```

or

```bash
make distclean
```

## Resume

📄 Latest Resume

**https://vatsal.live/resume**

## Acknowledgements

This repository is based on the excellent **autoCV** template by Jitin Nair, with modifications for my own resume structure and automated deployment workflow.

Original project:
https://github.com/jitinnair1/autoCV
