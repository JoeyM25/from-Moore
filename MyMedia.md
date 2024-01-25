# Joey Moore
My favorite TV show is Better Call saul. My favorite movie is Whiplash. My favorite color is blue. 
![Me](coverpicture.jpg)
---
# Media I recommend
| Name | Why I recomend it | Creator |
| --- | --- | --- |
| The Distance | This song has a solid base line and is just a fun listen | Cake |
| The hunger games | I just watched this movie for the first time, while it's a little dated, but that seemed to add to it. | Suzanne Collins |
| Lord of the Rings | A really good movie series that tells an intriguing story and sets a lot of precedent for other movies | J. R. R. Tolkien |
| Breaking bad | It has Bryan Cranston and Aaron Paul | Vince Gilligan |
---
# Good quotes
> "I don't know, but today seems kinda odd" -- *Ice Cube*

> "Turn down for what?" -- *Lil' Jon*
---
# Some code
Merge a series of lists into a list of lists. For example, [1, 2, 3] and [4, 5, 6] would merge into [[1, 2, 3], [4, 5, 6]].
```
def merge(*args, missing_val = None):
    max_length = max([len(lst) for lst in args])
    out_list = []
    for i in range(max_length):
        out_list.append([args[k][i] if i < len(args[k]) else missing_val for k in range(len(args))])
    return out_list 
```
![source](https://code.pieces.app/collections/python)
