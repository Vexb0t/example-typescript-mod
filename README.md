# Example TypeScript Mod
Example EaglerForge mod template.

## How to build?
You can use 2 build systes, bun is for linux - macos machines, esbuild is cross platform really.
# 1 - Bun 
WARNING : Bun is experimental on windows

1. Run `bun install`
2. Modify your files accordingly.
3. Run `bun run build-bun`
4. profit
# 2 - esbuild
1. Run `npm install -g esbuild`
2. Modify your files accordingly.
3. Run `node run build-es`
4. profit ( againe )
## Notes
- Dont remove `//@ts-ignore`.
- Both build tasks will generate source maps and it will watch your files.