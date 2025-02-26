## Special forms

| Form | Description |
| - | - |
| `(quote <v>)`/`'<v>` | Returns `v` unevaluated. |
| `(define <sym> <v>)` | Binds `sym` to `v`. Returns `v`. |
| `(define (<sym> <p>...) <v>)` | Binds `sym` to a function with parameters `p` that returns `v`. Returns said function. |

## Primitive functions

| Function | Description |
| - | - |
| `(reverse <l>)` | Returns `l` in reverse order. |
| `(append <l1> <l2>)` | Returns `l1` concatenated with `l2`. |
| `(list <...>)` | Returns every single argument back, as a list. |
