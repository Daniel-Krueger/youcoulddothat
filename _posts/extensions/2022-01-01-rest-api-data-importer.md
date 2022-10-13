---
permalink: /extension/:slug
layout: extension
title: "RestApi Dataimporter"
tags:
  - REST API
 # - Action
 # - Business rule
 # - Data source
 # - Label template
 # - Field extension JS
 # - Field extension logic
 # - Solution
excerpt: 
    The application uses Excel and the public WEBCON REST API to import/export data between WEBCON BPS environments.
sampleImage: 
  - url: https://www.ecosia.org/76a1f9cc-801a-4c09-9850-4ac21b67deb6 
    title: 'Teaser risk management'
source:
  url: https://github.com/WEBCON-BPS/RestApi-DataImporter
  label: 'REST API data-importer'
  type: GitHub
description:
  Please note that this is just a sample application, delivered under attached license.
  The application uses Excel and the public WEBCON REST API to import/export data between WEBCON BPS environments.
  A REST API account is required for the program to work correctly. Creating such an account is described here https://developer.webcon.com/docs/registration-and-authentiaction/
  Additionally, the application uses an external Aspose.Cells component, an appropriate license will also be required for it work correctly. Without a license, we will be able to use the demo version. The license file must be added to the project, then set the build action in its properties as embedded resource. Such a license must be assigned in the constructor of the ImporterMainForm class, an example in comments is already found there.
last_modified_at: 2022-09-10
---


