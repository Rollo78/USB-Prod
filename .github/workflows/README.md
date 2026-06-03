AMTEQ Produktion Android DEV USB

Diese APK ist nur fuer Entwicklung/Test am Handy.

URL in der App: http://127.0.0.1:5046/
Verbindung erfolgt ueber USB mit ADB Reverse:
adb reverse tcp:5046 tcp:5046

Ablauf:
1. APK ueber GitHub Action bauen.
2. APK am Handy installieren.
3. Handy per USB am PC anstecken.
4. Im Server-Ordner USB_TEST_STARTEN.bat starten.
5. PC-Server starten.
6. App am Handy oeffnen.
