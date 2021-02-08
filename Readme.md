1. created src folder which is my development file
2. Setup Project
- setting npm init
- install parcel-bundler
3. Wrote my dev and build script
- inside package.json file
    "scripts": {
    "dev":"parcel src/index.html",
    "build":"parcel build src/index.html"
  },