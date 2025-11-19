# piccolore

A tiny, fast library for styling terminal output with ANSI colors and styles.

- 0 dependencies
- ESM only
- 2 KB, total install size <4 KB
- Respects `NO_COLOR`
- Fully typed

## Usage

```js
import pc from 'piccolore';

console.log(pc.blue(`I’m ${pc.bold('really')} excited!`));
```

