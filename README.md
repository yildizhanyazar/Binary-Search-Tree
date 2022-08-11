# Binary Search Tree

[Patika dev'e gitmek için](https://www.patika.dev/tr)
[Benim hesabıma gitmek için](https://app.patika.dev/makoveli)
[Ödev sayfası için](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje)

---

## **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** 


1.   Binary-Search-Tree aşamalarını yazınız.

```
root = 7
				7
			  /	  \
		     5     8
		    / \     \
		   1   6     9
		  / \          
		 0   3
		    / \
		   2   4    
```

2.  Aşamalar (Adımlar)

```
- 7 yi seçtik diziden sayıları alalım.
- 5 7 den küçük soluna koyuyoruz.
- 1 7 den küçük soluna koyacağız ama 1 5 den küçük onunda soluna koyuyoruz.
- 8 7 den büyük sağına koyuyoruz. 
- 3 7 den küçük 5 ten küçük fakat 1 den büyük 1 in sağına koyuyoruz.
- 6 7 den küçük 5 den büyük 5 in sağına koyuyoruz.
- 0 7 den küçük 5 den küçük 1 den küçük 1 in soluna koyuyoruz.
- 9 7 den büyük 8 den büyük 8 in sağına koyuyoruz.
- 4 7 den küçük 5 den küçük fakat 1 den büyük 3 den büyük 3 ün sağına koyuyoruz.
- 2 7 den küçük 5 den küçük 1 den büyük 3 den küçük 3 ün soluna koyuyoruz.
```
