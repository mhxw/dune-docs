[View code on GitHub](https://dune.com/docs/data-tables/community/reservoir/attributes.md)

# Attributes

The `reservoir.attributes` table contains records with information about each attribute. This section of the app technical guide provides a detailed description of the columns in this table, including their data types and descriptions. 

The `id` column is an internal attribute ID, while the `attribute_key_id` column is an internal attribute key ID. The `value` column contains the attribute value, and the `token_count` column indicates the number of tokens that have the attribute. The `on_sale_count` column indicates the number of tokens that have the attribute and are currently on sale. 

The `floor_sell_value` column contains the current floor ask price, while the `sell_updated_at` column indicates the timestamp of the last update to the floor sale. The `collection_id` column contains the associated collection ID, and the `kind` column indicates the value type (string, number, date, range). The `key` column contains the associated key name. 

Finally, the `created_at` and `updated_at` columns indicate the timestamps of when the attribute was created and last updated, respectively. 

This section also provides two query examples for the `reservoir.attributes` table, which can be found at the provided links. These examples can be used as a reference for querying the table in the app.
## Questions: 
 1. What is the purpose of the `reservoir.attributes` table in the context of the Dune Docs project? 
   - The `reservoir.attributes` table contains records with information about each attribute in the Dune Docs project.
2. How is the `token_count` column calculated and what does it represent? 
   - The `token_count` column represents the amount of tokens that have the attribute, but it is unclear how it is calculated based on the information provided in the technical guide.
3. Are there any limitations or constraints on the data types that can be stored in the `value` column? 
   - The technical guide does not provide information on any limitations or constraints on the data types that can be stored in the `value` column.