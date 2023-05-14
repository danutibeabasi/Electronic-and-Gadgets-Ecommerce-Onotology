# Electronics and Gadgets E-commerce site ontology

# Abstract
This ontology is designed to model an Electronics and Gadgets E-commerce site, providing a structured framework for organizing and navigating the various electronic devices and gadgets that can be sold on the site. The ontology includes a hierarchy of categories and subcategories for different types of electronics, as well as characteristics and features that can be used to describe and compare these devices. It also incorporates information on accessories and peripherals that can be sold with these devices. The ontology can be used for a variety of purposes, such as product search, recommendation systems, and product comparisons. By providing a comprehensive and flexible framework for modeling e-commerce entities and their relationships, this ontology can facilitate more accurate and effective e-commerce applications, resulting in seamless transactions between buyers and sellers.

This repository contains the release of an ontology for an electronics and gadgets e-commerce site. The current release is version 1.0.1, which was released on April 20, 2023. The ontology is available in various formats including JSON-LD, RDF/XML, N-Triples, and TTL.

## Authors
The ontology was developed by Tareq Md Rabiul Hossain Chy, Nushrat Jahan and Utibeabasi Aniekan DAN all are from École nationale supérieure des mines de Saint-Étienne.

## License
The ontology is licensed under the GNU General Public License (GPL) version 3.0. A copy of the license is available in the repository.

## Introduction 
Ontology is a formal representation of concepts and their relationships in a domain. The ontology presented above provides a conceptual framework for modeling an e-commerce system. The motivation behind this ontology is to provide a structured and standardized vocabulary for describing e-commerce entities and their relationships. The ontology can be used for a variety of purposes, such as product search, recommendation systems, and product comparisons.

The ontology consists of various classes, such as Payment, Brand, Category, Delivery, Offer, Order, Product, Specification, Transaction, and User. These classes are arranged in a hierarchy that reflects their relationships. For example, Payment is a parent class that has two subclasses, PaymentProvider and PaymentMethod. PaymentProvider has two subclasses, Bank and CreditCardCompany, while PaymentMethod has three subclasses, CashPayment, CreditCardPayment, and PaypalPayment. Similarly, other classes in the hierarchy have their own subclasses and relationships.

The state of the art in e-commerce ontologies is constantly evolving, with new ontologies and extensions being developed to meet the needs of specific domains. The goal of this ontology is to provide a comprehensive and flexible framework for modeling e-commerce entities and their relationships, which can be used by various e-commerce applications. By using this ontology, e-commerce applications can provide more accurate and effective search results, product recommendations, and comparisons, as well as facilitate seamless transactions between buyers and sellers.

## Description
The Electronics and Gadgets E-commerce site ontology is designed to represent various entities and relationships within the context of an e-commerce platform. The ontology contains several classes such as Payment, Brand, Category, Delivery, Offer, Order, Product, Specification, Transaction, and User.

The Payment class includes various subclasses such as PaymentProvider, PaymentMethod, Bank, CreditCardCompany, CashPayment, CreditCardPayment, and PaypalPayment, while the Brand class includes a NamedBrand subclass with entities such as Apple, Asus, Dell, LG, Lenovo, Samsung, and Song. The Category class has subclasses such as AudioEquipment, GamingAccessories, and SmartPhone.

The Delivery class is composed of DeliveryMethod, DeliveryProvider, and DeliveryStatus subclasses, with entities such as ExpressDelivery, InternationalDelivery, LocalDelivery, SameDayDelivery, StandardDelivery, DHL, FedEx, UPS, Delivered, FailedDelivery, OutForDelivery, Processing, Returned, and Shipped.

The Offer class contains subclasses such as Discount and Promotion, with entities such as FixedAmountDiscount and PercentageDiscount. The Order class includes subclasses such as CancelledOrder and OnlineOrder, while the Product class includes subclasses such as EarPhone, HeadPhone, Iphone, and SamsungGalaxyPhone.

The Specification class includes subclasses such as Features, PerformanceSpecification, PhysicalSpecification, Price, ProductQuantitativeValue, and Warranty. The Transaction class has a single subclass, OnlineTransaction, while the User class includes a Role subclass with entities such as Buyer, RetailBuyer, WholesaleBuyer, Seller, Retailer, and WholeSaler.

Overall, the Electronics and Gadgets E-commerce site ontology provides a structured representation of various entities and relationships within an e-commerce platform, making it easier to manage and analyze data related to electronic and gadget products.

## Ontology Files

The main ontology files are:
- e-gadgets.owl: the ontology file in OWL format.
- e-gadgets.ttl: the ontology file in Turtle (ttl) format.

Both files contain the same ontology, but use different syntax and serialization formats.

## Documentation Files

The documentation files include:
- index.html: the main documentation file, providing an overview of the ontology and its classes and properties and full documentation.
- provenance: a folder detailing the provenance of the ontology, including its creators and sources.
- resources: a folder listing external resources that were used to develop the ontology.

## Serialization Files

The serialization files include:

- ontology.jsonld: the ontology file serialized in JSON-LD format.
- ontology.nt: the ontology file serialized in RDF N-Triples format.
- ontology.rdf: the ontology file serialized in RDF/XML format.
- ontology.ttl: the ontology file in Turtle (ttl) format.

These files provide alternative ways to represent the ontology in different serialization formats. 


## Format
The ontology is available is those format:
- JSON-LD
- RDF/XML
- N-Triples
- TTL

## Provenance
For the provenance of this ontology, please refer to provenance/provenance-en.html.

## References
- Zimmermann, A. (n.d.). Modelling e-commerce data and related knowledge. Retrieved from https://www.emse.fr/~zimmermann/Teaching/KRR/homework.html
- Garijo, D. (n.d.). WIzard for DOCumenting Ontologies (WIDOCO). Retrieved from https://github.com/dgarijo/Widoco
- Stanford University. (n.d.). Protégé: An open-source ontology editor. Retrieved from https://protege.stanford.edu/
- Hepp, M. (n.d.). GoodRelations ontology. Retrieved from https://www.heppnetz.de/projects/goodrelations/
- W3C. (2012). OWL 2 Web Ontology Language Document Overview (Second Edition). Retrieved from https://www.w3.org/TR/owl2-overview/
