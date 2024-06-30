# Modules and packages
### Foundation
1.  <details>
    <summary>Why we need modules?</summary>

    * Instead of putting codes into single file, we can put related code into separate files called modules. This helps the organisation of a large code base. 

    * Serveral modules are organised into a package.
    
    * The organisation into modules and packages help in many ways:
      
      * **Simplicity** Modules focus on single problem. 
      * **Maintainability** It is easier to maintain smaller files. 
      * **Reusability** Code could be reused by different applications. 
      * **Scoping** Modules have their own namespaces.   
    </details>

2.  <details>
    <summary>What are namespaces and scopes?</summary>

    * Namespace is a collection of currently defined symbolic names along with information about the object each name references.
    
      * There are 4 types of namespaces: Built-In, Global, Enclosing, and Local.
      
      * An analogy is the country code of telephone numbers. To dial a telephone number accross countries, we need to prefix a national telephone number with its country code. That national number is supposed to be recognised for any caller within the same country (or within the same namespace)  
    
    * Scopes: The scope of a name is a region of a program in which that name has a meaning. The meaning is determined by the intepreter at runtime depending on:
    
      * Where the name definition occurs
      * Where in the code the name is referred.  
    </details>