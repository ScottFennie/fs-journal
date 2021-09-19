## MongoDb Relationship Documents

# In simple terms what is a sub-document?

They are essentially just documents that are nested within other documents.

# When might you use a sub-document?

In MongoDB you can nest Schemas within other schemas.This would be a great use of a "subdoc" because it would allow you to simply nest an object as a child inside of a parent schema rather than creating a whole new schema. This keeps projects much smaller and more manageable.

# How do you add to a collection of sub-documents? What about editing them?

On of the easiest ways to add to a sub-doc would be to simply pass a nested object into a new model. To edit these su-docs you can simply use the find-one feature to find the array you are looking for, and then change the array after it is found.


Today's Project: https://github.com/ScottFennie/Galaxy