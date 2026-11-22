# #36. Interleaved

Challenge: <https://cssbattle.dev/play/36>

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
  <div class = "one"></div>
  <div class = "two"></div>
  <div class = "three"></div>
  <div class = "four"></div>
  <div class = "five"></div>
</div>
<style>
  * {
    margin: 0;
    padding: 0;
  }
  .container {
    width: 400px;
    height: 300px;
    background:#1A4341;
    position: relative;
  }
  .one {
    position: absolute;
    width: 50px;
    height: 200px;
    background: #F3AC3C;
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
    bottom: 0px;
    left: 25px;
  }
  .two {
    position: absolute;
    width: 50px;
    height: 200px;
    background: #F3AC3C;
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
    bottom: 0px;
    left: 175px;
  }
  .three {
    position: absolute;
    width: 50px;
    height: 200px;
    background: #F3AC3C;
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
    bottom: 0px;
    right: 25px;
  }
  .four {
    position: absolute;
    width: 50px;
    height: 200px;
    background: #998235;
    border-bottom-left-radius: 25px;
    border-bottom-right-radius: 25px;
    top: 0px;
    left: 100px;
  }
  .five {
    position: absolute;
    width: 50px;
    height: 200px;
    background: #998235;
    border-bottom-left-radius: 25px;
    border-bottom-right-radius: 25px;
    top: 0px;
    left: 250px;
  }
</style>
```
