# Magyar Biblia fordítások JSON array, JSON dictionary, dictionary with int keys, és XML formátumokban

Mindegyik formátum UTF-8 kódolású.

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
