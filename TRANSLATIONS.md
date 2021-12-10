# Translation Guideline

### We strongly promote diversity and inclusion and so, we welcome documentation localization in any language by contributors from any background.

## Translation Prerequisites

Before going for translating a topic, always make sure —

- The intended topic hasn't already been translated to the target language by anyone else
- You have filed an isssue on the repository for the translation request and it has been approved
- You are well aware of the Git and GitHub basics including but not limited to forking, branching, issue filing, PR submitting etc.

> 📝 Files with wrong encodings can cause massive trouble. Save the translations files with the correct **UTF-8** encoding.

## Getting Started

### Under each doc module, look for the "translations" folder which would contain the translated versions.

Use the following naming convention for translated files-

> `filename.[language].md`

Here, `[language]` is a two letter language abbreviation following the **ISO 639-1** standard (e.g. _README.bn.md_ for Bengali language).

> 📝 Don't forget to update the relative paths of the images in order to display them properly.

## Exclusions

Do not translate the following directories.

```
assets/
.git/
```
