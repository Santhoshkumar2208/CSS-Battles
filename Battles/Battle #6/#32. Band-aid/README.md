# #32. Band-aid

Challenge: <https://cssbattle.dev/play/32>

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
  <div class = "rect-1"></div>
  <div class = "rect-2"></div>
  <div class = "square"></div>
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
    background: #FFFFFF;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .rect-1 {
    position: absolute;
    width: 50px;
    height: 200px;
    background: #F3AC3C;
    transform: rotate(-45deg);
  }
  .rect-2 {
    position: absolute;
    width: 50px;
    height: 200px;
    background: #A3A368;
    transform: rotate(45deg);
  }
  .square {
    position: absolute;
    width: 50px;
    height: 50px;
    background: #FBE18C;
    transform: rotate(45deg);
  }
</style>
```
