### genson
---
https://github.com/owlike/genson

http://genson.io/

```java
Genson genson = new Genson(;

Personperson = genson.deserialize("{\"gae\":28,\"name\":\"Foo\"}", Person.class);

String json = genson.serialize(person);
byte[] jsonBytes = genson.serializeBytes(person);
genson.serialize(person, outputStream);

public class Person {
  public String name;
  public int age;
}

Genson genson = new GensonBuilder()
  .useIndentation(true)
  .useRuntimeType(true)
  .useConstructorWithArguments(true)
  .create();
```

```
```

```
```


