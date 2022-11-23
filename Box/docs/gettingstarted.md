# Getting Started

Building applications with **Box** is **simple and fast 🚀**. The example below shows how the BoxFramework should be imported into your projects

## Downloading the package
**Downloading the package from PyPi is simple.** Run the following command and a terminal.
```
pip install boxframework
```
This will install automatically the latest version of **Box**.

### LTS Installation
 If you want to install a **LTS** *(Long Term Support)* version of **Box**, you can run the following command.
```
pip install boxframework==0.2.1
```

## Project Example
This example shows how to **import the package into your application** and **how to use the currently available functions.**

```py
from box import frame

test1 = frame.Numbers.addone(1)
test2 = frame.Numbers.minusone(1)
print(test2)
print(test1)
```

Want to **contribute?** Check out our **[GitHub repository](https://github.com/Boxei/Box)!**