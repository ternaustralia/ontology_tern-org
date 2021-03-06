# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.16] - 2020-09-07
- Created classes in the tern-org namespace rather than previously using schema.org directly.

## [0.0.15] - 2020-03-20
### Added
- schema:QuantitativeRange
- schema:maxValue
- schema:minValue
- schema:unitCode
- schema:value
- tern-org:projectManager
- tern-org:ProjectManagerRole


## [0.0.14] - 2020-03-20
### Added
- import prov


## [0.0.13] - 2020-03-20
### Added
- schema:line
- Class restrictions on schema:GeoCoordinates and schema:GeoShape


## [0.0.12] - 2020-03-20
### Added
- schema:Place
- schema:location
- schema:elevation
- schema:geo
- schema:GeoCoordinates
- schema:GeoShape
- schema:latitude
- schema:longitude
- schema:Event


## [0.0.11] - 2020-03-20
### Added
- tern-org:DroneOperator
- tern-org:droneOperator


## [0.0.10] - 2020-03-19
### Added
- schema:Role and its subclasses
    - tern-org:CollaborativeInvestigatorRole
    - tern-org:CollaborativeOrganizerRole
    - tern-org:DataManagerRole
    - tern-org:FundingOrganizationRole
    - tern-org:LandOwnerRole
    - tern-org:PrincipalInvestigatorRole
    - tern-org:TechnicianRole
- tern-org:successor
- tern-org:predecessor
- tern-org:landOwner
- tern-org:collaboratorOrganization
- tern-org:principalInvestigator
- tern-org:technician
- tern-org:dataManager
- tern-org: collaboratorInvestigator
- schema:startDate
- schema:endDate

## [0.0.9] - 2020-02-17
### Added
- Added tern-org:isDissolved to explicitly identify if an organization has been dissolved. Filtering organizations with schema:dissolutionDate and org:changedBy was not explicit enough as sometimes these information may not be available/applicable. 

## [0.0.8] - 2020-02-12
### Added
- schema:FundingAgency.

## [0.0.7] - 2020-01-14
### Added
- tern-org:Manufacturer.
### Changed
- org:Site and schema:OwnershipInfo are now subclasses of schema:Thing.

## [0.0.6] - 2020-01-10
### Added
- Added org:Site, org:hasPrimarySite, org:hasSite, org:basedAt, and org:siteAddress.

## [0.0.5] - 2020-01-09
### Added
- Added schema:model.

## [0.0.4] - 2019-12-13
### Added
- Added schema:Product, schema:typeOfGood, and schema:OwnershipInfo and its properties. 

## [0.0.3] - 2019-12-04
### Added
- Added ORCID property for people.

## [0.0.2] - 2019-11-26
### Added
- Added specialised classes for Organisations. 

## [0.0.1] - 2019-11-24
### Added
- Initial release.
- A stable vocabulary about Organisation relationships to Organisations and People. Change Events as well as Postal Addresses are available.