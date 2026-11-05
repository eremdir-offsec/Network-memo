## Contenu

1. Couches OSI et encapsulation
2. Ports et protocoles
3. IPv4 et subnetting
4. IPv6 et acheminement
5. Équipements, supports et topologies
6. Ethernet, VLAN et STP
7. Routage, OSPF et NAT
8. Wireless et implantation physique
9. Services, exploitation et continuité
10. Sécurité réseau
11. Méthode et outils de dépannage
12. Automatisation et mise en pratique
13. Lexique des acronymes essentiels

## Comment l'utiliser

Commencez par le trajet d'une visite web en première page. Pour chaque sujet, vérifiez que vous pouvez expliquer la fonction, donner un exemple et choisir un premier test en cas de panne. Le tableau des ports sert de référence rapide; les exemples de subnetting et de dépannage sont à refaire sans regarder la réponse.

Par exemple, lorsqu'un poste accède à un site :

```text
Lien Ethernet ou Wi-Fi → IP et default gateway → DNS → ARP ou NDP
→ routage → TCP/TLS → HTTP(S)
```

Si l'accès par adresse IP fonctionne mais pas par nom, commencez par tester **DNS**. Si le poste n'obtient aucune adresse IP utilisable, examinez **DHCP**, le **VLAN** et le lien local.

## Modifier le document

Ouvrez le fichier `.docx`, apportez vos changements, puis exportez-le au format PDF si vous souhaitez publier une nouvelle version. Conservez les deux fichiers sous les noms ci-dessus pour que les liens du README restent valides.

## Portée

Ce document est un aide-mémoire de synthèse. Il ne remplace pas la documentation technique complète ni les essais dans un environnement de laboratoire. Les exemples de commandes Cisco IOS sont fournis comme repères pratiques; ils ne sont pas nécessaires pour lire les explications générales.
