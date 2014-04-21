ts Cookbook
===========

Installs ts (test script).

Requirements
------------

- none?

Attributes
----------

#### ts::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['ts']['git_repository']</tt></td>
    <td>String</td>
    <td>Source Repo</td>
    <td><tt>https://github.com/thinkerbot/ts.git</tt></td>
  </tr>
  <tr>
    <td><tt>['ts']['git_revision']</tt></td>
    <td>String</td>
    <td>Source Revision</td>
    <td><tt>master</tt></td>
  </tr>
</table>

Usage
-----

Just include `ts` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[ts]"
  ]
}
```

License and Authors
-------------------
Authors: Simon Chiang
