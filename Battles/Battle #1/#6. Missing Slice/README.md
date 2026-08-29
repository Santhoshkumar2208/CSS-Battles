# #6. Missing Slice

Challenge: <https://cssbattle.dev/play/6>

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
    background: #E3516E;
  }
  .circle {
    position: absolute;
    width: 200px;
    height: 200px;
    border-radius: 50%;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    background: conic-gradient(#FADE8B 0% 25%, #E3516E 25% 50%, #F7F3D7 50% 75%, #51B5A9 75% 100%)
  }
</style>
```
