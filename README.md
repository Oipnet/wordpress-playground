> **Unofficial build.** PHP 8.6.0 compiled from WordPress Playground v3.1.65 with the patches in
> `source/` of the `forelse-php-8-6-v3.1.65` branch, published under the `@php-wasm/web-8-5` name so that
> `@php-wasm/web@3.1.65` loads it as is (`loadWebRuntime('8.5')` runs PHP 8.6). Used by apprendre.forelse.fr
> until the official `@php-wasm/web-8-6` package exists.

# @php-wasm/web-8-5

PHP 8.5 WebAssembly binaries for the web.

This package contains:

- JSPI and Asyncify variants of PHP 8.5 compiled to WebAssembly
- intl extension for PHP 8.5

## Installation

```bash
npm install @php-wasm/web-8-5
```

## Usage

```typescript
import { getPHPLoaderModule, getIntlExtensionPath } from '@php-wasm/web-8-5';

const loaderModule = await getPHPLoaderModule();
const intlPath = await getIntlExtensionPath();
```

## Related Packages

- [@php-wasm/web](https://www.npmjs.com/package/@php-wasm/web) - Main package (requires version packages)
- [@php-wasm/universal](https://www.npmjs.com/package/@php-wasm/universal) - Universal PHP.wasm bindings

## License

GPL-2.0-or-later
