# ScanBarCode

##連續掃描條碼

![image](https://github.com/LinEven/Blin/blob/main/images/read.gif)

```HTML
    <script language="javascript">
      var input = document.getElementById("myInput");
      input.addEventListener("keyup", function (event) {
        if (event.keyCode === 13) {
          event.preventDefault();
          document.getElementById("myBtn").click();
        }
      });
```
