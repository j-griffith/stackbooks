## stackbooks

A minimal collection of Ansible Playbooks for some of the things I often need
to do on an OpenStack cloud.  In particular, playbooks for running 3'rd party
CI against the SolidFire Cinder driver.

## Motivation

Once upon a time, I wrote sos-ci and it was good.  Then things started getting
bloated and a bit hard to follow.  I also had duplicate playbooks laying around
because I do things like stack and run tempest outside of a CI context on an
almost daily basis.

So... why not make the playbooks a sub-repo and let them exist independently.

## Contents

Individual/stand-alone playbooks in .yml format, as well as a special `contrib`
directory for things like template files and any special scripts that we might
want to xfr to a machine and run.

## License

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
