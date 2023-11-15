# vacuum-test

Using Vacuum for multi-file specs in a flat or nested (with subdirs) structure

`npm vacuum:flat`

Run vacuum against the flat structure. Everything validates without error.

`npm vacuum:nested`

Run vacuum against the nested structure. Vacuum reports the following error (linebreaks added for readability):

```
{ "time": "2023-11-14T16:18:12.009824-08:00",
  "level": "ERROR",
  "msg": "
    error building path item 'schema build failed: reference 'user.model.yaml#/User' cannot be found at line 11, col 21'
"}
```
