# Binnen-I-be-gone-für-Safari
Für alle, die Binnen-I be gone für Safari bislang vermisst haben


Leider gibt es für Safari relativ wenig Addons, so gibt es auch keine Binnen-I be gone Erweiterung. 
Zum Glück hat Apple in ihre Entwicklungsumgebung Xcode ein Übersetzer eingebaut, mit dem man Chrome oder Firefox Erweiterungen einfach für Safari übersetzen lassen kann. 

Dies ist eine Anleitung wie man das Beliebte Binnen-I be gone Addon für Chrome oder Firefox für Safari übersetzten kann. 
Keine Angst, selber programmieren muss man nicht, ein bisschen Ahnung von Xcode und dem Terminal schadet allerdings auch nicht. 


1. Google Chrome installieren (sollte auch mit Firefox funktionieren) und die Binnen-I be gone Erweiterung installieren 

2. Xcode installieren
<img width="845" alt="Bildschirmfoto 2021-04-28 um 16 36 51" src="https://user-images.githubusercontent.com/35576062/116422378-f878bb80-a83f-11eb-9b86-052bcf527882.png">
 
 
3. Seine Apple ID für den Entwickler Modus freischalten [(Link)](https://idmsa.apple.com/IDMSWebAuth/signin?appIdKey=891bd3417a7776362562d2197f89480a8547b108fd934911bcbea0110d07f757&path=%2Faccount%2F&rv=1)
<img width="2048" alt="Bildschirmfoto 2021-04-28 um 16 33 23" src="https://user-images.githubusercontent.com/35576062/116421855-82745480-a83f-11eb-850f-58106de3345a.png">
 
 
4. Xcode starten. Wenn man gefragt wird, ob man zusätzliche Komponenten installieren möchte auf "Install" klicken
![1ca552c25db049bc850a4cc3db084a08](https://user-images.githubusercontent.com/35576062/116421679-5b1d8780-a83f-11eb-9c6f-50fe6d2ea575.png)


5. In den Einstellungen von Xcode unter "Accounts" seine Apple ID eintragen
<img width="942" alt="Bildschirmfoto 2021-04-28 um 16 39 49" src="https://user-images.githubusercontent.com/35576062/116422916-7e950200-a840-11eb-84a0-9fd57d1e3a8c.png">
 
 
7. Xcode schließen

8. Finder öffnen, mit Shift+Command+. versteckte Ordner Anzeigen lassen
![img](https://user-images.githubusercontent.com/35576062/116423911-6376c200-a841-11eb-9102-a86f840c812a.png)


9. Nach /Users/BENUTZERNAME/Library/Application Support/Google/Chrome/Default/Extensions Navigieren und den Ordner 2.7_0 kopieren

10. Irgendwo einen neuen Ordner erstellen für das Xcode Projekt, z.B. bei /Dokumente/Xcode/Binnen-I be gone

11. In diesen Ordner jetzt den gerade kopierten Ordner einfügen
<img width="1136" alt="Bildschirmfoto 2021-04-28 um 16 49 21" src="https://user-images.githubusercontent.com/35576062/116424447-cf592a80-a841-11eb-8b9c-5c1d480234c1.png">


12. Terminal öffnen und zu dem gerade kopierten Ordner navigieren. Wenn Sie dem obrigen Beispiel gefolgt sind müssen Sie cd /Users/seb201/Documents/Xcode/Binnen-I\ be\ gone eintippen

13. Ins Terminal ls eingeben, jetzt sollte da 2.7_0 stehen, wenn nicht sind Sie im falschen Ordner oder haben den falschen Ordner kopiert
<img width="682" alt="Bildschirmfoto 2021-04-28 um 16 52 03" src="https://user-images.githubusercontent.com/35576062/116425074-51495380-a842-11eb-992a-f29b6c954ecb.png">


14. Jetzt xcrun safari-web-extension-converter 2.7_0 ins Terminal eintippen
<img width="682" alt="Bildschirmfoto 2021-04-28 um 16 55 34" src="https://user-images.githubusercontent.com/35576062/116425727-cae14180-a842-11eb-89c9-98fe85faa5dc.png">


15. Die Frage mit y+Enter bestätigen

16. Jetzt sollte sich Xcode öffnen 

17. Nun wie in den unten stehenden Bildern, das Entwicklerzertifikat auf sein eigenes Zertifikat umbiegen 
<img width="1512" alt="Bildschirmfoto 2021-04-28 um 16 58 35" src="https://user-images.githubusercontent.com/35576062/116426034-10057380-a843-11eb-94b3-6fc35d6f5ea4.png">


27. Testen Sie das Programm unter XXX
28. Klicken Sie auf Archiv dann auf XXX
29. Speicherort auswählen XXX
30. Jetzt im Finder den Ordner suchen, wo Sie das eben abgespeicherte Archiv abgelegt haben
31. Doppelklick auf Binnen-I be gone
32. Nun nur noch in den Safari Einstellungen bei Erweiterungen die Binnen-I be gone Erweiterung mit dem Häckchen aktivieren

Fertig

Dank an

Idee
