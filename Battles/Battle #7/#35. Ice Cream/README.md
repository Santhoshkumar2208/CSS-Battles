# #35. Ice Cream

Challenge: <https://cssbattle.dev/play/35>

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
    background: #293462;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .big-rect {
    position: absolute;
    width: 100px;
    height: 150px;
    background: #FFF1C1;
    top: 50px;
    border-top-left-radius: 50px;
    border-top-right-radius: 50px;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
  }
  .small-rect {
    position: absolute;
    width: 30px;
    height: 50px;
    background: linear-gradient(to bottom, #A64942 0% 20%, #FE5F55 20% 100%);
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    bottom: 50px;
  }
</style>
```
