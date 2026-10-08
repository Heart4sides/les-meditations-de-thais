```dataview
>> TABLE  WITHOUT ID
>> file.link as "Temple Quadra", join(build, ", ") as Build
>> WHERE contains(Category, [[Temple Quadra]]) AND build
>> Sort file.name asc
>> LIMIT 100
>> ```