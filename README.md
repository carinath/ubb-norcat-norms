# ubb-norcat-norms

This is a set of [normalization rules](https://knowledge.exlibrisgroup.com/Alma/Product_Documentation/010Alma_Online_Help_(English)/Metadata_Management/016Working_with_Rules/020Working_with_Normalization_Rules) (norms) for cataloging workflows in Ex Libris Alma.
Ubb-norcat-norms can be used to change bibliographic records imported from exernal resources. This set of normalization rules are customized according to [RDA and Norwegian cataloging rules](https://rdakatalogisering.sikt.no/) and language. The norms can be freely copied and customized to other languages and cataloging spesifications, or simply just function as inspiration for a further exploration of normalization rules in Alma. 

## Why use norms?

At the University of Bergen Library, catalogers primarily spend time cataloging non-Norwegian materials in Alma. Bibliographic records for Norwegian publications are supplied from the National Library of Norway. 

Therefore, our catalogers mostly work with bibliographic records imported from external catalogs in Alma, such as LOC, BNB and DNB, and correct these according to Norwegian RDA cataloging and language. By applying Ubb-norcat-norms, catalogers can spend less time on fixing small formal details, and instead focus on metadata enrichment.

## What it does

Ubb-norcat-norms transforms imported bibliographic records to records following Norwegian cataloging rules. Some of the functions include:
* Translating common words and expressions to Norwegian ("paperback" to "heftet, "Includes bibliographic references (p. 162-189)" to "Bibliografi: side 162-189" (and much more)). Mainly from English, Swedish and German, but more translations will be included in updated versions.
* Deleting redundant fields and subfields
* Creating missing fields and subfields 
* Copying information from one field or subfield to another
* Correcting various indicators and control fields
* Removing ISBD-punctuation
* Other small functions not mentioned (see the code for a full overview)

### Example

![Example](/images/ubb-norcat-norms_example.PNG?raw=true)

(Result after applying ubb-norcat-norms to the right)

**Note: The norms cannot be used as an alternative to cataloging. A lot of repetative actions are automated, but the norms does not check if the data in imported records are correct. All records must still be controlled by a skilled professional ;-)**

## How to use ubb-norcat-norms

The norms can be used in various ways. 
For Norwegian libraries in the BIBSYS-consortia, the norms can easily be used on imported records in two ways:
1. Use the Enhance Record-function in MDE and choose "UBB-hylleklare bøker"
   or,
2. Open split mode in MDE, with the bibliographic record on one side, choose Rules on the other and search "UBB-hylleklare bøker". This will enable you to preview the changes before applying the norms. **Important! Do NOT change the code directly in "UBB-hylleklare bøker"**

We recommend that the norms are applied to records manually by one of these two methods (in other words, **not** used as an automatic import filter in Alma). This is because a "one record at a time"-apporach allows us to discover new field variants that require updates and improvements in the code.

For libraries outside the consortia it is possible to copy the latest version from [versions](https://github.com/carinath/ubb-norcat-norms/tree/main/versions). Feel free to save a local copy and modify as needed :-)

## Webinar recording

There is a webinar recording for Norwegian speakers about ubb-norcat-norms [(click here to watch on Sikt's site)](https://vimeo.com/930617948).

 ## Need help?

 For technical issues or help see [Ex Libris' site](https://knowledge.exlibrisgroup.com/Alma/Product_Documentation/010Alma_Online_Help_(English)/Metadata_Management/016Working_with_Rules/020Working_with_Normalization_Rules). Ideas or need an update in the  version available in the the BIBSYS-consortia network? Contact [Carina](https://www.uib.no/personer/Carina.Thornes) at The University of Bergen Library. 





