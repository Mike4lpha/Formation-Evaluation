# Formation_Evaluation

## Introduction:
### Problem Statement
Identifying subsurface lithologies or rock types is essential for all geoscientists and petrophysicists in order to explore our subsurface resources, particularly in the oil and gas industry. Lithology refers to the type of rock that forms the subsurface, and it is classified into, for instance, sandstone, claystone, marl, limestone, and dolomite. Several subsurface data can be used to identify lithologies, such as wireline logs petrophysical data. However, it is often a tedious, repetitive and time-consuming task. This project will predict lithology from petrophysical logs using machine learning techniques (classification) and add to the solution of these problems since these logs are direct proxies of lithology.

Wireline Log Datasets
The data consist of 118 wells dataset spans through the South and North Viking graben and penetrates a highly variable geology from the Permian evaporites in the south the the deeply buried Brent delta facies in the North. An investigation of the provided training data clearly shows that the lithologic record offshore Norway is dominated by shales and shaly sediments. This is followed by sandstones, limestones, marls and the tufts.

The provided dataset contains well logs, interpreted lithofacies and lithostratigraphy for 90+ released wells from offshore Norway. The well logs include the well name (WELL), the measured depth, x,y,z location for the wireline measurement as well as the well logs CALI, RDEP, RHOB, DHRO, SGR, GR, RMED, RMIC, NPHI, PEF, RSHA, DTC, SP, BS, ROP, DTS, DCAL, MUDWEIGHT. An explanation of the abbreviations is shown in below.

## Logs Interpretations Description
### The data contains the metadata columns:

WELL: Well Name
DEPTH_MD: Measured Depth
X_LOC: UTM X Coordinate
Y_LOC: UTM Y Coordinate
Z_LOC: DEPTH
GROUP: NPD lithostratigraphy group
FORMATION: NPD lithostratgraphy formation

### The data contains the well log curves:

BS: Bit Size
CALI: Caliper Log
DCAL: Differential Caliper log
RDEP: Deep Resistivity
RMED: Medium Resistivity
RSHA: Shallow Resistivity
RXO: Flushed Zone Resistivity
RHOB: Bulk Density
GR: Raw Gamma Ray
SGR: Spectral Gamma Ray
SP: Spontaneous Potential
ROP: Rate of Penetration
ROPA: Average Rate of Penetration
NPHI: Neutron Porosity
PEF: Photoelectric Absorption Factor
RMIC: Micro Resistivity
DTS: Sonic (Shear Wave)
DTC: Sonic (Compressional Wave)
DRHO: Density Correction Log
MUDWEIGHT: Weight of Drilling Fluid
