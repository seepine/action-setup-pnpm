# actions-setup-pnpm

> Use corepack, if you want to set pnpm version, setting the packageManager field in package.json like `"packageManager":"pnpm@8.10.2"`

## Usage

```yml
- name: Setup pnpm and Install
  uses: seepine/actions-setup-pnpm@v1
```

## Input


| Output Item  | Description                                                                                            | Required | Default |
| ------------ | ------------------------------------------------------------------------------------------------------ | -------- | ------- |
| run_instasll | The working dir for the action                                                                         | false    | true    |
| cwd          | Changes node's process.cwd() if the project is not located on the root. Default to process.cwd() files | false    | .       |
