This project only compiles `index.ts` but if you look at `build-out` the
output also compiled `http.js`. Why?

It seems like `@types/node` has a pointer to `http` module which is than 
incorrectly assumed to be `http.ts` file.