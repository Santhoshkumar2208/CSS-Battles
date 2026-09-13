# #29. Suffocate

Challenge: <https://cssbattle.dev/play/29>

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
    background: #F3AC3C;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .square {
    width: 200px;
    height: 200px;
    background: #1A4341;
    border-radius: 100px;
    corner-shape: scoop;
  }
</style>
```
