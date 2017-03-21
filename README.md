# Repo: puppet-example-hiera

## Content

This repositoy contains a customer controllable hiera config file.

## Background

Up to version 4.9, puppet can only have a global hiera.yaml config 
file per server instance (puppetserver). So the hiera.yaml can not
easily be part of the puppet repo. To allow controlling the content
of the hierarchy, an extra repo can be included on puppetmasters.

## License

Apache 2.0 License

```
   Copyright 2016 T-Systems Multimedia Solutions GmbH

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```