## Given a table of `values` with a range anywhere from `6-12`

| Item | Value (%)               |
| -------- | ------------------------ |
| result_1 |         10          |
| result_2 |         20          |
| result_3 |         30          |
| result_4 |         40          |
| result_5 |         50          |
| result_6 |         60          |
| result_7 |         70          |
| result_8 |         80          |

## Main
Create a React Component that takes in values from the table and returns a svg polygon.

### The basic component should be called as:
```js
<Polygon>
    <Vertex title="result_1" value={10}/>
    <Vertex title="result_2" value={20}/>
    <Vertex title="result_3" value={30}/>
    <Vertex title="result_4" value={40}/>
    <Vertex title="result_5" value={50}/>
    <Vertex title="result_6" value={60}/>
    <Vertex title="result_7" value={70}/>
    <Vertex title="result_8" value={80}/>
<Polygon/>
```
### A More polished component should be called as:
```js
<Polygon vertices={_vertices} rotation={_rotation}/>
```

## Requirements 
- Polygon vertices should animate outwards from the center on first render
- Polygon vertices should animate towards any new set value within the table
- Polygon should support rotation by a certain degree 

## Tips
- The `dimensions` that set the boundary for the polygon can be any value (but should `not` be set through tsx syntax).
- The higher the `value`, the further towards the boundary the point will be.





