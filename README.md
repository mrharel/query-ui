# query-ui
query selector based on UI criteria 

## Introduction
Chrome extension and headless browsers developers often need to crawl or find elements in a page which they are not the developers of. As the JS frameworks are becoming more advanced it is becoming more challening to rely on element ids, class names or any other attribute. For example, a lot of the advance websites are using some auto generated class names which might be changed when there is a new build. 

Let's take a look at the following example.
In our example, let's say we want to extract search results from a google search. I searched in Google: [who is the goat in tennis](https://www.google.com/search?ei=VWgXX9SdJ9SN1fAP2YSyGA&q=who+is+the+goat+in+tennis&oq=who+is+the+goat+in+te&gs_lcp=CgZwc3ktYWIQARgAMgIIADIGCAAQFhAeMggIABAWEAoQHjIGCAAQFhAeMgYIABAWEB4yBggAEBYQHjIGCAAQFhAeMgYIABAWEB4yBggAEBYQHjIGCAAQFhAeOgQIABBHOgQIABBDOgIILlC_d1isfWCFiQFoAHABeACAAWKIAeIDkgEBNpgBAKABAaoBB2d3cy13aXrAAQE&sclient=psy-ab). While this is a rhetorical question, since we all know that it is Roger Federer, let's examin the dom structure of that result page:

![Google Search](https://github.com/mrharel/query-ui/blob/master/static/Screenshot%202020-07-21%20at%2023.17.09.png)
Looking at the DOM structure, one might use the class `g` to query search results in the page, but that will provide additional elements which are not search results as we want. 


notes to self: check in Warren dashboard how i can select one of the total revenue cubes...


