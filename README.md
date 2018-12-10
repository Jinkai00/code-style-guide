# CodeStyleGuide
Style guide for different language

## Python
[PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)

module_name, package_name, ClassName, method_name, ExceptionName, function_name, GLOBAL_VAR_NAME, instance_var_name, function_parameter_name, local_var_name.

| Type                       | Public             | Internal                                                          |
| :------------------------- | :----------------- | :---------------------------------------------------------------- |
| Modules                    | lower_with_under   | _lower_with_under                                                 |
| Packages                   | lower_with_under   |                                                                   |
| Classes                    | CapWords           | _CapWords                                                         |
| Exceptions                 | CapWords      	    |                                                                   |
| Functions	                 | lower_with_under() |	_lower_with_under()                                               |
| Global/Class Constants     | CAPS_WITH_UNDER    |	_CAPS_WITH_UNDER                                                  |
| Global/Class Variables	   | lower_with_under   |	_lower_with_under                                                 |
| Instance Variables         | lower_with_under	  | _lower_with_under (protected) or __lower_with_under (private)     |
| Method Names	             | lower_with_under() |	_lower_with_under() (protected) or __lower_with_under() (private) |
| Function/Method Parameters | lower_with_under	  |                                                                   |
| Local Variables            | lower_with_under	  |                                                                   |
