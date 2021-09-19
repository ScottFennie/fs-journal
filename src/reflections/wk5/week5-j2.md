## MongoDb Relationships... it's complicated

# What are the three types of relationships?

1) One-to-one
2) One-to-many
3) Many-to-many

# What are the benefits of the traditional linking of relationships instead of Embedding

Linking keeps things simple and fairly secure. If you link by Id's, you do not have to worry about many of the complication problems that come with embedding, you simply find the link through generated Id's.

# What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?

You need to start by considering the "categories" you are linking. There are several ways to accomplish aa many-to-many relationship, so its worth while to take the time to find the simplest method to link your objects. For example, if one of your categories is incredibly large in size and you link in the wrong direction, you may suddenly be breaking the 16Mb max document size. Relationships need to be considered before hand.


Daily Project: https://github.com/ScottFennie/GregslistV3