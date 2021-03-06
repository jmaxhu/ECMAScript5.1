# SUMMARY

* [简介](introduction.md)
* [范围](scope.md)
* [一致性](conformance.md)
* [引用标准](normative.md)
* [概述](ch4_overview.md)
  * [Web脚本](ch4_overview/web_scripting.md)
  * [语言概述](ch4_overview/language_overview.md)
    * [对象](ch4_overview/language_objects.md)
    * [The Strict Variant of ECMAScript](ch4_overview/language/strict.md)
  * [Definitions](ch4_overview/definitions.md)
    * [type](ch4_overview/definitions.md#type)  
    * [primitive value](ch4_overview/definitions.md#primitive)
    * [object](ch4_overview/definitions.md#objects)
    * [constructor](ch4_overview/definitions.md#constructor)
    * [prototype](ch4_overview/definitions.md#prototype)
    * [native object](ch4_overview/definitions.md#native_object)
    * [built-in object](ch4_overview/definitions.md#builti-in_object)
    * [host object](ch4_overview/definitions.md#host_object)
    * [undefined value](ch4_overview/definitions.md#undefined_value)
    * [Undefined type](ch4_overview/definistions/undefined_type)
    * [null value](ch4_overview/definitions.md#null_value)
    * [Null type](ch4_overview/definitions.md#null_type)
    * [Boolean value](ch4_overview/definitions.md#boolean_value)
    * [Boolean type](ch4_overview/definitions.md#boolean_type)
    * [Boolean object](ch4_overview/definitions.md#boolean_object)
    * [String value](ch4_overview/definitions.md#string_value)
    * [String type](ch4_overview/definitions.md#string_type)
    * [String object](ch4_overview/definitions.md#string_object)
    * [Number value](ch4_overview/definitions.md#number_value)
    * [Number type](ch4_overview/definitions.md#number_type)
    * [Number object](ch4_overview/definitions.md#number_object)
    * [Infinity](ch4_overview/definitions.md#infinity)
    * [NaN](ch4_overview/definitions.md#nan)
    * [function](ch4_overview/definitions.md#function)
    * [built-in function](ch4_overview/definitions.md#built-in_function)
    * [property](ch4_overview/definitions.md#property)
    * [method](ch4_overview/definitions.md#method)
    * [built-in method](ch4_overview/definitions.md#built-in_method)
    * [attribute](ch4_overview/definitions.md#attribute)
    * [own property](ch4_overview/definitions.md#own_property)
    * [inherited property](ch4_overview/definitions.md#inherited_property)
* [Notational Conventions](ch5_notational_conventions.md)
  * [Syntactic and Lexical Grammars](ch5_notational_conventions/syntactic.md)
    * [Context-Free Grammars](ch5_notational_conventions/syntactic.md#context-free)
    * [The Lexical and RegExp Grammars](ch5_notational_conventions/syntactic.md#regexp)
    * [The Numeric String Grammar](ch5_notational_conventions/syntactic.md#numeric)
    * [The Syntactic Grammar](ch5_notational_conventions/syntactic.md#syntactic)
    * [The JSON Grammar](ch5_notational_conventions/syntactic.md#json)
    * [Grammar Notation](ch5_notational_conventions/syntactic.md#grammar)
  * [Algorithm Conventions](ch5_notational_conventions/algorithm.md)
* [Source Text](ch6_source_text.md)
* [Lexical Conventions](ch7_lexical_conventions.md)
  * [Unicode Format-Control Characters](ch7_lexical_conventions/unicode_format_control_characters.md)
  * [White Space](ch7_lexical_conventions/white_space.md)
  * [Line Terminators](ch7_lexical_conventions/line_terminators.md)
  * [Comments](ch7_lexical_conventions/comments.md)
  * [Tokens](ch7_lexical_conventions/tokens.md)
  * [Indentifier Name and Identifiers](ch7_lexical_conventions/indentifier.md)
    * [Reserved Words](ch7_lexical_conventions/reserved_words.md)
      * [Keywords](ch7_lexical_conventions/reserved_words.md#keywords)
      * [Future Reserved Words](ch7_lexical_conventions/reserved_words.md#future_reserved)
  * [Punctuators](ch7_lexical_conventions/punctuators.md)
  * [Literals](ch7_lexical_conventions/literals.md)
    * [Null Literals](ch7_lexical_conventions/literals.md#null)
    * [Boolean Literals](ch7_lexical_conventions/literals.md#boolean)
    * [Numeric Literals](ch7_lexical_conventions/literals.md#numeric)
    * [String Literals](ch7_lexical_conventions/literals.md#string)
    * [Regular Expression Literals](ch7_lexical_conventions/literals.md#regexp)
  * [Automatic Semicolon Insertion](ch7_lexical_conventions/automatic_semicolon_insertion.md)
    * [Rules of Automatic Semicolon Insertion](ch7_lexical_conventions/automatic_semicolon_insertion.md#rule)
    * [Examples of Automatic Semicolon Insertion](ch7_lexical_conventions/automatic_semicolon_insertion.md#examples)
* [Types](ch8_types.md)
  * [The Undefined Type](ch8_types/undefined.md)
  * [The Null Type](ch8_types/null.md)
  * [The Boolean Type](ch8_types/boolean.md)
  * [The String Type](ch8_types/string.md)
  * [The Number Type](ch8_types/number.md)
  * [The Ojbect Type](ch8_types/object.md)
    * [Property Attributes](ch8_types/object.md#property)
    * [Object Internal Properties and Methods](ch8_types/object.md#internal)
  * [The Reference Specification Type](ch8_types/reference_type.md)
    * [GetValue (V)](ch8_types/reference_type.md#getvalue)
    * [PutValue (V, W)](ch8_types/reference_type.md#putvalue)
  * [The List Specification Type](ch8_types/list_type.md)
  * [The Completion Specification Type](ch8_types/completion_type.md)
  * [The Property Descriptor and Property Identifier Specification Types](ch8_types/property.md)
    * [IsAccessorDescriptor (Desc)](ch8_types/property.md#isAccessorDescriptor)
    * [IsDataDescriptor (Desc)](ch8_types/property.md#isDataDescriptor)
    * [IsGenericDescriptor (Desc)](ch8_types/property.md#isGenericDescriptor)
    * [FromPropertyDescriptor](ch8_types/property.md#fromPropertyDescriptor)
    * [ToPropertyDescriptor (Obj)](ch8_types/property.md#toPropertyDescriptor)
  * [The Lexical Environment and Environment Record Specification Types](ch8_types/lexical.md)
  * [Algorithms for Object Internal Methods](ch8_types/algorithms.md)
    * [GetOwnProperty] (P)](ch8_types/algorithms.md#getOwnProperty)
    * [GetProperty] (P)](ch8_types/algorithms.md#getProperty)
    * [Get] (P)](ch8_types/algorithms.md#get)
    * [CanPut] (P)](ch8_types/algorithms.md#canPut)
    * [Put] (P, V, Throw)](ch8_types/algorithms.md#put)
    * [HasProperty] (P)](ch8_types/algorithms.md#hasProperty)
    * [Delete] (P, Throw)](ch8_types/algorithms.md#delete)
    * [DefaultValue] (hint)](ch8_types/algorithms.md#defaultValue)
    * [DefineOwnProperty] (P, Desc, Throw)](ch8_types/algorithms.md#defineOwnProperty)
* [Type Conversion and Testing](ch9_conversion_testing.md)
  * [ToPrimitive](ch9_conversion_testing/toPrimitive.md)
  * [ToBoolean](ch9_conversion_testing/toBoolean.md)
  * [ToNumber](ch9_conversion_testing/toNumber.md)
    * [ToNumber Applied to the String Type](ch9_conversion_testing/toNumber.md#string)
  * [ToInteger](ch9_conversion_testing/toInteger.md)
  * [ToInt32: (Signed 32 Bit Integer)](ch9_conversion_testing/toInt32.md)
  * [ToUint32: (Unsigned 32 Bit Integer)](ch9_conversion_testing/toUint32.md)
  * [ToUint16: (Unsigned 16 Bit Integer)](ch9_conversion_testing/toUint16.md)
  * [ToString](ch9_conversion_testing/toString.md)
    * [ToString Applied to the Number Type](ch9_conversion_testing/toString.md#number)
  * [ToObject](ch9_conversion_testing/toOjbect.md)
  * [CheckObjectCoercible](ch9_conversion_testing/checkObject.md)
  * [IsCallable](ch9_conversion_testing/isCallable.md)
  * [The SameValue Algorithm](ch9_conversion_testing/sameValue.md)
* [Executable Code and Execution Contexts](ch10_execute.md)
  * [Types of Executable Code](ch10_execute/code.md)
    * [Strict Mode Code](ch10_execute/code.md#strict)

