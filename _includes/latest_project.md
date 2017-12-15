
### Most Recent Project: [Prefixy](https://github.com/prefixy/prefixy){:target="_blank"}

[Prefixy](https://github.com/prefixy/prefixy){:target="_blank"} is a highly scalable, query optimized hosted prefix search service for building autocomplete suggestions. Suggestions dynamically update in response to user input, so users only see the most relevant suggestions. We utilized asynchronous, batched Redis calls in order to provide non-blocking writes and extremely fast in-memory reads. Multi-tenancy was implemented by utilizing JSON web tokens, Redis namespacing, and MongoDB collections. The system design includes two Node/Express servers, Redis, MongoDB, a CLI, and a JavaScript client.
