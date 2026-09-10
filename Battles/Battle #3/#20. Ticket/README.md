# #20. Ticket

Challenge: <https://cssbattle.dev/play/20>

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
  <div class = "big-rect"></div>
  <div class = "small-rect"></div>
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
    background: #62306D;
  }
  .big-rect {
    position: absolute;
    width: 140px;
    height: 100px;
    background: #F7EC7D;
    top: 100px;
    left: 100px;
    border-top-left-radius: 20px;
    border-top-right-radius: 10px;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 10px;
    corner-shape: scoop;
  }
  .small-rect {
    position: absolute;
    width: 60px;
    height: 100px;
    background: #E38F66;
    top: 100px;
    left: 240px;
    border-top-left-radius: 10px;
    border-top-right-radius: 20px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 20px;
    corner-shape: scoop;
  }
</style>
```
