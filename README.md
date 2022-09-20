# Magyar Biblia fordítások JSON array, JSON dictionary, dictionary with int keys, és XML formátumokban

Mindegyik formátum UTF-8 kódolású.

### Teljes Biblia:
1. Károlyi Gáspár fordítás (1590)
2. Aranyos Károlyi 1685 Amsterdam, Tótfalusi Kis Miklós kiadása (1685)
3. Káldi György Neovulgatából (1782)
4. Káldi György forditás átdolgozása SZIT (1930)
5. Kecskeméthy István református teológus (1935)
6. Protestáns újfordítású Biblia (1990)
7. Krisztus Szeretete Egyház - Revideált Károli Biblia 7. kiadás (2011)
8. Veritas Kiadó - Revideált Károli (2011)

### Újszövetség:
1. P. Soós István karmelita szerzetes (1911)
2. Czeglédy Sándor magyar református lelkész, író, műfordító, bibliafordító (1924)
3. Dr. Masznyik Endre evangélikus teológus (1925)
4. Raffay Sándor evangélikus püspök (1929)
5. P. Békés Gellért bencés és P. Dalos Patrik oratoriánus (1951)
6. Budai Gergely református teológus (1967)
7. Ravasz László református püspök (1971)
8. Vida Sándor baptista lelkész (VIKART BT, 1993) (1971)
9. Csia Lajos Református teológus (1978)
10. Egyszerű fordítás (2003)

### Ószövetség:
1. IMIT fordítás

Az egyes fordításokhoz tartozó információk megtalálhatók a bibles_meta nevű mappában.

## JSON array formátum
```javascript
{
  "Könyv neve 1":
    [
      [
        "1. vers",
        "2. vers",
        ...
      ],
      [
        "1. vers",
        "2. vers",
        ...
      ],
      ...
    ],
  "Könyv neve 2":
  [
    ...
}
```

## JSON dictionary formátum
```javascript
{
  "Könyv neve 1":
    {
      "1": {
        "1": "1. vers",
        "2": "2. vers",
        ...
      },
      "2": {
        "1": "1. vers",
        "2": "2. vers",
        ...
      },
      ...
    },
  "Könyv neve 2":
  {
    ...
}
```

## Dictionary with int keys formátum
```javascript
{
  "Könyv neve 1":
    {
      1: {
        1: "1. vers",
        2: "2. vers",
        ...
      },
      2: {
        1: "1. vers",
        2: "2. vers",
        ...
      },
      ...
    },
  "Könyv neve 2":
  {
    ...
}
```

## XML formátum
```xml
<?xml version="1.0" encoding="UTF-8" ?>
<root>
  <Könyv_neve_1>
    <1>
      <1>vers szövege</1>
      <2>vers szövege</2>
      ...
    </1>
    <2>
      <1>vers szövege</1>
      <2>vers szövege</2>
      ...
    </2>
    ...
  </Könyv_neve_1>
  <Könyv_neve_2>
  ...
```

A Biblia fordítások forrása:
https://baranyilaszlozsolt.com/theword-magyar-bibliak
    ezen belül:
https://baranyilaszlozsolt.com/theword/bibles.zip
