# Java I Cheat Sheet

## Comments

<table>

<tr>
<td>Explanation</td>
<td>Example</td>
</tr>

<tr>
<td>Single</td>
<td>

```Java
// comment  text
```

</td>
</tr>

<tr>
<td>Multiline (Basic)</td>
<td>

```Java
/*
comment text
*/
```

</td>
</tr>

<tr>
<td>Multiline JavaDoc</td>
<td>

```Java
/**
 * comment text
 * @author BobSaidHi
*/
```

</td>
</tr>

</table>

More [info](https://www.oracle.com/technical-resources/articles/java/javadoc-tool.html)

Longer [list](https://www.tutorialspoint.com/java/java_documentation.htm)

| Tag | Explanation |
|---|---|
| `@author` | Author tag |
| `@version` | Version tag |
| `@param` | Explains one of the method's parameters |
| `@return` | Explains what the method returns |
| `@see` | References more information |
| `@since` | When something was first implemented |
| `@deprecated` | Deprecated tag |



## Primitive Variables

<table>

<tr>
<td> Type </td>
<td> Symbol/ Keyword </td>
<td> Example </td>
</tr>

<tr>
<td> integer </td>
<td> `int` </td>
<td>

```Java
// Multiple Lines
int i;
i = 0;

// Single Line
int i = 0;
```

</td>

<tr>
<td> double </td>
<td> `int`` </td>
<td>

```Java
// Multiple Lines
int i;
i = 0;

// Single Line
int i = 0;
```

</td>

</table>



```Java

int

char

String


```

| Keyword | Explanation |
| --- | --- |
| `int` | integer primiative |
| char | charecter primaitve |
| String | String object, implmetned as charecter array (`char[]`)
| short | |
|long | |
| double | |
|float | |


## Print Statements

[JavaDOC](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/System.html#out)

```Java
// Print something out
System.out.print("I'm a String");

// Print something out and add a line break
System.out.println("I'm a String");

// Concatenating a String and a integer
System.out.println("Five as a number is: " + 5);


```

> Please note that "I'm a String" (including the quotes) can be replaced by almost anything, including other data types, variables, and even some objects.

## Escape Sequences

| Sequence | Meaning |
|---|---|
| `\` | Open escape sequence |
| `\t` | tab |
| `\n` | line break (new line) |
| `\"` | Allows the use of double quotes in a String |
| `\'` | Allows the use of a single quot in a char |
| `\\` | Allows the use of a backslah in text

[Furhter Reading](https://www.informit.com/articles/article.aspx?p=30241&seqNum=3)
