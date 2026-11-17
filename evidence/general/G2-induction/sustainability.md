# ICCS Environmental Sustainability Policy

### Office Equipment Reuse
- Unused equipment needs to be checked for reuse before ordering new ones for new starters. Need to check : Remaining warranty of the equipment, full functionality of the equipment, system reset and data wiping before reuse. 
- There is an [inventory sheet](https://docs.google.com/spreadsheets/d/15jcCD2Ig1MkHKncvauN3nEL2SgUuFa67DVHn6lpF7fg/edit?usp=sharing) used to track all our equipment. The sheet should be used by the line manager when someone leaves or joins and equipment status should be updated as equipment unused or equipment newly bought.
- If the equipment is functioning fine even after 5 years of use i.e. beyond warranty period, team should be encouraged to continue using it rather than ordering new ones.
- Equipment the team can't reuse goes back to UIS for wider reuse or recycling. There is a form that needs to be filled to arrange collection of e-waste. For link to the form and other details, refer to the university's [official document](https://www.em.admin.cam.ac.uk/estate-operations/recycling-and-waste/waste-electrical-and-electronic-equipment-weee).

### Training
- Team members need to undergo mandatory training to understand aspects of energy consumption and carbon footprint associated with their work. Literacy is the first step towards solving the problem
- One of the primary courses that should be undertaken is the [SPARKhub DRI Emissions training](https://sdratraining.sparkhub.eu/). The course is an intro to the environmental impact of digital research (emissions, materials, e-waste and water from our computing, storage and data) and practical steps researchers can take to reduce it.
- There are other relevant courses like [Green HPC](https://epcced.github.io/2025-07-02_GreenHPC_UCL/), [Measure AI's Carbon Footprint](https://greensoftware.foundation/standards/sci-ai/) etc. that can be undertaken.

### Computing
- Computing on HPC and other systems (e.g. CSD3, cloud, GPU servers) uses significant energy, so it should be used efficiently.
- Test and debug on small cases or short jobs before launching large runs.
- Choose the right hardware for the job, e.g. only use GPUs where the code benefits from them.
- Avoid unnecessary reruns: use checkpointing for long jobs, and reuse existing results and outputs where possible.
- Carbon footprint of large runs can be estimated with tools like the [Green Algorithms calculator](http://calculator.green-algorithms.org/). Where timing is flexible, consider scheduling jobs when grid carbon intensity is lower, with scheduling tools like [CATS](https://github.com/GreenScheduler/cats).
- Keep the HPC Inventory and Compute Pipeline in the [inventory sheet](https://docs.google.com/spreadsheets/d/15jcCD2Ig1MkHKncvauN3nEL2SgUuFa67DVHn6lpF7fg/edit?usp=sharing) up to date. 

### Data Cleaning
- Regular cleanups should happen at the end of each project. Spaces that would require clearing are - office laptops, any shared spaces on CSD3, RDS etc. 
- Cleanups should be performed by respective Project Leads after discussing with rest of the project RSEs at the end of each project. Any individual-usage cleanup should be taken up by the individual.
- Team should make sure that they carefully delete only their own project-specific folders/directories and not touch other projects.
- Any datasets that may be required beyond the end of the project need a fair reason to stay on the systems - e.g. possible project extension, use for reproducibility, shared with other projects etc.
- If the PI or project needs the data after ICCS's involvement ends, transfer it to their machine or transfer ownership of the files.
- Any large datasets used for ICCS projects are to be logged in a [data resource inventory](https://docs.google.com/spreadsheets/d/15jcCD2Ig1MkHKncvauN3nEL2SgUuFa67DVHn6lpF7fg/edit?usp=sharing). Large dataset means any project datasets used for analysis or training purposes, and not local standalone files.
- The reason for the logging and cleanup exercise is that stored data sits on drives that draw power, need cooling and are usually duplicated in backups, so data nobody uses still causes emissions and e-waste.
- If in doubt, consult the Senior/Principal RSE on the project.


### Contributing to Sustainability initiatives
- Team should be proactive in adopting any newly introduced optimisations like the Green-CI practices, CATS Scheduler and share any new practices they are aware of, that can be helpful to the team.
- Team should co-operate with the sustainability/GreenDiSC representatives and collectively work towards attaining sustainability of the computing practices.



# GreenDiSC

### Introduction to GreenDiSC

GreenDiSC stands for Green Digital Sustainability Certification. It is an initiative designed to encourage teams to track and manage their work-related carbon footprint. More information can be found [here](https://www.software.ac.uk/GreenDiSC).

ICCS is actively working towards getting the GreenDiSC Bronze certification through extensive auditing and inventory building of the resources in use. For more information contact [Surbhi Goel](https://iccs.cam.ac.uk/people/surbhi-goel) or [Jack Atkinson](https://iccs.cam.ac.uk/people/jack-atkinson).

### Inventories

The GreenDiSC Inventory sheet can be found [here](https://docs.google.com/spreadsheets/d/15jcCD2Ig1MkHKncvauN3nEL2SgUuFa67DVHn6lpF7fg/edit?usp=sharing). The sheet contains different tabs to collect information for different types of resources used by the ICCS team in their work:

- **Office Inventory** – hardware used by each team member (laptops, desktops, monitors, tablets, external drives), with purchase details, current status, and what to do with unused devices.
- **HPC Inventory** – the HPC systems and allocations the team uses.
- **Compute Pipeline** – the computational workflows the team runs and the resources they use.
- **Data Resource Inventory** – the resources that the team uses for projects to store/access data.

### Repository

The project is maintained via GitHub and can be found [here](https://github.com/Cambridge-ICCS/GreenDISC). There is a [project board](https://github.com/orgs/Cambridge-ICCS/projects/59/views/1) used to create, track and resolve project-related issues.

### For new starters

All new joiners are expected to complete the [Green HPC Training course](https://epcced.github.io/2025-07-02_GreenHPC_UCL/). The course is assumed to introduce the RSEs to basic concepts of carbon emissions associated with computing resources they use in routine work. The long-term goal is to understand and incorporate best practices to mitigate carbon emissions from our use of resources as far as possible.

New joiners are also supposed to fill in hardware and compute use related details in the inventory sheet linked [here](https://docs.google.com/spreadsheets/d/15jcCD2Ig1MkHKncvauN3nEL2SgUuFa67DVHn6lpF7fg/edit?gid=0#gid=0). The sheet is also linked in the [induction checklist](Induction%20Checklist.png) (screenshot; the induction checklist lives in the private ICCS handbook repository).

### For existing team members

All team members are expected to complete the mandatory [SPARKhub DRI Emissions training](https://sdratraining.sparkhub.eu/). Line managers need to make sure that the training is completed by each of the team members.

### Further reading

Resources on the environmental sustainability of RSE work,
- [Green Software Practitioner](https://badges.greensoftware.foundation/credentials/green-software-practitioner)
- [Measure AI's Carbon Footprint with Purpose](https://greensoftware.foundation/standards/sci-ai/)
- [Green Research Computing](https://guides.lib.umich.edu/c.php?g=1459709&p=10930231)
- [CATS: Climate-Aware Task Scheduler](http://github.com/GreenScheduler/cats)
