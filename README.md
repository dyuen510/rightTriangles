# rightTriangles

<h1 align ='center'><strong>Four Different Positions For a Right Triangle.</strong></h1>
Four different positions for a right triangle with ejs6. 

All these examples uses repeat() to console out a right triangle. 
Repeat() constructs and returns a new string which contains the specified number of copies of the string
on which it is called. 

<h2 align ='center'><strong> Simple Triangle </strong></h2>

<p align ='center'>const triangle = (n) => {
    for(let i = 1; i<=n ; i++){
        console.log('#'.repeat(i) + ' '.repeat(i))
}}</p>

<div align="center">
    <img src="images/simpleTri.png" width="400px"</img> 
</div>

<h2 align ='center'><strong> staircase </strong></h2>

<p align = 'center' style ='background-color:#d3d3d3'> const staircase = (n) =>{
    for (let i = 1; i<=n; i++){
        console.log(' '.repeat(n-i) + '#'.repeat(i))
}}</p>

<div align="center">
    <img src="images/staircase.png" width="400px"</img> 
</div>


<h2 align ='center'><strong> reversedTriangle </strong></h2>

<p align = 'center'> const reversedTriangle = (n) =>{
    for(let i = 0; i< n; i++){
        console.log('#'.repeat(n-i) + ' '.repeat(i))
    }
}</p>

<div align="center">
    <img src="images/reversedTri.png" width="400px"</img> 
</div>

<h2 align ='center'><strong> reversedStaircase </strong></h2>

<p align = 'center'> const reversedStaircase = (n) => {
    for(let i = 0; i< n; i++){
        console.log(' '.repeat(i) + '#'.repeat(n-i))
    }
}
</p>

<div align="center">
    <img src="images/reversedStair.png" width="400px"</img> 
</div>



