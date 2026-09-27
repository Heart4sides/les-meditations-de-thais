```dataview
> LIST WITHOUT ID
> file.link + " (" + join(Contenant, ", ") + ") - " + join(Peasant, ", ") 
> WHERE contains(MArchetype, this.file.link) OR contains(Sharchetype, this.file.link) contains(Contenant.Category.Category, [[Fiction]]) 
> Sort file.name asc
> LIMIT 100
> ```