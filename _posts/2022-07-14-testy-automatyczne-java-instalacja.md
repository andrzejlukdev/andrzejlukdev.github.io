---
layout: post
title:  "Testy automatyczne - Java - instalacja"
date:   2022-07-05 17:56:39 +0200
categories: Test Automation
permalink: "/testing/:title"
author: "andrzejlukdev"
---
<img src="https://andrzejlukdev.github.io/_postimages/img_setup_java.png" alt="java">

<h4>Pobieranie instalatora Java:</h4>
1.Przechodzimy na strone gówną ORACLE https://www.oracle.com/index.html
2.Wybieramy z menu głównego Products -> Java
3.W sekcji Java SE wybieramy Oracle JDK
4.Wybieramy odpowiedni system operacyjny (Windows/macOS) i pobieramy x64 Installer

<h4>Instalacja Java:</h4>
1.

<h4>Sprawdzenie w systemie zainstalowanej wersji Javy:</h4>
Windows:
1.Uruchamiamy Command line
2.Wpisujemy polecenie Java -version

macOS:
1.Uruchamiamy Terminal
2.Wpisujemy polecenie Java -version

<h4>Ustawianie zmiennej środowiskowej Javy:</h4>
Windows:
1.Mój Komuter -> PPM -> Właściwości -> Zaawansowane ustawienia systemu -> Zaawansowane -> Zmienne środowiskowe
2.Jeżeli posiadasz już zmienną środowiskową JAVA_HOME — trzeba ją edytować, jeżeli jej nie ma — stworzyć nową.
3.Jako wartość trzeba wskazać ścieżkę do katalogu, gdzie zainstalowana jest Java, np.: C:\Program Files\Java\jdk1.8.0_25\

macOS:
