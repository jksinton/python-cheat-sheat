# Python Cheat Sheat

Docstring template for a python function:
~~~
    """A description of the function that gives enough information to write 
    a call to the function without reading the function's name.
    
    Args:
        List each parameter by name. 

    Returns:
        Describe the semantics of the return value.

    Raises:
        List all exceptions that are relevant to the interface followed by a description.
    """
~~~

## dcc.Store

The ```dcc.Store component``` is used to store JSON data in the browser.

### Store Properties

storage_type (a value equal to: 'local', 'session' or 'memory'; default 'memory'): 
The type of the web storage. 

memory: only kept in memory, reset on page refresh. 

local: window.localStorage, data is kept after the browser quit. 

session: window.sessionStorage, data is cleared once the browser quit.


https://dash.plotly.com/dash-core-components/store
