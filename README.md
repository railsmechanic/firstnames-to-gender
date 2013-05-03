# Country based gender file
The JSON file is the 'data grounding' of the free webservice www.namesia.de, which allows you to discover the gender of a first name in a simple, RESTful way. The JSON file itself is based on the awesome *nam_dict.txt* file, created by Jörg Michael. This file was included in a software package distributed by the german IT magazine *c't*.

Download the full article: https://www.heise.de/artikel-archiv/ct/2007/17/182_40-000-Namen

Download the software package: http://www.heise.de/ct/ftp/07/17/182

## Content of names.json
**Name:**			The complete first name, UTF-8 encoded
**Gender:**		The gender consisting of male, female and unisex
**Country:**	The country to which the gender refers

The file is structured as follows:

	[
		{
			"name": "Aaron",
			"gender": "male",
			"country": "uk"
		},
		{
			"name": "Aarron",
			"gender": "male",
			"country": "uk"
		},…
	]

## License
The previously mentioned dictionary file *nam_dict.txt* - the foundation for my work - was created 2007-2008 by Jörg Michael (astro*dot*joerg*at*googlemail*dot*com) and licensed under the GNU Free Documentation License.

Due to the requirements of the GNU Free Documentation License I publish my *names.json* file under the same license terms. (See LICENSE file).