# #37. Tunnel

Challenge: <https://cssbattle.dev/play/37>

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
  <div class = "big"></div>
  <div class = "medium"></div>
  <div class = "small"></div>
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
  .big {
    position: absolute;
    width: 250px;
    height: 250px;
    background: #243D83;
  }
  .medium {
    position: absolute;
    width: 150px;
    height: 150px;
    background: #6592CF;
    transform: rotate(15deg);
  }
  .small {
    position: absolute;
    width: 75px;
    height: 75px;
    background: #243D83;
    transform: rotate(30deg);
  }
</style>
```
