#### Hauptaufgabe

#### 1.Erstelle einen neuen Ordner mit dem Namen myFirstProject

        mkdir myFirstProject

#### 2.Gehe in den eben erstellten Ordner

        cd myFirstProject

#### 3.Erstelle 3 Dateien mit den Namen data1.txt, data2.txt und data3.md

        touch data1.txt data2.txt data3.md

#### 4.Schreibe in die data1.txt mit Nano einen Text und speichere ihn.

        nano data1.txt 

(Schreibe deinen Text und speichere mit CTRL + O, verlasse mit CTRL + X)

#### 5.Erstelle einen Ordner mit dem Namen Markdown und verschiebe die data3.md in den Ordner.

        mkdir Markdown
        mv data3.md Markdown/

#### 6.Gehe in den Markdown-Ordner und schreibe in die Datei eine Überschrift. Eine h1-Überschrift in Markdown wird mit # Überschrift geschrieben.

        cd Markdown

        nano data3.md 

(Füge deine Überschrift als # Überschrift hinzu, speichere mit CTRL + O und verlasse mit CTRL + X)

#### 7.Gehe aus dem Markdown-Ordner raus und lösche die data2.txt.

        cd ..
        rm data2.txt

#### Bonus

####  1. Erstelle einen weiteren Ordner neben dem Markdown-Ordner, der Markdown2 heißt.

        mkdir Markdown2

#### 2. Verschiebe die data3.md aus dem Markdown-Ordner in den Markdown2-Ordner.

        mv Markdown/data3.md Markdown2/

#### 3. Lösche den Markdown-Ordner.

        rm -r Markdown

#### 4. Verschiebe die Datei data1.txt in einen Ordner mit dem Namen TextDateien, den es noch nicht gibt.
        
        mkdir Textdateien && mv data1.txt Textdateien/

Wenn du noch Fragen hast oder weitere Hilfe benötigst, lass es mich wissen!