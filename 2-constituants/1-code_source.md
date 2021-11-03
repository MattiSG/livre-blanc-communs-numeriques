# Source Code

Digital services are primarily software. Even if by definition they cannot be reduced to this technical essence, their primary nature is the execution of computer code. This code, in a readable and executable form, is therefore an obvious component to share.

## Free License

The rules applicable to a source code are set out in licenses, that is to say contracts by which the copyright holder defines the conditions under which this program may be used, distributed or modified. Certain types of licenses, such as free licenses, guarantee rights to the public: reading, duplication and redistribution. These rights therefore prevent the re-appropriation of the existing material.

**A minimum constraint is that the source code be made available under a free license\[^9].**

**Operational recommendation: use an EUPL license or one of the licenses mentioned in article **[**D323-2-1 of the Code des relations entre le public et l'administration (CRPA)**](https://is.gd/rYk7h7)**.**

## Re-Sharing Clause <a href="re-sharing" id="re-sharing"></a>

Nevertheless, the digital commons cannot be reduced to software. As we have seen, their specificity comes from the existence of a _community_. It is this community gathered around the software that must be preserved in order to avoid re-appropriation, either active or by desertion of the community except by one actor.

Active re-appropriation can only be prevented by the implementation of a re-sharing clause \[Aigrin, 2002]. Such a clause ensures that improvements to the software are made available to the community, by making it mandatory to publish changes to the source code. In the absence of such a clause, simply taking the source code of software that are part of digital commons and adding a feature attractive to users without sharing the code that adds said feature \[Aigrin, 2002] is enough to move the community to this new version \[Verdier & Murciano, 2015]. The new version, no longer governed by a commons, thereby deprives the original commons of its substance. A re-sharing license is therefore the most suitable license for the contributory commons.

**For contributory services, the license includes the provision of source code with a re-sharing clause.**

**Operational recommendation: use an Affero GNU Public License 3.**

## Integrating Solicitation <a href="integration-solicitation" id="integration-solicitation"></a>

Beyond usage, the ability of users to contribute to the service must be preserved. The use of free licenses guarantees the right to modify the code, but contribution also means the systematic evaluation of these modifications and their integration whenever relevant. Without this ability to contribute, open source software are just another form of monologue.

**A minimum constraint is to provide a means of soliciting the integration of changes made by a contributor into the original code base.**

**Operational recommendation: use tools that specialise in collaborative development, which provide a consolidated platform for both code availability and contribution of code, and suggestions for improvements, such as **[**Framagit**](https://framagit.org)**, **[**GitLab**](https://about.gitlab.com)** or **[**GitHub**](https://github.com)**.**

## Commitments on Integrations <a href="delay-processing" id="delay-processing"></a>

As with usage, the "contributability" of the commons cannot be measured solely by the technical capacity to request the integration of modifications. A contributor whose requests are never answered will quickly become frustrated and stop contributing, and the public visibility of this lack of response will discourage others.

**It is useful to commit to a time frame for processing\[^10] integration requests and to a communication charter\[^11] with potential contributors, to ensure an open and engaging atmosphere.**

**Operational recommendation: establish and publish rules of procedure describing how to handle requests for integration of modifications\[^12].**

## Documentating Operations <a href="ops" id="ops"></a>

Also with this objective in mind, the technical methods that allow the service to be operated, in terms of its system administration, should be documented and shared in the same way as the source code. Indeed, if just a single person (natural or legal) knows about the infrastructure needed to operate the service, there is a risk of re-appropriation.

**A minimum constraint is to provide documentation on the technical operation of the service.**

**Operational recommendation: document in an executable way through a **[**configuration management system**](https://fr.wikipedia.org/wiki/Gestion\_de\_configuration\_logicielle)**, which allows the infrastructure to be defined as code.**

\[^9]: Exhaustive list available at [opensource.org/licenses/alphabetical](http://opensource.org/licenses/alphabetical).

\[^10]: "Processing" does not necessarily mean integrating, but at least making an initial evaluation of whether the contribution is welcome, or justifying the rejection of its integration by providing references for improving future contributions. This delay should be as short as possible: beyond a few days, the feeling is no longer one of discussion, and the community is lost.

\[^11]: Such charters are generally referred to as _code of conduct_.

\[^12]: See also "How to acknowledge contributions" in the appendix.
