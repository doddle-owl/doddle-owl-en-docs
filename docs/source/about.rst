=======================
What is DODDLE-OWL?
=======================

DODDLE-OWL (a Domain Ontology rapiD DeveLopment Environment – OWL extension) is a domain ontology development tool for the Semantic Web. DODDLE-OWL makes reuse of existing ontologies and supports the semi-automatic construction of taxonomic and other relationships in domain ontologies from documents.

Introduction
==================
Ever since the necessity of ontologies has been acknowledged to share common understandings between people and software agents, ontologies have become very popular and significant in many application areas. As the Semantic Web is the most attractive application filed of ontologies, many ontologies has been represented by the ontology description language, OWL (Web Ontology Language). However, as well as other application areas, it still takes many costs for users to develop and maintain domain ontologies.

Regarding domain ontology development support, many tools have been done with knowledge engineering, natural language processing and data mining techniques to make possible automatic domain ontology construction from existing information resources, such as texts and general ontologies. However, as the techniques are not yet mature to achieve the task and domain ontology structure depends on the aspects from human experts (users), full automatic process does not go well with the task. Instead of developing full automatic environment, it is more important to provide refined semi-automatic environment with integrated facilities to construct practical domain ontologies. Furthermore, as open software is easy to evolve developed software, it is significant to build up interactive domain ontology development environment with open software.

From the above consideration, we propose an interactive domain ontology development environment called DODDLE-OWL (a Domain Ontology rapiD DeveLopment Environment – OWL extension). DODDLE-OWL is written in Java language. DODDLE-OWL has the following six modules: Ontology Selection Module, Input Module, Construction Module, Refinement Module, Visualization Module, and Translation Module. DODDLE-OWL makes reuse of existing ontologies such as WordNet and EDR as general ontologies to construct taxonomic relationships (defined as classes) and other relationships (defined as properties and their domains and ranges) for concepts. Especially, to realize the user-centered environment, DODDLE-OWL is mounted with user interactive functions in each module.
