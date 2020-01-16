# trolug-nikola
TroLUG Website in Nikola

TODO
----
* akzeptables Template finden oder selbst schreiben (100% legal, keine designs kopieren!)
* Inhalte von Sphinx nach Nikola kopieren
* Etherpads einheitlich auf ccc pad umziehen
* Beraten: Was machen wir mit alten etherpads?
* Die Terminliste schlau generieren. Tabellen mit ASCII Art zeichnen ist ungeeignet, weil die Titel unterschiedlich lang sind. Als Lösung könnte vielleicht (https://getnikola.com/handbook.html#the-global-context-and-data-files) oder https://getnikola.com/handbook.html#template-based-shortcodes dienen.

Workflow
--------
Besonders praktisch ist die Arbeit mit zwei Terminals.


    Terminal 1
    nikola auto --browser 

    Terminal 2
    git pull
    vim pages/foo.rst
    git commit -m "pages: Termine 2021"
    git push
    # Nun PR erzeugen.



Links
-----
* https://getnikola.com/creating-a-site-not-a-blog-with-nikola.html
* https://getnikola.com/quickref.html

