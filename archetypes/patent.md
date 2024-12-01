---
date: '{{ .Date }}' # date in which the content is created - defaults to "today"
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'
draft: false # set to "true" if you want to hide the content
patentTitle: "" # The patent title
patentId: "" # The patent ID
issued: "" # The date the patent was issued
patentURL: "" # The URL to view the full patent on Google Patents
pdfURL: "" # The URL for the patemt to be downloaded
abstract: "" # The patent abstract
inventors:
  - name: "" # The name of the inventor
    linkedin: "" # The LinkedIn profile URL

## For the content, you can use a title and a job description.
## For example:
# ### The title
# The patent text
#
---