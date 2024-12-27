<<<<<<< HEAD
## PowerBI - Pro, Premium, F

**My journey :** On a transition journey from Tableau to PowerBI I am picking up a lot of new knowledge in the data engineering space. Here is my journey from building custom visuals, negotiating with DAX and picking up other query languages besides SQL (NoSQL, Spark and KQL)

### Data engineering is 

Learning by breaking things is one of the most natural & frustrating way to learn. Data engineering is one of them. I picked up NoSQL for the first time this year and boy did i pick the wrong language to learn from. For in MongoDB, it was not obvious that .find and .aggregate were 2 different scope of operations.

The below code pretty much sums up my early experience working without schema

```javascript
db.I.find({ workingSchemaless: "quitelibreating" })
db.I.find({ workingSchemaless: "chaotic" })
=======
## PowerBI - Embeded, Paginated, Authent

**My journey :** On a transition journey from Tableau to PowerBI while picking up data engineering as the challenge arises. Here is my journey building custom visuals, negotiating with DAX and getting certified on the cheap. 

### 1. Data engineering for dummies

A better approach to learning a new language (NoSQL) would be to rebuild a backbone of knowledge instead of trying to build of exisiting. It was not that obvious that .find and .aggregate were 2 different scope of operations
Aggregation pipelines introduce some overhead compared to .find, especially if you're only filtering and not transforming data.
$match allows more flexibility in combining with other stages, while .find is limited to basic retrieval.

```javascript
db.collection.find({ status: "active" })

db.collection.aggregate([
  { $match: { status: "active" } },
  { $group: { _id: "$category", count: { $sum: 1 } } }
])
>>>>>>> b3df16420fc9a2496c9ae7110b552f0392bbac9a
```
If you only need to find documents, use .find. If you need to chain operations (like grouping or transforming), $match becomes part of the broader aggregation pipeline.

That was until I found aggregation stage / pipelines. If aggregation is to ETL what find is to filtering (limited to basic retrieval).


```javascript

db.Collection.updateOne({ _id: "myMind" }, { $set: { blown: true } })

```
If you only need to find documents, use .find. If you need to chain operations (like grouping or transforming), $match becomes part of the broader aggregation pipeline.

### 2. Digital 


QR code, word cloud (tag clouds) were big back in 2009.

### 3. To work the visual or visualise the work?
Do I work the visuals - figuring out all the default properties, formatting options and configurations or do I visualise what they would be and then develop it from scratch? I find   


<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Where to next?

Understanding where the next challenge will arrive from

<!-- For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/). -->
