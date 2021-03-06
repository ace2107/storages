# Changelog for Thoth's Storage Module

## [0.1.0] - 2018-Jul-17 - goern

### Fixed

Make slash after prefix explicit, [#59](https://github.com/thoth-station/storages/pull/59)

## [0.0.33] - 2018-Jul-01 - goern

### Changed

Coala now has a max_line_lenght of 120, some unneeded E501 have been removed.

## [0.0.30] - 2018-Jun-26 - goern

### Added

Starting with this release we have a Zuul-CI pipeline that:

* lints on Pull Requrest and gate/merge

## Release 0.5.3 (2018-10-11T16:13:37)
* Automatic update of dependency boto3 from 1.9.19 to 1.9.21
* using envvar that are injected by OpenShift to discover janusgraph servcie host and port, this requires that a service called "janusgraph" is created
* Automatic update of dependency boto3 from 1.9.16 to 1.9.19
* Automatic update of dependency pytest from 3.8.1 to 3.8.2
* Automatic update of dependency boto3 from 1.9.15 to 1.9.16
* Update README file
* Automatic update of dependency boto3 from 1.9.14 to 1.9.15
* Automatic update of dependency thoth-common from 0.3.5 to 0.3.6
* Introduce query for gathering dependencies
* Automatic update of dependency thoth-common from 0.3.2 to 0.3.5
* Automatic update of dependency boto3 from 1.9.11 to 1.9.14
* Introduce method for gathering python package versions
* Introduce observation models and adapter
* Specify Python index from which the package came from
* Automatic update of dependency thoth-common from 0.3.1 to 0.3.2
* Automatic update of dependency boto3 from 1.9.10 to 1.9.11
* Automatic update of dependency boto3 from 1.9.9 to 1.9.10
* Introduce check whether the given Python package exists
* Automatic update of dependency pytest from 3.7.3 to 3.8.1
* Automatic update of dependency boto3 from 1.8.3 to 1.9.9
* Automatic update of dependency pytest-cov from 2.5.1 to 2.6.0
* Automatic update of dependency thoth-common from 0.2.4 to 0.3.1
* Automatic update of dependency moto from 1.3.4 to 1.3.6
* Update janusgraph.py
* Sync debian packages to the graph database

## Release 0.5.4 (2018-10-12T09:14:50)
* Edge property is not a vertex property
* Automatic update of dependency thoth-common from 0.3.6 to 0.3.11
* Automatic update of dependency boto3 from 1.9.21 to 1.9.22

## Release 0.6.0 (2018-10-22T10:43:00)
* Automatic update of dependency thoth-common from 0.3.11 to 0.3.12
* fixing project.post.jobs.trigger-build.vars.webhook_url
* Automatic update of dependency boto3 from 1.9.27 to 1.9.28
* Automatic update of dependency boto3 from 1.9.26 to 1.9.27
* Automatic update of dependency requests from 2.19.1 to 2.20.0
* Automatic update of dependency boto3 from 1.9.25 to 1.9.26
* Automatic update of dependency boto3 from 1.9.24 to 1.9.25
* Automatic update of dependency pytest from 3.8.2 to 3.9.1
* Automatic update of dependency boto3 from 1.9.23 to 1.9.24
* Add timestamp to the result schema
* Automatic update of dependency cython from 0.28.5 to 0.29
* Automatic update of dependency boto3 from 1.9.22 to 1.9.23

## Release 0.7.0 (2018-10-30T22:37:43)
* Use job id as document id instead of pod id
* Implement image lookup for fast checks of image analyses
* Automatic update of dependency thoth-common from 0.3.14 to 0.3.15
* Automatic update of dependency thoth-common from 0.3.13 to 0.3.14
* Automatic update of dependency thoth-common from 0.3.12 to 0.3.13
* Automatic update of dependency pytest from 3.9.2 to 3.9.3
* Automatic update of dependency boto3 from 1.9.32 to 1.9.33
* Automatic update of dependency boto3 from 1.9.30 to 1.9.32
* Automatic update of dependency boto3 from 1.9.29 to 1.9.30
* Automatic update of dependency pytest from 3.9.1 to 3.9.2
* Automatic update of dependency boto3 from 1.9.28 to 1.9.29
* Remove ignore comments
* Fix CI

## Release 0.7.1 (2018-10-31T00:40:59)
* Fix wrong base class

## Release 0.7.2 (2018-10-31T12:22:42)


## Release 0.7.3 (2018-11-07T10:04:34)
* Automatic update of dependency boto3 from 1.9.38 to 1.9.39
* Automatic update of dependency boto3 from 1.9.37 to 1.9.38
* Introduce dependency monkey reports adapter
* Fix query to retrieve all package versions
* Exclude test directory
* Automatic update of dependency moto from 1.3.6 to 1.3.7
* Automatic update of dependency thoth-common from 0.3.16 to 0.4.0
* Fix document naming
* Fix CI failures
* Rename error flags
* Introduce unparsed flag
* Introduce unparsed flag
* Automatic update of dependency pytest from 3.9.3 to 3.10.0
* Keep schema up2date with recent schema changes
* Hostname is not equal to document id
* Introduce methods for checking unsolvable and unparsed packages
* Automatic update of dependency boto3 from 1.9.36 to 1.9.37
* Introduce transitive dependencies gathering method
* Normalize names of packages that are inserted into graph database
* Automatic update of dependency boto3 from 1.9.35 to 1.9.36
* Automatic update of dependency uvloop from 0.11.2 to 0.11.3
* Automatic update of dependency boto3 from 1.9.34 to 1.9.35

## Release 0.7.4 (2018-11-07T13:17:46)
* Fix unparseable solver result sync

## Release 0.7.5 (2018-11-08T10:43:48)
* Use common date utilities for creating datetime from timestamp
* Fix queries to janusgraph - aggregate by document ids
* Add method for counting documents
* Add methods in janusgraph for metrics
* Automatic update of dependency boto3 from 1.9.39 to 1.9.40
* Correctly handle decorator wrappers

## Release 0.7.6 (2018-11-08T13:09:47)
* Fix indentation error

## Release 0.8.0 (2018-11-15T12:22:25)
* Automatic update of dependency boto3 from 1.9.44 to 1.9.45
* Automatic update of dependency pytest from 3.10.1 to 4.0.0
* Automatic update of dependency boto3 from 1.9.43 to 1.9.44
* Add a query to check for solved packages
* Automatic update of dependency boto3 from 1.9.42 to 1.9.43
* Automatic update of dependency pytest from 3.10.0 to 3.10.1
* Automatic update of dependency boto3 from 1.9.41 to 1.9.42
* Automatic update of dependency boto3 from 1.9.40 to 1.9.41
* Automatic update of dependency requests from 2.20.0 to 2.20.1
* Extend quieries to janusgraph
* Extend quieries to janusgraph
* Fix return values
* Make sure to hit indexes with queries
* Fix indentation error
