# Day X: Installation and Setup

**Date:** 01/10/2026
**Time spent:** 30 mins

## Goal
My today's goal is setup and installation of Typescript.


### Install Node.js
Typescript tools run on Node.js.Can be downloaded from nodejs.org

# Verify installation:

```bash
node --version
npm --version
```

### Install TypeScript


```bash
npm install -g typescript
```


# Verify installation:

```bash
tsc --version
```


### To Compile .ts file we use:

```bash
tsc Hello.ts
```


Notes: This compile the typescript and create a .js extention file in same folder.

### To run Compile file we use:

```bash
node Hello.js
```


### Install TSX
```bash
npm install -g tsx
```
Notes: tsx can run typescript code without compiling.
For example:
```bash
tsx Hello.ts
```
## Next
- Basics of Typescript