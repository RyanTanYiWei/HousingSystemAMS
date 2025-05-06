# Beyond Student Housing: A Systems Approach to understand the Student Housing Crisis in Amsterdam
Ryan Tan Yi Wei, Alexander Dietz, Ludwig Branzk, Canan Tezgec, Ariel Goldin (TU Delft)

## Abstract
The ongoing student housing shortage in Amsterdam underscores the need for policies accounting for complex housing market dynamics and ensuring future availability and affordability of housing for students. This paper employs a System Dynamics approach, aiming to develop a holistic understanding of the intricate mechanisms among three subsystems: supply, demand, and rent, to analyze the path dependencies driving the evolution of the student housing crisis. A backward-looking analysis revealed that past policies mainly targeted the rent subsystem to stimulate housing affordability and availability for students. Current policies often neglect the private housing market trajectory, prompting this paper to encourage policymakers to view the "student housing crisis" more broadly. The policy proposal aims to augment the existing National Student Housing Action Plan by capping rent to control growing reliance on private housing while utilizing its total capacity.

## How to Use (SFD)
- The stock-and-flow diagram is our [model](SFD_master.mdl) that quantifies the system and is used to run validations, scenarios and policy tests.
- The outputs of our experiments are contained within the folders [simulations](Simulations) and [sensitivity](Sensitivity). If the outputs would like to be visualized in the stock-and-flow diagram, it is recommended to move the output files into the root folder (same directory as the SFD file) and accessed in vensim via _control panel_ > _data set_.
- For replicability, all the scenario and policy tests were kept on the right end of the model where you can toggle them with switches depending on the scenario you intend to simulate.

# Folder Structure
The repository is structured as follows:
- [Paper](SD_Final_Paper_Group5a.pdf): Final paper which explains the contexts, results and discusses the implications.
- [Presentation](Misc/Presentation.pdf): Presentation summarizes the main findings of the paper.
- [SFD_master](SFD_master.mdl): Stock-and-flow diagram is our quantitative model.
- [CLD_master](CLD_master.mdl): The causal loop diagram is our qualitative model used for conceptualization.
- [Simulations](Simulations): Folder contains all scenarios/policy outputs from the SFD.
- [Sensitivity](Sensitivity): Folder contains all sensitivity outputs from the SFD.
- [Misc](Misc): Folder contains additional materials i.e. the excel sheet to track model variables and data used.
