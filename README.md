DITA product cascading demonstration
======================

This project aims at demonstrating how DITA features enable the cascading of product documentation and characteristics.

The features such as keys, conkeyref and conref push are used to:

* cascading the content and the characteristics from the most general product definitions to the most specific ones
* same thing, but for the components
* the product characteristics (values) are available to the author via variables (conkeyref)
* the information and the document structure are separated. The same information can be reused in multiple document structures, the document map just need to import (mapref) the necessary information module (map).
  
I have made up the information content of this demo. The content describes a range of cars, the Forrester range. The structure of the modules is represented here: https://www.lucidchart.com/documents/view/474c-c584-5087ba4c-8f89-1ba10a40476b
  
# Spotted limitations (to be confirmed)

* If a key reference is included in an element or a block that is conref pushed, it is not resolved.
* If an element A is pushed inside a block/element B that is also conref psuhed, element A is not pushed.

 
