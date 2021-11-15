# Schema-to-model
Genrates models based on Schema.org definitions.

The idea for an this app is that it would read pre-defined data structures (schema vocabularies) and generate models based on that. The best thing is that it would also generate all successors. For example: For Article it would generate Author, Category, Publisher... Maybe this app is not the best way to develop, but it is a way to kickstart it.

Technical details: Application will get schema information from schema.org. It will then use https://github.com/Abdenasser/dr_scaffold to generate objects. Later, I also plan to make generators for other languages
