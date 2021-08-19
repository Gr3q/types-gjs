# types-gjs

Typescript definitions for GJS - Gnome JavaScript

Generated with [GitHub - Gr3q/GIR2TS: TypeScript declaration generator for GObject Introspection.](https://github.com/Gr3q/GIR2TS) and manually cleaned up.

## Usage

This only works on a system where Gnome or some GTK based DM is installed.

Intended to be used with code running off of Gnome JS engine.

It can be included in the project by creatding a declaration file, for example `gjs.d.ts`:

```ts
import "@ci-types/gjs";
```
