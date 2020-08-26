base.html in templates is for constant webpage elements, such as a logo or unchanging text.

generic.html in templates is for showing parameter entry boxes on the webpage and passes arguments in (while talking to forward_models.py in forward_models folder) to show a graph.

app_exoctk.py pulls generic.html (which calls base.html) and displays it.

forward_models.py takes in arguments entered and processes them while talking to generic grid.