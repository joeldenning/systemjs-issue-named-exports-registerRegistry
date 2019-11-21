# systemjs-issue-named-exports-registerRegistry

1. Start up a web server
```sh
npx serve .
```
2. Open browser to url printed in terminal
3. Open browser console. Notice how the first and second import do not result in the same thing. The named-exports extra doesn't apply to the second import.