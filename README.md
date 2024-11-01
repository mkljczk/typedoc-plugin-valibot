# typedoc-plugin-valibot

Improves display of types created with [Valibot](https://valibot.dev/)'s `v.InferOutput type.

## Usage

```bash
npm install --save-dev typedoc-plugin-valibot
```

```jsonc
// typedoc.json
{
    "plugin": ["typedoc-plugin-valibot"],
}
```

<!-- See [an example](https://gerritbirkeland.com/typedoc-plugin-zod/types/Abc.html) of this plugin in action. -->

<!-- ## Change Log

### v1.2.1 (2024-08-18)

-   Fix warnings about referenced but not present reflections in packages mode, #6.
-   Copy comments from schema object declaration to type alias, #7.

### v1.2.0 (2024-06-22)

-   Support TypeDoc 0.26.

### v1.1.2 (2024-01-06)

-   Added support for the `z.input` type, #3.

### v1.1.1 (2023-12-26)

-   Fixed conversion of symbols where the same name is used for a type and variable, #2.

### v1.1.0 (2023-08-25)

-   Add support for TypeDoc 0.25.x

### v1.0.2

-   Update peer dependency to allow TypeDoc 0.24

### v1.0.1

-   Add GitHub links to NPM package -->
