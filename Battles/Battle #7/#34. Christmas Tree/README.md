# #34. Christmas Tree

Challenge: <https://cssbattle.dev/play/34>

## Result

<table>
	<tr>
		<th width="50%">User Submission</th>
		<th width="50%">Target</th>
	</tr>
	<tr>
		<td width="50%" align="center">
			<img src="./user.png" alt="User Submission" width="100%">
		</td>
		<td width="50%" align="center">
			<img src="./target.png" alt="Target" width="100%">
		</td>
	</tr>
</table>

## Code

```html
<div class = "container">
  <div class = "triangle-1"></div>
  <div class = "triangle-2"></div>
  <div class = "triangle-3"></div>
</div>
<style>
  * {
    margin: 0;
    padding: 0;
  }
  .container {
    position: relative;
    width: 400px;
    height: 300px;
    background: #007065;
  }
  .triangle-1 {
    position: absolute;
    width: 250px;
    height: 100px;
    background: #FFEECF;
    corner-shape: bevel;
    border-radius: 50%/100% 100% 0 0;
    top: 50px;
    left: 75px;
    z-index: 3;
  }
  .triangle-2 {
    position: absolute;
    width: 250px;
    height: 100px;
    background: #F5C181;
    corner-shape: bevel;
    border-radius: 50%/100% 100% 0 0;
    top: 100px;
    left: 75px;
    z-index: 2;
  }
  .triangle-3 {
    position: absolute;
    width: 250px;
    height: 100px;
    background: #00A79D;
    corner-shape: bevel;
    border-radius: 50%/100% 100% 0 0;
    top: 150px;
    left: 75px;
    z-index: 1;
  }
</style>
```
