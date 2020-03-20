#Code Styles

##Resharper

* Environment
    * Editor
        * Editor appearance
            * Highlightings
                - Highlight with: *Outline*
        * Editor behaviour
            - Auto-insert closing brace: *on enter after an opening brace*
* Code Inspection
    * Code Annotations
        - Machine.Specifications.Annotations
* Code Editing
    * Code cleanup
        * My Code Cleanup
            * C#
                - Apply file layout
                - Update file header
                * Code styles
                    - Use explicit or implicit modifier definition for types
                    - Use explicit or implicit modifier definition for type members
                - Remove code redundancies
                * Optimize 'using' directives
                    - Optimize 'using' directives
                - Reformat code
            * XAML
                - Collapse empty tags
    * C#
        * Formatting Style
            * Line Breaks and Wrapping
                * Line Wrapping
                    - Right margin (columns): *80*
                    - Wrap formal parameters: *Chop if long*
                    - Wrap after "(" in declaration: *True*
                    - Wrap invocation arguments: *Chop if long*
                    - Wrap after "(" in invocation: *True*
                    - Wrap extends/implements list: *Chop if long*
                    - Wrap array initializer: *Chop if long*
                * Spaces
                    - Space around multiplicative: *True*
                    - Space within array access brackets: *False*
                    - Space within fixed parentheses: *False*
                    - Space within for parentheses: *False*
                    - Space within method call parentheses: *False*
                    - Space within method parentheses: *False*
                    - Space within parentheses: *False*
                    - Space within typecast parentheses: *False*
                    - Space within typeof parentheses: *False*
        * File Layout
            * Default pattern
                - Public Delegates
                - Public Enums
                - Static Fields and Constants
                - Fields (order by: readonly, name)
                - Constructors
                - Properties, Indexers (order by: access, name)
                - Interface Implementations
                - All other members (order by: access, static, name)
                - Nested Types
            * MSpec pattern
                - Non static private fields
                - Static private fields
                - All other members
        * Code Style
            * Modifiers
                - Prefer explicit/implicit private modifier for type members: *Implicit*
                - Prefer explicit/implicit internal modifier for types: *Implicit*
