# 💻 08. API's uitlezen > oefening 05

## 🛠️ opdrachten

Tijdens dit labo leer je
 - gebruik maken van een API-sleutel voor toegang.

### Postman opstarten

 - Start Postman.

### authentificatie met api key

 - [API: News API](https://newsapi.org)
 - endpoint: /top-headlines

---

1. Maak een nieuw verzoek naar de API.
2. Gebruik de endpoint /top-headlines.
3. Voeg een X-Api-Key header toe met je API-sleutel.
4. Voer het verzoek uit en bekijk de respons.

{
"status": "ok",
    "totalResults": 33,
    "articles": [
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "BFM Business",
            "title": "Nouveau pacte de stabilité adopté au Parlement - 23/04 - BFM Business",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMijQFodHRwczovL3d3dy5iZm10di5jb20vZWNvbm9taWUvcmVwbGF5LWVtaXNzaW9ucy9sZXMtZXhwZXJ0cy1kdS1zb2lyL25vdXZlYXUtcGFjdGUtZGUtc3RhYmlsaXRlLWFkb3B0ZS1hdS1wYXJsZW1lbnQtMjMtMDRfVk4tMjAyNDA0MjMwODM2Lmh0bWzSAZEBaHR0cHM6Ly93d3cuYmZtdHYuY29tL2FtcC9lY29ub21pZS9yZXBsYXktZW1pc3Npb25zL2xlcy1leHBlcnRzLWR1LXNvaXIvbm91dmVhdS1wYWN0ZS1kZS1zdGFiaWxpdGUtYWRvcHRlLWF1LXBhcmxlbWVudC0yMy0wNF9WTi0yMDI0MDQyMzA4MzYuaHRtbA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T18:04:02Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Le Soir",
            "title": "« Une situation inédite » : record de cas importés de dengue en France - Le Soir",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMicGh0dHBzOi8vd3d3Lmxlc29pci5iZS81ODMwODkvYXJ0aWNsZS8yMDI0LTA0LTIzL3VuZS1zaXR1YXRpb24taW5lZGl0ZS1yZWNvcmQtZGUtY2FzLWltcG9ydGVzLWRlLWRlbmd1ZS1lbi1mcmFuY2XSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T17:53:30Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Foot Mercato",
            "title": "Inter Milan : l'échange lunaire entre Thuram, Cahlanoglu et le président - Foot Mercato",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMidWh0dHBzOi8vd3d3LmZvb3RtZXJjYXRvLm5ldC9hMjgzODYxMTQyNTk1Nzc4NjUzNS1pbnRlci1taWxhbi1sZWNoYW5nZS1sdW5haXJlLWVudHJlLXRodXJhbS1jYWhsYW5vZ2x1LWV0LWxlLXByZXNpZGVudNIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T17:19:58Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "RTBF",
            "title": "Les Niouzz - Mardi 23 avril - Auvio - RTBF",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiOWh0dHBzOi8vYXV2aW8ucnRiZi5iZS9tZWRpYS9sZXMtbmlvdXp6LWxlcy1uaW91enotMzE4NTU0NtIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T16:38:50Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Sudinfo.be",
            "title": "Kendji Girac blessé par balle ce lundi : le chanteur est « tiré d'affaire », annonce son manager - Sudinfo.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMigwFodHRwczovL3d3dy5zdWRpbmZvLmJlL2lkODI3OTMzL2FydGljbGUvMjAyNC0wNC0yMy9rZW5kamktZ2lyYWMtYmxlc3NlLXBhci1iYWxsZS1jZS1sdW5kaS1sZS1jaGFudGV1ci1lc3QtdGlyZS1kYWZmYWlyZS1hbm5vbmNlLXNvbtIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T15:43:01Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "DH Les Sports +",
            "title": "L’inquiétude est grande chez Decathlon après l’annonce de la fermeture du dépôt de Willebroek : “Très inquiet... - DH Les Sports +",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMi3AFodHRwczovL3d3dy5kaG5ldC5iZS9jb25zby9jb25zb21tYXRpb24vMjAyNC8wNC8yMy9saW5xdWlldHVkZS1lc3QtZ3JhbmRlLWNoZXotZGVjYXRobG9uLWFwcmVzLWxhbm5vbmNlLWRlLWxhLWZlcm1ldHVyZS1kdS1kZXBvdC1kZS13aWxsZWJyb2VrLXRyZXMtaW5xdWlldC1wb3VyLWxhLXN1aXRlLW1lbWUtcG91ci1sZXMtbWFnYXNpbnMtU1hUNUZMNFpVVkVIM1BDUjJCVUhaRlkyQ0kv0gHrAWh0dHBzOi8vd3d3LmRobmV0LmJlL2NvbnNvL2NvbnNvbW1hdGlvbi8yMDI0LzA0LzIzL2xpbnF1aWV0dWRlLWVzdC1ncmFuZGUtY2hlei1kZWNhdGhsb24tYXByZXMtbGFubm9uY2UtZGUtbGEtZmVybWV0dXJlLWR1LWRlcG90LWRlLXdpbGxlYnJvZWstdHJlcy1pbnF1aWV0LXBvdXItbGEtc3VpdGUtbWVtZS1wb3VyLWxlcy1tYWdhc2lucy1TWFQ1Rkw0WlVWRUgzUENSMkJVSFpGWTJDSS8_b3V0cHV0VHlwZT1hbXA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T15:17:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Sudinfo.be",
            "title": "Course-poursuite mortelle à Couillet : le fuyard que poursuivaient Benjamin Leduc et son collègue policier court toujours - Sudinfo.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMigwFodHRwczovL3d3dy5zdWRpbmZvLmJlL2lkODI3OTA4L2FydGljbGUvMjAyNC0wNC0yMy9jb3Vyc2UtcG91cnN1aXRlLW1vcnRlbGxlLWNvdWlsbGV0LWxlLWZ1eWFyZC1xdWUtcG91cnN1aXZhaWVudC1iZW5qYW1pbi1sZWR1Yy1ldNIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T15:03:50Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "lalibre.be",
            "title": "Regard noir, \"journalisme de chéquier\" et liaisons secrètes achetées : le premier témoin du procès de Trump... - lalibre.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMi0QFodHRwczovL3d3dy5sYWxpYnJlLmJlL2ludGVybmF0aW9uYWwvMjAyNC8wNC8yMy9yZWdhcmQtbm9pci1qb3VybmFsaXNtZS1kZS1jaGVxdWllci1ldC1saWFpc29ucy1zZWNyZXRlcy1hY2hldGVlcy1sZS1wcmVtaWVyLXRlbW9pbi1kdS1wcm9jZXMtZGUtdHJ1bXAtcG91cnJhaXQtYmllbi1zY2VsbGVyLXNvbi1zb3J0LUpDQldLNE5KUUpHQ1RDWVpJM1pNSk5PQUpJL9IB4AFodHRwczovL3d3dy5sYWxpYnJlLmJlL2ludGVybmF0aW9uYWwvMjAyNC8wNC8yMy9yZWdhcmQtbm9pci1qb3VybmFsaXNtZS1kZS1jaGVxdWllci1ldC1saWFpc29ucy1zZWNyZXRlcy1hY2hldGVlcy1sZS1wcmVtaWVyLXRlbW9pbi1kdS1wcm9jZXMtZGUtdHJ1bXAtcG91cnJhaXQtYmllbi1zY2VsbGVyLXNvbi1zb3J0LUpDQldLNE5KUUpHQ1RDWVpJM1pNSk5PQUpJLz9vdXRwdXRUeXBlPWFtcA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T15:01:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "DH Les Sports +",
            "title": "Les premières images de Wout van Aert à l’entraînement depuis sa terrible chute (VIDÉO) - DH Les Sports +",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMioAFodHRwczovL3d3dy5kaG5ldC5iZS9zcG9ydHMvY3ljbGlzbWUvMjAyNC8wNC8yMy9sZXMtcHJlbWllcmVzLWltYWdlcy1kZS13b3V0LXZhbi1hZXJ0LWEtbGVudHJhaW5lbWVudC1kZXB1aXMtc2EtdGVycmlibGUtY2h1dGUtdmlkZW8tSVBIV1ZYUkJUNUdFTlBCUFpYQkxHRFMyRkEv0gGvAWh0dHBzOi8vd3d3LmRobmV0LmJlL3Nwb3J0cy9jeWNsaXNtZS8yMDI0LzA0LzIzL2xlcy1wcmVtaWVyZXMtaW1hZ2VzLWRlLXdvdXQtdmFuLWFlcnQtYS1sZW50cmFpbmVtZW50LWRlcHVpcy1zYS10ZXJyaWJsZS1jaHV0ZS12aWRlby1JUEhXVlhSQlQ1R0VOUEJQWlhCTEdEUzJGQS8_b3V0cHV0VHlwZT1hbXA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T14:50:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "i24NEWS en Français",
            "title": "L'armée Israélienne Dément Avoir Creusé Des Fosses Communes Dans Les Hôpitaux De Gaza - I24NEWS - i24NEWS en Français",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMidGh0dHBzOi8vd3d3LmkyNG5ld3MudHYvZnIvYWN0dS9pc3JhZWwtZW4tZ3VlcnJlL2FydGMtdHNhaGFsLWRlbWVudC1hdm9pci1jcmV1c2UtZGVzLWZvc3Nlcy1kYW5zLWxlcy1ob3BpdGF1eC1kZS1nYXph0gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T14:44:32Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "lalibre.be",
            "title": "La princesse Kate partage une photo du prince Louis à l'occasion de son anniversaire - lalibre.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiogFodHRwczovL3d3dy5sYWxpYnJlLmJlL2xpZmVzdHlsZS9wZW9wbGUvMjAyNC8wNC8yMy9sYS1wcmluY2Vzc2Uta2F0ZS1wYXJ0YWdlLXVuZS1waG90by1kdS1wcmluY2UtbG91aXMtYS1sb2NjYXNpb24tZGUtc29uLWFubml2ZXJzYWlyZS1MWFA2UEdHN1FCRkRYQzVGSjNMU09BSlVQUS_SAbEBaHR0cHM6Ly93d3cubGFsaWJyZS5iZS9saWZlc3R5bGUvcGVvcGxlLzIwMjQvMDQvMjMvbGEtcHJpbmNlc3NlLWthdGUtcGFydGFnZS11bmUtcGhvdG8tZHUtcHJpbmNlLWxvdWlzLWEtbG9jY2FzaW9uLWRlLXNvbi1hbm5pdmVyc2FpcmUtTFhQNlBHRzdRQkZEWEM1RkozTFNPQUpVUFEvP291dHB1dFR5cGU9YW1w?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T14:00:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "DH Les Sports +",
            "title": "Guerre en Ukraine: \"Le fait de séjourner à l'étranger ne dispense pas un citoyen de ses devoirs envers la patrie\"... - DH Les Sports +",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMitAFodHRwczovL3d3dy5kaG5ldC5iZS9hY3R1L21vbmRlLzIwMjQvMDQvMjMvZ3VlcnJlLWVuLXVrcmFpbmUtbGUtZmFpdC1kZS1zZWpvdXJuZXItYS1sZXRyYW5nZXItbmUtZGlzcGVuc2UtcGFzLXVuLWNpdG95ZW4tZGUtc2VzLWRldm9pcnMtZW52ZXJzLWxhLXBhdHJpZS1DSEVXNU5XM0NaRDQ3Sko1V01RQUZGSElWRS_SAcMBaHR0cHM6Ly93d3cuZGhuZXQuYmUvYWN0dS9tb25kZS8yMDI0LzA0LzIzL2d1ZXJyZS1lbi11a3JhaW5lLWxlLWZhaXQtZGUtc2Vqb3VybmVyLWEtbGV0cmFuZ2VyLW5lLWRpc3BlbnNlLXBhcy11bi1jaXRveWVuLWRlLXNlcy1kZXZvaXJzLWVudmVycy1sYS1wYXRyaWUtQ0hFVzVOVzNDWkQ0N0pKNVdNUUFGRkhJVkUvP291dHB1dFR5cGU9YW1w?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T13:15:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Sudinfo.be",
            "title": "Résultats sur la pollution des broyeurs à métaux : « À Engis, elle est croissante et c'est inquiétant » - Sudinfo.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMigwFodHRwczovL3d3dy5zdWRpbmZvLmJlL2lkODI3ODA5L2FydGljbGUvMjAyNC0wNC0yMy9yZXN1bHRhdHMtc3VyLWxhLXBvbGx1dGlvbi1kZXMtYnJveWV1cnMtbWV0YXV4LWVuZ2lzLWVsbGUtZXN0LWNyb2lzc2FudGUtZXQtY2VzdNIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T12:31:50Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Sudinfo.be",
            "title": "« Je dois apprendre à vivre avec » : Céline Dion donne des nouvelles de son état de santé - Sudinfo.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMifmh0dHBzOi8vd3d3LnN1ZGluZm8uYmUvaWQ4Mjc3ODMvYXJ0aWNsZS8yMDI0LTA0LTIzL2plLWRvaXMtYXBwcmVuZHJlLXZpdnJlLWF2ZWMtY2VsaW5lLWRpb24tZG9ubmUtZGVzLW5vdXZlbGxlcy1kZS1zb24tZXRhdC1kZdIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T12:09:27Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "RTL info",
            "title": "De la tour antigel aux bougies: les vignerons ont lutté contre le gel cette nuit - RTL info",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMikAFodHRwczovL3d3dy5ydGwuYmUvYWN0dS9iZWxnaXF1ZS9tZXRlby9kZS1sYS10b3VyLWFudGlnZWwtYXV4LWJvdWdpZXMtbGVzLXZpZ25lcm9ucy1vbnQtbHV0dGUtY29udHJlLWxlLWdlbC1jZXR0ZS1udWl0LzIwMjQtMDQtMjMvYXJ0aWNsZS82NjE2MznSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T12:05:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "lalibre.be",
            "title": "Mathilde Panot (LFI) convoquée par la police: \"la première fois qu'une présidente de l'opposition est convoquée... - lalibre.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMi1gFodHRwczovL3d3dy5sYWxpYnJlLmJlL2ludGVybmF0aW9uYWwvZXVyb3BlLzIwMjQvMDQvMjMvbWF0aGlsZGUtcGFub3QtbGZpLWNvbnZvcXVlZS1wYXItbGEtcG9saWNlLWxhLXByZW1pZXJlLWZvaXMtcXV1bmUtcHJlc2lkZW50ZS1kZS1sb3Bwb3NpdGlvbi1lc3QtY29udm9xdWVlLXBvdXItdW4tbW90aWYtYXVzc2ktZ3JhdmUtQllDWFBYQlpLTkhGVk9OSlFQWUM3WlJDR0Uv0gHlAWh0dHBzOi8vd3d3LmxhbGlicmUuYmUvaW50ZXJuYXRpb25hbC9ldXJvcGUvMjAyNC8wNC8yMy9tYXRoaWxkZS1wYW5vdC1sZmktY29udm9xdWVlLXBhci1sYS1wb2xpY2UtbGEtcHJlbWllcmUtZm9pcy1xdXVuZS1wcmVzaWRlbnRlLWRlLWxvcHBvc2l0aW9uLWVzdC1jb252b3F1ZWUtcG91ci11bi1tb3RpZi1hdXNzaS1ncmF2ZS1CWUNYUFhCWktOSEZWT05KUVBZQzdaUkNHRS8_b3V0cHV0VHlwZT1hbXA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T11:59:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "lalibre.be",
            "title": "Virus H5N1 dans le lait de vache: les chercheurs constatent \"une nouvelle étape dans la propagation du virus... - lalibre.be",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMixQFodHRwczovL3d3dy5sYWxpYnJlLmJlL3BsYW5ldGUvc2FudGUvMjAyNC8wNC8yMy92aXJ1cy1oNW4xLWRhbnMtbGUtbGFpdC1kZS12YWNoZS1sZXMtY2hlcmNoZXVycy1jb25zdGF0ZW50LXVuZS1ub3V2ZWxsZS1ldGFwZS1kYW5zLWxhLXByb3BhZ2F0aW9uLWR1LXZpcnVzLWF1eC1tYW1taWZlcmVzLVlWSUpUNFhQUU5EWlJFVVQ1NjZaQkVSWlpNL9IB1AFodHRwczovL3d3dy5sYWxpYnJlLmJlL3BsYW5ldGUvc2FudGUvMjAyNC8wNC8yMy92aXJ1cy1oNW4xLWRhbnMtbGUtbGFpdC1kZS12YWNoZS1sZXMtY2hlcmNoZXVycy1jb25zdGF0ZW50LXVuZS1ub3V2ZWxsZS1ldGFwZS1kYW5zLWxhLXByb3BhZ2F0aW9uLWR1LXZpcnVzLWF1eC1tYW1taWZlcmVzLVlWSUpUNFhQUU5EWlJFVVQ1NjZaQkVSWlpNLz9vdXRwdXRUeXBlPWFtcA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T11:39:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "L'Echo",
            "title": "Solvay sous pression | Barco dévisse | Avis de brokers sur UCB, Solvay, KBC, Nextensa et Mithra (+Briefing) - L'Echo",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMipwFodHRwczovL3d3dy5sZWNoby5iZS9sZXMtbWFyY2hlcy9hY3R1L2FjdGlvbnMtYnJ1eGVsbGVzL3NvbHZheS1zb3VzLXByZXNzaW9uLWJhcmNvLWRldmlzc2UtYXZpcy1kZS1icm9rZXJzLXN1ci11Y2Itc29sdmF5LWtiYy1uZXh0ZW5zYS1ldC1taXRocmEtYnJpZWZpbmcvMTA1NDE2NDIuaHRtbNIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T10:43:53Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Le Soir",
            "title": "Espionnage au Parlement européen en faveur de la Chine : l'assistant arrêté a été suspendu - Le Soir",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMifGh0dHBzOi8vd3d3Lmxlc29pci5iZS81ODI5MTUvYXJ0aWNsZS8yMDI0LTA0LTIzL2VzcGlvbm5hZ2UtYXUtcGFybGVtZW50LWV1cm9wZWVuLWVuLWZhdmV1ci1kZS1sYS1jaGluZS1sYXNzaXN0YW50LWFycmV0ZS1ldGXSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T10:40:24Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "DH Les Sports +",
            "title": "Tollé après l'adoption de la loi britannique visant à expulser des migrants au Rwanda - DH Les Sports +",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMimwFodHRwczovL3d3dy5kaG5ldC5iZS9hY3R1L21vbmRlLzIwMjQvMDQvMjMvdG9sbGUtYXByZXMtbGFkb3B0aW9uLWRlLWxhLWxvaS1icml0YW5uaXF1ZS12aXNhbnQtYS1leHB1bHNlci1kZXMtbWlncmFudHMtYXUtcndhbmRhLVNQS1dPQlRLWE5DVkpKN0FLRzJZV01XUElVL9IBqgFodHRwczovL3d3dy5kaG5ldC5iZS9hY3R1L21vbmRlLzIwMjQvMDQvMjMvdG9sbGUtYXByZXMtbGFkb3B0aW9uLWRlLWxhLWxvaS1icml0YW5uaXF1ZS12aXNhbnQtYS1leHB1bHNlci1kZXMtbWlncmFudHMtYXUtcndhbmRhLVNQS1dPQlRLWE5DVkpKN0FLRzJZV01XUElVLz9vdXRwdXRUeXBlPWFtcA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-23T10:33:00Z",
            "content": null
        }
    ]
}