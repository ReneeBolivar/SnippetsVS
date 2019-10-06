# SnippetsVS
Simple snippets for Visual Studio to help developers who need coding agility xD

## Install
Download the current's files of this repository and follow the steps described on [Microsoft Documentation](https://docs.microsoft.com/en-us/visualstudio/ide/walkthrough-creating-a-code-snippet?view=vs-2019#import-a-code-snippet)

### Static constructor
Enter **sctor** and press 'Tab' twice to create a static constructor.

```
static ClassName()
{

}
```

### Public method
Enter **pubmet** and press 'Tab' twice to create a public method with a void return and without params

```
public void Method()
{

}
```

### Private method
Enter **primet** and press 'Tab' twice to create a private method with a void return and without params

```
private void Method()
{

}
```

### Try/Catch/Finally
Enter **tcf** and press 'Tab' twice to create a try/catch/finally block and import automatically the **System** namespace.

```
try
{
}
catch(Exception)
{
}
finally
{
}
```

### Documentation
Enter **doc** and press 'Tab' twice to create a simple template of a documentation with XML  comment and import automatically the **System** namespace.

```
/// <summary>
/// Method Information
/// </summary>
/// <param name="args">Parameter</param>
/// <exception cref="Exception">Default Exception</exception>
/// <returns>
/// Method Return
/// </returns>
/// See more on this link <see cref="https://docs.microsoft.com/en-us/dotnet/csharp/"/>]]>
```
