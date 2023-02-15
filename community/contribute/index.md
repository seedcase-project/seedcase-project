---
title: "Overview"
---

{{< include ../../includes/_wip.qmd >}}

![Project blocks that make up the seedcase
project.](/images/project-blocks.svg){width="70%"}

While the core of the seedcase project is the seedcase software
"Product" itself, it depends on the proper functioning of additional
"blocks". The seedcase Product relies on the two foundation layers,
which are the "Documentation" about the Product and its use as well as
the "Culture and Collaboration" that enables both Documentation and
Product to be developed. Supporting all these layers are the support
structures that tell "How" and "Why" things are done.

## Product block

The Product only exists because of the two bottom layers and the
supports. More details about the Product are found in its own GitHub
repository (not created yet).

```{=html}
<!--
Use later on when we've started building the product?

-   pipeline/ (automatic processes for tasks, like rebuilding changelog
    etc)
-   api/
-   common-data-model/setup.\*
-   common-data-model/update.\*
-   build-data-model
-   update-data-model
-   build-changelog
-   update-changelog
-   generate-data-doi
-   update-
-   Matrix/Pathways
    -   Four users
    -   Three layers
-   Connectors
    -   R
    -   Python
    -   Bash/shell
    -   RedCap
Installation

-   installing.md
-->
```
## Documentation block

This block contains multiple components, related to the overall project,
to user-friendly usage documents, and to technical details about the
software itself.

For the project itself, those are found in the [About](/about/index.md)
pages or in the `about/` folder in the GitHub repository. This includes
the contact, history of the project, governance, mission, and the
purpose.

For the Product itself, documents describe the design and architecture,
such as the programmatic pathways between user input to the backend of
the infrastructure. These details are found in the
[Design](/design/index.md) pages (or in the `design/` folder on the
GitHub repository).

In addition to the these documentation sources, there will also be
tutorials and usage instructions in the [Usage](/usage/index.md) section
(`/usage/` folder). More detail will be added later.

## Culture and collaboration block

The culture and collaboration block forms the foundation of the entire
project. Without this, none of the other blocks can exist. There are two
components to this block: the informal and formal.

Culture in general is something that is organic and develops on its own.
It can be difficult to document or make explicit. Depending on the
specific social dynamics of the team, of internal collaborators, and of
external contributors, culture can change quite a bit. Much of these
dynamics might happen through other channels like in-person activities,
Issue discussions, or on online communication platforms like Discord).
However, a healthy culture requires some self-awareness,
self-reflection, and ultimately some self-regulation to stay healthy.

The formal component of culture and collaboration mostly deals with
logistical and organizational aspects, like where and how often we meet
(virtually), how we do meetings, how we coordinate work tasks and
milestones, what expectations there are for working together (for
instance during co-working sessions), and how we do work. There is some
back-and-forth between this component and the Support blocks, with the
Support blocks informing on, and than being refined by, how the culture
should be and how we collaborate.

The informal component is almost entirely about the spontaneous social
dynamics and interactions, but also can be about things people might
learn about or think might be interesting to share with others. For
things we want to share, we will try to (very informally) put them in a
document in the [Community Posts](/community/posts.md) section (in the
`community/posts.md` and `community/posts/` files). This will be things
like sharing new tools, knowledge gained from a course or conference, or
other things that might come up.

Depending on what gets written in these documents, we might convert them
into something more official, like publishing in an outlet.

## "Why" support block

This support block contains explanations and justifications for why we
choose the technologies, workflows, and designs that we do. This is not
just for the Product itself, but also for the Documentation and Culture
and Collaboration. Files and content related to this support block are
found in [Design Decisions](/design/decisions.md) (files in
`design/decisions/`) and [Contributing
Decisions](/community/contribute/decisions.md) (files in
`community/contribute/decisions/`).

## "How" support block

The "How" Support block is the more technical aspects of how this
project is managed (in the [Governance](/community/GOVERANCE.md)
document), how to contribute (in the
[Contributing](/community/CONTRIBUTING.md) document), and what are
expected behaviours (in the [Code of
Conduct](/community/CODE_OF_CONDUCT.md) document). More detail is found
in the [Community](/community/index.md) page.