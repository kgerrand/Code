Five datasets were used in this project. They are each briefly explained below, adding context to the undertaken exploratory data analysis.

**dunking-data.csv**
This large dataset contains experimental data collected whilst repeatedly dunking different biscuits into tea. Six experimental parameters are collected, inspired by the Washburn equation.

1. *gamma* - the tea surface tension (N m<sup>-1</sup>)

2. *phi* - the contact angle between the biscuit and the tea surface (rad)

3. *eta* - the tea dynamic viscosity (Pa s)

4. *L* - the distance up the biscuit that the tea was visible (m)

5. *t* - the time after initial dunking that the measurement was made (s)

6. *biscuit* - the type of biscuit (Rich Tea/Digestive/Hobnob)


**microscopy-data.csv**
This dataset is a subset of *dunking-data.csv* - it contains one sixth the amount of data. It contains very similar parameters to the large dataset, however, biscuit type is not mentioned, and an additional parameter is added. This is a measure of the biscuit's pore radius, having been determined using microscopy.

1. *gamma* - the tea surface tension (N m<sup>-1</sup>)

2. *phi* - the contact angle between the biscuit and the tea surface (rad)

3. *eta* - the tea dynamic viscosity (Pa s)

4. *L* - the distance up the biscuit that the tea was visible (m)

5. *t* - the time after initial dunking that the measurement was made (s)

6. *r* - the radius of the pore (m)


**tr-1/2/3.csv**
These final three datasets are used to measure capillary flow rate. Each corresponds to a given biscuit, but is it unknown to which. Time ranges from 30 s to 300 s. 

1. *t* - the time after initial dunking that the measurement was made (s)

2. *L* - the distance up the biscuit that the tea was visible (m)

3. *dL* - an estimate of the uncertainty in *L* (m)

A number of constants were used for these measurements.

• *gamma* = 6.78 x 10<sup>-2</sup> N m<sup>-1</sup>

• *phi* = 1.45 rad

• *eta* = 9.93 x 10<sup>-4</sup> Pa s