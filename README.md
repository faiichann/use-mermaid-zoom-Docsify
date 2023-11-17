# Get starting Docsify 
install the docsify-cli globally.
```bash
pnpm add -g docsify-cli
```
Create your new project with the docsify-cli init option.
```bash
docsify init docs
```
You can also specify the --theme and --plugins
```bash
docsify init docs --theme buble --plugins
```
Then run the local developer server with the following command.
```bash
docsify serve docs
# or
docsify serve .
```