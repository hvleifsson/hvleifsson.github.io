<br> 
### <a href="https://hvleifsson.github.io/articles">Back to articles</a>

# What's the difference between CAD software?

I categorize CAD software in dimension-driven or coordinate-driven. CAD software is used to generate geometry and vary in how they define its relations with other geometries. Some CAD softwares are used for creating a geometry and then render it. Some CAD softwares are used to create geometry, make manufacuring drawings and define relations. Some CAD softwares are used to create layouts, buildings and all types of drawings. I'll focus on CAD softwares with mechanical purposes. In this article I'll explain some relational differences which hopefully could be useful to consider. 

Example of CAD software can be seen in below table. 

| Relations | Dimension-driven | Coordinate-driven | 
|:-------------------:|:----------------:|:----------------:|
| Example CAD software | Inventor | AutoCAD |

Inventor and AutoCAD are both capable of parametric modeling, but differ in how they form relations with other geometries. 
Generally you would use a dimension-driven CAD software to manufacture end products. The example end product for this example will be a valve. You would use, for example, Inventor to design the traditional molded and machined parts, generate assembly instructions and quantifying all needed items to build the valve. 
Common headaches using dimension-driven CAD software usually boils down to: 
* How the parts and relationships are defined
* How the products and the quantifying is communicated 

Consider, for example, that you are going to model a slight version to an end product. Only a couple of parts shall be redesigned and changed. The time to finish this task vastly depends on how well the previous end product has been modeled and defined. Is there a skeleton so that you can just replace the parts and not redo the relationships? There might be various older and newer numbering systems or suppressed parts without information. Maybe there is no way to directly import or sync the quantifying to other company systems. 

Advice: Use skeletons, write and apply a company CAD practises. Document, train and discuss often. Solve problems instead of maintaining them. 
<br> 
Generally you would use coordinate-driven CAD software to place and plan the usage of end products. For example use AutoCAD to plan and place valves in a facilty. Generate drawings where the individual end products can be identified and assembled according to plan. 
Common headaches using coordinate-driven CAD software usually boils down to:
* How the .dwg files are organized
* Revising foundational changes

Consider, for example, that a placement of a wall has moved 200mm in the facility. You need to move each .dwg that is affected by this change. Depending on your application and hardware this might be a simple task or it will require some time. Even small changes, that shouldn't require much replanning, might mean that you need to recreate many of those drawn lines.  
Advice: Verify sound foundation information, write and apply a company CAD practises. Document, train and discuss often. Solve problems instead of maintaining them. 
<br> 
<br> 
 
In summary see table below. 
| Relations | Dimension-driven | Coordinate-driven | 
|:-------------------:|:----------------:|:----------------:|
| Example CAD software | Inventor | AutoCAD |
| Filename extension | .ipt .iam | .dwg |
| Common purpose | Manufacture end products | Place and plan usage of end products | Direct-model geometry
| Constraints | Local coordinates and mates | Global coordinates and drawn lines |
| Quantifying | Needed items to build end product | Amount of end products |
