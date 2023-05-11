<h1 align="center">
  <img src='https://user-images.githubusercontent.com/77310871/236178717-7ce72cfb-085a-4609-863b-cfceb3d6c9f2.png'>
  <br><br>
  AwesomeCV-Typst Submodule
</h1>

## What is this for?

**AwesomeCV-Typst** is a [**Typst**](https://github.com/typst/typst) template for making **Résume**, **CV** or **Cover Letter** inspired by the famous LaTeX CV template [**Awesome-CV**](https://github.com/posquit0/Awesome-CV). It provides customizations and **multilingual support** beyond the original LaTeX project.

See the [Example repository](https://github.com/mintyfrankie/awesomeCV-Typst) for a complete demonstration.

## Usage

You can either clone the example repository and modify it locally to have a hands-on experience, or you might want to add this submodule repository and build up your own Typst project.

### Method 1: Clone the [example repository](https://github.com/mintyfrankie/awesomeCV-Typst)

```bash
git clone https://github.com/mintyfrankie/awesomeCV-Typst
cd awesomeCV-Typst
typst --font-path ./src/fonts compile cv.typ
``` 

### Method 2: Add the submodule repository to your git project

```bash
cd your/CV/project
git submodule add https://github.com/mintyfrankie/awesomeCV-Typst-Submodule awesomeCV
typst compile cv.typ
```

When the template file is updated:

```bash
git submodule update --remote
```

## Credit

- [**Typst**](https://github.com/typst/typst) is a newborn, open source and simple typesetting engine that offers a better scripting experience than [**LaTeX**](https://www.latex-project.org/).
- [**Awesome-CV**](https://github.com/posquit0/Awesome-CV) is the original LaTeX CV template from which this project is heavily inspired. Thanks [posquit0](https://github.com/posquit0) for your excellent work!