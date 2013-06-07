jQuery Autoclear
================

A simple plugin to clear input text fields on focus, and manage default values.


How to use
----------------

To set a field's default value, you need to use the title and value attributes:

    <input type="text" value="Default Value" title="Default Value" />
    
Then, to enable the autoclear feature, simple add the .clear class to it:

    <input type="text" value="Default Value" title="Default Value" class="autoclear"/>
    
Styling
----------------

This plugin also allows you to easily style your input elements wether they've been modified by the user or not.

On startup, your field will simply have the .clear class. Then, on focus, a .modifiedinput class will be added to the field. 
When the user leaves the field, the plugin checks if the value has changed from the default value. 
If it has changed, the .modifiedinput class remains, else it's removed.
    
That's it!
