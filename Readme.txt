1. Najpierw dodajemy wojew�dztwa.
przyk�adowy Json
{
  "name": "Wielkopolska"
}

2. P�niej dodajemy Powiaty z Id Wojew�dztwa
przyk�adowy Json
{
  "name": "Powiat Koni�ski",
  "wojewodztwoId": 1
}

3. P�niej dodajemy Gminy z Id Powiatu
przyk�adowy Json
{
  "name": "Gmina Konin",
  "powiatId": 1
}

4. P�niej dodajemy miasto z Populacj� i Id Gminy
przyk�adowy Json
{
  "name": "Konin",
  "population": 50000,
  "gminaId": 1
}