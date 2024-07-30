
# Plagiarism Detector

A web application to check if a document's contents are plagiarised or not.


## Steps:

- User enters a query/text.
- Gets processed (Uppercase to lowercase, Removal of punctuationmarks, etc.)
- Resulting URL, matched contents are checked for similarity with given text query.
- The Plagiarism Percentage is returned on the web page along with links of sites matched.


## Web Screenshots:

Main Window:

![8](https://github.com/user-attachments/assets/22a64f49-bdac-4d7c-aaf3-20fc85b64307)

![6](https://github.com/user-attachments/assets/9159798b-5cce-4ef8-8663-8c79f074514e)

Results Window:

![7](https://github.com/user-attachments/assets/1b687ac6-0b02-4bb7-bad7-8ca0d0bb57c5)


Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
  run main.py
```

