% Meine Erste Präsentation
% Referent: Sanjivi Mahenthiran
% Date: \today
---
theme: "Berlin"
header-includes:
colortheme: "seahorse"
fronttheme: "structurebold"
author: Sanjivi Mahenthiran
---

# Erste Folie
Dies ist eine **erste** Markdown Präsentation!
> Durch dieses befehl ist es möglich!
````bash
pandoc -t beamer <filename.md> -o <praesentationname>.pdf
````

# Auszählung mit Formatierung

- punkt 1 mit *kursiven text*
- punkt 2 mit **fettem test**
- punkt 3 mit ~~gestrichenen test~~

# Formeln unt Quoting
> **Merke:**
> Markdown und Pandoc sind cool und mächtig!!!

$$ \int_a \limits ^\infty \frac{x^2-a}{e^{x-b}}
dx $$

# Checkboxen
[] Joe
[x] Mama
[x] Deez
[] Nuts

# R Markdown
````R
plot(x1, y1, main = "Overlay")
```` 


