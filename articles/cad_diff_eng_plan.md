<br> 
### <a href="https://hvleifsson.github.io/articles">Back to articles</a>

# What's the difference between CAD software?

I categorize CAD software in dimension-driven or geometry-driven. In this article I'll explain the difference which hopefully could be useful to consider. 

Example of CAD software can be seen in below table. 

|  | Dimension-driven | Geometry-driven |
|:-------------------:|:----------------:|:----------------:|
| CAD software | Inventor | AutoCAD |

Generally you would use a dimension-driven CAD software to manufacture end products. The example end product for this example will be a valve. You would use, for example, Inventor to design the traditional molded and machined parts, generate assembly instructions and quantifying all needed items to build the valve. 
Common headaches using dimension-driven CAD software usually boils down to: 



Generally you would use geometry-driven CAD software to place and plan the usage of end products. For example use AutoCAD to plan and place valves in a facilty. Generate drawings where the individual end products can be identified and assembled according to plan. 
Common headaches using geometry-driven CAD software usually boils down to:
* How the dwg files are organized
* Revising foundational changes. 



For example i.e. just move the thing 200mm to the left
Changing equipment might mean to redefine everything. 


Note that most things can be scriptable but usually only worth doing if you've been doing it the same way always. 
Limited relationships (you can build them but seldom helpful in my experience). 


Amount of valves
| CAD software | Modify relationships | Move all affected items |

In summary see table below.  

|  | Dimension-driven | Geometry-driven |
|:-------------------:|:----------------:|:----------------:|
| CAD software | Inventor | AutoCAD |
| Filename extension | .ipt .iam | .dwg |
| Common purpose | Manufacture end products | Place and plan usage of end products |
| Common question | Manufacturable? Component strong enough? | Constructable on site? Item reachable? |
| Constraints | Local coordinates and relationships | Global coordinates |
| Quantifying | Needed items to build end product | Amount of end products |
| Model | 3D | 2D (3D) |
| Data | Part number PMI (Product Manufacturing Information) | TAG number Item specific data |

