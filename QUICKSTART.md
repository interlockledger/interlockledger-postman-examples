# Using the IL2 REST API

## How to use this collection

We are using collection variables to store some responses to be used in other requests. Before running any request, please, check if you need a variable and set up a new value or run a request that set a value to this variable. There is a brief description of each request in the collection.

This collection is organized in folder, each folder is related to a kind of request. You can run the requests in sequence, according to the folder name:

* 0-Node
* 1-Chains
* 2-JSON Documents
* 3-Multi-Documents


## Before using this collection

Before using this collection, you will need to import the PFX certificate and set some collection's variables.

### Importing this Collection
* Open Postman
* Click **Import**
* Choose [IL2 API Example.postman_collection.json](postman/IL2%20API%20Example.postman_collection.json)
* Click **Import**

### Importing PFX certificate
* Click **File -> Settings**
* Click on the **Certificates** tab
* Click **Add Certificate**
* Fill the API url in **Host**
* Choose **PFX file**
* Fill the certificate password in **Passphrase**
* Click **Add**

### Defining Collection Variables
* On the Collections tab,  click on the "**...**" beside the collection name and press **Edit**
* Click on the **Variables** tab
* On the `node_address` variable, change the **CURRENT VALUE** to your API url
* Click **Update**


