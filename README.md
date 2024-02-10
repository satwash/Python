# **Python List Slicing**


## **Notations:**

```
list[:]             >> All        
list[Low:]          >> Low to End      
list[:High]         >> Begining to (High-1)
list[Low:High]      >> Low to (High-1)
list[::Step]        >> Start to (End-1) with Step
list[Low::Step]     >> Low to End with Step
list[:High:Step]    >> Start to (High-1) with Step
list[Low:High:Step] >> Low to (High-1) with Step
```
## **Example**

```python
list= ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I']
```


***Simple***

```python
list[3]      >> 'D'
list[-3]     >> 'G'
list[:]      >> ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I']
list[3:]     >> ['D', 'E', 'F', 'G', 'H', 'I']
list[:3]     >> ['A', 'B', 'C']
list[-3:]    >> ['G', 'H', 'I']
list[:-3]    >> ['A', 'B', 'C', 'D', 'E', 'F']
```

```python
list= ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I']
```


***Double with step***
```python
list[2:7:4]  >> ['C', 'G']
list[2:7:5]  >> ['C']
list[2:7:2]  >> ['C', 'E', 'G']
list[1:8:2]  >> ['B', 'D', 'F', 'H']
list[-7:8:2] >> ['C', 'E', 'G']
```

```python
list= ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I']
```

***More variations***
```python
list[-1::]   >> ['I']
list[-3::]   >> ['G', 'H', 'I']
list[3::]    >> ['D', 'E', 'F', 'G', 'H', 'I']
list[::-1]   >> ['I', 'H', 'G', 'F', 'E', 'D', 'C', 'B', 'A']
list[::-4]   >> ['I', 'E', 'A']
list[::4]    >> ['A', 'E', 'I']
list[::-2]   >> ['I', 'G', 'E', 'C', 'A']
list[::2]    >> ['A', 'C', 'E', 'G', 'I']

```

