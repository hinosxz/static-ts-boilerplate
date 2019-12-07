# static-ts-boilerplate
TypeScript boilerplate for a static website

# Prerequisites
You need a package manager like `npm` or `yarn` and that's all!

## Set up
```
git clone https://github.com/hinosxz/static-ts-boilerplate.git
cd static-ts-boilerplate
npm install
```

## Use
You can edit the `index.html` file for the content, the typescript files in the `src` directory and the styles in
 the `styles` directory. Once you're done, you can run `yarn tsc` and javascript will be built in a `scripts` directory 
 that'll be called by the html file.
 
 There's also a light server setup using concurrency that detects changes to your source code and refreshes your page 
 automatically. To use this feature, simply run:
 ```
npm start
```

## Lint
This boilerplate is configured to use eslint with typescript-eslint and prettier rules. You can configure your IDE for 
eslint to see errors and warnings and being able to automatically fix code on save.

To run eslint manually:
```
npm run lint
```


