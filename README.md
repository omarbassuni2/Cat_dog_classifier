There is two ways of installing and using this program the first is:-

-	Download pets dataset from this link
	https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765
-	Paste it in a Directory, copy this directory name and paste instead of my directory with forward slashes not backslashes
-	run the cells
-	Now you have trained my model and you're ready to use it

the second way is:-
-	download the cat_dog_classifier_model in the same directory your anaconda projects are created at
-	write this line of code
	variable_name = tf.keras.models.load_model('cat_dog_classifier_model')
-	use variable_name as your model
-	Now you can use my model