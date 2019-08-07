# pesy-bare


[![CircleCI](https://circleci.com/gh/yourgithubhandle/pesy-bare/tree/master.svg?style=svg)](https://circleci.com/gh/yourgithubhandle/pesy-bare/tree/master)


**Contains the following libraries and executables:**

```
pesy-bare@0.0.0
│
├─test/
│   name:    TestPesyBare.exe
│   main:    TestPesyBare
│   require: pesy-bare.lib
│
├─library/
│   library name: pesy-bare.lib
│   namespace:    PesyBare
│   require:
│
└─executable/
    name:    PesyBareApp.exe
    main:    PesyBareApp
    require: pesy-bare.lib
```

## Developing:

```
npm install -g esy
git clone <this-repo>
esy install
esy build
```

## Running Binary:

After building the project, you can run the main binary that is produced.

```
esy x PesyBareApp.exe 
```

## Running Tests:

```
# Runs the "test" command in `package.json`.
esy test
```
