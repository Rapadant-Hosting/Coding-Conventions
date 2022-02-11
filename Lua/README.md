# Rapadant Hosting Coding Conventions

## Lua

The following are a set of guidelines for programming Lua-related content for Rapadant Hosting:

- Indentation should be 4 wide spaces(by pressing tab on your keyboard, not actual spaces)
- Variables are to be formatted as follows:
  - globalVars *(use only when necesary)*
  - localVars *(try to use this more often than globals)*
  - ConfigTable.configVar
  - ENUM_VALUE *(use only when necesary)*
- Every bracket should be spaced. Squar brackets are optional
- Every file should end with three empty lines.
- Always use default Lua operators if others are provided. For example, always use `or` instead of `||`.
- If statements should not contain brackets unless it; is a large statement, has mathematical equations or if needed for ease of reading.
- String identifiers, such as for events (or hooks in Garry's Mod), should be formatted like `Unique Event Name`.


