#面试总结

#### #ifndef/#define/#endif的格式：
    #ifndef A_H意思是"if not define a.h"  如果不存在a.h
    接着的语句应该#define A_H  就引入a.h
    最后一句应该写#endif   否则不需要引入
    #ifndef GRAPHICS_H // 防止graphics.h被重复引用 
    #define GRAPHICS_H 
