# #38. Not Simply Square

Challenge: <https://cssbattle.dev/play/38>

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
  <div class = "white"></div>
  <div class = "top"></div>
  <div class = "bottom"><div>
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
    background: #293462;
  }
  .white {
    position: absolute;
    width: 200px;
    height: 200px;
    background: #FFF1C1;
  }
  .top {
    position: absolute;
    width: 100px;
    height: 200px;
    background: linear-gradient(to bottom,#FE5F55 75%, #A64942 25%);
    left: 200px;
  }
  .bottom {
    position: absolute;
    width: 200px;
    height: 100px;
    background: linear-gradient(to right,#FE5F55 75%, #A64942 25%);
    top: 200px;
  }
</style>
```
