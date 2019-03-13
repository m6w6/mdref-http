# static string http\Env::negotiateEncoding(array $supported[, array &$result])

Negotiate the client's preferred encoding.

> ***NOTE:***  
> The first element of $supported encodings serves as a default if no encoding matches.

## Params:

* array $supported  
  List of supported content encodings.
* Optional array &$result  
  Out parameter recording negotiation results.
  
## Returns:

* NULL, if negotiation fails.
* string, the negotiated encoding.
