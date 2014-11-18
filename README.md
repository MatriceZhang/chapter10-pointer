chapter10-pointer
=================


//
//  main.cpp
//  chapter10_pointer
//
//  Created by zhangshiyu on 11/18/14.
//  Copyright (c) 2014 ZSY. All rights reserved.
//

#include <iostream>
using namespace std;

int main()
{
    int var1=11;
    int var2=22;
    
    cout<<&var1<<endl;
    cout<<&var2<<endl<<endl;    //print address of variables
    
    int *ptr;    //pointer to integers
    
    ptr=&var1;
    cout<<ptr<<endl;    //print pionts value
    return 0;
}
