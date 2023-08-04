# Java-tips

### Records
```
public record Greeting(long id, String content) {}
```
It's like a simple version of the java class. It is used to define attributes within a model and access them directly.

<br />

### AtomicLong
```
AtomicLong counter = new AtomicLong();
```
A numeric type object that provides functions similar to an identifier.
```
counter.incrementAndGet();  // current number + 1
```
