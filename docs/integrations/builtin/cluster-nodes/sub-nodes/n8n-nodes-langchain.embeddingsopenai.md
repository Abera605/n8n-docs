---
#https://www.notion.so/n8n/Frontmatter-432c2b8dff1f43d4b1c8d20075510fe4
title: Embeddings OpenAI
description: Documentation for the Embeddings OpenAI node in n8n, a workflow automation platform. Includes details of operations and configuration, and links to examples and credentials information.
---

# Embeddings OpenAI

Use the Embeddings OpenAI node to generate embeddings for a given text.

On this page, you'll find the node parameters for the Embeddings OpenAI node, and links to more resources.

/// note | Credentials
You can find authentication information for this node [here](/integrations/builtin/credentials/openai/).
///

--8<-- "_snippets/integrations/builtin/cluster-nodes/sub-node-expression-resolution.md"


## Node options

* **Model**: The model to use for generating embeddings.
* **Base URL**: the URL to send the request to. Use this if you are using a self-hosted OpenAI-like model. 
* **Batch Size**: maximum number of documents to send in each request.
* **Strip New Lines**: whether to remove new line characters from input text. n8n enables this by default.
* **Timeout**: maximum amount of time a request can take in seconds. Set to `-1` for no timeout.

## Templates and examples

<!-- see https://www.notion.so/n8n/Pull-in-templates-for-the-integrations-pages-37c716837b804d30a33b47475f6e3780 -->
[[ templatesWidget(title, 'embeddings-openai') ]]

## Related resources

Refer to [LangChains's OpenAI embeddings documentation](https://js.langchain.com/docs/modules/data_connection/text_embedding/integrations/openai){:target=_blank .external-link} for more information about the service.

--8<-- "_snippets/integrations/builtin/cluster-nodes/langchain-overview-link.md"
--8<-- "_glossary/ai-glossary.md"
