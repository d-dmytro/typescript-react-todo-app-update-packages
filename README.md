# Updating the task mate app's dependencies to latest

## Step One

We can use the `npm-check-updates` tool to update all dependencies to latest: (https://www.npmjs.com/package/npm-check-updates)[https://www.npmjs.com/package/npm-check-updates]

Example:

```
# Install the package
npm i -g npm-check-updates

# Check what packages can be updated
ncu

# Write the new package version to your package.json
ncu -u

# Install updates
npm i
```

Check this commit:
https://github.com/d-dmytro/typescript-react-todo-app-update-packages/commit/99e77105562cd773ddb4a94eadfb8518f950878e

## Step Two

Fix schema undefined error that appears after updating

Check this commit:
https://github.com/d-dmytro/typescript-react-todo-app-update-packages/commit/2839072cf4d296ffab8bdc80766988c0e32d7acd

## Step Three

Fix the Apollo Server setup after upgrading apollo-server-micro

Check this commit:
https://github.com/d-dmytro/typescript-react-todo-app-update-packages/commit/3989cb6f206ca8c36f7ed5f130e73e06c3438e93
