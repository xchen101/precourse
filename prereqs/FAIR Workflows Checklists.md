# Guide for researchers to implement FAIR workflows

Conventional research practice tends to withhold the procedural documents, supporting datasets, and other relevant materials generated during the research process, relegating them as distractions from the primary focus of scientific papers: the presentation of results. However, the limitations of this approach have become increasingly apparent due to phenomena such as 'publish or perish,' the reproducibility crisis, and academic fraud. In response, the research community is advocating for greater accountability, transparency, and openness. This call is being met by various initiatives across disciplinary domains, all aimed at making research data and supporting resources FAIR: findable, accessible, interoperable, and reusable.

| Benefits of incorporating FAIR Workflows in the research process Collaboration: Science thrives on collaboration. Even when working independently, your research can benefit others. Sharing work, processes, results, and providing context to make them FAIR are the initial steps toward fostering successful collaboration. Crediting: Every stage of research merits recognition. By showcasing the extensive work throughout the research process, including creating tangible outputs and attributing them to the individuals and organizations involved, we can effectively acknowledge contributions and demonstrate impact. Compliance: Adhering to best practices is essential. Planning and executing each stage of research with FAIR principles in mind helps navigate policies and requirements from institutes, funders, and collaborators. This proactive approach streamlines data sharing, reporting, and preservation efforts. |
| :---- |

Persistent identifiers (PIDs) are central to achieving FAIR and Open research. These identifiers play a crucial role in facilitating the discoverability, provenance tracking, and preservation of research outputs. By utilizing PIDs and standardized metadata in the sharing process, researchers can effectively describe and connect their outputs, thereby enhancing their FAIRness.

| A primer of the FAIR principles[^1] for researchers Making scholarly works Findable involves making them available as scholarly records, ensuring they can be indexed and searched. The most comprehensive index for scholarly works is generated from DOI metadata. Making scholarly works Accessible entails providing a pathway to make the work available to others. This can be achieved by depositing the work in a scholarly repository or utilizing platforms that host works and facilitate DOI registration for completed work. Making scholarly works Interoperable means describing them with standardized metadata and creating meaningful links among related works so that they can be incorporated into different technical and domain environements \- this can be done by indicating relationships to other works during the sharing/deposition process. Making scholarly works Reusable means providing sufficient context for each individual work so that they can be understood and responsibly applied in subsequent research \- this requires outputs be annotated with licensing, provenance, and community standards information in their PID metadata.  |
| :---- |

This guide serves as a practical resource for researchers, offering insights into how to manage and share their work effectively during the research process. It emphasizes leveraging open scholarly infrastructure, such as PIDs and metadata, to ensure that research outputs are FAIR. Included are checklists designed to help researchers navigate the available PIDs for different output types at each stage of the research process, as well as guidance on effectively utilizing PID metadata to annotate outputs for proper description and linkage. 

| Research stage | Why | What | Tools that support creation and sharing of outputs and this stage | How to share FAIR(ly) |
| :---- | :---- | :---- | :---- | :---- |
| Project planning | Provide a shared understanding for expected FAIR practice in the project Create points of reference through which all relevant outputs of the project can be linked and discovered | Project page Data management plan | OSF DMPTool/ARGO | Take advantage of tools/platforms that are integrated with open infrastructure to create and share outputs Register DOIs for each output Use PIDs to reference related people, organizations, and resources in the metadata |
| Method planning  | Enhance reproducibility  Increase credibility and create guardrail against bad practice | Preregistration Metadata template | OSF, ASpredicted CEDAR Selected journals  | All of the above, and Reference project and/or DMP in the DOI metadata when registering new outputs |
| Experimentation and analysis | Follow up on the registered activities and mark deviations  Create robust records to supplement research outcome Credit all contributors in the research process | Experimental protocols Code and software Dataset  | protocols.io Brainlife.io Dryad, Zenodo Domain data repos e.g. OpenNeuro, Ebrains | All of the above, and  Reference corresponding registration in the DOI metadata when registering new outputs Create reference among related data/code/protocol in the metadata |
| Dissemination | Expedite dissemination of project outputs Invite community engagement and feedback Lower barrier of access | Preprint  Presentation slides Paper  | General purpose repos e.g. Zenodo/Figshare Preprint servers e.g. bioRxiv, PsyArXiv  OA publishing manager e.g. ChronosHub Most journal publishers | All of the above, and Cite shared outputs by their DOIs in manuscripts and presentations |

The what why hows of FAIR sharing throughout the research process.

In order to achieve FAIR principles, it's crucial for researchers to make certain research objects, typically hidden away, available as reusable outputs.

This means in addition to publishing a paper, researchers make available a corpus of outputs generated during the project to support the claims in the paper, distribute credits to all contributors, and provide reuse value for the community. These resources benefit the broader scholarly community when they are shared, identified, and linked together.

The checklists below lay out steps to make research outputs FAIR using PIDs and metadata. They are arranged by the main stages of the research process. Check the different actions to take in order to: create key points of reference for people, organization, funding; keep authorship, contributorship unambiguously acknowledged; establish relationships among outputs to provide contexts for reuse; and cite the outputs the same way literature is cited in publications.

## What are the recommended PIDs and how to link them

### Identifying resources and outputs 

The Digital Object Identifier (DOI) system was designed to keep track of content online, and DOIs have been used to enable the reference and linking of scholarly content since two decades \- first by Crossref to support mainly scholarly literature, then by DataCite to support datasets and other types resources. DOI registration/ creation is supported by most publishing and open sharing platforms through the integration with Crossref or DataCite. Through these submission workflows, standardized metadata are created, stored openly and permanently, thus becoming part of the global corpus of scholarly record. The DOI registration process is either overlooked by the publisher, or in the case of self-deposition for open sharing, by the researchers themselves. 

### Identifying researchers

The most prevalently adopted researcher identifier, both by researchers and research supporting systems, is the Open Researcher and Contributor ID (ORCID). When submitted with scholarly works for open sharing or publishing, ORCID IDs can be embedded to the DOI metadata of the works, linking the researcher to their outputs. This will rely on the publishing system to integrate with both ORCID and DOI systems, for researchers this means creating ORCID IDs (if you don’t have one already), providing the ORCID iDs for all authors and contributors during the output submission process, and authorizing the publishing platform/ repository to populate your ORCID record whenever a new work is published/ shared with your ORCID attached. ORCID, along with many platforms also support the further specification of contributor role information, providing this information is important for fair crediting of researchers. 

### Identifying organizations

The Research Organization Registry (ROR) is a registry for research organizations, providing open PIDs (ROR ID) for organizations to connect them to researchers and research outputs. When creating metadata for scholarly works during the submission process, ROR IDs can be used for unambiguous identification of affiliation of researchers, funders of the project or work, or other prominent roles involved in the creation of publication of scholarly works. 

### Linking researcher, organization, and outputs

The most reliable way to create links among entities, is to create PIDs for the outputs, and embed identifiers of related entities in the metadata of the published/shared outputs. In practice, researcher have the opportunity to contribute to the creation and enrichment of the metadata when publishing articles in scholarly journals, depositing datasets in data repositories, submitting outputs to open sharing platforms, or managing research objects on collaborative research environments, given that these platforms are integrated with the PID systems. 

All that being said, researchers can’t do it alone. Making research FAIR also very much relies on the wider adoption of both technical and social infrastructure across sectors in the research ecosystem, to provide the support and incentives for culture change.

# 

# Project planning 

The project planning stage is the perfect time to create a list of the resources available, such as researchers, facilities, and source of finances, and to outline the works that will be generated, to keep track of these entities and their corresponding PIDs, so that they can be consistently acknowledged, referenced to, and credited throughout the project.

## Checklist

- [ ] All researchers in the project have ORCID IDs  
- [ ] All organizations involved in the project have ROR IDs  
- [ ] The project itself has a DOI  
- [ ] A DOI (DMP ID) for the data management plan  
- [ ] A DOI for the grant or award that funds the project  
- [ ] ORCID IDs of researchers and ROR IDs of organizations are linked to the project and DMP  
- [ ] The grant ID is linked to the DMP ID and the project ID  
- [ ] If the project is an extension of a previous project, it is referenced in the project metadata  
- [ ] If the project will reuse existing datasets or other resources, they are cited in the DMP

# Method planning 

Making methodological decisions is pivotal, and it can yield key outputs that will be important points of reference throughout the research process by the project team and beyond. Notably, the best practice for any research methods involving hypothesis testing is to create a detailed research plan and share it in a registry, making them accessible and citable.

## Checklist

- [ ] A DOI for the study registration/experiment plan detailing the methods for data collection, treatment, and analysis  
- [ ] A DOI for the newly created tools, standards, or procedure that support the proposed methods  
- [ ] The creators, contributors, and supervisors of methodology are acknowledged in the method document metadata through their ORCID IDs  
- [ ] The umbrella project is referenced in the study registration metadata through its DOI  
- [ ] If experiment reuses protocol/methodology documents, they are referenced in the experiment  
- [ ] If multiple registrations are created, they are linked to one another using appropriate relation type metadata  
- [ ] If the study registration describe an analysis that uses existing datasets or protocols, they are cited in the registration

# Experiment and analysis 

The protocol, notes, data, codebook, and processing workflows—generated between the start of data collection and the delivery of the final analysis outcome—are key products of any research study. 

## Checklist

- [ ] A DOI for each dataset produced in response to the preregistration  
- [ ] A DOI for the experimental protocol  
- [ ] All contributing researchers acknowledged in the specific outputs they worked on, using their ORCID IDs, with appropriate contributor roles  
- [ ] Acknowledge the instrument or facility used in the experiment in the protocol metadata  
- [ ] Link the dataset, analysis code, and results to their corresponding registration  
- [ ] If shared separately, link the protocol, dataset, analysis code and results to each other  
- [ ] Link the dataset, code, and other resources back to the DMP (by either updating the DMP or reference the DMP ID in the output metadata)  
- [ ] If the protocol used in the experiment and analysis is adapted from an existing protocol from a separate project, cite the original protocol in the new one  
- [ ] If the analysis reused a software package shared by other researchers, cite the software in the derived dataset

# Dissemination 

Engaging with the research community to stimulate discussions is an integral part of the research process, and it starts well before the manuscript has been published.

## Checklist

- [ ] Make important communicative materials (poster, presentation, recording) presented to the peer community publicly accessible and identified with a DOI  
- [ ] A DOI for the preprint  
- [ ] Acknowledge the authors, presenters, and contributors to the poster/slides/recording, using their ORCID IDs, with appropriate contributor roles  
- [ ] Acknowledge the grants in the preprint and publication DOI metadata  
- [ ] Acknowledge the researchers in the specific output they worked on, using their ORCID IDs, with appropriate contributor roles  
- [ ] Link the preprint  to the project/registrations it reports on  
- [ ] Link the preprint to the manuscript when submitted to a journal  
- [ ] Cite the key datasets and software cited in the preprint and formal publication

# Appendix \- supporting tools 

Digital tool selection has become an integral part of method development in collaborative research projects, and the numerous options offered by the vibrant community of research tools and platforms creators and providers can make it daunting for researchers to choose and commit to one or a particular set of tools. We want to suggest a number of selection criteria based on the requirements of FAIR and open sharing of research \- the integration of PID functionalities and metadata management capabilities \- and provide exemplar tools and platforms based on our experience in the FAIR Workflows project.

|  | Research support | Domain focus | Output type | PID integration | Metadata support |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Open Science Framework** | Research collaboration  Project management Preregistration  | Generic | Project Preregistration (all resource types) | DOI ROR ORCID | Generic Domain Connection |
| **DMPTool** | DMP authoring DMP management | Generic | Output management plan | DOI ROR ORCID | Generic Domain Connection |
| **ASpredicted** | Preregistration  | Generic | Study registration  |  |  |
| **CEDAR Workbench** | Metadata template creation Metadata management | Generic | Metadata template Metadata instance Metadata element | DOI | Generic Domain |
| **protocols.io** | Protocol authoring Protocol publishing | Generic | Protocol | DOI ORCID | Generic Connection |
| **Brainlife.io** | Data analytics Output publishing  | Neuroscience | Software | DOI | Generic Domain Connection |
| **Dryad** | Data publishing  | Generic | Dataset Code Software | DOI ROR ORCID | Generic Domain Connection |
| **Zenodo** | Output publishing  | Generic | Dataset Software (all resource types) | DOI ROR ORCID | Generic Domain Connection |
| **OpenNeuro** | Data publishing  | Neuroscience | Dataset | DOI ORCID | Generic Domain Connection |
| **Ebrains** | Data analytics Data publishing  | Neuroscience | Dataset Model Interactive resource | DOI | Generic Domain Connection |
| **bioRxiv** | Preprint sharing | Life sciences | Preprint | DOI ROR ORCID | Generic Domain Connection |
| **PsyArXiv** | Preprint sharing | Psychology | Preprint | DOI ROR ORCID | Generic Domain Connection |
| **ChronosHub** | Open Access publishing | Generic | Journal article | DOI ROR ORCID | Generic Connection |

# Selecting Tools for research and research sharing workflows

Integration with Open Infrastructure

- [ ] Does the platform support DOI creation for the work you created on it?  
- [ ] Does the platform support linking your ORCID to the work you created on it?  
- [ ] Does the platform allow you to link related works using their DOI to the work you created on it?

Support domain specific metadata 

- [ ]   
- [ ] Does the platform integrate with domain specific tools and/or data format

Institutional and community endorsement

- [ ] 

# Acknowledgement 

This guide is an output of the implementing fair workflows project. This is based on a typical neuroscience research project that contains studies of behavior data and brain scans data.

![][image1]  
*This project was made possible through the support of a grant from Templeton World Charity Foundation, Inc. The opinions expressed in this publication are those of the author(s) and do not necessarily reflect the views of Templeton World Charity Foundation, Inc.*

[^1]:  [https://www.go-fair.org/fair-principles/](https://www.go-fair.org/fair-principles/) 

[image1]: <data:image/png;base64,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>