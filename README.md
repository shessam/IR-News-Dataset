# Iranian News Dataset
Iranian news dataset was prepared that crawled 4965 news from the websites of news agencies for developing extractive document/text summarization systems.

### Dataset Content:
- Asr-E Iran: 1848 News file
- Mashreghnews: 16 New file
- Roozno: 1232 New file
- Sobhanehonline: 157 News file
- Tabnak: 1712 New file


In the dataset, every news is in a separate file and the content of each file as follows:
### File Content:
The first line includes information related to the news. This information includes `the name of the news agency`, `title`, `link`, `category`, `publication date` , `ID code`, and `tag`, separated by `###`.

The second line includes the ID number of sentences that make up the context of the summarized text. If the summarized text contains more than one sentence, the IDs of the sentences are separated by `@@@`.

The third line to the end includes the sentences of the news text, each sentence is in a separate line. At the beginning of these lines, there is an ID number for the sentences.
