<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Natura 2000 Visualizer</title>
    <script type="application/ld+json">
    {
      "@context": "http://schema.org",
      "@type": "Dataset",
      "name": "Natura 2000 Impact Assessment Form Data Visualizer",
      "description": "A data visualization and form assistance tool for Natura 2000 impact assessment evaluations.",
      "dataSource": [
        {
          "@type": "DataCatalog",
          "name": "Geospatial Data",
          "description": "Geospatial datasets providing map layers for Natura 2000 areas.",
          "accessMode": "Open Access",
          "distribution": {
            "@type": "DataDownload",
            "contentUrl": "https://inpn.mnhn.fr/programme/natura2000",
            "encodingFormat": "GeoJSON"
          }
        },
        {
          "@type": "DataCatalog",
          "name": "Biodiversity Reports",
          "description": "Reports on biodiversity relevant to Natura 2000.",
          "accessMode": "Open Access",
          "distribution": {
            "@type": "DataDownload",
            "contentUrl": "https://biodiversite.eu/fr/evaluations/natura2000",
            "encodingFormat": "PDF"
          }
        },
        {
          "@type": "DataCatalog",
          "name": "Environmental Impact Assessments",
          "description": "Data from past environmental impact assessments.",
          "accessMode": "Open Access",
          "distribution": {
            "@type": "DataDownload",
            "contentUrl": "https://www.ecologie.gouv.fr/evaluation-environnementale",
            "encodingFormat": "CSV"
          }
        }
      ],
      "variableMeasured": [
        {
          "@type": "PropertyValue",
          "name": "Protected Species",
          "description": "Information on species protected under Natura 2000."
        },
        {
          "@type": "PropertyValue",
          "name": "Habitat Data",
          "description": "Geospatial habitat data linked to protected areas."
        },
        {
          "@type": "PropertyValue",
          "name": "Environmental Impact Factors",
          "description": "Assessment data on environmental impact for Natura 2000 sites."
        }
      ],
      "license": "https://creativecommons.org/licenses/by/4.0/",
      "creator": {
        "@type": "Organization",
        "name": "Natura2000 Data Project",
        "url": "https://natura2000dataproject.org"
      }
    }
    </script>
</head>
<body>
    <h1>Natura 2000 Visualizer</h1>
    <p>Bienvenue sur l'outil de visualisation et d'aide à l'évaluation des incidences Natura 2000.</p>
    
    <h2>Sources de données</h2>
    <ul>
        <li>
            <a href="https://inpn.mnhn.fr/programme/natura2000" target="_blank">
                Données géospatiales des zones Natura 2000 (INPN)
            </a>
        </li>
        <li>
            <a href="https://biodiversite.eu/fr/evaluations/natura2000" target="_blank">
                Rapports sur la biodiversité (Portail européen de la biodiversité)
            </a>
        </li>
        <li>
            <a href="https://www.ecologie.gouv.fr/evaluation-environnementale" target="_blank">
                Évaluations des impacts environnementaux (Ministère de la Transition Écologique)
            </a>
        </li>
    </ul>
</body>
</html>
