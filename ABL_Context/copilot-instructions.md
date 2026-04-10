# GitHub Copilot Instructions for OpenEdge ABL 12.8

This file provides context and guidance for GitHub Copilot when working with OpenEdge ABL (Advanced Business Language) code.

## About OpenEdge ABL

OpenEdge ABL is a business application development language created by Progress Software Corporation. It is designed for building multi-tier applications with strong database integration, particularly with the OpenEdge database.

## Key Language Characteristics

- **Case-insensitive**: Keywords and identifiers are not case-sensitive
- **Strong database integration**: Built-in support for database operations
- **Object-oriented**: Supports classes, interfaces, and inheritance
- **Event-driven**: Supports event handling for GUI and business logic
- **Modern syntax**: Use `var` statement instead of `DEFINE VARIABLE` when possible
- **Keywords**: Always use lowercase for keywords (preferred style)

## Documentation References

The following documentation files are available in the `ABL_Context/` folder. Reference these when generating or explaining ABL code:

# OpenEdge 12.8 ABL Reference Documentation

This rules file references OpenEdge 12.8 documentation for ABL syntax and API reference.

## ABL Syntax Reference

#User interface
**ABL_Context/user_interface_statements.txt**: Reference for ABL user interface statements.

#Transaction
**ABL_Context/transaction_statements.txt**: Reference for ABL transaction syntax statements.

#String manipulation
**ABL_Context/string_manipulation.txt**: Reference for ABL string manipulation syntax.

#Memory manipulation
**ABL_Context/memory_manipulation.txt**: Reference for ABL memory manipulation syntax.

#Punctuation and special characters
**ABL_Context/punctuation_and_special_characters.txt**: Reference for ABL punctuation and special characters syntax.

#Query manipulation
**ABL_Context/query_manipulation.txt**: Reference for ABL query manipulation syntax.

#Dynamic statements
**ABL_Context/dynamic__statements.txt**: Reference for ABL dynamic statements.

#Logical data (datasets, temp-tables)
**ABL_Context/logical_data_datasets_temp_tables.txt**: Reference for ABL logical data manipulation using datasets and temp-tables.

#Widget reference
**ABL_Context/widget_reference.txt**: Reference for usage of ABL widgets.

#Handle reference
**ABL_Context/handle_reference.txt**: Reference for usage of ABL handle-based objects.

#Handle Attributes and Methods
**ABL_Context/handle_attributes_and_methods_reference_introduction.txt**: Consider for an introduction to handle attributes, handle methods, COM object properties, and COM object methods.

**ABL_Context/handle_attributes_and_methods_reference_a_d.txt**: Reference for handle attributes, handle methods, COM object properties, and COM object methods A to D.

**ABL_Context/handle_attributes_and_methods_reference_e_h.txt**: Reference for handle attributes, handle methods, COM object properties, and COM object methods E to H.

**ABL_Context/handle_attributes_and_methods_reference_i_o.txt**: Reference for handle attributes, handle methods, COM object properties, and COM object methods I to O.

**ABL_Context/handle_attributes_and_methods_reference_p_s.txt**: Reference for handle attributes, handle methods, COM object properties, and COM object methods P to S.

**ABL_Context/handle_attributes_and_methods_reference_t_z.txt**: Reference for handle attributes, handle methods, COM object properties, and COM object methods T to Z.

#Handle-based Object Events
**ABL_Context/handle_based_object_events_reference.txt**: Reference for ABL events.

#Class, Interface, and Enumeration
**ABL_Context/class_interface_and_enumeration_reference.txt**: Reference for the information related to classes, interfaces, and enumerations.

#Class Properties and Methods
**ABL_Context/class_properties_and_methods_reference.txt**: Reference for built-in class property and method that ABL supports for working with ABL classes and structured error handling.

#Class Events
**ABL_Context/class_events_reference.txt**: Reference for information related to the events that are associated with class-based objects, including both ABL and .NET objects, and how the application can respond to them.

#Array
**ABL_Context/array_statements.txt**: Reference for information related to arrays.

#Auditing
**ABL_Context/auditing_statements.txt**: Reference for information related to auditing.

#Calculation functions
**ABL_Context/calculation_functions.txt**: Reference for information related to calculation functions.

#Code execution
**ABL_Context/code_execution.txt**: Reference for information related to code execution functions.

#Data manipulation
**ABL_Context/data_manipulation_and_database_management.txt**: Reference for information related to data manipulation and database information.

#Data type conversion
**ABL_Context/data_type_conversion.txt**: Reference for information related to data type conversion functions.

#Date and time functions
**ABL_Context/date_manipulation.txt**: Reference for information related to date and time functions.

#Input Output statements
**ABL_Context/input_output_statements.txt**: Reference for information related to input output statements.

#Integration
**ABL_Context/integration_statements.txt**: Reference for information related to integration.

#Object Oriented Programming
**ABL_Context/object_oriented_syntax.txt**: Reference for information related to object oriented programming.

#Operating System functions
**ABL_Context/operating_system.txt**: Reference for information related to operating system functions.

#Security
**ABL_Context/security_statements.txt**: Reference for information related to security.

#Session management
**ABL_Context/session_management.txt**: Reference for information related to session management.

#Variable definition
**ABL_Context/variable_definition.txt**: Reference for information related to variable definition statements (DEFINE VARIABLE and VAR).

#XML manipulation
**ABL_Context/xml_manipulation.txt**: Reference for information related to xml manipulation.

#Keyword Index
**ABL_Context/keyword_index.txt**: Reference for a list of reserved keywords. ALL keywords listed in this file are reserved in ABL and cannot be used as identifiers (such as variable names, frame names, etc.) without potential conflicts. When advising on ABL code, always check against this list to ensure identifiers don't conflict with reserved keywords.

#Error handling
**ABL_Context/abl_error_handling.txt**: Reference for error handling statements and syntax (BLOCK-LEVEL, ROUTINE-LEVEL, etc.).

**ABL_Context/abl_error_handling___complete_reference.txt**: Reference for comprehensive error handling concepts, CATCH blocks, condition handling, and error handling patterns.

#Collections
**ABL_Context/collections.txt**: Reference for information on collections.

## ABL API Reference

#OpenEdge.ABLUnit
**ABL_Context/openedge_abl_api_reference___openedge.ablunit.txt**: Reference for OpenEdge ABLUnit testing framework classes and methods.

#OpenEdge.ApplicationServer
**ABL_Context/openedge_abl_api_reference___openedge.applicationserver.txt**: Reference for OpenEdge Application Server API classes and methods.

#OpenEdge.BusinessLogic
**ABL_Context/openedge_abl_api_reference___openedge.businesslogic.txt**: Reference for OpenEdge Business Logic API classes and methods.

#OpenEdge.BusinessRules
**ABL_Context/openedge_abl_api_reference___openedge.businessrules.txt**: Reference for OpenEdge Business Rules API classes and methods.

#OpenEdge.Core
**ABL_Context/openedge_abl_api_reference___openedge.core.txt**: Reference for OpenEdge Core API classes including Assert, Collections, DataType, Json, Memptr, Reflection, Rounding, String, and WidgetHandle utilities.

#OpenEdge.DataAdmin
**ABL_Context/openedge_abl_api_reference___openedge.dataadmin.txt**: Reference for OpenEdge DataAdmin API classes for database administration and management.

#OpenEdge.Logging
**ABL_Context/openedge_abl_api_reference___openedge.logging.txt**: Reference for OpenEdge Logging API classes and methods for application logging.

#OpenEdge.Messaging
**ABL_Context/openedge_abl_api_reference___openedge.messaging.txt**: Reference for OpenEdge Messaging API classes for message handling and queuing.

#OpenEdge.Mobile
**ABL_Context/openedge_abl_api_reference___openedge.mobile.txt**: Reference for OpenEdge Mobile API classes for mobile application development.

#OpenEdge.Net
**ABL_Context/openedge_abl_api_reference___openedge.net.txt**: Reference for OpenEdge Net API classes including HTTP, ServerConnection, and URI utilities.

#OpenEdge.Rest
**ABL_Context/openedge_abl_api_reference___openedge.rest.txt**: Reference for OpenEdge REST API classes for RESTful web services.

#OpenEdge.Security
**ABL_Context/openedge_abl_api_reference___openedge.security.txt**: Reference for OpenEdge Security API classes for authentication and authorization.

#OpenEdge.Web
**ABL_Context/openedge_abl_api_reference___openedge.web.txt**: Reference for OpenEdge Web API classes for web application development.


## Best Practices for ABL Development

### Modern ABL Syntax
- Use `var` instead of `DEFINE VARIABLE` for cleaner code
- Use lowercase for all keywords
- Use meaningful variable names
- Prefer object-oriented approaches when appropriate

### Error Handling
- Use structured error handling with `CATCH` blocks
- Implement proper `UNDO, THROW` for error propagation
- Always handle database errors appropriately

### Database Operations
- Use `NO-LOCK` for read-only operations to avoid locking
- Use `EXCLUSIVE-LOCK` only when necessary
- Always use `TRANSACTION` blocks for data modifications
- Consider using temp-tables for complex data manipulation

### Code Organization
- Use classes and interfaces for reusable components
- Separate business logic from UI logic
- Use include files for common definitions
- Follow consistent naming conventions

### Performance
- Use indexes effectively in database queries
- Minimize database round-trips
- Use `BUFFER` for multiple references to the same table
- Consider using `PRESELECT` for better query performance

## When Generating ABL Code

1. **Check reserved keywords**: Consult `ABL_Context/keyword_index.txt` to avoid using reserved words as identifiers
2. **Use appropriate syntax**: Reference the relevant documentation file for the feature you're implementing
3. **Follow modern patterns**: Prefer `var`, lowercase keywords, and object-oriented approaches
4. **Include error handling**: Always implement proper error handling with `CATCH` blocks
5. **Add comments**: Explain complex business logic and database operations

## Example Code Patterns

### Variable Declaration (Modern)
```abl
var character cCustomerName = "".
var integer iOrderCount = 0.
var decimal dTotalAmount = 0.00.
```

### Database Query with Error Handling
```abl
define variable cName as character no-undo.

do transaction on error undo, throw:
    find first Customer where Customer.CustNum = 12345 no-lock no-error.
    if available Customer then
        cName = Customer.Name.
    else
        undo, throw new Progress.Lang.AppError("Customer not found", 0).
end.
```

### Class Definition
```abl
class MyApp.BusinessLogic.CustomerManager:
    
    method public void SaveCustomer(input pcName as character):
        define buffer bCustomer for Customer.
        
        do transaction on error undo, throw:
            create bCustomer.
            assign bCustomer.Name = pcName.
        end.
    end method.
    
end class.
```
