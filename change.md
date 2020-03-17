i<h4 id="path-to-regexp"><path-to-regexp</h4>

 From Express 5 onwards, following are the changes with respect to path-to-regexp which has direct implications to route.
 * RegExp special characters can now only be used in a parameter, as opposed to anywhere.
 * Parameters can have suffixes to augment meaning - *, + and ?. E.g. `/:user*`
 * No wildcard asterisk (*) - use parameters instead ((.*) or :splat*)
