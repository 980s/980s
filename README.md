<font color="red"> 
<p align="center"><a href=https://kybleat.straw.page>Strawpage</a><a href=https://1890s.straw.page target="_blank"></a>
<p align="center"><img width="1004" height="841" alt="image" src="https://github.com/user-attachments/assets/2fce761b-af39-42a1-aba0-e3e73437f99b" />




<p align="center"<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8" />
	<meta http-equiv="X-UA-Compatible" content="IE=edge" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<title>Hide a secret text message inside a text message</title>
</head>

<body>
	<div>
		<label for="publicText">Public text</label>
		<textarea id="publicText" cols="30" rows="10"></textarea>
		<label for="secretText">Secret text</label>
		<textarea id="secretText" cols="30" rows="10"></textarea>
		<input type="button" value="hide" onclick="hide_click()" />
		<input type="button" value="unhide" onclick="unhide_click()" />
		<br />
		<label for="result">Result</label>
		<textarea id="result" cols="30" rows="10"></textarea>
	</div>
	<style>
		input[type=button] {
			width: 100px;
			background-color: #4CAF50;
			color: white;
			padding: 14px 20px;
			margin: 10px 10px;
			border: none;
			border-radius: 4px;
			cursor: pointer;
		}

		input[type=button]:hover {
			background-color: #45a049;
		}

		textarea {
			width: 100%;
			height: 150px;
			padding: 12px 20px;
			box-sizing: border-box;
			border: 2px solid #ccc;
			border-radius: 4px;
			background-color: #f8f8f8;
			resize: none;
		}

		div {
			border-radius: 5px;
			background-color: #f2f2f2;
			padding: 20px;
		}

	</style>
	<script>var in_browser = true;</script>
	<script src="./hide-text.js"></script>
	<script>
		function hide_click() {
			result.value = "";
			if (publicText.value.length == 0) {
				publicText.focus();
				return;
			}
			if (secretText.value.length == 0) {
				secretText.focus();
				return;
			}
			result.value = hide_text(publicText.value, secretText.value);
		}
		function unhide_click() {
			publicText.value = '';
			secretText.value = '';
			if (result.value.length == 0) {
				result.focus();
				return;
			}
			secretText.value = unhide_text(result.value);
		}
	</script>
</body>

</html>






  


<p align="center"><p align="center">
  <a href="https://github.com/kittinan/spotify-github-profile">
    <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=31rhghy6eby5deomgoypfuhasgqq&cover_image=true&theme=novatorem&show_offline=true&background_color=121212&interchange=false&profanity=false&hide_remaster=false&bar_color=5c0700&bar_color_cover=false">
  </a>
</p>
