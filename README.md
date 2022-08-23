# shodanapi-py

## Shodan Basic Query Results Script for Massive Attacks with Nuclei or Other Automated Exploitation Tool

![shodan api in python](https://github.com/well0x01/shodanapi-py/blob/main/results-shodan-api-py.png)

## Commands

* python3 shodanapi.py
* input search query

## Example

Example with search query: "grafana"

![grafana](https://github.com/well0x01/shodanapi-py/blob/main/grafana-example.png)

* cat output.txt | awk '{print $2}' | tr -d "[]''" | httpx -silent -p 3000 | nuclei -tags grafana -es info

