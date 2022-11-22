# FeedbackFruits tsconfig
Shared tsconfig for all Node.js/Typescript-based projects

Usage:
```sh
yarn add -D @feedbackfruits/tsconfig
```

```json
{
  "extends": "@feedbackfruits/tsconfig",
  "compilerOptions": {
    "outDir": "./dist",
    "rootDir": "./src",
	}
}
```

*Note: outDir and rootDir are required, these cannot be set in this template*
