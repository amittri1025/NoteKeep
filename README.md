
## Introduction
This is a full stack app created by Amit

## How to run
Since this app requires , the LTS version of Node js it would give errors initially
(working over that)
But I have a fix

For Windows, use the below command in cmd:
```
set NODE_OPTIONS=--openssl-legacy-provider
```
For Unix, use:
```
export NODE_OPTIONS=--openssl-legacy-provider
```

Paste these commands in Command Prompt or Terminal.

Then DO.

```
npm start
```
