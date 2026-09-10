# #21. SitePoint Logo

Challenge: <https://cssbattle.dev/play/21>

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
  <div class = "short-1"></div>
  <div class = "long-1"></div>
  <div class = "short-2"></div>
  <div class = "long-2"></div>
</div>
<style>
  * {
    margin: 0;
    padding: 0;
    background: #222;
    width: 400px;
    height: 300px;
  }
  .container {
    position: relative;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-190px) rotate(-45deg);
  }
  .short-1 {
    position: absolute;
    width: 30px;
    height: 80px;
    background: #F2994A;
    left: 130px;
    top: 110px;
    border-radius: 10px 0 5px 0px;
  }
  .long-1 {
    position: absolute;
    width: 80px;
    height: 30px;
    background: #F2994A;
    top: 110px;
    left: 150px;
  }
  .short-2 {
    position: absolute;
    width: 30px;
    height: 80px;
    background: #2D9CDB;
    right: 191px;
    top: 160px;
    border-radius: 5px 0 10px 0px;
  }
  .long-2 {
    position: absolute;
    width: 70px;
    height: 30px;
    background: #2D9CDB;
    left: 110px;
    bottom: 60px;
  }
</style>
```
