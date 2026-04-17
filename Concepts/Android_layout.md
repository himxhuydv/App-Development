# Android Layout
Define the structure of the user interface (UI) in a Android application.it determines how UI Components like textview,button,imageview.etc.are arraneged.
Layouts are basically defined in Xml files inside the res/layout and tre renderd in an activiy or fragment 
1.TableLayout
arrange elements in rows and coloumn like a table.
2.GridLayout
arrange in grid formate(rows and columns.like Calculator layout)
3.AbsoluteLayout(Deprecated) 
Uses exact X and Y postions

## Width & height values and layout attributes
this define how much the space a view occupies inside it's parent layout
- Match_parent-views take the full available space of the parent
- Wrap_content-as much require by it's content 
- dp(desity -independent pixels) used for layout dimensions to maintain consistent size across the different screen densities
- Sp(scale-indepenedent pixels)-used for the text size ,adjust based on user font sizze settins.
- 