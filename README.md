# BIM_data_template
Data template for Building Information Modelling (BIM) using [buildingSMART](http://www.buildingsmart-tech.org/) IFC definitions

## Template purpose
The template attempts to gather together a data set that will be suitable for facilities management use for a typical commercial / health / educational / institutional building.

The template provides the fields required and not the data. The data should be populated as a construction project progresses through the design and build phases.

[BIMsense](https://bimsense.co.uk) use the data template to directly populate IFC models.

## The data explained

1. Uses the [UK Uniclass2015](https://toolkit.thenbs.com/articles/classification#classificationtablescodes). Uniclass codes both Pr - Products and Ss - Systems (where applicable) should be applied to objects within a model.
2. Objects within the model should be correctly identified as the correct Ifc entity, for example all windows should be an IfcWindow entity.
3. The identified property sets follow where possible those available within the Ifc framework
4. Uuses the [RIBA plan of work](https://www.architecture.com/knowledge-and-resources/resources-landing-page/riba-plan-of-work) project stages 
5. References the 'employer purposes' from [BS 1192-4:2014 Collaborative production of information. Fulfilling employer's information exchange requirements using COBie. Code of practice](https://shop.bsigroup.com/forms/PASs/BS-1192-4-2014/)


| Column | Description |
|--------|-----------|
| A - D | Reference to the applicable Uniclass codes |
| E | Ifc object reference |
| F | Property set required |
| G | The name of the attribute required within the model |
| H | Mapping to COBie |
| I - J | Ifc data types |
| L | Not used - intentionally blank |
| M | The designer responsible for including the data template |
| N | The project stage when the data temnplate should be added to the model |
| O | The project stage when the data should be populated within the model |
| P - X | Reference to the relevant 'employer purposes' |

## Planned improvements

1. The column G identified attributes are not fully consistent and require improvement or additional explaination.
2. Provide a custom ParameterMappingTable.txt for import of IFC (with the template data) into revit

## License
This information is licensed under Creative Commons Attribution Share Alike 4.0

Please use the template and contribute to improvements

## Acknowledgements

The BIM data template has been developed with valuable assistance from:

1. [University of Leeds](https://www.leeds.ac.uk/) - Louis Hynes
2. [Sewell Construction](https://sewell-construction.co.uk/) - Matt Longden and Katy Robertson
