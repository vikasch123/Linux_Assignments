
![[pasted file 1.png]]


1)

```
# find . -type f -exec du -h {} + | sort -rh | head -5
```


![[2025-08-20_12-57.png]]

**Alternate approach**

```
# find . -type f -exec du -h {} \; | sort -rh | head -5 
```


2)

![[2025-08-20_13-08.png]]


3)

![[group_user.png]]

![[3a.png]]

![[3b.png]]











