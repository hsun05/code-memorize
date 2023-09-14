# code-memorize
A Javascript site that helps you memorize codes

## How to use
1. Paste your original code into [.code_input] textbox
```
<textarea id="code" class="code_input">
<!-- CODE INPUT AREA START -->
#include <stdio.h>

void main(){
  int a = 1;
}
<!-- CODE INPUT AREA END -->
</textarea>
```
2. Write codes to test and hint for that into const mission on line 83
```
const mission = {
  "int a = 1;", "int a is missing"
}
```

## Comments
You can use ``` // ```, but you can't use ``` /*  */ ```
