PathFinder
==========
Implementation of finding a path from point A to point B. Test.

##Initial data

The initial data is presented in the XML file in the following format:
	
	<?xml version="1.0"?>
	<root>
		<cities>
			<city id="5" name="Астана" />
			...
			<city id="{city_n}" name="{title_n}" />
		</cities>
		
		<nodes>
			<node from="5" to="84" length="63" />
			<node from="5" to="390" length="82" />
			...
			<node from="{sourceid}" to="{targetid}" length="distance" />
		</nodes>
	</root>

`cities` represents a set of settlements, `nodes` - directions between them (with distances).

The file is called `data.xml` and is placed in the same folder with the built assembly - in `bin/debug` or `bin/release`.

## Plans:
 * Check the algorithm for correctness;
 * Implement visualization of settlements and paths;
