- Plain text file format 
- Note, not a flat file structure like CSV 
- Originally derived from JavaScript, but is now a language-independent data format 
- Whitespace (outside of strings) is meaningless 
- One (root) JSON object allowed per file, but there are ways to store many different things in one JSON object 
## Examples
- Object is an unordered collection of name/value pairs, where the names (aka keys) are strings 
	- { "name": "James", "age": "don’t' worry about it", "classes": ["CSE380", "CSE498"]}
	- { "name": "James", "classes": [ {"Name": "CSE380", "Students": 48, "Topic": "Databases and Cloud"}, {"Name": "CSE498", "Students": 158, "Topic": "Capstone"} ], "Employed": true }

## Datatypes
- [[JSON Strings]]
- [[JSON Numbers]]
- [[JSON Array]]

## [[JSON Schema]]