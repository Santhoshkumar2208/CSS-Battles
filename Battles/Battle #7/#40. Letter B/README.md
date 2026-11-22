# #40. Letter B

Challenge: <https://cssbattle.dev/play/40>

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
  <div class = "rect-1"></div>
  <div class = "rect-2"></div>
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
    background: #6592CF;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .circle {
    position: absolute;
    width: 200px;
    height: 200px;
    background: radial-gradient(at center, #6592CF 0 35%, #243D83 0 100%);
    border-radius: 50%;
  }
  .rect-1 {
    position: absolute;
    width: 100px;
    height: 100px;
    background: #6592CF;
    left: 100px;
    top: 50px;
  }
  .rect-2 {
    position: absolute;
    width: 50px;
    height: 100px;
    background: #243D83;
    left: 100px;
    top: 50px
  }
</style>
```
