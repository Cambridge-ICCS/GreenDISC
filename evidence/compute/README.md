# Compute 

The directory contains all the hpc infrastructure related evidences for each of the three crieteria under it. The images are attched in the respective sub-directories, the links/retorics are placed below:

## C1-B: Catalog computing infrastructures used
1. Filled inventory for HPC Infrastructure

    The `HPC Inventory` tab of the GreenDiSC inventory sheet (attched below) records the HPC systems ICCS uses (CSD3, run by RCS, and other external systems) and the team's allocations on them. 

    - [HPC Inventory sheet](https://docs.google.com/spreadsheets/d/15jcCD2Ig1MkHKncvauN3nEL2SgUuFa67DVHn6lpF7fg/edit?gid=1291326356#gid=1291326356)

2. Replies from HPC and facilities teams

    We asked the CSD3 HPC team questions about the local facilities energy and power infrastructure. The answers are added in the below attached sheet under the tab `HPC Inventory`. 

    - Attached in /evidence/compute/C1-infrastructure

    Screenshots of responses from HPC Team are attached as well.

    - _Screenshot 1:[HPC Team on Power Infra.png](C1-infrastructure/HPC%20Team%20on%20Power%20Infra.png)_
    - _Screenshot 2:[HPC Team on Power Infra2 .png](C1-infrastructure/HPC%20Team%20on%20Power%20Infra2%20.png)_

3. Gaps identified

    - **No internal compute:** ICCS does not own or run any on-site compute or clusters. All HPC we use is provided by external services (CSD3 run by RCS, and other external systems).
    - **Gaps are on external systems:** details such as power usage effectiveness (PUE), energy sources and hardware power data are controlled by the providers. We have gathered as much as the providers could share, and the gaps are marked in the `HPC Inventory` tab.


## C2-B: Identify computing workflow hotspots
1. Filled inventory

    The Compute Pipeline tab records the main computational workflows the team runs, the resources each one uses (system, node type, typical job size and frequency), and which workflows are the largest consumers (the "hotspots").

    - [Compute Pipeline sheet](https://docs.google.com/spreadsheets/d/15jcCD2Ig1MkHKncvauN3nEL2SgUuFa67DVHn6lpF7fg/edit?gid=609389557#gid=609389557)

2. Description of the process to keep the inventory up-to-date

    The ICCS Handbook sustainability policy (`engagement/sustainability.md`, private repository) sets out how the HPC Inventory and Compute Pipeline tabs are kept current:

    - **Ongoing:** the "Computing" section of the policy asks everyone to _"Keep the HPC Inventory and Compute Pipeline in the inventory sheet up to date"_, adding new workflows, systems or allocations as they start using them.

        _Screenshot: [ICCS Sustainability Policy .png](C3-best-practices/ICCS%20Sustainability%20Policy%20.png) (see "Computing" section)_

    - **New starters:** at induction, new joiners only add their personal hardware to the inventory sheet, as they are not yet allocated to any projects or HPC systems. They read the sustainability policy as part of induction, so they know to add their HPC systems and workflows to the HPC Inventory and Compute Pipeline tabs once they are allocated to a project.

        _Screenshot 1: [ICCS Sustainability Policy - GreenDiSC.png](C3-best-practices/ICCS%20Sustainability%20Policy%20-%20GreenDiSC.png) (see "For new starters" section)_

        _Screenshot 2: [Induction Checklist.png](C3-best-practices/Induction%20Checklist.png)_

3. Scope of the inventory

    - **Consultancy-style work:** much of ICCS's work is on other groups' projects and codes. On these projects we introduce green computing best practices where we can (e.g. efficient HPC use, greener CI).
    - **What is inventoried:** the Compute Pipeline tab only documents ICCS's own internal codes and workflows. Workflows owned and run by partner groups are not included.

## C3-B: Collect educational material on sustainable computing best practices
1. Policy repository

    ICCS keeps its sustainability guidance in the ICCS Handbook under `engagement/sustainability.md`. The repository is private, but pdfs and screenshots of relevant sections have been attached as evidence.

    _Screenshot 1: [ICCS Sustainability Policy - GreenDiSC.png](C3-best-practices/ICCS%20Sustainability%20Policy%20-%20GreenDiSC.png)_


2. Training dates and attendance list

    The training is self-paced, and everyone must finish it by a fixed deadline. Completion is recorded per person in the training record sheet, and line managers make sure their team members complete it. The mandatory introductory training is [Emissions of DRI](https://sdratraining.sparkhub.eu/)

    - **Existing team members:** deadline 12th Dec 2026

        _Screenshot: [Slack message on Mandatory Training.png](C3-best-practices/Slack%20message%20on%20Mandatory%20Training.png)_


    - **New members:** expected to complete the training as part of their induction. It is an item on the induction checklist, which the line manager walks through with them.

        _Screenshot: [Induction Checklist.png](C3-best-practices/Induction%20Checklist.png)_

    - [Training record sheet](https://docs.google.com/spreadsheets/d/1IxOrgmOg3g_BgMkkefgaNP95MXoCWqW8S4_DaDI5oHE/edit?usp=sharing)


3. How it is made available
    - **ICCS Handbook sustainability page:** links the training, with separate instructions for new starters and existing staff.

        _Screenshot 1: [ICCS Sustainability Policy - GreenDiSC.png](C3-best-practices/ICCS%20Sustainability%20Policy%20-%20GreenDiSC.png)_

        _Screenshot 2: [ICCS Sustainability Policy.png](C3-best-practices/ICCS%20Sustainability%20Policy%20.png)_

    - **Induction checklist:** includes three Green DiSC items: read the handbook page, complete the *Emissions of Digital Research Infrastructure* training, and get added to the inventory sheet with an explanation of how to fill it in. This makes sure every new joiner sees the material in their first weeks.

        _Screenshot: [Induction Checklist.png](C3-best-practices/Induction%20Checklist.png)_

4. Additional material relevant to our work

    Beyond the mandatory training, the handbook points the team to material suited to the kind of computing ICCS does (see "Training" section of [ICCS Sustainability Policy.png](C3-best-practices/ICCS%20Sustainability%20Policy%20.png)):

    - **HPC:** because we often use HPC systems, we encourage members to also complete Andy Turner's EPCC [Green HPC course](https://epcced.github.io/2025-07-02_GreenHPC_UCL/) at their own discretion.
    - **CI/CD:** we often work on repositories with many GitHub Actions workflows, so we point people towards our own [green-ci](https://github.com/Cambridge-ICCS/green-ci) material ([docs](https://cambridge-iccs.github.io/green-ci)) for reducing the cost of CI.



