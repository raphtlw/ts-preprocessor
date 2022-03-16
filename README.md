# ts-preprocessor

i want this to be possible:

```ts:index.ts
#define loop while(true)

loop {
  console.log("poop")
}
```

### How to install

This is a wrapper around the TypeScript compiler API. It aims to serve as a drop-in replacement for the TypeScript compiler.

```shell
npm i ts-preprocessor
```

To run this preprocessor, use

```shell
tsp index.ts
```
