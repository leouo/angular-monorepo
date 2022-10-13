# Angular Monorepo

Just a monorepo with an lib app and one consumer spa app

## 1 - First build `components-lib`
```
npm run build components-lib
```

## 2 - Link `components-lib` dist files
```
# go to dist files
cd dist/components-lib

# link dist files as an package
npm link
```

## 3 - Link `components-lib` as a module
```
# go back to root directory of monorepo
cd ../../

# install the linked package
npm link components-lib
```

## 4 - Start SPA Application
```
npm start spa-application
```
