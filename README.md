# CERIF Scholarly Publications Module

A module to represent scholarly publications in the refactored CERIF.
Its secondary purpose is to demonstrate the liason between the [CERIF Core](https://github.com/EuroCRIS/CERIF-Core) and a module.

## Status

(2021-07-06) Experimental.

## Scope

The Scholarly Publications Module consists of the following entities:
* [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md) (imported from [the CERIF Core](https://github.com/EuroCRIS/CERIF-Core))
  * [Textual Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Textual_Document.md) (imported from [the CERIF Core](https://github.com/EuroCRIS/CERIF-Core))
     * [Journal Article](./entities/Journal_Article.md)
     * [Monograph](./entities/Monograph.md)
* [Journal](./entities/Journal.md)
* [Contributorship](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contributorship.md) (imported from [the CERIF Core](https://github.com/EuroCRIS/CERIF-Core))
  * [Editorship](./entities/Editorship.md)
  * [Publishership](./entities/Publishership.md)
* [Contribution Statement](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contribution_Statement.md) (imported from [the CERIF Core](https://github.com/EuroCRIS/CERIF-Core))
  * [CRediT Contribution Statement](./entities/CRediT_Contribution_Statement.md)
* [Textual Document Accessibility Specification](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Textual_Document_Accessibility_Specification.md) (imported from [the CERIF Core](https://github.com/EuroCRIS/CERIF-Core))
  * [COAR Accessibility Specification v1.0](./entities/COAR_Accessibility_Specification_v_1_0.md)
    * [Open Access](./entities/Open_Access_COAR_Accessibility_Specification_v_1_0.md)
    * [Restricted Access](./entities/Restricted_Access_COAR_Accessibility_Specification_v_1_0.md)
    * [Embargoed Access](./entities/Embargoed_Access_COAR_Accessibility_Specification_v_1_0.md)
    * [Metadata Only Access](./entities/Metadata_Only_Access_COAR_Accessibility_Specification_v_1_0.md)
    

And the following data types:
* [ISBN](./datatypes/ISBN.md)
* [ISSN](./datatypes/ISSN.md)
* CRediT
  * [Role Type](./datatypes/CRediT_Role_Type.md)
  * [Degree of Contribution](./datatypes/CRediT_Degree_of_Contribution.md)

## Illustrative Diagrams
![The module diagram](./diagrams/module.svg)

![The example diagram](./diagrams/example.svg)

## Usage note
This module cannot be used without the core.
The module includes the following examples:
* [Journal Article](./examples/Journal_Article_Example1.md)
* ...

## Development

This module relies on the [CERIF-Core](https://github.com/EuroCRIS/CERIF-Core): we include some shared [entities](https://github.com/EuroCRIS/CERIF-Core/tree/main/entities) and [datatypes](https://github.com/EuroCRIS/CERIF-Core/tree/main/datatypes) from it and we also re-use the [building environment](https://github.com/EuroCRIS/CERIF-Core/tree/main/tools) for the diagrams. This module is developed in line with the [guidelines](https://github.com/EuroCRIS/CERIF-Core/tree/main/guidelines).
