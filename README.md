# Awesome Python Models [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome Python libraries, which implement models, schemas, serializers/deserializers, ODM's/ORM's, Active Records or similar patterns.

- [Awesome Python Models](#awesome-python-models)
    - [Model/Schema](#model-schema)
    - [ODM/ORM/Active Record](#odm-orm-active-record)
    - [Data/validation](#data-validation)
- [Other resources](#other-resources)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

- - -

## Model, Schema
*Libraries implementing some kind of model, letting you to serialize/deserialize python object to some data structures.*
* :ghost: [ascetic](https://bitbucket.org/emacsway/ascetic) - Ascetic, a lightweight Python datamapper ORM.
* ![alt text](https://avatars1.githubusercontent.com/u/25880274?v=3&s=32 "The attrs Cabal") 
  [attrs](https://github.com/python-attrs/attrs) - Python Classes Without Boilerplate.
* ![alt text](https://avatars2.githubusercontent.com/u/825580?v=3&s=32 "Jaime Gil de Sagredo Luna") 
  [booby](https://github.com/jaimegildesagredo/booby) - data modeling and validation Python library.
* ![alt text](https://avatars3.githubusercontent.com/u/5652479?v=3&s=32 "roronya")
  [causalmodels](https://github.com/roronya/causalmodels) - causal modeling in Python.
* ![alt text](https://avatars2.githubusercontent.com/u/452227?v=3&s=32 "Pylons Project")
  [colander](https://github.com/Pylons/colander) - A serialization/deserialization/validation library for strings, mappings and lists.
* ![alt text](https://avatars1.githubusercontent.com/u/824379?v=3&s=32 "tarvitz")
  [composite](https://github.com/tarvitz/composite/) - Declarative XML files parse, unparse with help of lxml library.
* ![alt text](https://avatars0.githubusercontent.com/u/3585075?v=3&s=32 "datastore")
  [datastore.objects](https://github.com/datastore/datastore.objects) - simple object mapper on top of datastore (not relational).
* ![alt text](https://avatars1.githubusercontent.com/u/574291?v=3&s=32 "Alfred Santacatalina Gea")
  [dirty-models](https://github.com/alfred82santa/dirty-models) - Dirty model for python.
* [dejavu](http://www.aminus.net/dejavu/chrome/common/doc/2.0a/html/intro.html) - Dejavu is a thread-safe Object-Relational Mapper for Python applications.
* ![alt text](https://avatars1.githubusercontent.com/u/723451?v=3&s=32 "Adrian Perez")
  [gnarl](https://github.com/aperezdc/gnarl) - Lightweight module to define serializable, schema-validated classes
* ![alt text](https://avatars1.githubusercontent.com/u/124167?v=3&s=32 "Sebastian Heimann")
  [guts](https://github.com/emolch/guts) - Lightweight declarative YAML and XML data binding for Python.
* ![alt text](https://avatars2.githubusercontent.com/u/29016?v=3&s=32 "Matt Good")
  [jsonmapper](https://github.com/mgood/jsonmapper) - Python JSON<->Object mapper.
* ![alt text](https://avatars1.githubusercontent.com/u/956019?v=3&s=32 "Szczepan Cieślik")
  [jsonmodels](https://github.com/beregond/jsonmodels) - jsonmodels is library to make it easier for you to deal with structures that are converted to, or read from JSON.
* ![alt text](https://avatars3.githubusercontent.com/u/1021723?v=3&s=32 "Max Kamenkov")
  [jsonobjects](https://github.com/caxap/jsonobjects) - jsonobjects allows you to declaratively specify how to extract and convert elements from a JSON document.
* ![alt text](https://avatars1.githubusercontent.com/u/94514?v=3&s=32 "Dimagi")
  [jsonobject](https://github.com/dimagi/jsonobject) - A simple json-object mapping for Python.
* :ghost: [jsonpickle](https://github.com/jsonpickle/jsonpickle) - Python library for serializing any arbitrary object graph into JSON.
* ![alt text](https://avatars1.githubusercontent.com/u/488217?v=3&s=32 "Mike Waites")
  [kim](https://github.com/mikeywaites/kim) - A JSON Serialization and Marshaling framework.
* ![alt text](https://avatars0.githubusercontent.com/u/111217?v=3&s=32 "Neil Isaac")
  [lazycontract](https://github.com/neilisaac/lazycontract) - Python library to define declarative contracts for serialization and deserialization.
* ![alt text](https://avatars3.githubusercontent.com/u/87913??v=3&s=32 "Aurélien")
  [lupin](https://github.com/holinnn/lupin) - Python document object mapper (load python object from JSON and vice-versa).
* ![alt text](https://avatars1.githubusercontent.com/u/10334301?v=3&s=32 "Python object serialization and deserialization, lightweight and fluffy")
  [marshmallow](https://github.com/marshmallow-code/marshmallow) - A lightweight library for converting complex objects to and from simple Python datatypes.
* :ghost: [metaparams](https://github.com/mementum/metaparams) - Python meta framework for Parameters in classes.
* ![alt text](https://avatars0.githubusercontent.com/u/6988?v=3&s=32 "Jamie Matthews")
  [micromodels](https://github.com/j4mie/micromodels) - Declarative dictionary-based model classes for Python.
* ![alt text](https://avatars2.githubusercontent.com/u/27304?v=3&s=32 "Andy Mikhailenko")
  [monk](https://github.com/neithere/monk) - An unobtrusive data modeling, manipulation and validation library.
* ![alt text](https://avatars3.githubusercontent.com/u/633032?v=3&s=32 "Hearsay Social")
  [normalize](https://github.com/hearsaycorp/normalize) - A toolkit for wrapping network data in Python objects.
* ![alt text](https://avatars0.githubusercontent.com/u/9479519?v=3&s=32 "Caxiam")
  [model-api](https://github.com/caxiam/model-api) - For modeling remote APIs in an ORM fashion.
* ![alt text](https://avatars2.githubusercontent.com/u/323018?v=3&s=32 "Marek Polak")
  [object-mapper](https://github.com/marazt/object-mapper) - ObjectMapper is a class for automatic object mapping in Python.
* ![alt text](https://avatars3.githubusercontent.com/u/1693676?v=3&s=32 "IOAM")
  [param](https://github.com/ioam/param) - Make your Python code clearer and more reliable by declaring Parameters.
* :ghost: [prettyrecord](https://github.com/skorczan/prettyrecord) - Structures like SQLAlchemy's declarative_base or Django's models in your project!
* ![alt text](https://avatars3.githubusercontent.com/u/4039449?v=3&s=32 "Samuel Colvin")
  [pydantic](https://github.com/samuelcolvin/pydantic) - Data validation using Python 3.6 type hinting.
* ![alt text](https://avatars3.githubusercontent.com/u/251374?v=3&s=32 "Spotify")
  [pyschema](https://github.com/spotify/pyschema) - Python library for class-based schema definition, object serialization and data validation.
* ![alt text](https://avatars1.githubusercontent.com/u/2567468?v=3&s=32 "Trust Sanger Institute - Human Genetics Informatics")
  [python-json](https://github.com/wtsi-hgi/python-json) - Python library for easily JSON encoding/decoding complex class-based Python models, using an arbitrarily complex (but easy to write!) mapping schema.
* ![alt text](https://avatars1.githubusercontent.com/u/922613?v=3&s=32 "30loops")
  [python-docar](https://github.com/30loops/python-docar) - A library for document oriented architectures.
* ![alt text](https://avatars3.githubusercontent.com/u/1820812?v=3&s=32 "F-Secure Corporation")
  [resource-api](https://github.com/F-Secure/resource-api) - A framework that allows developers decoratively define resources and relationships between them.
* ![alt text](https://avatars0.githubusercontent.com/u/7866441?v=3&s=32 "Schematics") 
  [schematics](https://github.com/schematics/schematics) - Python Data Structures for Humans™.
* ![alt text](https://avatars2.githubusercontent.com/u/275106?v=3&s=32 "Marrow Open Source Collective")
  [schema](https://github.com/marrow/schema/) - A generic declarative schema system.
* ![alt text](https://avatars0.githubusercontent.com/u/152941?v=3&s=32 "Jordan McCoy")
  [scheme](https://github.com/jordanm/scheme) - A declarative schema framework for Python.
* ![alt text](https://avatars1.githubusercontent.com/u/5894089?v=3&s=32 "Maksim Ekimovskii")
  [simple-models](https://github.com/prawn-cake/simple-models) - Simple models - keep your API messages in shape with validation and handy descriptors based object interface.
* ![alt text](https://avatars1.githubusercontent.com/u/1730315?v=3&s=32 "Aljosha Friemann")
  [simple_model](https://github.com/afriemann/simple_model) - a very simple model framework for python.
* ![alt text](https://avatars0.githubusercontent.com/u/939501?v=3&s=32 "Jace Browning")
  [yorm](https://github.com/jacebrowning/yorm) - Automatic object-YAML mapping for Python.
  

## ODM, ORM, Active Record
*Libraries, implementing ODM/ORM/Active Record patterns, letting you to work with external objects (REST, DB) like normal python instances.*
* ![alt text](https://avatars3.githubusercontent.com/u/2315?v=3&s=32 "dw")
  [acid](https://github.com/dw/acid) - SQLite for NoSQL.
* :ghost: [butterdb](https://github.com/terrible-ideas/butterdb) - butterdb is a Python object mapper for Google Drive Spreadsheets.
* ![alt text](https://avatars1.githubusercontent.com/u/27804?v=3&s=32 "Django")
  [django](https://github.com/django/django) - The Web framework for perfectionists with deadlines (includes ORM layer).
* ![alt text](https://avatars2.githubusercontent.com/u/825580?v=3&s=32 "Jaime Gil de Sagredo Luna")
  [finch](https://github.com/jaimegildesagredo/finch) - Asynchronous RESTful API consumer for Python.
* ![alt text](https://avatars1.githubusercontent.com/u/506791?v=3&s=32 "Steven Arcangeli")
  [flywheel](https://github.com/stevearc/flywheel) - Object mapper for Amazon's DynamoDB.
* ![alt text](https://avatars3.githubusercontent.com/u/48549?v=3&s=32 "Brian Jinwright")
  [kev](https://github.com/capless/kev) - Python ORM for key-value stores. Currently supported backends are Redis, S3, and a S3/Redis hybrid backend.
* ![alt text](https://avatars0.githubusercontent.com/u/3344584?v=3&s=32 "Center for Open Science")
  [modular-odm](https://github.com/CenterForOpenScience/modular-odm) - A database-agnostic Object-Document Mapper for Python.
* ![alt text](https://avatars3.githubusercontent.com/u/1502485?v=3&s=32 "MongoEngine")
  [mongoengine](https://github.com/MongoEngine/mongoengine) - A Python Object-Document-Mapper for working with MongoDB.
* ![alt text](https://avatars3.githubusercontent.com/u/555648?v=3&s=32 "Sébastien Eustace")
  [orator](https://github.com/sdispater/orator) - The Orator ORM provides a simple yet beautiful ActiveRecord implementation.
* ![alt text](https://avatars1.githubusercontent.com/u/3248238?v=3&s=32 "ponyorm")
  [pony](https://github.com/ponyorm/pony) - Pony Object Relational Mapper.
* ![alt text](https://avatars0.githubusercontent.com/u/119974?v=3&s=32 "Charles Leifer")
  [peewee](https://github.com/coleifer/peewee) - a small, expressive orm -- supports postgresql, mysql and sqlite.
* ![alt text](https://avatars1.githubusercontent.com/u/7572385?v=3&s=32 "GenePeeks, Inc.")
  [py-rest-orm](https://github.com/GenePeeks/py-rest-orm) - Generic Python REST ORM. Inspired by Django. Powered by Requests.
* ![alt text](https://avatars2.githubusercontent.com/u/2125212?v=3&s=32 "Mohamed Daif")
  [python-rest-model](https://github.com/mdaif/python-rest-model) - A standard way to consume a RESTful service, inspired by Django models.
* ![alt text](https://avatars0.githubusercontent.com/u/126780?v=3&s=32 "Burak Yiğit Kaya")
  [pyresto](https://github.com/BYK/pyresto) - A generic ORM framework for RESTful APIs.
* ![alt text](https://avatars3.githubusercontent.com/u/45120?v=3&s=32 "mongodb")
  [pymodm](https://github.com/mongodb/pymodm) - A Pythonic, object-oriented interface for working with MongoDB.
* ![alt text](https://avatars2.githubusercontent.com/u/236514?v=3&s=32 "Jharrod LaFon")
  [PynamoDB](https://github.com/jlafon/PynamoDB) - A pythonic interface to Amazon's DynamoDB.
* ![alt text](https://avatars3.githubusercontent.com/u/391998?v=3&s=32 "sebastien requiem")
  [redisco](https://github.com/kiddouk/redisco) - A Python Library for Simple Models and Containers Persisted in Redis.
* ![alt text](https://avatars2.githubusercontent.com/u/319844?v=3&s=32 "Andrei Horak")
  [remodel](https://github.com/linkyndy/remodel) - Very simple yet powerful and extensible Object Document Mapper for RethinkDB, written in Python.
* ![alt text](https://avatars1.githubusercontent.com/u/96970?v=3&s=32 "Joeri Bekker")
  [restorm](https://github.com/joeribekker/restorm) - RestORM allows you to interact with resources as if they were objects.
* :ghost: [storm](https://storm.canonical.com) - Storm is an object-relational mapper (ORM) for Python developed at Canonical.
* :ghost: [sqlobject](http://www.sqlobject.org) - SQLObject is a popular Object Relational Manager for providing an object interface to your database, with tables as classes, rows as instances, and columns as attributes.
* ![alt text](https://avatars2.githubusercontent.com/u/4458558?v=3&s=32 "SurveyMonkey")
  [wukong](https://github.com/SurveyMonkey/wukong) - An ORM Client library for SolrCloud.
* ![alt text](https://avatars0.githubusercontent.com/u/443794?v=3&s=32 "Alexander Zelenyak")
  [yadm](https://github.com/zzzsochi/yadm) - Yet Another Document Mapper (ODM) for MongoDB.
* ![alt text](https://avatars2.githubusercontent.com/u/119974?v=3&s=32 "Charles Leifer")
  [walrus](https://github.com/coleifer/walrus) - Lightweight Python utilities for working with Redis.


## Data validation
*Libraries for validating custom data structures.*  
* ![alt text](https://avatars1.githubusercontent.com/u/26229868?v=3&s=32 "eve")
  [cerberus](https://github.com/pyeve/cerberus) - Lightweight, extensible data validation library for Python.
* ![alt text](https://avatars0.githubusercontent.com/u/1328688?v=3&s=32 "Michael Selik")
  [destructure](https://github.com/selik/destructure) - Easy declarative schema validation with optional name-binding.
* ![alt text](https://avatars1.githubusercontent.com/u/329822?v=3&s=32 "Julian Berman")
  [jsonschema](https://github.com/Julian/jsonschema) - jsonschema is an implementation of JSON Schema for Python (supporting 2.7+ including Python 3).
* ![alt text](https://avatars0.githubusercontent.com/u/22664290?v=3&s=32 "Shivaprasad Bhat")
  [pyschemes](https://github.com/shivylp/pyschemes) - PySchemes is a library for validating data structures in Python.
* ![alt text](https://avatars0.githubusercontent.com/u/872991?v=3&s=32 "Davide Zanotti")
  [pyvaru](https://github.com/daveoncode/pyvaru) - Rule based data validation library for python 3.  
* ![alt text](https://avatars0.githubusercontent.com/u/1761188?v=3&s=32 "Shezad Khan")
  [required](https://github.com/shezadkhan137/required) - Required is a simple library which allows you to validate dependencies across multiple fields.
* ![alt text](https://avatars1.githubusercontent.com/u/619158?v=3&s=32 "Vladimir Keleshev")
  [schema](https://github.com/keleshev/schema) - schema is a library for validating Python data structures, such as those obtained from config-files, forms, external services or command-line parsing, converted from JSON/YAML (or something else) to Python data-types.
* ![alt text](https://avatars0.githubusercontent.com/u/6067509?v=3&s=32 "Colm O'Connor")
  [strictyaml](https://github.com/crdoconnor/strictyaml) - Type-safe YAML parser and validator.
* ![alt text](https://avatars0.githubusercontent.com/u/446761?v=3&s=32 "Podio")
  [valideer](https://github.com/podio/valideer) - Lightweight data validation and adaptation Python library.
* ![alt text](https://avatars0.githubusercontent.com/u/6367792?v=3&s=32 "guyskk")
  [validr](https://github.com/guyskk/validr) - A simple, fast, extensible python library for data validation.
* ![alt text](https://avatars0.githubusercontent.com/u/41767?v=3&s=32 "Alec Thomas")
  [voluptuous](https://github.com/alecthomas/voluptuous) - Voluptuous, despite the name, is a Python data validation library. It is primarily intended for validating data coming into Python as JSON, YAML, etc.


# Other resources
* [fullstackpython: Object-relational mappers (ORMs)](https://www.fullstackpython.com/object-relational-mappers-orms.html)
* [Python ORM/ODM Examples, For The Sleepy](https://github.com/sloria/PythonORMSleepy)
* [martinfowler: Active Record](https://www.martinfowler.com/eaaCatalog/activeRecord.html)
* [martinfowler: Data Mapper](https://martinfowler.com/eaaCatalog/dataMapper.html)
* [wiki: Object-relational mapping](https://en.wikipedia.org/wiki/Object-relational_mapping)
* [Higher Level Database Programming](https://wiki.python.org/moin/HigherLevelDatabaseProgramming)


# Other Awesome Lists
List of lists.
* Monty
    * [awesome](https://github.com/sindresorhus/awesome)
    * [lists](https://github.com/jnv/lists)
* Python
    * [awesome-python](https://github.com/vinta/awesome-python)
    * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy)
    * [pycrumbs](https://github.com/kirang89/pycrumbs)
    * [python-github-projects](https://github.com/checkcheckzz/python-github-projects)
    * [python_reference](https://github.com/rasbt/python_reference)
    * [pythonidae](https://github.com/svaksha/pythonidae)
    
# Contributing
If you know some project/library that is not listed here, just let me know! Or even better, create a pull request.
