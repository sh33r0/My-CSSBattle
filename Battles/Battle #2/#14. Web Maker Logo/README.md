# #14. Web Maker Logo

Challenge: <https://cssbattle.dev/play/14>

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
<body bgcolor=F2F2B6><p><p a><style>p{
    width:0;
    border-style:solid;
    border-width:130px 75px 0 75px;
    border-color: #FF6D00 transparent;
    margin:85 52;
    }
  p[a]{
    transform:rotate(180deg);
    position:fixed;
    top:0; left:138;
    z-index:-1;
  }
  p:after{
    content:'';
    width: 0;
    height:0;
    border-style:solid;
 border-width: 0 75px 130px 75px;
border-color: #FD4602 transparent;
    position:fixed;
    top:85; left:170;
    z-index:1;
  }
    p[a]:after{
    top:-130; left:35;
    }
```
