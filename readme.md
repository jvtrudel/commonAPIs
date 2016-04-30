# Common APIs Pattern

API is an important concept in collaborative web development. Combining different APIs that provides data or services is a powerful way to rapidly build useful services at very low cost. APIs are already well spread but their co-integration still represent an important challenge for the web development community.

## An abstract model to catalyze API ecosystem development

This project is an attempt to formalize the problem as a pattern that could inspire solution developers and enhance collaborative tools development.

## Ontology

### Users

  - **business-collaborator**: individual or organization that have interest in the development of an App.
  - **End Users**: individual that use an App.
  - **End-product-developer** : individual or organization developing an App.
  - **Integrator**: individual or organization developing Glueing API.
  - **data/service provider**: individual or organization that provide data or service through an API.

### Strategy or goal

Real life, commercial or business goals of the business-collaborators.


### Use case

The strategy formulated from the end-user's point of view. One strategy may be implemented with many use cases.

### Virtual/real axis

What is the virtual domain (web, APIs, cloud, etc.) and what in is the reality (people, event, places, etc.).

### local/global

Things located in local area vs things that are from everywhere else.

### App

Web app, offline app, website, etc. Anything with which users can directly interact.

### Glueing API

API developed to combine different data sources and services. An ideal Glueing API could be the only tool used by web/app developers.

### Data sources API

Source of data that could be accessed using an API.

### Services API

Web service that can treat provided data.

## Actual and important issues

### Data format specification and conversion

We need to rapidly and easily understand data formats and structure. Standards are not always available or good choice. Declarative specifications are perfect and allow organic collaborative development.

### API (data source and service) availability

Good and appropriate data should be accessible through API.

### (semi)Automatic integration of new API

It should be possible to automatically (or almost!) integrate new set of data, or new services.

## Example and proof of concept

See [http://tmoms.felab.ca](http://tmoms.felab.org) for an application example. Sources of the proof of principle can be found there [https://github.com/jvtrudel/commonAPIs/blob/master/examples/tmoms](https://github.com/jvtrudel/commonAPIs/blob/master/examples/tmoms)

![tm + OMS example](https://github.com/jvtrudel/commonAPIs/blob/master/data/example1.jpg)
