# Endoscopy Artefact Detection & Segmentation
The project involved the pixel-wise detection &amp; segmentation of artefacts for high-quality endoscopic frame restoration.
The augmented data was passed through Faster R-CNN, Cascade R-CNN &amp; RetinaNet models. These base models' outputs were then fed into a class agnostic non-maximum suppression algorithm independently before combining the results through an ensemble model. Then a false-positive elimination was applied to the output of the ensemble model.
