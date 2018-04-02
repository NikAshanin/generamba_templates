# Generamba templates

## touchin

Module with controller, view-model and assembly

## touchin-stateful
Module with controller, view model and assebly. It loads some data from network and handles empty and error states.

## touchin-pagination
Module with controller, view model, cursor and assebly. It loads paginated results from network and handles empty and error states using PaginationWrapper.

## touchin-tablecell

Module for cell generation. Contains: Cell, ViewModel and xib file

### Example

Part of Rambafile to include templates

```ruby
catalogs:
- 'https://github.com/TouchInstinct/generamba_templates'

templates:
- {name: touchin}
- {name: touchin-stateful}
- {name: touchin-pagination}
- {name: touchin-tablecell}
```

