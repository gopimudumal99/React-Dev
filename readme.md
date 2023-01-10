caret^ and tilda~ in npm

- package.lock json is very important file it lock the package version and it will not move in .gitignore
- package.lock.json maintain exact version of it
- it also maintain hash(integrity) of it
- package.lock.json file help us generate the nodemodules on server

npx -> execute using npm

npx parcel index.html => it will create a development build for us and it is hosted on server
npx parcel build index.html => remove the main key in package.json

script tag his module type so given type = 'module' so this will help to read the browser the import export

git ignore -> anything which have auto generated we put into gitignore => anything can we generate on server that will put into gitignore

1. Parcel:Bundler

- Hot module reload (HMR)
  - this is the thing the parcel is doing which means that parcel keep a track on all the files which you updated
  - how does HMR works there is some thing known as file watchers algorithm which is used by parcel
  - and this file watcher algorithm written in c++
- file matches algorithm (c++)
- BuNDLING
- cleaning our code
- Minify)cleaning the code
- Dev and production build
- Super Fast build algorithm
- Image Optimization
- Caching while development
- compression files
- compatible with Older version of browsers
- HTTPS on dev machine => npx parcel index.html --https
- manage the PORT Number
