# Prepare the config file
In order to prevent any kind of confusion **only XML** configs are accepted. You can easily convert from the other formats to XML by using the in-game command `/igi save <filename>.xml`.

*Note: even if your config file is already in the XML format you should still use the command before submission. That will ensure that the file is properly formatted.*

## Config file name
All submitted files should have the following filename structure:

```
InGameInfo-<author>-<shortname>.xml
InGameInfo-<author>-<shortname>.md
InGameInfo-<author>-<shortname>-001.png
InGameInfo-<author>-<shortname>-002.png
InGameInfo-<author>-<shortname>-003.png
...
```

Where you should replace the `author` tag with your own name/nickname and `shortname` with something short that roughly describes your config file (`default_tweaked`, `compact`, `thaumcraft`, etc).

# Description file
Use the following template for your description file (`.md`):
```
## < name >
< short description >

**Config file:** [click!](InGameInfo-<author>-<shortname>.xml)
**Author:** < author >

### Screenshots
![](InGameInfo-<author>-<shortname>-001.png)
![](InGameInfo-<author>-<shortname>-002.png)
![](InGameInfo-<author>-<shortname>-003.png)
...
```

Optionally, you may specify contributors bellow the author using the following template:
```
**Contributors:**
  * < contributor 1 >
  * < contributor 2 > - < optional short description of the contribution >
  * < contributor 3 > - < optional short description of the contribution >
  * ...
```
