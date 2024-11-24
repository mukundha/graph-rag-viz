# Visualization for Graph RAG / Vector Graph

A simple visualization for how Graph RAG links and represents Data. AstraDB [Example here](https://github.com/datastax/graph-rag-example)

Built using [d3.js](https://d3js.org/)

# Get Started

[Playground](https://mukundha.github.io/graph-rag-viz/)

### Visualize your data in AstraDB

Export data using [`dsbulk`](https://docs.datastax.com/en/dsbulk/reference/dsbulk-cmd.html)

`./dsbulk unload -b <secure-connect-bundle.zip> -u <client_id> -p <client_secret> -query "select kind, link_from_tags, link_to_tags, metadata_s from <namespace>.<table_name> limit 100" -url ./export.csv`

Now, you should be able to load the csv file to Playground

### [LICENSE](LICENSE)
Apache 2.0
