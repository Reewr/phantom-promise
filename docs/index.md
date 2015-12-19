<a name="module_promise-phantom"></a>
## promise-phantom
<a name="module_promise-phantom.create"></a>
### promise-phantom.create(options)
The main function of the wrapper. This creates a new phantom object

**Kind**: static method of <code>[promise-phantom](#module_promise-phantom)</code>  
**Promise**: <code>Phantom</code> A wrapper around the Browser object  

| Param | Type | Description |
| --- | --- | --- |
| options | <code>object</code> |  |
| options.path | <code>string</code> | Path to phantomJS/SlimerJS.                              If this is not set, node-phantom-simple                              will search $PATH |
| options.parameters | <code>object</code> | An object of key/value of options for PhantomJS |
