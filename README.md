## magia-extractor

Magia Extractor is a Python tool used to automatically discover URLs, forms, inputs, and JavaScript files from target websites — useful for reconnaissance, bug bounty hunting, and web security testing.

## Features
- Crawl links
- Extract forms and input fields
- Download JavaScript files
- Randomize user-agents
- Delay requests
- save the output


## installation
```
git clone https://github.com/Dudu-1102/Extractor
cd Extractor
pip install -e . --break-system-package
magia-extractor -h
 ```

## Usage 
```
magia-extractor -h
extract inputs - forms 
magia-extractor -u https://example.com 
magia-extractor -l urls.txt -f -crawl --radnom-agent -o result
```
