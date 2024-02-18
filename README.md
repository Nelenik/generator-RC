Generator generates react component directory, which includes by default js, jsx, css files.

Runs by command in terminal: `yo rc {args} {options}`

Following options activate generation of such files like: 
- `--cssm` - css-modules;
- `--sc` - scss;
- `--sa` - sass;
- `--le` - less;
- `--ts` - ts for react(index.ts -barrel file and tsx file)

Arguments:
- Path to the component (by default folder is created in current directory);
- Components name (by default it generates "Component")