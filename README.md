# Data Exercise: Data Formatting 001

Exercise for data input parsing and output formatting that requires additional datasets to decode and then to output data in a specified format.

## Requirements

This exercise can be completed in just about any language that includes i/o parsing. For this example we are requiring the following:

| Prerequisite    | Spec | Description
| --------------- | ------------ | ---------------------| 
| Python | 3.7.2 or [latest version](https://docs.python.org/) | For this exercise, we are going to use python. |
| Git | 2.20.1 or [latest version](https://git-scm.com/) | A well-crafted Git commit message is the best way to communicate context about a change to fellow developers  and your future self. |
| Documentation | Standard documentation practices: [python](https://docs.python.org/3/reference/lexical_analysis.html#comments), [general](https://en.wikipedia.org/wiki/Best_coding_practices#Commenting) |  Comments should describe the why, not the what for other developers and your future self.  |

## Included Files

In the `data/` directory:

| File    | Description
| --------------- | ------------ | 
| coded.xls | Data that has been morse coded |
| morse.csv | CSV key for morse code used in this exercise |
| periodic.xls | Periodic table data |

## Instructions

1. Decode `coded.xls`
2. Use the decoded data to generate a dataset that includes the following data:

| key    | value
| --------------- | ------------ | 
| id | atomic number |
| config | electronic configuration |
| year | year discovered |
| description | [Element] ([Symbol]) was discovered in [year] with a [bonding status] bonding status and a [standard state] standard state. It's group block is [group block].  If the bonding status, standard state or group block is not provided, omit it while maintaining standard english grammer. |

3. Take the newly generated dataset and save it to a CSV file UTF-8 LF encoded that is labeled `output-timestamp.csv` (where timestamp is replaced with a epoch timestamp)

While working through the solution, document your code by including comments in the source.

Commit your work often with messages that describe your work and push your commits to this remote repo.
