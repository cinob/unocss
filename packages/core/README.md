# @unocss/core

The core engine of [UnoCSS](https://github.com/antfu/unocss) without any presets. Can be used as the engine of your own atomic-css framework.

## Usage

```ts
import { createGenerator } from '@unocss/core'

const generator = createGenerator({ /* user options */ }, { /* default options */ })

const { css } = await generator.generate(code)
```

## License

MIT License © 2021-PRESENT [Anthony Fu](https://github.com/antfu)
