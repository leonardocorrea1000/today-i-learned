## How to iterate with JSONObject

```java
Iterator<String> iter = json.keys();
while (iter.hasNext()) {
    String key = iter.next();
    try {
        Object value = json.get(key);
    } catch (JSONException e) {
        // Something went wrong!
    }
}
```

Source: http://stackoverflow.com/questions/13573913/android-jsonobject-how-can-i-loop-through-a-flat-json-object-to-get-each-key-a