# Google Search Scraper

This is a Bash script that can be used to scrape Google search results for a given query string. The script will scrape the first 10 pages of Google search results and extract any URLs containing the specified search term.

## Prerequisites

- Bash shell
- `curl` command-line tool
- `grep` command-line tool

## Usage

1. Modify the `search_term` variable in the script to specify the query string you want to search for.
2. Open a terminal and navigate to the directory containing the script.
3. Run the script using the command `./google_search_scraper.sh`.
4. The script will loop through the first 10 pages of Google search results for the specified query string and extract any URLs containing the search term `web3.pdf`.
5. The extracted URLs will be saved to files named `search_results_page_${i}_urls.txt`, where `${i}` is the page number (0-9).

## License

This script is released under the [MIT License](https://opensource.org/licenses/MIT).
