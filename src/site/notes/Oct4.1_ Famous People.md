```dataview
>> TABLE link(banner, "200") as "Image"
>> WHERE contains(Archétype.Category, [[Full Type]]) AND !contains(Typer, [[Thaïs]])
>> Sort file.name asc
>> LIMIT 100
>> ```