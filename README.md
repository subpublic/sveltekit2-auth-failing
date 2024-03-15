# sveltekit2-auth-failing

Test of sveltekit2 auth. Fails on build

```
TypeError: Cannot read properties of undefined (reading 'length')
    at Object.handle (/.svelte-kit/output/server/chunks/hooks.server.js:136:26)
    at respond (/.svelte-kit/output/server/index.js:2603:43)

node:internal/event_target:1033
  process.nextTick(() => { throw err; });
```
