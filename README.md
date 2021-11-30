# node-password-generator

A simple command-line app to generate random passwords using Node.js along with Commander and Chalk

## Usage

Install dependencies

```
npm install
```

Run file

```
node index (options)
```

To create a symlink to run "node-password-generator" from anywhere

```
npm link
# Now you can run
passgen (options)
# To remove symlink
npm unlink
```

## Options

| Short | Long              | Description                      |
| ----- | ----------------- | -------------------------------- |
| -l    | --length <number> | length of password (default: 12) |
| -s    | --save            | save password to passwords.txt   |
| -nn   | --no-numbers      | remove numbers                   |
| -ns   | --no-symbols      | remove symbols                   |
| -h    | --help            | display help for command         |
| -V    | --version         | Show the version                 |
