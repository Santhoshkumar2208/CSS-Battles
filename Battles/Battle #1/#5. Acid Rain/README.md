# #5. Acid Rain

Challenge: <https://cssbattle.dev/play/5>

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
  <div class = "shape-1 center"></div>
  <div class = "shape-1 adjust-left"></div>
  <div class = "circle"></div>
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
    background: #0B2429;
  }
  .shape-1 {
    position: absolute;
    width: 120px;
    height: 120px;
    border-radius: 50% 0% 50% 50%;
    z-index: 1;
  }
  .center {
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    background: #998235;
  }
  .adjust-left {
    top: 150px;
    left: 80px;
    background: #F3AC3C;
  }
  .circle {
    position: absolute;
    width: 120px;
    height: 120px;
    border-radius: 50%;
    background: #F3AC3C;
    left: 200px;
    bottom: 150px;
    z-index: 
  }
</style>
```
