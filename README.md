# pint-lang README
Syntax highlighting for the Pint programming language.
## Screenshots
![image](https://github.com/essential-contributions/pint-syntax/assets/7286454/bd289c24-f4fa-4798-a61c-1cbf1b9ace3b)
![image](https://github.com/essential-contributions/pint-syntax/assets/7286454/1e6bedc3-d858-4bdf-8ee3-618531f097e1)
## Update
Edit the `pint.tmLanguage.yaml` file and run:
```bash
npx js-yaml syntaxes/pint.tmLanguage.yaml > syntaxes/pint.tmLanguage.json 
npx vsce package
```