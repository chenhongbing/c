# c
    int *p;
    int a=2;
    unsigned long b=6422312;
    p=&a;
    printf("%d\n",*p);
    printf("%p\n",&a);  //&a是int *类型,以内存形式,十六进制打印出来
    printf("%d\n",&a);
    printf("%d\n",&b);
    printf("%d\n",(void *)b);      //此时b是一个void *指针,打印的是该指针存取的地址
    //printf("%d\n",*(void *)b);
    //此时b是一个int *指针,里面存取的是一个地址,在对该地址进行解引用,即提取相应地址的值
    printf("%d\n",*(int *)b);
    printf("%d\n",*(void **)b);
