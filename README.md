# SwiftLintConfig

**disabled_rules:**
```
  - trailing_whitespace
  - force_cast
  - nesting
  - line_length
  - identifier_name
  # TODOs and FIXMEs should be resolved.
  - todo
```

**opt_in_rules:**
```
  ## Style
  # Closure expressions should have a single space inside each brace.
  - closure_spacing
  # Prefer implicit returns in closures, functions and getters.
  - implicit_return
  # Imports should be sorted.
  - sorted_imports
  # Operators should be surrounded by a single whitespace when they are being used.
  - operator_usage_whitespace
  # Prefer Self over type(of: self) when accessing properties or calling methods.
  - prefer_self_type_over_type_of_self
  # Parentheses are not needed when declaring closure arguments.
  - unneeded_parentheses_in_closure_argument
  # All imported modules should be required to make the file compile.
  - unused_import
  # Don’t include vertical whitespace (empty line) before closing braces.
  - vertical_whitespace_closing_braces
  # Don’t include vertical whitespace (empty line) after opening braces.
  - vertical_whitespace_opening_braces
  
  ## Metrics
  # Closure bodies should not span too many lines.
  - closure_body_length
  # Number of associated values in an enum case should be low
  - enum_case_associated_values_count

  ## Idiomatic
  - explicit_init
  - force_unwrapping

  # Discouraged explicit usage of the default separator.
  - joined_default_parameter
  # Prefer someBool.toggle() over someBool = !someBool.
  - toggle_bool
```
