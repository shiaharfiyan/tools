# tools

Console command line app powered by [Spectre.Console](https://spectreconsole.net/)

# Usage help
![image](https://user-images.githubusercontent.com/62987279/205299280-5a2e76b8-2324-4045-8db1-8a2474e36167.png)

# Plugin
For now, you can use plugin command to scan plugins directory ([exename]_plugins > tools_plugins), renaming the tools to other name will generate new plugin folder.
e.g. tools.exe renamed to a.exe, when executed it will generate a_plugins folder.

# Plugin's commands
```
tools plugin scan
```
![image](https://user-images.githubusercontent.com/62987279/205301756-fd080a90-e449-41aa-a93d-e790ff46ca54.png)

# Generator plugin
Include generate command.

![image](https://user-images.githubusercontent.com/62987279/205299725-77470572-5972-4f8e-9ccf-e991a4f37348.png)

### Example
```
tools gen text 15 -s an
```
![image](https://user-images.githubusercontent.com/62987279/205300350-f42419e4-39a8-4ab8-9840-fff9766d7599.png)

```
tools gen pattern XXXX-DD-DD-DDD-XXXXXXX -s an
```
![image](https://user-images.githubusercontent.com/62987279/205300677-86fa7ca1-bb70-4645-9331-7b7d72d410d4.png)

```
tools gen guid
```
![image](https://user-images.githubusercontent.com/62987279/205300846-578cf0de-7b2a-4e74-b322-53b344d0bb44.png)

## Create your own plugin
Read [tools.core](https://github.com/shiaharfiyan/tools.core#readme)
