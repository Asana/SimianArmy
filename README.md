[![NetflixOSS Lifecycle](https://img.shields.io/osslifecycle/Netflix/SimianArmy.svg)](OSSMETADATA)
[![Build Status](https://travis-ci.org/Netflix/SimianArmy.svg?branch=master)](https://travis-ci.org/Netflix/SimianArmy)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## PROJECT STATUS: RETIRED

**The Simian Army project is no longer actively maintained**. Some of the Simian
Army functionality has been moved to other Netflix projects:

* A [newer version of Chaos Monkey](https://github.com/netflix/chaosmonkey) is available as a standalone service.
* [Swabbie] is a new standalone service that will replace the functionality provided by Janitor Monkey.
* Conformity Monkey functionality will be rolled into other [Spinnaker] backend services.


[Swabbie]: https://github.com/spinnaker/swabbie
[Spinnaker]: https://www.spinnaker.io/

### REASON FOR FORKING (ASANA)
The original project is no longer maintained, and therefore not accepting patches. As of May 1st, 2021,
Bintray/Jcenter repositories will no longer resolve artifacts. The build.gradle in the original project
used jcenter to get the netflix-oss gradle plugin. This fork replaces that with mavenCentral, which now contains the needed artifact.

### DESCRIPTION

The Simian Army is a suite of tools for keeping your cloud operating in top
form.  Chaos Monkey, the first member, is a resiliency tool that helps ensure
that your applications can tolerate random instance failures


### DETAILS

Please see the [wiki](https://github.com/Netflix/SimianArmy/wiki).

### SUPPORT

[Simian Army Google group](http://groups.google.com/group/simianarmy-users)

Because the project is no longer maintained, there is a good chance that nobody will be able to answer a support question.

### LICENSE

Copyright 2012-2016 Netflix, Inc.

Licensed under the Apache License, Version 2.0 (the “License”); you may not use this file except in
compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is
distributed on an “AS IS” BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
implied. See the License for the specific language governing permissions and limitations under the
License.
