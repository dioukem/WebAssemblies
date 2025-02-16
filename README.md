If the CDN is https://cdn.jsdelivr.net/pyodide/v0.27.2/full/pyodide.js it will throw an exception Uncaught SyntaxError: The requested module './pyodide.js' does not provide an export named 'loadPyodide.
To fix this,  replace pyodide.js to pyodide.mjs as https://cdn.jsdelivr.net/pyodide/v0.27.2/full/pyodide.mjs . This will resolve the issue
