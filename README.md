# HTTPApiDoc

HTTPApiDoc aims to create a standard for documenting HTTP based APIs of almost any complexity.

However it is the position of this project, that limitless power is a dangerous thing for developers and API designers. Correspondingly, some things will be deliberately not taken into this standard. If you feel like some possibilities are missing please feel free to create an issue or provide a pull request to enhance this standard.

This standard will organically grow and will be released in versions that aim for targets.

The project will aim to create the standard as an XML, as XML can document structures and meta information in a tree form and the structure may not be polluted through it.



# Version Targets

## Version 1.0

**Status**: work in progress

**Additions**
- Type and structure documentation
- Structured strings
  - Query String format
  - JSON format
- Entry Points
  - Request format
    - URL
      - Protocol
      - User
      - Password
      - Host
      - Port
      - url-path (including dynamic elements)
      - Query
    - Headers
    - Body
  - Response format
    - Headers
      - Simplified http status notation
    - Body
- Common behaviour of all entry points
  - Common response
  - Common header