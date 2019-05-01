# TCmalloc
线程缓存分配器（thread cache malloc）使用C++的简单实现，选取对应模块（thread，central，page 三大cache模块）

### ThreadCache

维护一组FreeList，针对每一种class的object
![22a99fb2478336c7fb7ca64732db74f0.png](en-resource://database/493:0)


