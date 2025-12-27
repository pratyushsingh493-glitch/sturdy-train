# sturdy-train
Starting My journey as an open source contributor!! 
# Fresh_Start
Author-Pratyush Singh  <--2 spaces   
new line<--1 line leave

heoo!!!
## Fresh_Start2
ok everything is alright

### Fresh_Start3
This is **bold**

this i *italic*

This is bold+italic ***bpl***

This is ~~crossed off~~

This is how u <mark>highlight</mark>

This is an example of superscript x<sup>2</sup>

This is an example of subscript H<sub>2</sub>O

Emoji Time

😊  🪄

Here is my code:

```cpp
#include<bits/stdc++.h>
using namespace std;
#define f(i,x,n) for(int i=x;i<n;i++)
int main()
{
    int t;
    cin>>t;
    while(t--){
        int n;
        cin>>n;
        int a[n],d[n];
        f(i,0,n){
            cin>>a[i];
        }
        f(i,0,n){
            cin>>d[i];
        }
        int mx=-1;
        f(i,0,n){
            if(d[i]>a[(n+i+1)%n]+a[(n+i-1)%n]){
                mx=max(mx,d[i]);
            }
        }
        cout<<mx<<endl;
    }
    return 0;
}
```

For more details check out for [EMOJI](https://emojipedia.org/)

you can also click this 👉<https://emojipedia.org/>

You can also add images

![CODEFORCES](https://images.seeklogo.com/logo-png/38/1/codeforces-logo-png_seeklogo-380978.png)

### There are some more formatting:

> hello  
>>this is fun  
>>>and cool  
>>ok   
>>this  
>Borong

Itachi

***

Naruto

# List

* item1
* item 2
    * the next 
        * this is crazy
            * Awsome

1. Item 1
2. Item 2
    * This looks good

# Table
Get excited to make some tables

| x | x<sup>2</sup> |
|:--|--------------:|
| 1 | 1             |
| 2 | 4             |
| 3 | 9             |
| 4 | 16            |
| 5 | 25            |
| 6 | 36            |
| 7 | 49            |
| 8 | 64            |

you cav use:

* left allignment
>:----
* right allignment
>----:
* centre allignment
>:----:

# Check Box

* [ ] random

- [x] random