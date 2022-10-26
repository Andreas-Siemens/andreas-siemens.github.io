---
layout: post
title:  "Installation von InfluxDB"
date:   2022-10-26 20:58:35 +0200
categories: jekyll update
---
Die folgende Anleitung beschreibt die Installation der InfluxDB Datenbankplattform auf einem Ubuntu Server als Dienst mit systemd. Zum Zeitpunkt der Installation waren folgende Versionen aktuell:

- Ubuntu 20.04.2 LTS (GNU/Linux 5.4.0-94-generic x86_64)
- InfluxDB V2.2

## Download des deb-Pakage

Der Download erfolgt durch folgenden Befehl:


{% highlight bash %}
wget https://dl.influxdata.com/influxdb/releases/influxdb2-2.2.0-amd64.deb
{% endhighlight %}

Sollte inzwischen eine neuere Version von InfluxDB vorliegen, so muss der Versionsstring 2.2.0 entsprechend angepasst werden.

## Installation

Durch den folgenden Befehl erfolgt die Installation: