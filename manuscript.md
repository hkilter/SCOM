An Ontological Model for Supply Chain Systems
=============================================

*H. Kemal Ilter <sup>a</sup> and Akif A. Bulgak <sup>b</sup>*

*<sup>a</sup> Department of Management Information Systems, Yildirim Beyazit University, Turkey.*
*<sup>b</sup> Department of Mechanical and Industrial Engineering, Concordia University, Canada.*

## 1. Introduction

According to articles about the developments in last two decades, while supply chains (SCs) are becoming more complex and hard to manage structures along their related industries, information systems are going to a different level that should provide more information than before. More information means that analysts should working more efficiently on gathered data by means of new approaches such as analysis of the big data. In the area of supply chain (SC), there are plenty of approaches to reveal the chain’s properties, and to have a chance to put added value on the value of the chain as a whole with its members (main producer, suppliers, transporters, retailers, wholesalers and even consumers). In the literature of the supply chain, many other disciplines have at least one role to describe the chain’s world and provide connections in this environment.

In SC literature, many authors use their own understanding to describe the SCs properties which contains most of information gathered from the industry itself. This information is related to the operational and practical part of the industry, however scientist’s (or analyst’s) perceived fallacies, problems and myths of the related industry come with this information. So many articles have lots of conceptual mistakes due to the lack of a proper definition of the SC. Is there a need to describe the SC concept as a "world"? Is it possible to define all SC properties and relations to reveal the power of a conceptual framework for all -past, present and future- industries? This article is about a model that define and describe any supply chain "completely".

As an example, a researcher needs a manual if he wishes to understand how a machine works, or a philosopher needs a conceptual thinking platform to describe his thoughts about an idea. So scientists need at least one complete, sharable and expandable ontology to understand and manage a SC. It can be said that a SCM ontology study is a combination of three research fields; Supply Chain Management (industrial engineering and business administration), Ontology Engineering (conceptual studies, modeling, operations research, computer engineering, management information systems, etc.) and Semantic Web (computer engineering, database management, system analysis, software engineering, artificial intelligence studies, etc.)

This article is centering upon a supply chain ontology development which is at the intersection of various problems. First problem is about the “lack of ontological models”. Especially in developing countries, there are limited ontological studies (vocabularies, RDF/OWL/DublinCore or XML models, visual schema, semantics, etc.) to use them in software development processes of supply chain management. On the other hand, if software engineers need an ontology to develop their supply chain management application, they have to get it from outsourced companies located in developed countries or use it as an ontology developed for another particular project. Second problem is the “lack of fundamental details of shareable information among industries”. Common language is a key factor to have a chance to develop for a small or medium size enterprise in any industry. With the lack of proper definitions and acceptable sharing options, it is obvious that the efficiency and productivity of the firm will decrease. “Limitations in planning complex systems” is the third problem for the supply chain development. High complexity of systems force international companies to create their conceptual models which allow to concentrate and focus their environment. Last problem can be the “simplification of real models to practice in processes”. The theory and the practice have to be represented in real life examples in almost same meaning. In supply chain teaching and practice, it thought to be no necessity to put a real problem with its all factors and elements on the table. However, a complete ontological model and its appropriate visualization may be helpful for decision makers in any way.

## 2. Literature Review

According to some scientists (Uschold and Grüninger, 1996; Sowa, 2000a; Staab et al, 2001) ontology studies seem to be addressed in terms of philosophy and artificial intelligence. Sowa (2000a; 2000b) defined the ontology as “the science of existence” in the field of philosophy. This definition reflects the vision of a particular system about related sections/categories in a proprietary world. In terms of the artificial intelligence field, ontology is an engineering work which explains a certain reality with a dictionary (Gruber, 1993; Farquhar et al, 1997; Fikes and Farquhar, 1999; Guarino, 1995; van Heijst et al, 1995; Staab et al, 2001). This dictionary contains a number of assumptions about the designed meanings of words. The concept of ontology is propounded as a philosophical theory for describing the nature of existence. However, as stated by Gruber (1993), it seems artificial intelligent scientists have changed the concept of ontology to describe “a common and shared understanding about some issues that can provide communication between human and application systems”. Ontology-based systems work on key points such as acquisition of knowledge, its conversion to a conceptual form and its presentation in an understandable way  (Farquhar et al, 1997). Ontology converts tacit knowledge to explicit knowledge (Gruber, 1993; Guarino, 1995; Uschold and Grüninger, 1996). On the other hand, ontological rules reveal commonly accepted facts and nature of logic as formal models, and provide opportunities about sharing them between human and software applications (Gruber, 1993; Farquhar et al, 1997; Fikes and Farquhar, 1999; Guarino, 1995; van Heijst et al, 1995; Staab et al, 2001; Sowa, 2000a; Sowa, 2000b).

Various researchers such as Guarino (1998), Vasconcelos et al (2002) and Fonseca et al (2002) emphasized the necessity of ontology applications in terms of designing and using information systems with:

* integrating a wide variety of information in a way that can be understood easily, 
* presenting interoperability of heterogeneous computing platforms, and 
* providing sharable opportunities for solving common problems.

Using ontology as a part of the information system helps diffusion of the idea of ontological based information system (Vasconcelos et al, 2002). Ontology can be used for gathering information semantics, describing it with a formal language and storing related meta-data in a database (Guarino, 1998). On the other hand, ontology which consolidates various information sources into semantics, seems to has a fundamental role in the information system (Guarino, 1998). Accordingly, from the off-system point of view, the ontology has another role of integration for all three components; database, application and user-interface, as well as some mandatory tasks; developing problem solving approaches and acquiring system outputs.
In general, artificial intelligence technologies are discussed inadvertently without a connection to ontologies (Jennings and Wooldridge, 1995; Wooldridge and Jennings, 1995; Zambonelli et al, 2000; Cabri et al, 2000; Barbuceanu and Fox, 1994; Jennings, 1994; Castro-Schez et al, 2004). However agent-based computation has a significant importance in design of software systems (Cabri et al, 2000; Jennings, 2000). In this type of computation environment, some agent abilities provide a disruptive development step for software systems such as:

* autonomously planning by cooperation and coordination with other agents (Jennings and Wooldridge, 1995; Wooldridge and Jennings, 1995), and
* acting with intelligent behaviours in uncertain dynamic environments (Castro-Schez et al, 2004; Cabri et al, 2000).

It can be said that there is a continuous development on the relationship between artificial agents and information systems to be able to increase overall system performance (Barbucenau et al, 1994).

Intelligent agents have to be supported with a conceptual description language (ontology). On the other hand, the Internet can be a computational environment to integrate artificial intelligence. Day by day, the world wide web is approaching its next generation, the “fully semantic world wide web” which provides automatic web services  based on data semantics and algorithms (Ding, 2001; Fensel et al, 2001; Guarino et al, 1999; Harmelen, 2002; Ding et al, 2002). Ontologies are beginning to be fundamental key values in the next generation of the web and web services cross the technology borders of the web itself by making information processes automated (Staab et al, 2001). Ontologies has a task to connect formal and real world semantics each other. Staab et al’s (2001) proposition, in general, seems to be accepted to develop the semantic web. It presents an idea about the addition of conceptual informational platforms to current web services. Artificial intelligent agents can use the information if it can be described with an ontology, thus automated web services can penetrate the web more efficiently. Stojanovic et al (2001) emphasized that the integration of semantic web can lead to get an opportunity to develop intelligent agents. Semantic technologies (UDDI, SOAP, WSDL, etc.) and ontology languages (DAML, OIL, UPML, etc.) continue to provide such integration efforts for last two decades.

Uschold et al’s (1998) study has a pioneer role about representation of using ontological applications to model an enterprise system. Model based institutional design, analysis and process are key tasks for modeling an enterprise system (Fox and Gruninger, 1999; Malone et al, 1999; Ushold et al, 1998; Gruninger et al, 2000; Kim et al, 2001). On the other hand these models can make developed models reusable, consistent and efficient (Malone et al, 1999; Ushold et al, 1998). Gruninger and Fox (1996) support this idea that can be a possibility to describe domains and organizational processes with these models such as TOVE which has various logical descriptions of processes, cases, and time.

Architecture of supply chain management can be described a sort of processes which can be managed by multi-tasking artificial agents (Fox et al, 2000). Agents can integrate information to supply chain’s planning and scheduling processes by converting it to ontologies and micro-theories as mentioned by Swaminathan et al (1998). Therefore, as Norman et al (2004) indicated, the supply chain can be designed as a combination of various models which provide a modular architecture based on multi-usable in different applications.

Efforts of Chandra and Tumanyan who provide conceptual integration of ontological rules to analysis and design of supply chains (Chandra and Tumanyan, 2001; Chandra and Tumanyan, 2002a; Chandra and Tumanyan, 2002b; Chandra et al, 2002; Chandra and Tumanyan, 2003; Chandra et al, 2003; Chandra and Tumanyan, 2004a; Chandra and Tumanyan, 2004b; Chandra and Tumanyan, 2004c) can be seen clearly in this field of study. The main idea that is suggested by Chandra and Tumanyan is about an integrated environment in which there are two opportunities for supply chain members; (1) sharing data and information with other members and (2) working on a common problem together. In this field, studies continue to face problem-based information needs of organizations since the beginning of system taxonomies which cover systematic information framework. Chandra and Tumanyan (2001, 2002a, 2002b, 2003, 2004a, 2004b, 2004c) indicated that there are some necessities for performing ontological applications to extract or gather, process, describe and share information between members of the supply chain. According to Chandra and Tumanyan, this approach is important due to the reasons below:
    
* opportunity to overcome problematic relationships by covering all supply chain issues,
* ability to use developed ontologies directly in the decision making mechanism,
* usability of ontologies for modeling business processes by decomposition of these processes and identification of models by means of ontological objects,
* ability to support analysis studies which provide reusability of developed ontologies,
* ability to use XML for ontology development.
* ability to provide an integration between proposed processes for ontology development and various information resources.

For the last decade, it can be seen that terms of “tracking” and “tracing” are mentioned by some researchers in their studies (Yang et al, 2008; Chena et al, 2010; Sorensen et al, 2010; Thakur and Donnelly, 2010; Kuziemsky and Yazdi, 2011; Porto et al, 2011; Tao and Zhao, 2012; Hua et al, 2013) besides description purposes of the supply chain ontology. With these terms anyone can track or trace any particular production factor which is used in production processes towards to customer or opposite way respectively (Rese et al, 2013). Some researchers (Bhattacharya et al, 2010; Guo, 2009; Hepp, 2008; Izza, 2009; Millet et al, 2009; Panetto, 2007; Panetto, 2010; Panetto and Molina, 2008; Lia and Chanb, 2013; Zhonga et al, 2013; Candido, 2011; Dai and Zhong, 2012) seem to be right by their indications about these properties that cause a noticeable increment on the supply chain ontology using in different kind of industries. On the other hand, according to same researchers new technologies and approaches (robotics, artificial intelligence, evolutionary production systems, etc.) can be discussed in the literature more closely.

There are many efforts to create/develop ontologies in the literature which is related to supply chain management applications such as agriculture systems (Sorensen et al, 2010; Porto et al, 2011; Tao and Zhao, 2012; Hua et al, 2013), food systems (Ye et al, 2008; Thakur and Donnelly, 2010; Tao and Zhao, 2012), transportation systems (Chena et al, 2010) or health systems (Kuziemsky and Yazdi, 2011) systems. “Reference ontology” studies are continued to develop in various industries by researchers (Rese et al, 2013; Haller et al, 2008; Ulieru, 2005; Yeab et al, 2008; Grubic and Fan, 2010; Lu et al, 2010; Tursi, 2009; Ye, 2008) as well. 

In this article, our motivation is to be able to create an ontological model that covers a wide range of properties of SCs. On the other hand, this model will provide some answers to hard questions of SC field by presenting opportunities;

* increasing efficiency of artificial intelligence and intelligent agents in the decision making processes of SCs,
* observing effects of world class manufacturing applications on SCs,
* defining problem areas to improve performance of SCs,
* revealing inner dynamics of industries which have intense competitions between SCs such as health, food and defense,
* developing special types of SCM applications in case of disaster or crisis environments,
* increasing speed and precision for managers,
* improving optimization results,
* visualizing SC architectures.

There are some challenges for such an ontological SC model; (1) Is there any use of the description of a theoretical world such as a Supply Chain Ontology for a customer? Up to now, SCM seems to solve problems for industries, supply chains or supply chain members but customers. However, the customer is the most important element of any supply chain. One advantages of our model is perceived reflection of customer’s idea who can analyse the product or service before buying (or procurement) process. So, if there will be a mobile tool to read the code of the product (or service) everybody can reach any information they need. (2) From where does your model gather necessary information for converting it to a knowledge base? This is a real problematic topic that may refer to trade secrets and copyright issues as well as unwillingness of companies which are present at different places of SCs. But, there are some institutions which have all kind of information about properties of SCs already. Yet these are not a condensed form of information but we hope that open approaches will be the strategy of these SCs in the near future. (3) Is it possible to create such a complex world with all elements? Supply chains are complex but can be visible by appropriate tools like ontologies. In SC literature, there are tens of ontologies to show the conceptual architectures behind this complex infrastructures. So, we are motivated by these efforts (see for examples: Harps and Hansen, 2000; Lado et al, 1992; Lummus and Vokurka, 1999; New, 1996; Quinn, 1998; Simchi-Levi et al, 2000; Smith and Lockamy, 2000; Supply-Chain Council, 2006; Wells and Seitz, 2006) for defining and describing SCs in an open, sharable, reusable and changeable form.

## 3. Conceptual Framework of the SC Model

Foundational aspects of a supply chain are closely discussed by supply chain scientists (Davenport, 2004; Jung et al, 2004; Copacino, 1997; Milgate, 2001; Frankel et al, 2008; Narasimhan and Kim, 2001; Vargo, 2006; Ketchen and Hult, 2007; Helms et al, 2000; Simchi-Levi et al, 2004). Addition to this, relatively new issues are studied such as sustainability, member relations and value optimization. Scale of the respective supply chains (Towill, 1996; Surana et al, 2005; Kleijnen and Smits, 2003; Fynes et al, 2005; Towill et al, 1992; Christopher and Towill, 2000; Swaminathan et al, 1998; Holweg et al, 2005; Towill, 1996; Christopher, 2000) or macro-micro dimensions (Salema et al, 2010; Rudberg and West, 2008; Salema, 2009; Spekman et al, 1998) of them can be found in various SC journals. On the other hand, various scientists studied ontological properties and foundations of the supply chains (Noy, 2004; Pandit and Zhu, 2007; Grubic and Fan, 2010; Garcia-Flores et al, 2000; Zdravkovic et al, 2011; Chandra and Tumanyan, 2007; Chi, 2010; Fayez et al, 2005; Ye et al, 2008; Smirnov and Chandra, 2000; Ureten and Ilter, 2006).

In the light of these developments and discussions our model is specified with four layers to create a complete SC ontology world; Product Layer, Member Layer, Flow Layer and Operations Layer. Each layer has specific properties which are represented on the layer itself. A supply chain improvisation can be useful for describing layers and their ontological interaction. In this example, there is a main producer of a product (in this case this product is a table) as well as other members which act their roles as suppliers, transporters, distributors and customers.

### 3.1. Scope of the Model

![Figure 1: Development of the ontological supply chain dashboard (SCOD).][fig1]

As shown in the Figure 2, a supply chain network can be constructed to demonstrate a generic supply chain. For a real supply chain architecture, it can be said that its network can be more complex than the generic model.

![Figure 2: Representation of a generic SC network and its components.][fig2]

Scope of our model is 

### 3.2. Architecture: Layers and Interactions

Our model, SCOM, Ontological Supply Chain Management Model, is a domain ontology about the supply chain management. The model has four layers (Figure 3) of knowledge: Product, Flow , Member and Operation. Each layer has its own classes and properties. Layers can be integrated by overlapping in one level of knowledge which represents supply chain itself.

* Product Layer: This layer has a view of two sub-layers; first one is Goods and the second one is Service.
* Member Layer: In this layer, members of the supply chain are placed in appropriate order to connect product layer to flow layer.
* Flow Layer: This layer shows relationships that represent type of the flow between nodes of the member layer. It can be one of the three types; material, money and information. 
* Operation Layer: In operation layer of the model, there are various operations can be seen such as plan, source, make, deliver and return.
Properties, types of properties and their grammar examples can be seen in Appendices.

![Figure 3: Representation of conceptual model layers of SCOM.][fig3]

### 3.3. Ontological Foundations

In this article, we propose an ontological model in which Supply Chain Council’s SCOR (Supply Chain Operations Reference) is revised and embedded at the Operation Layer of the our model’s architecture. Addition to model’s layers of knowledge, a methodology used for development conceptually (Figure 4) such as (1) definition and conceptualization, (2) formalization and (3) application and visualization.

![Figure 4: Flowchart of the SCOM development methodology.][fig4]

In the definition and conceptualization step of the methodology, components of the ontology are defined as individuals (instances), properties and classes. Individuals, represent objects in the domain in which we are interested. Figure 5 shows a representation of some individuals in SC domain—in this article we represent individuals as diamonds in diagrams.

![Figure 5: Representation of individuals.][fig5]

Properties are binary relations on individuals - i.e. properties link two individuals together. For example, the property hasWeight might link the individual RawMaterial to the individual Weight. Properties can have inverses. For example, the inverse of hasWeight is isWeightOf. Properties can be limited to having a single value – i.e. to being functional. They can also be either transitive or symmetric. Figure 6 shows a representation of some properties linking some individuals together. 

![Figure 6: Representation of properties.][fig6]

Classes are interpreted as sets that contain individuals (Table 1). They are described using formal (mathematical) descriptions that state precisely the requirements for membership of the class. For example, the class RawMaterial would contain all the individuals that are raw materials in the domain of interest. Classes may be organised into a superclass-subclass hierarchy, which is also known as a taxonomy. Subclasses specialise their superclasses. For example consider the classes RawMaterial and PigAluminum – PigAluminum might be a subclass of RawMaterial (so RawMaterial is the superclass of PigAluminum). This says that, ‘All pig aluminum raw materials are raw materials’, ‘All members of the class PigAluminum are members of the class RawMaterials’. Classes are built up of descriptions that specify the conditions that must be satisfied by an individual for it to be a member of the class. 

**Table 1:** Relationship between a subclass and one of its properties.

![Table 1: Relationship between a subclass and one of its properties.][table1]

Second step of the ontology development is formalization. In this step a conceptual map is created by a reasoner with a grammar structure (Figure 7).

![Figure 7: An example of the conceptual map.][fig7]

Finally, in application and visualization step which is the last step of development, OWL (or RDF) is used for coding related conceptual map to an ontology (Table 2). Visualization of SC is a part of this step and it contains all respected layers in one unified architecture. It can be a 2D graph (Figure 8a) to represent the chain or a 3D interactive structure (Figure 8b). 

**Table 2:** Generic ontology application with OWL

![Table 2: Relationship between a subclass and one of its properties.][table2]

### 3.4. Mapping a Supply Chain

![Figure 8: (a) 2D and (b) 3D representation of a SC network.][fig8]

## 4. Case Study

Description of the case study ... 

![Figure 9: Representation of the main product for the case study.][fig9]

### 4.1. Architecture of the Case Study

![Figure 10: Representation of the supply chain for the case study.][fig10]

![Figure 11: Representation of the product layer.][fig11]

![Figure 12: Representation of the member layer.][fig12]

![Figure 13: Representation of the flow layer.][fig13]

![Figure 14: Representation of the operation layer.][fig14]

### 4.2. Ontological Properties

![Figure 15: Representation of individuals.][fig15]

![Figure 16: Representation of properties.][fig16]

**Table 3:** An example that shows relationship between a subclass and one of its properties.

![Figure 17: Conceptual map for the case study.][fig17]

**Table 4:** An example for a basic ontology application with OWL.

### 4.3. Mapping

![Figure 18: 2D representation of the example (Fig. 1) and a part of its HTML5+JavaScript code.][fig18]

![Figure 19: 3D interactive SCOM experiment.][fig19]

## 5. Discussion

In this article, we present a proposal to create a supply chain world as anyone can use it to establish a supply chain architecture in respect to related industry. This proposal has a fundamental ontology to create an conceptual supply chain world and its own dictionary (or vocabulary) to define properties and link each other. There are four integrated conceptual layers; (1) Product, (2) Member, (3) Flow and (4) Operation. Each conceptual layer has its own elements to define the layer itself with various properties. Therefore conceptual layers can be combined to obtain a complete supply chain model (Figure 9). Besides the unique layer structure of it, the presented model contains properties of the chain’s almost all elements.

![Figure 20: Representation of the architecture of SCOM.][fig20]

This article’s aim can be seen as a contribution purpose for revealing efficient answers to problems which are indicated in Introduction part. The presented model provides;

* For supply chain management software developers; ability to use an open model which is detailed and conceptually correct. It has a common industrial language to describe SC processes. 
* For SMEs; ability to (a) analyze their own added value to the chain, (b) find out problem areas and eliminate them, and (c) manage the evolving processes to better ones.   
* For academy; ability to (a) use the model for educational purposes in laboratories and (b) manipulate it to create various projects. 
* For public institutions; ability to increase speed and efficiency of their supply chains (eg. in case of emergency situations)

## References

*NOT INCLUDED*

[fig1]: http://hkilter.com/-images-scom/fig1.png "Figure 1: Development of the ontological supply chain dashboard (SCOD)."
[fig2]: http://hkilter.com/-images-scom/fig2.png "Figure 2: Representation of a generic SC network and its components."
[fig3]: http:/hkilter.com/-images-scom/fig3.png "Figure 3: Representation of conceptual model layers of SCOM."
[fig4]: http:/hkilter.com/-images-scom/fig4.png "Flowchart of the SCOM development methodology."
[fig5]: http:/hkilter.com/-images-scom/fig5.png "Representation of individuals."
[fig6]: http:/hkilter.com/-images-scom/fig6.png "Representation of properties."
[fig7]: http:/hkilter.com/-images-scom/fig7.png "An example of the conceptual map."
[fig8]: http:/hkilter.com/-images-scom/fig8.png "(a) 2D and (b) 3D representation of a SC network."
[fig9]: http:/hkilter.com/-images-scom/fig9.png "Representation of the main product for the case study."
[fig10]: http:/hkilter.com/-images-scom/fig10.png "Representation of the supply chain for the case study."
[fig11]: http:/hkilter.com/-images-scom/fig11.png "Representation of the product layer."
[fig12]: http:/hkilter.com/-images-scom/fig12.png "Representation of the member layer."
[fig13]: http:/hkilter.com/-images-scom/fig13.png "Representation of the flow layer."
[fig14]: http:/hkilter.com/-images-scom/fig14.png "Representation of the operation layer."
[fig15]: http:/hkilter.com/-images-scom/fig15.png "Representation of individuals."
[fig16]: http:/hkilter.com/-images-scom/fig16.png "Representation of properties."
[fig17]: http:/hkilter.com/-images-scom/fig17.png "Conceptual map for the case study."
[fig18]: http:/hkilter.com/-images-scom/fig18.png "2D representation of the example (Fig. 1) and a part of its HTML5+JavaScript code."
[fig19]: http:/hkilter.com/-images-scom/fig19.png "3D interactive SCOM experiment."
[fig20]: http:/hkilter.com/-images-scom/fig20.png "Representation of the architecture of SCOM."
[table1]: http:/hkilter.com/-images-scom/table1.png
[table2]: http:/hkilter.com/-images-scom/table2.png
