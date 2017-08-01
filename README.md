Java Virtual Machine Specification Java SE 8-zh</br>
**仅供交流学习，请勿用作商业用途** </br>
已翻译章节</br>
- [1.1. A Bit of History](https://github.com/yu-linfeng/Java-Virtual-Machine-Specification-Java-SE-8-zh/blob/master/1/1.1.A_Bit_of_History.md)</br>
- [1.2. The Java Virtual Machine](https://github.com/yu-linfeng/Java-Virtual-Machine-Specification-Java-SE-8-zh/blob/master/1/1.2.The_Java_Virtual_Machine.md)</br>

翻译认领</br>
- [ ] The Java® Virtual Machine Specification
- [ ] Table of Contents
- [ ] Preface to the Java SE 8 Edition
- [ ] 1. Introduction
- [x] ~~1.1. A Bit of History~~ ylf-170728
- [x] ~~1.2. The Java Virtual Machine~~ ylf-170730
- [x] ~~1.3. Organization of the Specification~~ ylf-170801
- [ ] 1.4. Notation
- [ ] 1.5. Feedback
- [ ] 2. The Structure of the Java Virtual Machine
- [ ] 2.1. The class File Format
- [ ] 2.2. Data Types
- [ ] 2.3. Primitive Types and Values
- [ ] 2.3.1. Integral Types and Values
- [ ] 2.3.2. Floating-Point Types, Value Sets, and Values
- [ ] 2.3.3. The returnAddress Type and Values
- [ ] 2.3.4. The boolean Type
- [ ] 2.4. Reference Types and Values
- [ ] 2.5. Run-Time Data Areas
- [ ] 2.5.1. The pc Register
- [ ] 2.5.2. Java Virtual Machine Stacks
- [ ] 2.5.3. Heap
- [ ] 2.5.4. Method Area
- [ ] 2.5.5. Run-Time Constant Pool
- [ ] 2.5.6. Native Method Stacks
- [ ] 2.6. Frames
- [ ] 2.6.1. Local Variables
- [ ] 2.6.2. Operand Stacks
- [ ] 2.6.3. Dynamic Linking
- [ ] 2.6.4. Normal Method Invocation Completion
- [ ] 2.6.5. Abrupt Method Invocation Completion
- [ ] 2.7. Representation of Objects
- [ ] 2.8. Floating-Point Arithmetic
- [ ] 2.8.1. Java Virtual Machine Floating-Point Arithmetic and IEEE 754
- [ ] 2.8.2. Floating-Point Modes
- [ ] 2.8.3. Value Set Conversion
- [ ] 2.9. Special Methods
- [ ] 2.10. Exceptions
- [ ] 2.11. Instruction Set Summary
- [ ] 2.11.1. Types and the Java Virtual Machine
- [ ] 2.11.2. Load and Store Instructions
- [ ] 2.11.3. Arithmetic Instructions
- [ ] 2.11.4. Type Conversion Instructions
- [ ] 2.11.5. Object Creation and Manipulation
- [ ] 2.11.6. Operand Stack Management Instructions
- [ ] 2.11.7. Control Transfer Instructions
- [ ] 2.11.8. Method Invocation and Return Instructions
- [ ] 2.11.9. Throwing Exceptions
- [ ] 2.11.10. Synchronization
- [ ] 2.12. Class Libraries
- [ ] 2.13. Public Design, Private Implementation
- [ ] 3. Compiling for the Java Virtual Machine
- [ ] 3.1. Format of Examples
- [ ] 3.2. Use of Constants, Local Variables, and Control Constructs
- [ ] 3.3. Arithmetic
- [ ] 3.4. Accessing the Run-Time Constant Pool
- [ ] 3.5. More Control Examples
- [ ] 3.6. Receiving Arguments
- [ ] 3.7. Invoking Methods
- [ ] 3.8. Working with Class Instances
- [ ] 3.9. Arrays
- [ ] 3.10. Compiling Switches
- [ ] 3.11. Operations on the Operand Stack
- [ ] 3.12. Throwing and Handling Exceptions
- [ ] 3.13. Compiling finally
- [ ] 3.14. Synchronization
- [ ] 3.15. Annotations
- [ ] 4. The class File Format
- [ ] 4.1. The ClassFile Structure
- [ ] 4.2. The Internal Form of Names
- [ ] 4.2.1. Binary Class and Interface Names
- [ ] 4.2.2. Unqualified Names
- [ ] 4.3. Descriptors
- [ ] 4.3.1. Grammar Notation
- [ ] 4.3.2. Field Descriptors
- [ ] 4.3.3. Method Descriptors
- [ ] 4.4. The Constant Pool
- [ ] 4.4.1. The CONSTANT_Class_info Structure
- [ ] 4.4.2. The CONSTANT_Fieldref_info, CONSTANT_Methodref_info, and CONSTANT_InterfaceMethodref_info Structures
- [ ] 4.4.3. The CONSTANT_String_info Structure
- [ ] 4.4.4. The CONSTANT_Integer_info and CONSTANT_Float_info Structures
- [ ] 4.4.5. The CONSTANT_Long_info and CONSTANT_Double_info Structures
- [ ] 4.4.6. The CONSTANT_NameAndType_info Structure
- [ ] 4.4.7. The CONSTANT_Utf8_info Structure
- [ ] 4.4.8. The CONSTANT_MethodHandle_info Structure
- [ ] 4.4.9. The CONSTANT_MethodType_info Structure
- [ ] 4.4.10. The CONSTANT_InvokeDynamic_info Structure
- [ ] 4.5. Fields
- [ ] 4.6. Methods
- [ ] 4.7. Attributes
- [ ] 4.7.1. Defining and Naming New Attributes
- [ ] 4.7.2. The ConstantValue Attribute
- [ ] 4.7.3. The Code Attribute
- [ ] 4.7.4. The StackMapTable Attribute
- [ ] 4.7.5. The Exceptions Attribute
- [ ] 4.7.6. The InnerClasses Attribute
- [ ] 4.7.7. The EnclosingMethod Attribute
- [ ] 4.7.8. The Synthetic Attribute
- [ ] 4.7.9. The Signature Attribute
- [ ] 4.7.9.1. Signatures
- [ ] 4.7.10. The SourceFile Attribute
- [ ] 4.7.11. The SourceDebugExtension Attribute
- [ ] 4.7.12. The LineNumberTable Attribute
- [ ] 4.7.13. The LocalVariableTable Attribute
- [ ] 4.7.14. The LocalVariableTypeTable Attribute
- [ ] 4.7.15. The Deprecated Attribute
- [ ] 4.7.16. The RuntimeVisibleAnnotations Attribute
- [ ] 4.7.16.1. The element_value structure
- [ ] 4.7.17. The RuntimeInvisibleAnnotations Attribute
- [ ] 4.7.18. The RuntimeVisibleParameterAnnotations Attribute
- [ ] 4.7.19. The RuntimeInvisibleParameterAnnotations Attribute
- [ ] 4.7.20. The RuntimeVisibleTypeAnnotations Attribute
- [ ] 4.7.20.1. The target_info union
- [ ] 4.7.20.2. The type_path structure
- [ ] 4.7.21. The RuntimeInvisibleTypeAnnotations Attribute
- [ ] 4.7.22. The AnnotationDefault Attribute
- [ ] 4.7.23. The BootstrapMethods Attribute
- [ ] 4.7.24. The MethodParameters Attribute
- [ ] 4.8. Format Checking
- [ ] 4.9. Constraints on Java Virtual Machine Code
- [ ] 4.9.1. Static Constraints
- [ ] 4.9.2. Structural Constraints
- [ ] 4.10. Verification of class Files
- [ ] 4.10.1. Verification by Type Checking
- [ ] 4.10.1.1. Accessors for Java Virtual Machine Artifacts
- [ ] 4.10.1.2. Verification Type System
- [ ] 4.10.1.3. Instruction Representation
- [ ] 4.10.1.4. Stack Map Frame Representation
- [ ] 4.10.1.5. Type Checking Abstract and Native Methods
- [ ] 4.10.1.6. Type Checking Methods with Code
- [ ] 4.10.1.7. Type Checking Load and Store Instructions
- [ ] 4.10.1.8. Type Checking for protected Members
- [ ] 4.10.1.9. Type Checking Instructions
- [ ] 4.10.2. Verification by Type Inference
- [ ] 4.10.2.1. The Process of Verification by Type Inference
- [ ] 4.10.2.2. The Bytecode Verifier
- [ ] 4.10.2.3. Values of Types long and double
- [ ] 4.10.2.4. Instance Initialization Methods and Newly Created Objects
- [ ] 4.10.2.5. Exceptions and finally
- [ ] 4.11. Limitations of the Java Virtual Machine
- [ ] 5. Loading, Linking, and Initializing
- [ ] 5.1. The Run-Time Constant Pool
- [ ] 5.2. Java Virtual Machine Startup
- [ ] 5.3. Creation and Loading
- [ ] 5.3.1. Loading Using the Bootstrap Class Loader
- [ ] 5.3.2. Loading Using a User-defined Class Loader
- [ ] 5.3.3. Creating Array Classes
- [ ] 5.3.4. Loading Constraints
- [ ] 5.3.5. Deriving a Class from a class File Representation
- [ ] 5.4. Linking
- [ ] 5.4.1. Verification
- [ ] 5.4.2. Preparation
- [ ] 5.4.3. Resolution
- [ ] 5.4.3.1. Class and Interface Resolution
- [ ] 5.4.3.2. Field Resolution
- [ ] 5.4.3.3. Method Resolution
- [ ] 5.4.3.4. Interface Method Resolution
- [ ] 5.4.3.5. Method Type and Method Handle Resolution
- [ ] 5.4.3.6. Call Site Specifier Resolution
- [ ] 5.4.4. Access Control
- [ ] 5.4.5. Overriding
- [ ] 5.5. Initialization
- [ ] 5.6. Binding Native Method Implementations
- [ ] 5.7. Java Virtual Machine Exit
- [ ] 6. The Java Virtual Machine Instruction Set
- [ ] 6.1. Assumptions: The Meaning of "Must"
- [ ] 6.2. Reserved Opcodes
- [ ] 6.3. Virtual Machine Errors
- [ ] 6.4. Format of Instruction Descriptions
- [ ] 6.5. Instructions
- [ ] 7. Opcode Mnemonics by Opcode
