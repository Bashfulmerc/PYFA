# PYFA
pyfa error

OS version: 	Windows-7-6.1.7601-SP1
Python: 	2.7.10
wxPython: 	3.0.2.0
SQLAlchemy: 	1.0.5
Logbook: 	1.0.0
pyfa version: 1.30.0 Stable - YC119.7 1.0
pyfa root: C:\Users\User\Documents\PYFA = EFT ++\pyfa\pyfa
save path: C:\Users\User\.pyfa
fs encoding: mbcs

EXCEPTION: [Errno 13] Permission denied: u'C:\\Users\\User\\.pyfa\\settings\\pyfaEOSSettings'

  File "C:\Users\User\Documents\PYFA = EFT ++\pyfa\pyfa\library.zip\gui\mainFrame.py", line 352, in OnClose
    SettingsProvider.getInstance().saveAll()
  File "C:\Users\User\Documents\PYFA = EFT ++\pyfa\pyfa\library.zip\service\settings.py", line 107, in saveAll
    settings.save()
  File "C:\Users\User\Documents\PYFA = EFT ++\pyfa\pyfa\library.zip\service\settings.py", line 126, in save
    with open(self.location, "wb") as f:


OCCURS on attempted closure of program
