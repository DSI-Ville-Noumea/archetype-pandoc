# pandoc-archetype

Archetype maven to generate a runnable pandoc skeleton.

## Installation de l'archetype dans le repository maven local

```
>> git clone https://github.com/DSI-Ville-Noumea/pandoc-archetype.git
>> cd pandoc-archetype
>> mvn install
```

## Créer un nouveau projet à partir de l'archetype

```
>> cd ..
>> mvn archetype:generate -DarchetypeArtifactId=pandoc-archetype -DarchetypeGroupId=nc.noumea.mairie -DarchetypeVersion=1.00.02 -DappName=myApp
```



