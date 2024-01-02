分割或者得到部分数组的方法 Arrays.copyOf(arr,n);

分割或者得到部分字符串的方法 string.substring(2,6);  重点：substring(2,6)中只截取索引2-5，不包括6

当使用ArrayList进行内部交换时，不能用数组那样的直接int[l]=temp，需要用arr.set()方法，因为ArrayList是对象引用不能直接赋值
