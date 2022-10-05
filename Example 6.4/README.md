# radial Line chart


 

<p>In order to make a line chart with a radial form, we will need to use the d3.lineRadial() generator</p>

```
     const LineGen_avg = d3.lineRadial()
            .angle(d=>angleScale(d.date))
            .radius(d=>radiusScale(d.t_avg)).curve(d3.curveCardinalClosed)

```

Using the same Boston Temperature dataset, the following visualization is made:
<img width="50vw" src="./img/preview.png" />