# Spatio-Temporal Collaboration Questionnaire (STCQ)

The purpose of this self-constructed questionnaire is to support the empirical evaluation of collaborative aspects within the context of virtual environments and human-computer interaction.

### Table of contents
* [Scientific Reference, and further information](#Scientific-Reference)
* [Questionnaire Composition](#Questionnaire-Composition)
* [How to use](#How-to-use)
* [Disclaimer](#Disclaimer)
* [References](#References)
* [License](#License)

## Scientific Reference

The questionnaire presented here has been introduced and used within the following scientific publication:

* Nico Reski, Aris Alissandrakis, and Andreas Kerren. An Empirical Evaluation of Asymmetric Synchronous Collaboration Combining Immersive and Non-Immersive Interfaces Within the Context of Immersive Analytics. *Frontiers in Virtual Reality*, 2:743445:1-29, 17 January 2022. DOI: [10.3389/frvir.2021.743445](https://doi.org/10.3389/frvir.2021.743445)

For any re-use, remix, and further adaptation, please cite the above stated publication.

#### Background / Motivation

Some of our research interests evolve around the interaction and collaboration in immersive virtual environments for the purpose of data analysis and meaning making, a research area commonly referred to as *Collaborative Immersive Analytics*.
In order to aid some of our empirical evaluations in regard to the investigation of collaborative aspects within that context, we ended up designing this questionnaire, derived and adopted from the conceptual collaboration dimensions described by Churchill and Snowdon (1998), Snowdon et al. (2001) respectively.

## Questionnaire Composition

The current version of questionnaire is thematically structured around the following four conceptual dimensions for collaboration in virtual environments as adopted from Churchill and Snowdon (1998):

* *Transitions between Shared and Individual Activities (TSIA)*: The interplay between individual and group efforts, including the ability to switch between these, within the scope of collaborative work.
* *Negotiation and Communication (NC)*: Verbal conversation (i.e., talk) facilitated through the ability of utilizing nonverbal information cues in order to discuss and interpret any task-related aspects of the activity (e.g., findings in the data, roles and structure of task approach, and so on).
* *Sharing Context (SC)*: Characteristics and features of the shared space that facilitate and support focused and unfocused collaborative work, leading to shared understandings.
* *Awareness of Others (AO)*: The ability to understand your partner's activity during times of (1) focused collaboration and active communication (i.e., group efforts), as well as (2) more independent and individual work.

Each thematic questionnaire section contains a number of relevant 5-point Likert scale statements / questions. This allows for quantitative analysis of the assessments as self-reported by the users. Note that there are a total of five different Likert scales used throughout the questionnaire, each appropriate to their respective statement / question.
 
## How to use

The questionnaire is intended to be completed by each collaborator independently of each other post-task completion, i.e., after the exposure with the to be evaluated collaborative system. The analysis and presentation of the collected answers are to be evaluated according to common data analysis practices. There is no overall collaboration score or alike. The results are to be interpreted contextually (1) within the four different dimensions, and (2) with respect to the design considerations and objectives of the evaluated collaborative system, e.g., to examine if the designed system enabled the users to collaborate as anticipated. 

#### Source Files

The file `stqc-template.pdf` contains a pre-compiled, generalized version of the questionnaire, that should enable the practitioner to apply the questionnaire *as is* without any additional changes.

The directory `src_latex` contains the LaTeX source files used to compile the questionnaire as presented in `stqc-template.pdf`. This should allow the practitioner to further customize, adopt, and extend the original questionnaire according to their desire. The individual Likert scale graphics (in `.pdf` file format) have been manually created using a graphics editor, and using the `Avenir Next` font family for the item labels.

##  Disclaimer

The Spatio-Temporal Collaboration Questionnaire was originally created to aid one of our empirical evaluations, investigating a collaborative system that consists of an immersive virtual reality and a non-immersive desktop application. Pairs of participants in our user interaction study used the collaborative system to explore a spatio-temporal dataset and complete a confirmative analysis task with no time limitations. The questionnaire enabled us to investigate aspects of the pairs' collaboration during the task completion.

As the questionnaire was useful within the scope our investigation, we believe that it could also be useful for other practitioners that aim to investigate similar matters, either as is or as a starting point to further adopt and extend the questionnaire. For further information about the questionnaire, including results analysis, presentation, and discussion within the scope of our investigation, please refer to the scientific reference listed at the top of this document.

## References

* Elizabeth F. Churchill and David Snowdon. Collaborative Virtual Environments: An Introductory Review of Issues and Systems. *Virtual Reality*, 3(1):3–15, March 1998. DOI: [10.1007/BF01409793](https://doi.org/10.1007/BF01409793)
* Dave Snowdon, Elisabeth F. Churchill, and Alan J. Munro. Collaborative Virtual Environments: Digital Spaces and Places for CSCW: An Introduction. In Elisabeth F. Churchill, David N. Snowdon, and Alan J. Munro, editors, *Collaborative Virtual Environments: Digital Places and Spaces for Interaction*, Computer Supported Cooperative Work (CSCW), pages 3–17. Springer, London, 2001. DOI: [10.1007/978-1-4471-0685-2_1](https://doi.org/10.1007/978-1-4471-0685-2_1)

## License
MIT License, see [LICENSE.md](LICENSE.md)

