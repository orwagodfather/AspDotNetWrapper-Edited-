# **AspDotNetWrapper** for test machine keys `viewstate` in **ASP.NET**

# download

clone and unzip file in windows 

# Used


```
AspDotNetWrapper.exe --keypath MachineKeys.txt --encrypteddata <viewstate> --decrypt --purpose=viewstate  --modifier=<__VIEWSTATEGENERATOR> --macdecode
```

replace the `<viewstate>` to `viewstate=` parameter `value  in the source`
replace the `<__VIEWSTATEGENERATOR>` to `__VIEWSTATEGENERATOR=` parameter `value  in the source`


![image](https://github.com/user-attachments/assets/2ee2d977-a5ac-4098-b462-4c551adf1b08)
