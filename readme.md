# Given a table of `values` with a range anywhere from `6-12`

| Item | Value (%) |
| --- | --- |
| result_1 | 10 |
| result_2 | 20 |
| result_3 | 30 |
| result_4 | 40 |
| result_5 | 50 |
| result_6 | 60 |
| result_7 | 70 |
| result_8 | 80 |

## Main
Create a React Component that takes in values from the table and returns a svg polygon.

The component should be called as:

```js
<Polygon max>
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

## Tips
- The `dimensions` that set the boundary for the polygon can be any value.
- The higher the `value`, the further towards the boundary the point will be.




