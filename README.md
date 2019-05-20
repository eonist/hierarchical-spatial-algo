# hierarchical-spatial-algo
An algorithm that positions tree structured data items as an inverted tree

**From this:** 

```
{
	"title":"pet grooming",
	"contributors":["Nikita","Angelo","PGG✌️"],
	"meta":["Pets","animals","nature"],
	"nodes":[
		{
			"title":"Tools",
			"nodes":[
				{"title":"clippers","url":"animals/clippers.json"},
				{"title":"Blades"},
				{"title":"Brushes"}
			]
		},
		{
			"title":"Workflows",
			"nodes":[
				{"title":"bathing"},
				{"title":"fur"},
				{"title":"claw"}
			]
		},
		{
			"title":"Tips",
			"nodes":[
				{"title":"Blogs"},
				{"title":"Books"}
			]
		}
	]
}
```

**To this:**

<img width="800" alt="img" src="https://raw.githubusercontent.com/learn-anything/img/master/petgrooming.png">


**Ascending symmetrically:** 

<img width="800" alt="img" src="https://raw.githubusercontent.com/learn-anything/img/master/Screen Shot 2017-05-22 at 02.39.34.png">
