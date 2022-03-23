## README.md
Brief Design Intuition
1. **Schema Option #1** (hashchat-schema.json): essentially followed the SocialConnections.json schema from the Data Model Registry. It's pretty simple but I'm not sure of it because it specifies only the connection between users and not the users or groups themselves. 
2. **Schema Option #2** (message-schema.json, user-schema.json, user-group-schema.json): These three schemas define message data, user data, and user group data. I created this one based on my conception of JSON schemas and relationships between entities (i.e. users). As you can see where "$refs" are mentioned, the three schemas all relate to one another, while allowing for clear definitions of each schema. 
