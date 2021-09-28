# Le titre

![Alt text](https://g.gravizo.com/svg?digraph%20G%20%7B%0A%20%20%20%20aize%20%3D%224%2C4%22%3B%0A%20%20%20%20main%20%5Bshape%3Dbox%5D%3B%0A%20%20%20%20main%20-%3E%20parse%20%5Bweight%3D8%5D%3B%0A%20%20%20%20parse%20-%3E%20execute%3B%0A%20%20%20%20main%20-%3E%20init%20%5Bstyle%3Ddotted%5D%3B%0A%20%20%20%20main%20-%3E%20cleanup%3B%0A%20%20%20%20execute%20-%3E%20%7B%20make_string%3B%20printf%7D%0A%20%20%20%20init%20-%3E%20make_string%3B%0A%20%20%20%20edge%20%5Bcolor%3Dred%5D%3B%0A%20%20%20%20main%20-%3E%20printf%20%5Bstyle%3Dbold%2Clabel%3D%22100%20times%22%5D%3B%0A%20%20%20%20make_string%20%5Blabel%3D%22make%20a%20string%22%5D%3B%0A%20%20%20%20node%20%5Bshape%3Dbox%2Cstyle%3Dfilled%2Ccolor%3D%22.7%20.3%201.0%22%5D%3B%0A%20%20%20%20execute%20-%3E%20compare%3B%0A%20%20%7D)

<p align="center">
<img src='https://g.gravizo.com/svg?digraph%20G%20%7B%0A%20%20%20main%20-%3E%20parse%20-%3E%20execute%3B%0A%20%20%20main%20-%3E%20init%20-%3E%20make_string%3B%0A%20%20%20main%20-%3E%20cleanup%3B%0A%20%20%20execute%20-%3E%20make_string%3B%0A%20%20%20execute%20-%3E%20printf2%3B%0A%20%20%20main%20-%3E%20printf%3B%0A%20%20%20execute%20-%3E%20compare%3B%0A%20%7D'/>
</p>


<img src='https://g.gravizo.com/svg?%2F%2A%2A%0A%2AStructural%20Things%0A%2A%40opt%20commentname%0A%2A%40note%20Notes%20can%0A%2Abe%20extended%20to%0A%2Aspan%20multiple%20lines%0A%2A%2F%0Aclass%20Structural%7B%7D%0A%0A%2F%2A%2A%0A%2A%40opt%20all%0A%2A%40note%20Class%0A%2A%2F%0Aclass%20Counter%20extends%20Structural%20%7B%0A%20%20%20%20%20%20%20%20static%20public%20int%20counter%3B%0A%20%20%20%20%20%20%20%20public%20int%20getCounter%2528%2529%3B%0A%7D%0A%0A%2F%2A%2A%0A%2A%40opt%20shape%20activeclass%0A%2A%40opt%20all%0A%2A%40note%20Active%20Class%0A%2A%2F%0Aclass%20RunningCounter%20extends%20Counter%7B%7D'>        
