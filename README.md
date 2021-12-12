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

In the `tsconfig.json` file the option [exactOptionalPropertyTypes](https://devblogs.microsoft.com/typescript/announcing-typescript-4-4/#exact-optional-property-types) should be set to true as for the construction of a GObject all properties are optional but are not allowed to be undefined. 