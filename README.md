# Auto-Py-To-App
 cx_Freeze GUI, designed for RiskQuantLib

# Notice
 If you meet bug when loading cx_Freeze as: 

 ```AttributeError: module 'lief._lief.logging' has no attribute 'LOGGING_LEVEL'```

 It is because cx_Freeze does not support the latest version of lief. You can fix this bug by uninstall lief and re-install an older version of lief, such as lief-0.12.1. Please use:

 ```pip install lief==0.12.1```