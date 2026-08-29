# #3. Push Button

Challenge: <https://cssbattle.dev/play/3>

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
  <div class = "rectangle">
    <div class = "circle">
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
    background: #6592CF;
  }
  .rectangle {
    position: absolute;
    width: 300px;
    height: 150px;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    background: #243D83;
  }
  .circle {
    position: absolute;
    width: 250px;
    height: 250px;
    border-radius: 50%;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    background: radial-gradient(circle at center, #EEB850 0px 25px, #243D83 25px 75px, #6592CF 75px 125px );
  }
</style>
```
