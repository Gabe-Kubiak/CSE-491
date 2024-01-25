A [[Schema]] is a definition of how the data should be formatted 
- [[Schema]] can be used for validation - [[JSON]] [[Schema]] is widely used, but still evolving 
- Widely used standard: http://json-schema.org


## Example JSON File
- { "id": 1, "name": "frozen pizza", "price": 10.50, "tags": [ "frozen", "pizza"] }
- Schema can help us define: 
	- What is the data? 
	- What is id? 
	- Is name required? 
	- Can price be 0? 
	- Are all tags strings?

>[!col]
>>[!col-md]
>>Example JSON File 
>>{ 
>>"id": 1, 
>>"name": "frozen pizza",
>>"price": 10.50,
>> "tags": [ "frozen", "pizza"] 
>>  }
>
>>[!col-md]
>>JSON Schema File 
>>{ "title": "Product",
>>"description": "Product from supermarket",
>>"type": "object 
>>}
>


	