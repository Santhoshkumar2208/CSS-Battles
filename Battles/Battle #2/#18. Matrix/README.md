# #18. Matrix

Challenge: <https://cssbattle.dev/battles>

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
  <div class = "columns">
    <div class = "triangle-1"></div>
    <div class = "triangle-2"></div>
    <div class = "triangle-1"></div>
    <div class = "triangle-2"></div>
    <div class = "triangle-2"></div>
    <div class = "triangle-1"></div>
    <div class = "triangle-2"></div>
    <div class = "triangle-1"></div>
    <div class = "triangle-1"></div>
    <div class = "triangle-2"></div>
    <div class = "triangle-1"></div>
    <div class = "triangle-2"></div>
  </div>
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
    background: #5C434C;
  }
  .columns {
    display: grid;
    grid-template-columns: repeat(4,1fr);
  }
  .triangle-1 {
    padding: 40px;
    border-top-left-radius: 100px;
    background: #F09462;
    margin: 10px;
  }
  .triangle-2 {
    padding: 40px;
    border-top-left-radius: 100px;
    background: #F5D6B4;
    margin: 10px;
  }
</style>
```
