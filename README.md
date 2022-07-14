# CERIF Scholarly Publications Module

A module to represent scholarly publications in the refactored CERIF.
Its secondary purpose is to demonstrate the liason between the [CERIF Core](https://github.com/EuroCRIS/CERIF-Core) and a module.

## Status
(2021-07-06) Experimental.

## Overview
Scholarly publications are:
* [Journal Articles](./entities/Journal_Article.md) appearing in [Journals](./entities/Journal.md)
* [Monographs](./entities/Monograph.md)
* ...

Four basic [accessibility specifications](./entities/COAR_Accessibility_Specification_v_1_0.md) are defined:
[Open Access](./entities/Open_Access_COAR_Accessibility_Specification_v_1_0.md),
[Embargoed Access](./entities/Embargoed_Access_COAR_Accessibility_Specification_v_1_0.md),
[Restricted Access](./entities/Restricted_Access_COAR_Accessibility_Specification_v_1_0.md) and
[Metadata Only Access](./entities/Metadata_Only_Access_COAR_Accessibility_Specification_v_1_0.md).

[Authorships](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Authorship.md) (imported from [the CERIF Core](https://github.com/EuroCRIS/CERIF-Core))
can be accompanied by [CRediT Contribution Statements](./entities/CRediT_Contribution_Statement.md).

Next to Authorship, this module also defines the contributions of [Editorship](./entities/Editorship.md) and [Publishership](./entities/Publishership.md).

[Reviewing manuscripts](./entities/Manuscript_Review_Activity.md) is another important type of Activity.
There are basically three main [Outcomes of such reviews](./entities/Manuscript_Review_Outcome.md): 
[Suggestion to publish as is](./entities/Manuscript_Suggestion_to_Publish_As_Is.md),
[Suggestion to publish with revisions](./entities/Manuscript_Suggestion_to_Publish_with_Revisions.md) and
[Suggestion to not publish](./entities/Manuscript_Suggestion_to_Not_Publish.md).

## Listings

### Entities
The Scholarly Publications Module consists of the following entities:
* [Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Document.md) (imported from [the CERIF Core](https://github.com/EuroCRIS/CERIF-Core))
  * [Textual Document](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Textual_Document.md) (imported from [the CERIF Core](https://github.com/EuroCRIS/CERIF-Core))
     * [Journal Article](./entities/Journal_Article.md)
     * [Monograph](./entities/Monograph.md)
* [Journal](./entities/Journal.md)
* [Contribution](https://github.com/EuroCRIS/CERIF-Core/blob/main/entities/Contribution.md) (imported from [the CERIF Core](https://github.com/EuroCRIS/CERIF-Core))
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
* [Manuscript_Review_Activity](./entities/Manuscript_Review_Activity.md)
* [Manuscript_Review_Outcome](./entities/Manuscript_Review_Outcome.md)
  * [Manuscript_Suggestion_to_Publish_As_Is](./entities/Manuscript_Suggestion_to_Publish_As_Is.md)
  * [Manuscript_Suggestion_to_Publish_with_Revisions](./entities/Manuscript_Suggestion_to_Publish_with_Revisions.md)
  * [Manuscript_Suggestion_to_Not_Publish](./entities/Manuscript_Suggestion_to_Not_Publish.md)

### Data Types
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
