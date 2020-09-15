<br> 
### <a href="https://hvleifsson.github.io/articles">Back to articles</a>

# Bill Of Material?

Everything starts after engineers have generated a Bill Of Material, BOM. A BOM is a database that lists all components that make up a specific product. When we say BOM, we usually mean Engineering BOM, EBOM. After EBOM is complete, everyone else's work can properly begin. In this article I’ll explain the differentiations I make. 

EBOM is the first BOM. Everything else is generated on top of this source. 
What document number is the manual needed for your product? How is it connected to the part number? How much grease do you need for each product? Where is the packaging material listed? Calling everything BOM makes it confusing, and in a world of for example 3D printed replacement parts, separating BOM becomes more and more needed and useful. 

Projects without end: 
EBOM: Engineering BOM [All components that make up the product]
MBOM: Manufacturing BOM (EBOM+Manufacturing part numbers) [Everything needed to manufacture the product. Fixtures, drill bits, instructions, G-code, machine time etc.]
ABOM: Assembly BOM (EBOM+Assembly part numbers) [Everything needed to assemble the end product. Packaging, pallets, grease, time, instructions, manuals etc. ]
SBOM: Service BOM (Subset of EBOM+Service part numbers) [Replacement parts, repair instructions etc.]

Projects without end: 
These types of project are usually finished after generating EBOM. Finishing means for example listing your discipline EBOM for the building. 


---------------------------------
Can you really express the exact material specification, paint specification, paint instruction, heat treatment procedure, standards, notes to manufacturing and revision information on one single drawing? A single drawing does not usually describe a complicated part. The documentation I'm speaking of is commonly described as PMI (Product Manufacturing Information) such as material specification, paint specification, paint instruction and heat treatment procedure for example.

To me, the answer to above question depends on why you are making a manufacturing drawing. In other words, the nature of the project. Everything you do can be noted as a project. A production and assembly is simply one big project that is without end. A project with end is for example a facility, where you need some parts manufactured for that single project. 

|  | Project without end | Project with end |
|:-------------------:|:----------------:|:----------------:|
| What should be on a manufacturing drawing? | ? | ? |

If you are in a project without end, you should want to do complete documentation. Documenting every specification seperatly, and connect it to the part number, instead of consolidating all the documentation on one drawing. 
Notes for manufacturing and revisions might be specific to that article, but material specification, standards, paint specification and instruction and heat treatment procedures are usually not. Changes to a paint specfication for example would require changes to all drawings where that specification is expressed. Without complete documentation with specifications on its own, you bring problems into the future that requires a lot of time to fix. A manufacturing drawing should only specify the geometry in an endless project. 

If you are in a project with end, you still want complete documentation but there is usually little need for exact reproducability. Then consolidation of the information on one drawing is faster and does not bring as much problems into the future. 

|  | Project without end | Project with end |
|:-------------------:|:----------------:|:----------------:|
| PMI on manufacturing drawing? | Documents seperate from drawing recommended | Acceptable on drawing |
| Part number? | Yes | Yes |
