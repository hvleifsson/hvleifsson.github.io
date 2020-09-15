<br> 
### <a href="https://hvleifsson.github.io/articles">Back to articles</a>

### [System Engineering] Bill Of Material?

Everything starts after engineers have generated a Bill Of Material, BOM. A BOM is a database that lists all components that make up a specific product. When we say BOM, we usually mean Engineering BOM, EBOM. After EBOM is complete, everyone else's work can properly begin. In this article I’ll explain the differentiations I make. 

EBOM is the first BOM. Everything else is generated on top of this source. 
What document number is the manual needed for your product? How is it connected to the part number? How much grease do you need for each product? Where is the packaging material listed? Calling everything BOM makes it confusing, and in a world of for example 3D printed replacement parts, separating BOM becomes more and more needed and useful. 

_**Projects without end:**_
<br> 
**EBOM: Engineering BOM** [All components that make up the product]
<br> 
**MBOM: Manufacturing BOM (EBOM+Manufacturing part numbers)** [Everything needed to manufacture the product. Fixtures, drill bits, instructions, G-code, machine time etc.]
<br> 
**ABOM: Assembly BOM (EBOM+Assembly part numbers)** [Everything needed to assemble the end product. Packaging, pallets, grease, time, instructions, manuals etc. ]
<br> 
**SBOM: Service BOM (Subset of EBOM+Service part numbers)** [Replacement parts, repair instructions etc.]
<br> 

_**Projects without end:**_
<br> 
These types of project are usually finished after generating EBOM. Finishing means for example listing your discipline EBOM for the building. 


<br> 

<br> 

<br> 

<br> 

<br> 

<br> 

<br> 
