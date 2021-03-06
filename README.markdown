# jQuery Select Autocomplete

jQuery Select Autocomplete lets you turn an HTML `<select>` tag into an auto-complete text input box and hides the select node in the DOM.  When a user types in the text input box, all matching options from the select list will show up in the auto-complete list and when one option is selected, the select control's selected item is set to the item picked from the auto-complete list.  This means that you don't have to change your processing code at all; just look for the select list`s value the same way you already were.

Assuming you have one or more select lists with a class of "autocomplete", just write: 

$(select.autocomplete).select_autocomplete();
  

### Example

See `index.html` for a working example.

## License

License is MIT. See LICENSE file.

## Todo

* figure out if there's a way to automagically manage the dependency on jquery.autocomplete
