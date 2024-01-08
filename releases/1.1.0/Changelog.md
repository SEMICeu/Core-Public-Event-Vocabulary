# Core Public Event Changelog

## Introduction

This document describes the (major) changes to [the current version 1.0.0](https://github.com/SEMICeu/Core-Public-Event-Vocabulary/tree/master/releases/1.0.0) of the Core Public Event Vocabulary for which a new version is being proposed ([version 1.1.0](https://semiceu.github.io/Core-Public-Event-Vocabulary/releases/1.1.0/)). The list of changes results in the new version to be considered as a minor release.

All of the changes were discussed and approved during the [webinar](https://joinup.ec.europa.eu/collection/semic-support-centre/event/webinar-review-core-vocabularies) of 27/10/2023.

## Detailed changes from v2.1.0 to v2.1.1

The table below gives an overview of the classes (and their definitions) within both data models. Classes that are related are juxta-positioned.

**C** stands for changes in classes

**R** stands for changes in relationships

**P** stands for changes in properties

**D** stands for changes in data types

| Nr | Core Public Event Vocabulary v1.0.0 | Core Public Event Vocabulary v1.1.0 | Rationale | GitHub / Change |
| --- | --- | --- | --- | --- |
| P1 | PublicEvent:eventStatus | PublicEvent:eventStatus | Addition of an eventStatus property using the [RFC 5545](https://www.rfc-editor.org/rfc/rfc5545) code list, with an appropriate usage note to model it correctly. | [#25](https://github.com/SEMICeu/Core-Public-Event-Vocabulary/issues/25) |
| P2 | - | PublicEvent:expectedNumberOfParticipants | The property is added to better model statistic of the event. | [#7](https://github.com/SEMICeu/Core-Public-Event-Vocabulary/issues/7) |
| P3 | PublicEvent:hasParticipation | PublicEvent:hasParticipation | Instances of the property can be counter to better model statistic of the event. | [#7](https://github.com/SEMICeu/Core-Public-Event-Vocabulary/issues/7) |
