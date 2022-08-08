
Dataset download https://www.kaggle.com/datasets/mistag/arthropod-taxonomy-orders-object-detection-dataset

Arthropoda Taxonomy Orders

This dataset contains images of (real) arthropods, where objects are labeled according to taxonomic orders.
Labels are systematic names, and their meaning are:
* Araneae: Spiders
* Coleoptera: Beetles
* Diptera: True flies, wich includes mosquitoes, midges, crane flies etc.
* Hemiptera: True bugs, which includes aphids, cicadas, planthoppers, shield bugs etc.
* Hymenoptera: Ants, bees and wasps
* Lepidoptera: Butterflies and moths
* Odonata: Dragonflies and damselflies

## Arthropod Taxonomy Orders Object Detection Dataset  
Invertebrate animal (arthropod) images annotated for object detection  

About Dataset  

### Context  

Species identification from an image is a complex problem. Image classification assumes there is only one species in the image. But generally we want to identify ALL species present in an image. Thankfully, biologists and taxonomists have systematically classified and ordered organisms in a taxonomic hierarchy. The ArTaxOr data set covers arthropods, which includes insects, spiders, crustaceans, centipedes, millipedes etc. There are more than 1.3 million species of arthropods described. Creating a single dataset to cover all those is not feasible. However, the identification problem can be broken down into multiple tasks, starting with object detection at order level (there are >120 orders of arthropods), then followed by family classification and finally species classification, as illustrated below:  

Notice though, many species (maybe most) cannot be identified to species level from a photo only, but requires study of microscopic details not visible in a photo. But identifying arthropods down to family level at least can be very useful.  

Test: Which of the photos below show a butterfly or moth (order Lepidoptera)? See answer at the bottom.  

### Content  
The dataset consists of images of arthropods in jpeg format and object boundary boxes in json format. There are between one and 50 objects per image.  
This dataset is actively maintained, and new orders will be added on a regular basis. Currently, the following orders are covered with at least 2000 objects per order:  
* Araneae (spiders), adults, juveniles
* Coleoptera (beetles), adults
* Diptera (true flies, including mosquitoes, midges, crane file etc.), adults
* Hemiptera (true bugs, including aphids, cicadas, planthoppers, shield bugs etc.), adults and nymphs
* Hymenoptera (ants, bees, wasps), adults
* Lepidoptera (butterflies, moths), adults
* Odonata (dragonflies, damselflies), adults  

Next in the pipeline to be added are:  

* Orthoptera (grasshoppers, locusts, crickets etc).  

### Acknowledgements  

Images are collected from various sources, including inaturalist.org and similar. Every image is originally published under a Creative Commons license. In this dataset the photographer and/or source is embedded in the EXIF tags. Images are otherwise unmodified.  

### Inspiration  

Species identification is a complex problem, and object detection is a natural first stage in a hierarchical approach to the problem.

Answer to question above:  
a) False. This is an owl fly from the order Neuroptera (netwinged insects).  
b) True. This is the raspberry clearwing moth.  
c) False. This is a whitefly from the order Hemiptera (true bugs).  
d) False. This is a drain fly from the order Diptera (true flies).  
e) True. This is the winter moth (female, which is flightless).  
