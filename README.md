# Convert-After-Effects-Expressions-for-Jsx

If you have an expression with more than one line and want to apply it with a Jsx script,
You have convert it like this:


// An After Effects expression:

var wiggleAmount = effect("Wiggle Amount")("Slider"); 
wiggle( 4, wiggleAmount );



// Converted expression for a jsx script:

'var wiggleAmount = effect("Wiggle Amount")("Slider");  \n'
'wiggle( 4, wiggleAmount ); \n'


Put your expressions in "exp.txt" and run the script. Your expressions in the txt file will be converted.
