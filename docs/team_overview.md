---
title: Team Overview
---

##  Overview

Iterative website Define, Design, Develop, Deploy and Maintenance teams may be operational at the same time creating, testing, and helping with maintenance  

<!-- <div style="text-align: center;"> -->
<!-- <b>Teams</b> -->

``` mermaid
	graph TD
    dev --- def
    dev --- des
    dev --- dep
    dev --- mnt
    def --- des
    dep --- mnt
    dev --- tst

    dev([Development])
    def([Define])
    des([Design])
    dep([Deploy])
    mnt([Maintenance])
    tst([Testing])
```

<!-- <b>Iterative Development Teams</b> -->

<!-- </div> -->

Reaching a [Minimum Viable Product](minimum_viable_product.md) is the first Development teams goal
 
- [Team Define](team_define.md)   
  Defining websites helps the Iterative Development teams and Stakeholders to understand the project.

- [Team Design](team_design.md)  
  Determines the core foundations of a user's website experience are:

- [Team Develop](team_develop.md)  
  Translates the Define and Design teams processes into website pages 

- [Team Deploy](team_deploy.md)  
  Deploys the website making it available on the Internet. The production version is deployed when Stakeholders agree.

- [Team Maintenance](team_maintenance.md)  
  Remediates the Define, Design, Develop, Deploy, or Security teams defects

