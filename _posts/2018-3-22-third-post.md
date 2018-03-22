---
layout:  post
title: 2018/3/22 machine learning
---

機器學習課程 2018/3/22 

今天裕成大大要演講~~~  介紹python 的基礎用法

l[0:5:2]  // start end step :[0 2 4]

# dict:   //類似MAP
d= dict({'a':1, 'b':2}) 
d['a']=1

# Global //function要用外部變數時要先用global

```
a=1
def d():
  global a
  a=2 
```  
  
# is
和a==b相同 

# with
with open('test.txt') as f // 開檔後會自動關閉

# class  //一定要加 self

```
class classs(object):
  """
  document~~
  """
  def __init__ (self):
    self.val1=1
    self.val2=2
    
  def public_method(self, x):
    return self._private(x)
    
  def _private(self,x):
    return x
```  
  


# 繪圖軟體
1. mat power lib ex: 畫loss rate
2. Pathlib







