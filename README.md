# Token Namer

Static single-page assistant to compose design token names, one value per slot. The tier (primitive or semantic) is the first choice and is not part of the name: it only decides which categories and steps are shown.

Live: https://msahores.github.io/token-namer/

Local use: open `index.html` with a double click (works over `file://`, no build, no dependencies).

The grammar (tiers, categories, steps, options and preview colors) lives in the `CONFIG` object at the top of `index.html`. To add an option, append `{ value, description }` to the matching list.

Primitive scales follow what frontend and design agreed in September 2026: color from 100 to 1000, dimensions in hundredths of a 4px base, radius numeric plus `full`, font weights by name. The semantic vocabulary is a frontend draft for the next iteration.

The collected list is stored in the browser's `localStorage`.
