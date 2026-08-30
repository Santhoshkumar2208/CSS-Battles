# #15. Overlap

Challenge: <https://cssbattle.dev/play/15>

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
  <div class = "circle left"></div>
  <div class = "circle right"></div>
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
    background: #09042A;
  }
  .circle {
    position: absolute;
    width: 150px;
    height: 150px;
    border-radius: 50%;
  }
  .left {
    top: 75px;
    left: 75px;
    box-shadow: inset 100px 0px 0px 0px #7B3F61;
  }
  .right {
    top: 75px;
    right: 75px;
    box-shadow: inset -100px 0px 0px 0px #E78481;
  }
</style>
```
