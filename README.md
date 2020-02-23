# trolug-nikola
TroLUG Website in Nikola


Nikola
------
Zum Bau der Webseite wird Nikola 8.x verwendet.
Falls diese Version in der vorliegenden Distribution nicht mitgeliefert wird, kann ein virtual environment helfen:

    mkdir nikola-env
    python3 -m venv nikola-env/
    source nikola-env/bin/activate
    pip install nikola


Workflow
--------
Praktisch ist die Arbeit mit zwei Terminals.


    Terminal 1
    nikola auto --browser 

    Terminal 2
    git pull
    vim pages/foo.rst
    git commit -m "pages: Termine 2021"
    git push
    # Nun PR erzeugen.


TODO
----
* akzeptables Template finden oder selbst schreiben (100% legal, keine designs kopieren!)
* Etherpads einheitlich auf ccc pad umziehen
* Beraten: Was machen wir mit alten etherpads?
* Können wir die Blogfunktion sinnvoll einsetzen, um eine Seite pro Treffen zu verwalten?


DONE
----
* Inhalte von Sphinx nach Nikola kopieren
* Die Terminliste schlau generieren. Tabellen mit ASCII Art zeichnen ist ungeeignet, weil die Titel unterschiedlich lang sind. Als Lösung könnte vielleicht (https://getnikola.com/handbook.html#the-global-context-and-data-files) oder https://getnikola.com/handbook.html#template-based-shortcodes dienen. CSV Tabellen funktionieren wieder. Danke Jan.


Links
-----
* https://getnikola.com/creating-a-site-not-a-blog-with-nikola.html
* https://getnikola.com/quickref.html

