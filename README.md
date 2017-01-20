# primo-explore-resource-icons

## installation

### setting up the dev environment

if you don't have a `package.json` as part of your view code, go to your package directory (e.g. `/primo-explore/custom/LCC_NEWUI`) and run:

```sh
npm init
```

follow the prompts and fill out basic information for your package.

### installing the icons

from inside your package directory (e.g. `/primo-explore/custom/LCC_NEWUI`), run:

```sh
npm install primo-explore-resource-icons
```

the icons used are from [The Noun Project](https://thenounproject.com/) under a Creative Commons Attribution (CC BY) license, so you need to credit them in a credits page on your site.

one way to do this is by adding the below code to your `home_en_US.html`:

```html
<a href="https://github.com/Alliance-PCJWG/primo-explore-resource-icons/blob/master/html/iconcredits.md" title="Icon Credits" target="_blank">Icon Credits</a>
```

You can learn more [here](https://thenounproject.zendesk.com/hc/en-us/sections/200137528-Icon-Credit-Requirements).

### uninstalling the icons

from inside your package directory (e.g. `/primo-explore/custom/LCC_NEWUI`), run:

```sh
npm uninstall primo-explore-resource-icons
```
