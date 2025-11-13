# Oase Creative Documentatie

Documentatie en playbooks voor het Oase Creative team.

## Development

Installeer de [Mintlify CLI](https://www.npmjs.com/package/mint) om je documentatie wijzigingen lokaal te previewen. Installeer met:

```
npm i -g mint
```

Voer het volgende commando uit in de root van je documentatie, waar je `docs.json` staat:

```
mint dev
```

Bekijk je lokale preview op `http://localhost:3000`.

## Publiceren van wijzigingen

Installeer de GitHub app vanuit je [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) om wijzigingen automatisch te deployen. Wijzigingen worden automatisch naar productie gezet na pushen naar de default branch.

## Troubleshooting

- Als je dev omgeving niet werkt: Voer `mint update` uit om ervoor te zorgen dat je de nieuwste versie van de CLI hebt.
- Als een pagina als 404 laadt: Zorg ervoor dat je draait in een folder met een geldige `docs.json`.

## Resources
- [Mintlify documentatie](https://mintlify.com/docs)
