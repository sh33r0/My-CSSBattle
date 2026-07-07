# #7. Leafy Trail

Challenge: <https://cssbattle.dev/play/7>

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
<div class="s"></div>
<div class="s a"></div>
<div class="s b"></div>
<style>
  body {
    background: #0b2429;
  }
  .s {
    position: absolute;
    background: #1a4341;
    width: 150px;
    height: 150px;
    top: 75px;
    left: 75px;
    border-top-left-radius: 100px;
    border-bottom-right-radius: 100px;
  }
  .a {
    left: 125px;
    background: #998235;
    z-index: 1;
  }
  .b {
    left: 175px;
    background: #f3ac3c;
    z-index: 2;
  }
</style>
```
