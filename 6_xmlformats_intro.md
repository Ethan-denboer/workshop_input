---
jupytext:
  cell_metadata_filter: -all
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# 6. Introduction to the Alto/Didle, TEI and Page format

Although XML is a structured way to store data, the structuring itself is left to the user. This means that there is not one style or format of XML. This has led to a high variety of different formats and styles of storing data and information with XML. To battle this multiple standards have been developed. These standards offer a guideline or framework for developers to store data. 

In humanities research multiple standards are in use. In this chapter we will shortly describe some of the standards that are commonly used within the KB, national library of the Netherlands, and will be used in this workshop.


## Alto
ALTO (Analyzed Layout and Text Object) is an open XML Schema developed by the EU-funded project called METAe. The standard was developed for the description of text OCR and layout information of pages for digitized material. The goal of this standard was to describe the layout and text in such a way that it would enable the reconstruction of the original appearance. 
ALTO is often used with a metadata encoding file for the description of the whole digitized object and for creating references across mulitple ALTO files, such as reading order description. Commenly used files are Didl and METS.

The ALTO standard is hosted by the Library of Congress (USA) and maintained by the Editorial Board initialized at the same time.

## Didl

The MPEG-21 Digital Item Declaration Language, Didl uses set of abstract concepts that together form a defined data model for complex digital objects. The overall goal for DIDL was to establish a uniform and flexible multimedia data abstraction and interoperabilty schema for declaring digital items. Within the MPEG-21 framework, a Digital Item is defined as a structured digital object with a standard representation, identification, and description. This Digital Item entity is also the fundamental unit of distribution and transaction within this framework. 

## TEI

The Text Encoding Initiative (TEI) is a non-profit consortium which collectively develops and maintains a standard for the representation of texts in digital form. They have developed a set of Guidelines which specify encoding methods for machine-readable texts, moestly focused on the humanities, social sciences and linguistics. The TEI Guidelines are widely used by libraries, museums, publishers, and individual scholars to present texts for online research, teaching, and preservation. 

The TEI Consortium is a non-profit membership organization composed of academic institutions, research projects, and individual scholars from around the world. 

## PAGE
PAGE has been designed to support the individual stages of the workflow of document image analysis methods (from document image enhancement to layout analysis to OCR) and their evaluation. PAGE is an image representation framework that not only records layout structure and page content, but information on image characteristics such as image borders, distortions and corresponding corrections, etc. 
It is used extensively in public contemporary and historical ground-truthed datasets and in the ICDAR Page Segmentation competition series.





