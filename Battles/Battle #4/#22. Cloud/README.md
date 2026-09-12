# #22. Cloud

Challenge: <https://cssbattle.dev/play/22>

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
</div>
<style>
  * {
    margin: 0;
    padding: 0;
  }
  .container {
    width: 400px;
    height: 300px;
    background: #F5D6B4;
  }
  .circle {
    width: 200px;
    height: 50px;
    border-radius: 10px 101px 101px 200px; 
    background: #D86F45;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,15px);
  }
  .circle:before {
    content: '';
    position: absolute;
    background: #D86F45;
    width: 95px;
    height: 95px;
    border-radius: 50%;
    bottom: 4px;
  }
  .circle:after{
    content: '';
    position: absolute;
    background: #D86F45;
    width: 100px;
    height: 100px;
    border-radius: 50%;
    bottom: 30px;
    right: 20px;
  }
</style>
```
