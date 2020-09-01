# Forked serverless-plugin-typescript
[![serverless](http://public.serverless.com/badges/v3.svg)](http://www.serverless.com) [![npm version](https://badge.fury.io/js/serverless-plugin-typescript.svg)](https://badge.fury.io/js/serverless-plugin-typescript) [![Build Status](https://travis-ci.org/claes-npm/serverless-plugin-typescript.svg?branch=master)](https://travis-ci.org/claes-npm/serverless-plugin-typescript)

## WARNING

### This is a forked version of serverless-plugin-typescript.

## Changes

The only change in this forked version is the option to skip the dependency copy (node_modules folder being copied to the build folder).

This is done by adding the argument `--doNotCopyDependencies` to the sls deploy or package command.

E.g.
```
serverless package --package .package --doNotCopyDependencies
```

## Features

The rest of the documentation can be read in the original repo.
