# TemplateMatching-NatGeo

This repository consists of an easy-to-use method to perform template matching on clips of soundscapes from Gorongosa National Park, Mozambique.

The repository consists of:
* template_matching_example.ipynb: A notebook demonstrating the process of template matching on a clip and how it works, using the red-eyed dove (_Streptopelia semitorquata_) as an example.
* template_matching.ipynb: A notebook where template matching can be performed on all the clips uploaded into data/clips. The user can customize the template that will be used, along with parameters such as the threshold for a match to be made and the suppression distance to avoid multiple matches in close proximity.

Notes for templates:
* For template matching to work as intended, template sounds should only be a few seconds long.
* Ideally, the template should be clean, with only the sound of interest being present.