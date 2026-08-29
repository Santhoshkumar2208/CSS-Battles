# #4. Ups n Downs

Challenge: <https://cssbattle.dev/play/4>

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
  <div class = "shape bottom-left"></div>
  <div class = "shape bottom-right"></div>
  <div class = "shape top"></div>
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
  .shape {
    position: absolute;
    width: 100px;
    height: 100px;
    border-radius: 100% 100% 0% 0%;
    background: #F7EC7D;
  }
  .top {
    bottom: 150px;
    left: 150px;
  }
  .bottom-left {
    transform: scaleY(-1);
    top: 150px;
    left: 50px;
  }
  .bottom-right {
    transform: scaleY(-1);
    top: 150px;
    left: 250px;
  } 
</style>
```
