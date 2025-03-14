# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 7.0.0 - 2022-08-18

    - Added an interactive console menu system. You can access it by using the --interactive flag.

## 6.1.0 - 2022-06-13

    - Updated to pyattck-data 2.1.0

## 6.0.0 - 2022-06-09

    - BREAKING CHANGE RELEASE
        - Complete revamp and removed 70% of code base
    - CONSIDER THIS A NEW VERSION

## 5.4.0 - 2022-04-04

    - Added access to malwares from techniques (thanks aacienfuegos)
    - Access deprecated attribute from all MITRE ATT&CK objects (thanks aacienfuegos)
    - Updated documentation
    - Improved support of ICS framework (thanks cohmoti)
    - Bumped minor version

## 5.0.0 - 2021-10-22

    - Added new V10 data sources support
    - Added ICS Framework
    - Documentation updates

## 2.1.0 - 2020-08-25

    - Fixed issue with mitigations not being accessible in enterprise techniques
    - Added ability to access nested subtechniques (or not) using 
      nested_techniques parameter when instantiating Attck object

## 2.0.5 - 2020-05-19

    - Fixed relationship links in enterprise malwares and techniques
    - Fixed retrieval of id property in preattack actors
    - Updated methods _set_wiki, _set_id, and _set_reference in each frameworks base classes

## 2.0.4 - 2020-05-15

    - Updated pendulum requirements version to have max version
    
## 2.0.3 - 2020-05-15 

    - Updating pendulum requirements version

## 2.0.2 - 2020-05-08

    - Updated and modified docstrings across package

## 2.0.1 - 2020-05-06

    - Fixed issue with pre-attack and mobile attack technique id mappings

## 2.0.0 - 2020-02-14
    
    - Major update which includes external datasets to add additional context to MITRE ATT&CK
    - Restructured and created enterprise object type for future expansion into other MITRE ATT&CK Frameworks
    - Improved access and speed when accessing relationship objects
    - Added configuration settings and optional loading of datasets from local file paths

## 1.0.3

    - Fixed issue with appending techniques correctly

## 1.0.2

    - Updated Documentation

## 1.0.1

    - Updating Documentation with new reference links

## 1.0.0
    
    - Initial release of pyattck to PyPi
