# Anstasiya Tsarikevich

!["Avatar"](./photo.jpg)

### Contacts: 
+37529751055

### About me:
* diligence and organization;
* ethics and loyalty;
* punctuality;
* flexibility;
* ability to work in team;
* technical savvy;

### Skills:
* JavaScript Basic, CSS, HTML 

### Code examples:
```
<!DOCTYPE html>
<html>
<body>

<h1>Копировать текст</h1>

<p>Нажмите на кнопку, чтобы скопировать текст из текстового поля. Попробуйте вставить текст (например, ctrl+v) после этого в другом окне, увидите эффект.</p>

<input type="text" value="Привет мир" id="myInput">
<button onclick="myFunction()">Скопировать текст</button>

<p>Метод document.execCommand() не поддерживается в IE8 и более ранних версиях.</p>

<script>
function myFunction() {
  var copyText = document.getElementById("myInput");
  copyText.select();
  copyText.setSelectionRange(0, 99999)
  document.execCommand("copy");
  alert("Скопировал текст: " + copyText.value);
}
</script>

</body>
</html>
```

### Education: BSU Chemfak


### English language: A1

