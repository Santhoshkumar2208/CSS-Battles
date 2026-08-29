# #7. Leafy Trail

Challenge: <https://cssbattle.dev/play/7>

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
  <div class = "shape center"></div>
  <div class = "shape left"></div>
  <div class = "shape right"></div>
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
  .shape {
    position: absolute;
    width: 150px;
    height: 150px;
    border-radius: 67% 0% 67% 0%;
  }
  .center {
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    background: #998235;
    z-index: 1;
  }
  .left {
    top: 50%;
    left: 30%;
    transform: translate(-30%,-50%);
    background: #1A4341;
  }
  .right {
    top: 50%;
    right: 30%;
    transform: translate(30%,-50%);
    background: #F3AC3C;
    z-index: 1;
  }
</style>
```
