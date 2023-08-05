没有通过value直接返回key的方法，只有通过key找到value的方法（map.get()）

使用contains()方法时注意加上是containsKey()还是containsValue()

所有key的集合是keySet(),但是值的集合是values()

遍历键值对是用：

```java
Map<String, Integer> map = new HashMap<>();
// 添加键值对到哈希表
for (Map.Entry<String, Integer> entry : map.entrySet()) {
    String key = entry.getKey();
    Integer value = entry.getValue();
    System.out.println("Key: " + key + ", Value: " + value);
}
```
