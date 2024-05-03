# ddd
Domain Driven Design

[Link text Here](https://link-url-here.org)
<details>
  <a href='https://github.com/ddd-crew'>DDD Crew</a>
  <br />
  <a href='https://docs.vlingo.io'>DDD Design Tool</a>
  <br />
  <a href='https://kalele.io/vlingo-platform'>Xoom</a>
</details>


```mermaid
mindmap
  root((DDD))
    Education
      link The Blue Book "github.com"
      DDD crew
    Strategic
      S1
        [an <b>important</b> <a href='http://google.com'>link</a>]
        <a href='http://google.com'>another link</a>
      S2
        S21
          [an <b>important</b> <a href='http://google.com'>link</a>]
    Tactical
      T1
      T2
        T21
    Tools
      Context Mapper
        vlingo[<a href='https://docs.vlingo.io'>docs.vlingo.io</a>]
```
```mermaid
flowchart TB
  A[<a href='https://google.com'>works</a>]
```

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```
