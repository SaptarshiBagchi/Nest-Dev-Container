## Just a basic barebone template to dev containerize a nestjs application

1. Have remote container extension, docker extensions installed in vs code

2. ctrl + shift + p -> Reopen and build remote container and wait for the process to complete

3. npm run start:dev

If you are unable to detect git changes inside the dev container, make sure you run

```sh
git config --global --add safe.directory /workspaces/nestjs-app
```
