
Overview
--------

Each agent has suite of attributes that defines his/her demographic/infection/behavior status and dynamics.

### Key CD4 agent attributes

| Attribute         | Description                                                                                  |
|:------------------|:---------------------------------------------------------------------------------------------|
| CD4               | CD4 category of HIV+ agent (1: &gt;500, 2: 500-350, 3, 350-200; 4, &lt;200; 5, died of AIDS) |
| Time in CD4       | Time elapsed (days) in current CD4 category                                                  |
| CD4 initial value | Initial categorical CD4 value of agent (1, 2, or 3)                                          |
| Start AIDS CD4    | Time (days) since model start when agent enters AIDS (CD4 category changes to 4)             |

### Key Viral Load agent attributes

| Attribute      | Description                                    |
|:---------------|:-----------------------------------------------|
| SPVL           | SPVL                                           |
| Infection Time | Time of infection in days since start of model |
| Viral Load     | Current viral load                             |

### Key Demographic agent attributes

| Attribute | Description    |
|:----------|:---------------|
| Age       | Age in days    |
| Sex       | Male or female |
