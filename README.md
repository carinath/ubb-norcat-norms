# ubb-norcat-norms

This is a set of [normalization rules](https://knowledge.exlibrisgroup.com/Alma/Product_Documentation/010Alma_Online_Help_(English)/Metadata_Management/016Working_with_Rules/020Working_with_Normalization_Rules) (norms) for cataloging workflows in Ex Libris Alma.
Ubb-norcat-norms can be used to change bibliographic records imported from exernal resources. This set of normalization rules are customized according to RDA and Norwegian cataloging rules and language.

## What it does

Ubb-norcat-norms transforms imported bibliographic records to records following Norwegian cataloging rules. Some of the functions include:
* Translating common words and expressions to Norwegian ("paperback" to "heftet, "Includes bibliographic references (p. 162-189)" to "Bibliografi: side 162-189" (and much more)). Mainly from English, Swedish and German, but more translations will be included in updated versions.
* Deleting redundant fields
* Correcting various indicators and control fields
* Removing ISBD-punctuation
* Other small functions not mentioned (see the code for a full overview)

**Note: The norms cannot be used as an alternative to cataloging. A lot of repetative actions are automated, but the norms does not check if the data in imported records are correct. All records must still be controlled by a skilled professional ;-)**

## How to use ubb-norcat-norms

The norms can be used in various ways. 
For Norwegian libraries in the BIBSYS-consortia, the norms can easily be used on imported records in two ways:
1. Use the Enhance Record-function in MDE and choose "UBB-hylleklare bøker"
   or,
2. Open split mode in MDE, with the bibliographic record on one side, choose Rules on the other and search "UBB-hylleklare bøker". This will enable you to preview the changes before applying the norms. **Important! Do NOT change the code directly in "UBB-hylleklare bøker"**

For libraries outside the consortia it is possible to copy the latest version from [versions](https://github.com/carinath/ubb-norcat-norms/tree/main/versions). Feel free to save a local copy and modify as needed :-)

 ## Suggested workflow

![Suggested workflow](/images/ubb-norcat-norms_workflow.PNG?raw=true)

 ## Need help?

 For technical issues or help see [Ex Libris' site](https://knowledge.exlibrisgroup.com/Alma/Product_Documentation/010Alma_Online_Help_(English)/Metadata_Management/016Working_with_Rules/020Working_with_Normalization_Rules). Ideas or need an update in the  version available in the the BIBSYS-consortia network? Contact [Carina](https://www.uib.no/personer/Carina.Thornes) at The University of Bergen Library. 





