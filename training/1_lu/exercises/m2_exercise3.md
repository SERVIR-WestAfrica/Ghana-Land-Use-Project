# Module 2 - Exercise 3

## 1. Skills Practiced

This exercise will practice:

- [Select by Location](https://github.com/SERVIR-WA/GALUP/blob/master/training/1_lu/modules/module2.md#26-select-by-location)

## 2. Description

Normally, the residential areas will be built near the education facilities so that it will be convenient for the education of children. In this exercise, we will help to find out the IDUs of THLD that are in proximity (within the 1 miles) to the education facility by using the [Select by Location](https://github.com/SERVIR-WA/GALUP/blob/master/training/1_lu/modules/module2.md#26-select-by-location) tool.

## 3. GIS Dataset
You should use the following data to finish this exercise:
- _THLD\_poly.shp_ at
`GALUP-master -> training -> 1_lu -> datasets -> IDUs in the THLD District`.
- _Education\_Facilities.shp_ at `GALUP-master -> training -> 1_lu -> datasets -> Education facilities in THLD District`.

## 4. Instruction

1. Locate _THLD\_poly.shp_ and _Education\_Facilities.shp_ in the **_Browser Panel_** and add them to
   **_Map Canvas_**.
2. In the _Processing Toolbox_ panel, find the **<ins>Select by Location</ins>** tool under the _Scripts_  ![scripts](../../../images/M2E1/processingScript.svg) and double click to open the tool.
3. Parameter Setting:
   <ol type="a">
      <li><b>Input layer</b>: THLD_poly.shp</li>
      <li><b>Selection layer</b>: Education_Facilities.shp</li>
      <li><b>Join option</b>: Within a distance</li>
      <li><b>Within distance of selecting feature</b>: 1 mile</li>
      <li><b>Output layer</b>: EduProIDU.shp</li>
      <li>Set all other parameters as default</li>
      <li>Click <b>Run</b></li>
   </ol>
4. Create a _Layout_ and then add _Legend_, _Scale bar_, and _North Arrow_.
5. Export as a PDF file.

## 5.Result

- Upon completion, the map you got should look similar to this pdf
  [here](../pdf_maps/M2E3_EduProximity.pdf).
- Please go back to
  [Module 2](https://github.com/SERVIR-WA/GALUP/blob/master/training/1_lu/modules/module2.md#3-exercises) to complete the fourth exercise.