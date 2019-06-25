# MxDotNetUtils
Collection of useful classes for .Net development

1. CmdLineParams - Create class from Command Line parameters passed to main()
   - converts parameters and their arguments into useful types within a derived class in the App project - i.e. CmdLineParamsApp
   - allows for validation of parameters and arguments
   - provides help messages for incorrectly formed parameters and arguments

2. EnumOps - Methods for converting Enums to strings and vice versa
   - XlatToString<T>(T type) - converts type to string
   - XlatFromString<T>(string str, out T result) - converts string to type
