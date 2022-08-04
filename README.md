# Fail to build 

```shell
yarn run v1.22.19
$ vue-tsc --noEmit && vite build
src/App.vue:2:23 - error TS2614: Module '"./components/ArticleTest.md"' has no exported member 'frontmatter'. Did you mean to use 'import frontmatter from "./components/ArticleTest.md"' instead?

2 import ArticleTest, { frontmatter } from './components/ArticleTest.md'
                        ~~~~~~~~~~~


Found 1 error in src/App.vue:2

error Command failed with exit code 2.
```
