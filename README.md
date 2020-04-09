# typeorm-issue

## Instructions

```bash
npm i
npm run electron:build
./dist_electron/typeorm-issue-0.1.0.AppImage
```

This should reproduce the error.

Comment out the typeorm import in background.js and it works fine.