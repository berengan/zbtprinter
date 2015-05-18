# zbtprinter
A Cordova/Phonegap driver for Zebra bluetooth printers

##Usage
You can send data in ZPL Zebra Programing Language:

```
cordova.plugins.zbtprinter.print("AA:BB:CC:DD:EE:FF","^XA^FO10,10^AFN,26,13^FDHello, World!^FS^XZ",
    function(success) { 
        alert("Print ok"); 
    }, function(fail) { 
        alert(fail); 
    }
);
```

##Install
###Cordova

```
cordova plugin add https://github.com/berengan/zbtprinter.git
```

##ZPL - Zebra Programming Language
For more information about ZPL please see the  [PDF Official Manual](https://support.zebra.com/cpws/docs/zpl/zpl_manual.pdf)
