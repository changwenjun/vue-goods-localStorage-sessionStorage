# vue-goods-localStorage-sessionStorage

good-storage的使用
2017年09月28日 16:57:53
阅读数：1530
安装
npm install good-storage


用法

// localStorage

 storage.set(key,val) 

 storage.get(key, def)


 // sessionStorage
 storage.session.set(key, val)
 storage.session.get(key, val)



API
#set(key, val)

###set storage with key and val

#get(key, def)

###get storage with key, return def if not find

#remove(key)

###remove storage with key

#has(key)

###determine storage has the key

#clear()

###clear all storages

#getAll()

###get all the storages

#forEach(callback)
  
###forEach the storages and call the callback function with each storage


