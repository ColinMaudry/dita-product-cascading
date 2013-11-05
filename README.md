DITA product cascading demonstration
======================

This project aims at demonstrating how DITA features enable the cascading of product documentation and characteristics.

The features such as keys, conkeyref and conref push are used to:

* cascading the content and the characteristics from the most general product definitions to the most specific ones
* same thing, but for the components
* the product characteristics (values) are available to the author via variables (conkeyref)
* the information and the document structure are separated. The same information can be reused in multiple document structures, the document map just need to import (mapref) the necessary information module (map).
  
I have made up the information content of this demo. The content describes a range of cars, the Forrester range. The structure of the modules is represented here: https://www.lucidchart.com/documents/view/474c-c584-5087ba4c-8f89-1ba10a40476b

This project is licensed under the terms of the GNU General Public License 3. It applies to both the demo content and to the model it illustrates. In practice, in means you can use and adapt both the demo content and the model in your product, including commercial products, as long as you mentioned that I'm the original author, with a link to the project home page. 

## Spotted limitations (confirmed)

* If a key reference is included in an element or a block that is conref pushed, it is not resolved (the issue https://github.com/dita-ot/dita-ot/issues/1572).
* If an element A is pushed inside a block/element B that is also conref pushed, element A is not pushed (the issue https://github.com/dita-ot/dita-ot/issues/1573).

 
