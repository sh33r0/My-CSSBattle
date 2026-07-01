# #12. Wiggly Moustache

Challenge: <https://cssbattle.dev/play/12>

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
<body bgcolor=#F5D6B4><p><style>
  p{
    height:30px; width:60px;
    border: 20px solid #D86F45;
    border-radius:50px 50px 0 0;
    border-bottom:0;
    margin:100px 0 0 142px;
  }
  p:before{
    content:'';
    display: block;
    height:30px; width:60px;
    border: 20px solid #D86F45;
    border-radius:0 0 50px 50px;
    border-top:0;
    margin:30 0 0 -100px;
    filter:drop-shadow(160px 0 #D86F45);
  }
  p:after{
    content:'';
    position: absolute;
    border: 10px solid #D86F45;
    border-radius: 50%;
    margin: -60 0 0 -99;
    box-shadow:240px 0 #D86F45;
```
