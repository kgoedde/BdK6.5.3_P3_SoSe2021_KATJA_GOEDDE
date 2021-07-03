# Aufgabe 1 in BDK6.5.3 (wB/öB) P3 Data Librarianship und Programmierung


## 1. Text-Editor der Wahl
Als Text-Editor wurde Notepad++ ausgewählt. 


## 2. Eine Python-Bibliothek
Matplotlib
Mithilfe von Matplotlib können zweidimensionale Diagramme und Grafiken erstellt werden. Dabei können nicht nur statische, sondern auch animierte und interaktive Grafiken erstellt werden. 
Das Layout der Grafiken kann individuell gestaltet werden. 
Die Bibliothek könnte genutzt werden, um Daten auf bestimmte Fragestellungen zu untersuchen und auf verschiedene Weisen darzustellen. 


## 3. Eine Fehlermeldung und Ihre Lösung
Fehlermeldung:
KeyError                                  Traceback (most recent call last)
<ipython-input-30-22d7a63ab1e0> in <module>
----> 1 pm_data["result"]["title"]
KeyError: 'title'
   
Lösung:
Zwischen ["result"] und ["title"] musste noch die uid ["27708327"] eingetragen werden. Also: pm_data["result"]["["27708327"]["title"]
   

## 4. Was ist JupyterLab?
JupyterLab ist eine Weiterentwicklung von Jupyter Notebook. Das klassische Jupyter Notebook, welches seit 2011 zur Verfügung steht, ist nur schwierig anpass- und erweiterbar. In JupyterLab können neben den bereits bekannten Notebooks auch Texteditoren, Terminals und weitere benutzerdefinierte Komponenten innerhalb einer flexiblen Benutzeroberfläche mit mehreren Registerkarten verwendet werden. Es ist im Vergleich zum ursprünglichen Juypter Notebook um Funktionalitäten angereichert, unter anderem besteht z.B. die Möglichkeit einzelne Notebook Zellen per Drag and Drop an eine andere Stelle oder in ein anderes Notebook zu verschieben. 



## 5. Was ist der große Unterschied zwischen den Webframeworks flask und Django?
Das Webframework Flask wurde entwickelt, um einen schnellen und einfachen Einstieg bieten zu können und richtet sich  vor allem an EinsteigerInnen. Flask stellt keine eigenen Bibliotheken oder Tools zur Verfügung, sondern überlässt es dem/der NutzerIn Bibliotheken und Tools auszuwählen, die er/sie miteinbinden möchte. 
Django wurde entwickelt, um EntwicklerInnen zu unterstützen, Anwendungen möglichst schnell fertig zu stellen. Es richtet sich deswegen eher an erfahrenere Entwickler. Im Gegensatz zu Flask sind bereits Bibliotheken und Tools mit eingebunden. 