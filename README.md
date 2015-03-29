# github-languages
Reports username programming language statistics in bytes

Using http://d3pie.org/ d3 pie chart graph one can generate graphs of
languages programmed.

![Graph example](https://github.com/ernestas-poskus/github-languages/blob/master/example/graph.png)

How to:

1) generate and download template with desired configuration

> Start with a http://d3pie.org/#generator

2) if you have not reached your GitHub API request limit you can omit token

> go run main.go -user=YOUR_USER -token=YOUR_TOKEN > data.txt

3) Then replace ``"content":`` value with data.txt

![Graph example](https://github.com/ernestas-poskus/github-languages/blob/master/example/replace.png)
