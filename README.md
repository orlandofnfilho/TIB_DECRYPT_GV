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

For Example the GV is like below

#!oe2FVz/rcjokKW2hIDGE7nSX1U+VKRjA
 
Then use the GV value as input for the JavaCode input i.e. "#!oe2FVz/rcjokKW2hIDGE7nSX1U+VKRjA"  then will get the Decrypt value in Output Parameter.


## Créditos

[TibcoWorldIn](https://tibcoworldin.blogspot.com/2012/08/decrypting-password-data-type-global.html)