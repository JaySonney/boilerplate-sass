# Sass Boilerplate

This is a sample project using the [7-1 architecture pattern](https://sass-guidelin.es/#architecture) and sticking to [Sass Guidelines](https://sass-guidelin.es) writing conventions.

Each folder of this project has its own `README.md` file to explain the purpose and add extra information. Be sure to browse the repository to see how it works.

## Using the indented syntax

### Sass conversion

This boilerplate does not provide a `.sass` version as it would be painful to maintain both versions without an appropriate build process. However, it is very easy to convert this boilerplate to Sass indented syntax.

Clone it, head into the project and then run:

```
sass-convert -F scss -T sass -i -R ./  && find . -iname “*.scss” -exec bash -c 'mv "$0" “${0%\.scss}.sass"' {} \;
```

### Use with Sass

When using `sass` - in order to build that boilerplate, one needs to:

- install `sass` if not yet installed:

```bash
npm install -g sass
```

- run build command from command line:

```bash
sass stylesheets/main.scss dist/main.css
```
#   b o i l e r p l a t e - s a s s  
 