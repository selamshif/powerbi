# powerbi
use  a card 
Icon Im = 
var postiveicon =UNICHAR(9650)
var negativicon= UNICHAR(9660)
var result = IF ([YoYImport%] >0, postiveicon,
negativicon)
Return result

formating on colre on callout value 

Icon Color = IF([YoYExport%]>0, "Green", "Red")

