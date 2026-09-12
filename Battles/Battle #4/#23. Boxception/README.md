# #23. Boxception

Challenge: <https://cssbattle.dev/play/24>

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
  <div class = "square">
    <div class = "square-1">
      <div class = "square-2"></div>
    </div>
  </div>
</div>
<style>
  * {
    margin: 0;
    padding: 0;
  }
  .container {
    width: 400px;
    height: 300px;
    background: #F3AC3C;
    position: relative;
  }
  .square {
    position: absolute;
    width: 200px;
    height: 200px;
    background: #1A4341;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
  }
  .square-1 {
    position: absolute;
    width: 100px;
    height: 100px;
    background: #998235;
    bottom: 0;
  }
  .square-2 {
    position: absolute;
    width: 50px;
    height: 50px;
    background: #F3AC3C;
    bottom: 0;
    right: 0;
  }
</style>
```
