# #25. Blossom

Challenge: <https://cssbattle.dev/play/25>

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
  <div class = "shape-1"></div>
  <div class = "shape-2"></div>
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
    background: #998235;
  }
  .shape-1 {
    position: absolute;
    width: 80px;
    height: 100px;
    background: #1A4341;
    left: 110px;
    top: 60px;
    border-radius: 0px 50px 0px 50px;
  }
  .shape-1:before {
    content: '';
    position: absolute;
    width: 80px;
    height: 100px;
    background: #1A4341;
    left: 100px;
    top: 80px;
    border-radius: 0px 50px 0px 50px;
    transform: scaleY(-1);
  }
  .shape-2 {
    position: absolute;
    width: 80px;
    height: 60px;
    background: #F3AC3C;
    left: 110px;
    bottom: 60px;
    border-radius: 0px 50px 0px 50px;
  }
  .shape-2:before {
    content: '';
    position: absolute;
    width: 80px;
    height: 60px;
    background: #F3AC3C;
    left: 100px;
    bottom: 120px;
    border-radius: 0px 50px 0px 50px;
    transform: scaleY(-1);
  }
</style>
```
