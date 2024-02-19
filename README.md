# TIB_DECRYPT_GV V.1.0.0


## Java Code

```
package ProcessDefinition;
import java.util.*;
import java.io.*;
import com.tibco.security.ObfuscationEngine;
public class ProcessDefinitionJavaCode{
/****** START SET/GET METHOD, DO NOT MODIFY *****/
 protected String Input = "";
 protected String Output = "";
 public String getInput() {
  return Input;
 }
 public void setInput(String val) {
  Input = val;
 }
 public String getOutput() {
  return Output;
 }
 public void setOutput(String val) {
  Output = val;
 }
/****** END SET/GET METHOD, DO NOT MODIFY *****/
 public ProcessDefinitionJavaCode() {
 }
 public void invoke() throws Exception {
/* Available Variables: DO NOT MODIFY
 In  : String Input
 Out : String Output
* Available Variables: DO NOT MODIFY *****/
String var = new String(ObfuscationEngine.decrypt(Input));
 Output=var;
}
}
```

Por exemplo, o password será por padrão como abaixo:

#!oe2FVz/rcjokKW2hIDGE7nSX1U+VKRjA=

Então use o valor do password como entrada para a entrada do código Java, ou seja, "#!oe2FVz/rcjokKW2hIDGE7nSX1U+VKRjA" (sem aspas), então obteremos o valor descriptografado no parâmetro de saída."


## Créditos

[TibcoWorldIn](https://tibcoworldin.blogspot.com/2012/08/decrypting-password-data-type-global.html)