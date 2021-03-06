## Amazon Neptune Samples

Samples and documentation for using the Amazon Neptune graph database service

### Amazon Neptune Graphs and Jupyter Notebooks
Whether you’re creating a new graph data model and queries, or exploring an existing graph dataset, it can be useful to have an interactive query environment that allows you to visualize the results. This [directory](neptune-sagemaker/README.md) has samples from two blog posts to show you how to achieve this by connecting an Amazon SageMaker notebook to an Amazon Neptune database. Using the notebook, you load data into the database, query it and visualize the results.

* [Blog Post: Analyze Amazon Neptune Graphs Using Amazon Sagemaker Jupyter Notebooks](https://aws.amazon.com/blogs/database/analyze-amazon-neptune-graphs-using-amazon-sagemaker-jupyter-notebooks/)
* [Blog Post: Let Me Graph that for You - Part 1 - Air Routes](https://aws.amazon.com/blogs/database/let-me-graph-that-for-you-part-1-air-routes/)

### Gremlin

#### Collaborative Filtering 
This is an [example](gremlin/collaborative-filtering/README.md) of using Gremlin and making recommendations using collaborative filtering. It includes examples of loading data and Gremlin traversals.

#### Visualize data in Amazon Neptune using VIS.js library
This [GitHub lab](gremlin/visjs-neptune) will take you through hands-on excercise of visualizing graph data in Amazon Neptune using VIS.js library. Amazon Neptune is a fast, reliable, fully-managed graph database service available from AWS. With Amazon Neptune you can use open source and popular graph query languages such as Apache TinkerPop Gremlin for property graph databases or SPARQL for W3C RDF model graph databases.

#### ETL Process for Transforming and Loading Data Into Amazon Neptune
The following [lab](gremlin/etl-from-relational-model) uses the open [IMDB dataset](https://www.imdb.com/interfaces/). This is a small subset of the full IMDB.com application. With this dataset, we want to develop an application that allows for us to find whether or not an actor or actress is no more than [six degrees separated from the actor Kevin Bacon](https://en.wikipedia.org/wiki/Six_Degrees_of_Kevin_Bacon).  In this example, AWS Glue and Amazon Athena are used to discover and transform the relational model used by IMDB into a graph model that can be loaded into Amazon Neptune.  This pattern can be used to transform other relational models into graph models for similar purposes.

### SPARQL
**Coming soon!**

## License Summary

This sample code is made available under a modified MIT license. See the LICENSE file.
