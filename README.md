<h1 align="center">
  <img src='https://github.com/mintyfrankie/mintyfrankie/assets/77310871/64861d2d-971c-47cd-a5e8-5ad8659f2c2b'>
  <br><br>
  Brilliant CV Submodule
</h1>

fork from [brilliant-cv-submodule](https://github.com/mintyfrankie/brilliant-CV-submodule)

Add support for multi-version and language
Should be fully compatible with the original version, but minor changes in `metadata.typ` may be needed.

## guide for multi-version and language
### Compatibility
`varVersion` is used to specify the version of the CV, i.e., `modules_cn` or `modules_SinglePage` in my usage;
`varLanguage` is used to specify the language of certain entry.

Basic usage is the same as the original version, but you **need** to rename one of the variables in `metadata.typ` as follows:

```tex
varLanguage -> varVersion
```
Then your CV should be fully compatible with the original version.

### In-file language Switch

You can use `languageSwitch` to switch the language of certain entry in the same file.

```tex
title: languageSwitch((
      "en":[Master of Science, Electronics],
      "zh":[理学硕士, 电子学]
    )),
```
Notice the number of `(` and `)`.

it doesn't make sense to use key of `""` in the languageSwitch, But it should be compatible if you do so.


Please refer to the [example repository](https://github.com/HernandoR/lz-brilliant-cv) for more information.



Any issue or PR is welcomed!
