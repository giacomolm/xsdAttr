xsdAttr
=======

A small javascript library that given a particular schema retrieve all the attributes of a particular meta-element

Usage:

		var result = xsdAttr.getAttributes(schemaFile,element);
		
		for(var propName in result) {
		    if(result.hasOwnProperty(propName)) {
			    console.log(propName);   
		    }
		}

