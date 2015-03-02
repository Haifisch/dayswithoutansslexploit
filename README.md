This is a small project to keep track of most Moderate-to-Severe SSL/TLS vulnerabilities and count the number of days between publications.

## Updating (easy)
If we've missed a vulnerability (we're human too ;P), please feel free to submit a new issue on this repo.


## Updating (harder)
To do this, you will need a clone of this repo, so clone it now before we start.
Once cloned, begin editing the catalog.json file in the "api" directory.

Here's a template of the basic JSON object for each vuln that's in the catalog

```json
{
  "name": "CVE-2014-1234",
  "date": "01/08/2015",
  "url": "https://googe.com",
  "description": "A simple description, usually taken from the source site, either paraphrased or cut down to keep short."
}
``` 
Just modify and add that object to the array, place it first as it will be the first vuln checked for. After that, and you've double (we'll triple check it for you for <b>free</b>) checked your work, feel free to push to your own clone and create a pull request.
