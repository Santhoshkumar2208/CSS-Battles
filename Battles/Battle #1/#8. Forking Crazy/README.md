# #8. Forking Crazy

Challenge: <https://cssbattle.dev/play/8>

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
  <div class = "stick"></div>
  <div class = "box"></div>
  <div class = "prong-1"></div>
  <div class = "inner-prong-1"></div>
  <div class = "prong-2"></div>
  <div class = "inner-prong-2"></div>
  <div class = "prong-3"></div>
  <div class = "inner-prong-3"></div>
  <div class = "prong-4"></div>
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
    display: flex;
    justify-content: center;
    align-items: center;
    background: #6592CF;
  }
  .stick {
    position: absolute;
    width: 20px;
    height: 55px;
    background: #060F55;
    bottom: 0;
  }
  .box {
    position: absolute;
    width: 140px;
    height: 100px;
    background: #060F55;
    bottom: 50px;
    border-bottom-left-radius: 70px;
    border-bottom-right-radius: 70px;
  }
  .prong-1 {
    position: absolute;
    width: 20px;
    height: 110px;
    background: #060F55;
    bottom: 140px;
    left: 130px;
    border-top-left-radius: 70px;
    border-top-right-radius: 70px;
  }
  .prong-2 {
    position: absolute;
    width: 20px;
    height: 110px;
    background: #060F55;
    bottom: 140px;
    left: 170px;
    border-top-left-radius: 70px;
    border-top-right-radius: 70px;
  }
  .prong-3 {
    position: absolute;
    width: 20px;
    height: 110px;
    background: #060F55;
    bottom: 140px;
    left: 210px;
    border-top-left-radius: 70px;
    border-top-right-radius: 70px;
  }
  .prong-4 {
    position: absolute;
    width: 20px;
    height: 110px;
    background: #060F55;
    bottom: 140px;
    left: 250px;
    border-top-left-radius: 70px;
    border-top-right-radius: 70px;
  }
  .inner-prong-1 {
    position: absolute;
    width: 20px;
    height: 110px;
    background: #6592CF;
    bottom: 140px;
    left: 150px;
    border-bottom-left-radius: 70px;
    border-bottom-right-radius: 70px;
  }
  .inner-prong-2 {
    position: absolute;
    width: 20px;
    height: 110px;
    background: #6592CF;
    bottom: 140px;
    left: 190px;
    border-bottom-left-radius: 70px;
    border-bottom-right-radius: 70px;
  }
  .inner-prong-3 {
    position: absolute;
    width: 20px;
    height: 110px;
    background: #6592CF;
    bottom: 140px;
    left: 230px;
    border-bottom-left-radius: 70px;
    border-bottom-right-radius: 70px;
  }
</style>
```
