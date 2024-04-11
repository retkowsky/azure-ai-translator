# Azure AI Translator demos

**Azure AI Translator** is a cloud-based machine translation service you can use to translate text and documents with a **simple REST API call**.<br>
The service uses modern **neural machine translation technology**.<br><br>
This service can do **asynchronous batch document translation** and **synchronous document translation.**<br>
The **Custom Translator interface** allows you to use your translation memory to create **customized neural translation systems**. The customized translation system can be used to translate text and documents with the Translator service.<br><br>
More than 100 languages are recognized.<br>
https://learn.microsoft.com/en-us/azure/ai-services/translator/language-support<br><br>
Containers are available for Azure AI Translator.<br><br>
Website: https://azure.microsoft.com/en-us/products/ai-services/ai-translator<br>

## Python notebooks
1. Azure AI Translator informations
<a href="1 Azure AI Translator informations.ipynb">Notebook</a>
2. Language detection
<a href="2 Language detection.ipynb">Notebook</a>
3. Transliterate example
<a href="3 Transliterate example.ipynb">Notebook</a>
4. Translation
<a href="4 Translation.ipynb">Notebook</a>
5. Document translation batch
<a href="5 Document translation batch.ipynb">Notebook</a>
6. Synchronous Document Translation
<a href="6 Synchronous Document Translation.ipynb">Notebook</a>

Note: you need to update the **azure.env** file with your Azure AI Translator informations.

## An exemple of a custom webapp for text translation
<br>
<img src="webapp1.jpg">

## An exemple of a custom webapp for document translation
<br>
<img src="webapp2.jpg">

## Azure AI features

### 1. Text Translation
Execute text translation between supported source and target languages in real time. Create a dynamic dictionary and learn how to prevent translations using the Translator API.
<br><br>
https://learn.microsoft.com/en-us/azure/ai-services/translator/text-translation-overview

### 2. Asynchronous Batch Document Translation
Translate batch and complex files while preserving the structure and format of the original documents. Create a glossary to use with document translation. The batch translation process requires an Azure Blob storage account with containers for your source and translated documents.
<br><br>
https://learn.microsoft.com/en-us/azure/ai-services/translator/document-translation/overview

### 3. Synchronous Document translation
Translate a single document file alone or with a glossary file while preserving the structure and format of the original document. The file translation process doesn't require an Azure Blob storage account. The final response contains the translated document and is returned directly to the calling client.
<br><br>
https://learn.microsoft.com/en-us/azure/ai-services/translator/document-translation/reference/synchronous-rest-api-guide

### 4. Custom Translator
Build customized models to translate domain- and industry-specific language, terminology, and style. Create a dictionary (phrase or sentence) for custom translations.
<br><br>
https://learn.microsoft.com/en-us/azure/ai-services/translator/custom-translator/overview

## Documentation
https://learn.microsoft.com/en-us/azure/ai-services/translator/

## Language support
https://learn.microsoft.com/en-us/azure/ai-services/translator/language-support

## Pricing
https://azure.microsoft.com/en-us/pricing/details/cognitive-services/translator/

## What's new
https://learn.microsoft.com/en-us/azure/ai-services/translator/whats-new?tabs=csharp

## Repositories
https://github.com/orgs/MicrosoftTranslator/repositories

## FAQ
https://learn.microsoft.com/en-us/azure/ai-services/translator/translator-faq
<br><br>

10-April-2024 - Updated 11-April-2024<br>
Serge Retkowsky | serge.retkowsky@microsoft.com | https://www.linkedin.com/in/serger/
