SPDX-License-Identifier: Community-Spec-1.0

# File

## Summary

Refers to any object that stores content on a computer.

## Description

Refers to any object that stores content on a computer.
The type of content can optionally be provided in the contentType property.

If the isDirectory property is specified and set to true, then the file represents a directory and all content stored in that directory.

## Metadata

- name: File
- SubclassOf: /Software/SoftwareArtifact

## Properties

- contentType
  - type: /Core/MediaType
  - minCount: 0
  - maxCount: 1
- isDirectory
  - type: xsd:boolean
  - minCount: 0
  - maxCount: 1

## External properties restrictions

- /Core/Element/name
  - minCount: 1
