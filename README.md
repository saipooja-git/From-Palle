# From-Palle
# Sai Pooja Reddy Palle
###### Bawarchi 
Its a famous restaurant for **biryani**,where the food is delicious.
And people visit this restaurant very often.

-----
Appetizing
1. Biryani
    1. chicken biryani
    2. mutton biryani
2. Desserts
3. cool drinks

--------
* Charminar
    * Shopping
    * street food
* Golconda Fort
* Tank bund
* necklace road
![My info](MyMedia.md)


------------
The below are some books, that I would refer to read.
|Name of the book|Author|
|----------------|------|
|HalfGirlfriend|chetan bhagath|
|‘A Place Called Home’|preeti shenoy|
|‘The India Story’|Bimal Jalal|

------
|Name of the book|Reason|authorname|
|---------------|--------|----------|
|The Secret|I recommend this book,because it made be believe in me|Rhonda byrne|

---------------------
## Quotes ##

> To live is the rarest thing in the world. Most people exist, that is all.
> ***Oscar Wilde***
>
> You only live once, but if you do it right, once is enough.
> ***Mae West***


---------------------------------------------------
## code fencing ##

Python Singleton decorator
Tags: python, virtual environment, singleton decorator, python singleton

Decorator to create a singleton class.


```
def singleton(myClass):
	instances = {}
	def getInstance(*args, **kwargs):
		if myClass not in instances:
			instances[myClass] = myClass(*args, **kwargs)
		return instances[myClass]
	return getInstance

@singleton
class TestClass(object):
	pass 

```
lets go to snippet 16<https://code.pieces.app/collections/python>