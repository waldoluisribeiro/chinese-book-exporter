# Chinese Book Analyser

Chinese Book Analyser exports lists of the unique characters in books, along with their frequency, the average distance between their occurrences, and example sentences. It also exports lists of characters to learn, based on a specified threshold frequency, to approximately achieve a given comprehension percentage. Basic statistics can also be exported. All data are exported as CSV files.

## Usage
### Folders
#### Books
Choose the folder in which your books are stored in TXT format by selecting 'Browse' alongside the text field labelled 'Books'.

#### Export
Choose the folder to which you want to export the resulting CSV files by selecting 'Browse' alongside the text field labelled 'Export'.

### Hanzi
#### Mode
* None
* Individual: Exports a list of the unique characters in each selected book
* Shared: Exports a list of the characters in common among all the selected books

#### Export (Hanzi Mode: Individual)
* Unique Hanzi: Exports a list of the unique characters in each selected book
* Hanzi to Learn: Exports a list of the characters in each selected book to learn, based on the parameters in the 'Learning' section
* Both: Exports both of the above

#### Frequency (Hanzi Mode: Individual/Shared)
* Low > High
* High > Low

#### Distance (Hanzi Mode: Individual)
* Low > High
* High > Low

#### Learning (Hanzi Mode: Individual)
##### Usage examples
The number of example sentences to provide alongside each character in the exported lists. Ranges from 0 to 10. Defaults to 2.

##### Comprehension
The desired comprehension percentage. Ranges from 90 to 100. Defaults to 98.

##### Frequency threshold
The frequency from which to begin selected words to learn. Ranges from 10 to 50. Defaults to 20.

#### Statistics
* None
* Individual: Exports statistics for each selected book in separate CSV files
* Combined: Exports statistics for all selected books in a single CSV file