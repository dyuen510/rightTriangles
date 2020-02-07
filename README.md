# rightTriangles

<h1><strong>Four Different Positions For a Right Triangle.</strong></h1>
Four different positions for a right triangle with ejs6. 

All these examples uses repeat() to console out a right triangle. 
Repeat() constructs and returns a new string which contains the specified number of copies of the string
on which it is called. 

<h2><strong> Simple Triangle </strong></h2>

const triangle = (n) => {
    for(let i = 1; i<=n ; i++){
        console.log('#'.repeat(i) + ' '.repeat(i))
}}

<div align="center">
    <img src="simpleTri.png" width="400px"</img> 
</div>


