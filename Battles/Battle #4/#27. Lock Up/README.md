# #27. Lock Up

Challenge: <https://cssbattle.dev/play/27>

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
  <div class = "outer-circle">
    <div class = "inner-circle"></div>
  </div>
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
    background: #E38F66;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .outer-circle {
    position: relative;
    width: 200px;
    height: 200px;
    border-radius: 50%;
    background: #AA445F;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .inner-circle {
    position: absolute;
    width: 140px;
    height: 140px;
    border-radius: 50%;
    background: conic-gradient(#F7EC7D 90deg, #AA445F 90deg 180deg, #F7EC7D 180deg 270deg, #AA445F 270deg 360deg);
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .inner-circle:before {
    content: '';
    position: absolute;
    width: 80px;
    height: 80px;
    background: #AA445F;
    border-radius: 50%;
  }
</style>
```
