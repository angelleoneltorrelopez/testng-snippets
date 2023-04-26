# TestNG Snippets
This plugin for IntelliJ of TestNG Snippets for Java is a tool designed to help developers write tests more efficiently 
and quickly in Java projects that use TestNG as a testing framework. The plugin provides a wide variety of predefined 
code snippets that cover TestNG annotations, test data configurations, common test cases, assertions, and more.

Users can easily select the relevant snippet and add it directly to their test code, saving time and reducing common 
syntax errors. Additionally, the plugin also offers autocomplete functions to suggest relevant snippets while writing 
test code, allowing developers to write more accurate and complete tests in less time.

In summary, this TestNG Snippets plugin for IntelliJ is a valuable tool for any developer working with TestNG in Java 
projects, helping them increase efficiency and improve the quality of their tests.

## Installation
To install the snippets in Intellij IDEA, Press Ctrl+Alt+S to open the IDE settings and select Plugins.
Find the plugin in the Marketplace and click Install.

## Supported (file extensions)

- Java

## Snippets

### Project : `project`
```javascript
public void setUp() {
//settings
}

@Test(description = "Test description")
public void testName() {
Assert.assertTrue(true, "string message");
}
```

### Test : `test`
```javascript
@Test(description = "test description")
public void testName() {
Assert.assertTrue(true, "String message");
}
```

### After Method : `afterMethod`
```javascript
@AfterMethod
public void methodName() {        
}
```

### Before Method : `beforeMethod`
```javascript
@BeforeMethod
public void methodName() {        
}
```

### Parameter : `parameter`
```javascript
@Parameters({"parameter"})
```

### Optional : `optional`
```javascript
@Optional("variable")
```

### Asset Equals : `assertEquals`
```javascript
Assert.assertEquals("actual","expected","String message");
```

### Asset True : `assertTrue`
```javascript
Assert.assertTrue(true,"String message");
```

### Asset False : `assertFalse`
```javascript
Assert.assertFalse(false,"String message");
```

## License

[MIT](./LICENSE)