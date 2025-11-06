# 🕵️ Challenge 4 — GSM

## 📖 Context

An SMS was transmitted in encapsulated GSM traffic.

## 🎯 Goal

What is the message hidden, the number sending it and the recipient ?

_You should probably what GSMTAP et TP-UD are ;)_

**Answer Expected** :  
>FROM : +33XXXXXXXXX  
>TO : +33XXXXXXXXX  
>MESSAGE : It's cool !

## 📂 File provided

* `gsm.pcap`
## ANSWER :
TP-UD=00470053004d00200069007300200041007700650073006f006d006500200021;TP-UDL=32
GIVES : GS IS AWESOME !