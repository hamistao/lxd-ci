# LXD Weekly News

Scripts to generate a list of contributions for LXD weekly news within a specified time frame.

## Usage

To generate a weekly news template, replace `<from_date>` and `<to_date>` with dates in the `YYYY-MM-DD` format, then run the command:
```sh
weekly-changes.sh <from_date> <to_date>
```
If <to-date> is not provided, the script will grab the day six days after <from_date>, as it would be if the interval was from Monday to Sunday.
