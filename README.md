This project has been created with `npm create vite@latest`.

When running this project with `npm run dev`, everything works **fine**.

However, when compiling this project with `npm run build`, the following error appears:

```
src/App.vue:10:22 - error TS7006: Parameter 'n' implicitly has an 'any' type.

10  <Child @changeName="n => name = n" />
                        ~


Found 1 error in src/App.vue:10
```
