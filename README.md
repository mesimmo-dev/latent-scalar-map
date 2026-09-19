# latent-scalar-map

Minimal scalar transformation utility for deterministic numerical pipelines.

## Usage

```javascript
import { transform } from "@mesimmo-dev/latent-scalar-map";

const value = transform(5, 2, 1);

console.log(value);
// 11
```

## API

```javascript
transform(x, scale = 1, offset = 0)
```

Applies a linear scalar transformation:

```text
x × scale + offset
```

## License

MIT License

Copyright © 2026 M.E. Simmons
