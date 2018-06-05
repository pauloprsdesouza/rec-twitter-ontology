# The RecTwitter Ontology
A Twitter domain ontology was created for representing the extracted data of based on a Twitter user account. The process of building the Twitter ontology was based a development methodology called Methontology.


# Classes
Two classes were created based on information obtained in the conceptualization stage. Most terms have definitions which have been described in notes. Figure 1 presents examples of the created classes.
<p align="center">
  <img src="/images/class-ontology.png" width="500">
  <p align="center"><b>Figure 1: Two classes were created.</b></p>
</p>

Figure 1 shows the proposed ontology to annotate the information of Twitter users through two classes:

* <b>UserAccount</b>: represents a Twitter user account with all properties and characteristics related to him.
* <b>Tweet</b>: depicts a post published by one user, containing the information as for instance: text, url and hashtags.

# Object Property
Object properties are used to relate an individual of a class with the individual of another class <a href="https://www.w3.org/TR/owl-features/">[W3C]</a>. In this case, <b>13</b> object properties were created from <i>Protegé</i> tool to help in semantic annotation of information about this context.

<p align="center">
  <img src="/images/objectproperties.png" width="500">
  <p align="center"><b>Figure 2: The object properties.</b></p>
</p>

The property <i>hasLiked</i>, for example, associates the individual of the <i>UserAccount</i> (domain) class with the individual of the <i>Tweet</i> (range) class. Thus, the action of liking a tweet is represented by the interaction <i>liked</i> as shown in Figure 2.

# Datatype Property
Datatype properties are used to link an individual to a primitive value (string, int and others) <a href="https://www.w3.org/TR/owl-features/">[W3C]</a>. We created <b>13</b> datatype properties in <i>Protégé</i> tool. For instance: Date(<i>createdAt</i>), String (<i>email, name</i>) and others as shown in Figure 3.

<p align="center">
  <img src="/images/dataproperties.png" width="500">
  <p align="center"><b>Figure 3: The data type properties.</b></p>
</p>

