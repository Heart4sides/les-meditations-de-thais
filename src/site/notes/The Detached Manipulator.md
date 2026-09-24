```dataview
>> TABLE WITHOUT ID
>> join(GArchetype, ", ") as "Archetype"
>> WHERE file.link = this.file.link
>> Sort file.name asc
>> LIMIT 100
>> ```