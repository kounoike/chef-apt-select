apt-select Cookbook
===================
use [apt-select](https://github.com/jblakeman/apt-select) for speed up updates and upgrades by selecting a mirror with the lowest latency to your ubuntu system.

Requirements
------------
#### cookbooks
- `git` apt-select needs git for get sources.
- `python-bs4` - apt-select needs pyton-bs4.


Attributes
----------
Currently, no attributes supported.

Usage
-----
Just include `apt-select` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[apt-select]"
  ]
}
```

Contributing
------------

e.g.
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: KOUNOIKE Yuusuke

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
 
