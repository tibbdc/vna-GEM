## V.natriegens_model-name-1.0：修改边界条件后版本；

### 1.1：

V.natriegens_model-name-1.1.1：对biomass单体进行gap filing后，用ADD_xxxxx表示添加反应；
V.natriegens_model-name-1.1.2：对biomass单体进行gap filing后，用rxn_xxxxx的ID表示添加反应；

### 1.2：

V.natriegens_model-name-1.2.1：用ADD_xxxxx表示添加反应的ATP检查修正结果；
V.natriegens_model-name-1.2.2：用rxn_xxxxx的ID表示添加反应的ATP检查修正结果；
V.natriegens_model-name-1.2.3：先基于TD01的ATP检查结果修正后再检查ATP；

### 1.3：

V.natriegens_model-name-1.3.1：对用ADD_xxxxx表示添加反应的ATP检查后的模型进行氨基酸合成途径检查；
V.natriegens_model-name-1.3.2：对用rxn_xxxxx表示添加反应的ATP检查后的模型进行氨基酸合成途径检查；
V.natriegens_model-name-1.3.3：对先基于TD01的ATP检查结果修正后再检查ATP后的模型，再基于TD01的氨基酸合成途径检查结果修正后进行氨基酸合成途径检查；

### 1.4：

V.natriegens_model-name-1.4.1：对V.natriegens_model-name-1.3.3修正biomass units系数时，用ADD_xxxxx表示添加反应；
V.natriegens_model-name-1.4.2：对V.natriegens_model-name-1.3.3修正biomass units系数时，用rxn_xxxxx的ID表示添加反应；

### 1.5：

V.natriegens_model-name-1.5.1：修正biomass units系数后重新计算biomass时，再对biomass单体进行gap filing后，用ADD_xxxxx表示添加反应；
V.natriegens_model-name-1.5.2：修正biomass units系数后重新计算biomass时，再对biomass单体进行gap filing后，用rxn_xxxxx的ID表示添加反应；
V.natriegens_model-name-1.6.1：质量控制，继续修正模型时，用ADD_xxxxx表示添加反应；
V.natriegens_model-name-1.6.2：质量控制，继续修正模型时，用rxn_xxxxx的ID表示添加反应；