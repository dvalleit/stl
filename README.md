```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```
```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```
![TEST](CalibrationObject.stl)
```geojson
{
  "type": "Polygon",
  "coordinates": [
      [
          [-90,30],
          [-90,35],
          [-90,35],
          [-85,35],
          [-85,30]
      ]
  ]
}
```

### Here's a topoJSON map in markdown

```topojson
 {"type":"Topology","transform":{"scale":[0.003589294092944858,0.0005371535195261037],"translate":[-179.1473400003406,17.67439566600018]},"objects":{"counties":   {"type":"GeometryCollection","geometries":[{"type":"MultiPolygon","arcs":[[[0,1,2,3]]],"id":53073},{"type":"Polygon","arcs":[[4,5,6,7,8,9]],"id":30105},{"type":"Polygon","arcs": [[10,11,12,1
 ...
```


```stl
solid Mesh
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 15.337000 15.000000 109.000000
      vertex 15.337000 15.000000 139.000000
      vertex 99.000000 15.000000 0.000000
    endloop
  endfacet
endsolid Mesh
```
