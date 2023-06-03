# svelte-multiselect-test

Simple test using vite's svelte-ts template.

The `check` script fails.
```
$ pnpm run check

> svelte-multiselect-test@0.0.0 check /home/nick/Code/ngyewch/svelte-multiselect-test
> svelte-check --tsconfig ./tsconfig.json


====================================
Loading svelte-check in workspace: /home/nick/Code/ngyewch/svelte-multiselect-test
Getting Svelte diagnostics...

/home/nick/Code/ngyewch/svelte-multiselect-test/src/App.svelte:5:27
Error: Cannot find module 'svelte-multiselect' or its corresponding type declarations. (ts)
  import Counter from './lib/Counter.svelte'
  import MultiSelect from 'svelte-multiselect'



====================================
svelte-check found 1 error and 0 warnings in 1 file
ELIFECYCLE Command failed with exit code 1.
```

The `build` script works (even if the `check` script fails).
