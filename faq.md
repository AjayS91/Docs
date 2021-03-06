# Frequently Asked Questions

Please make sure to check the [Glossary and workflow](readme.md) before going through these questions.

## Ecosystem

> Q: How do people create their **own Mine**?

A: We plan to provide a variety of deployment options for the generic Mine software. The general theme is a downloadable that you can easily run on one of the available devices we plan to support. General candidates for platforms we plan to support are your own cloud node, local machine, smartphone, or possible even a raspberry pi. However, we have yet to curate a final list of places to store your data and are quite open minded about the possibilities.

> Q: How do people load data into their Mine?

A: We plan to provide an set of _adapters_ that allow easy access to existing data sinks like **Twitter Accounts**, **Smartwatches** and others. However a large thriving ecosystem of awesome developers is required to provide all _adapters_ required to create mines of huge value.
In addition to machine generated data there might be web interfaces where Miners can further enrich their data by providing personal details.

> Q: How do I know which **data** is already available in the Mines?

A: All data schemas will be publicly available and the before mentioned _adapters_ will create de-facto standards. Open Mined might show a counter of available _data sets_ and _data points_ per schema.

> Q: What is the current development state?

A: Currently the [demo](https://github.com/OpenMined/PySonar/blob/master/notebooks/Sonar%20-%20Decentralized%20Model%20Training%20Simulation%20(local%20blockchain).ipynb) shows the overall workflow of Open Mined. In addition all the functional steps are implemented using available open source libraries or open code from our side. The next step for Open Mined will be a large(r) scale proof of concept. While running several mines in the system we will identify several issues regarding performance, usability and overall system design. Those will be tackled in a second development phase.

## Technology

> Q: Why do you need a **Blockchain**?

A: The blockchain technology is currently used to mediate between _Farmers_ and _Miners_. It takes care of pointing _Miners_ to the correct network to train and also acts as a trust for the _Farmers Bounty_ to be fairly (which is not necessarily evenly) distributed across all participating _Miners_.

> Q: How can a data scientist design his **model**?

A: Early on the `syft` library will come with several basic models. Most available libraries like `scikitlearn` or `tensorflow` do not have _homomorphic encryption_ capabilities. Therefore they do not work with Open Mined out of the box. We will focus on bringing more ways to build your models later on during the development.

## My question is not answered

If you have a new question feel free to open an issue in this repository asking us to clarify or come visit us in slack.
