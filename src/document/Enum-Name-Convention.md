
### Enum name convention.

Protocol Buffers specification places enum type values 
in the same name space, if they are defined in the same protocol file.

OpenFeed adopted the "name suffix" convention to address this.
All enum types in the same protocol file must have distinct suffix.

Example:
```
enum OptionType {
	DEFAULT_OPTION = 0;
	CALL_OPTION = 1;
	PUT_OPTION = 2;
}
```
