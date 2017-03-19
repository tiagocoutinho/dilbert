# dilbert

downloader of dilbert comics

## Installation

    $ pip install dilbert-get

## Requirements

* bs4
* grequests

## Usage

    $ # Downloads all dilbert comics to ~/Downloads/dilbert
    $ dilbert-get

    $ # Downloads dilbert comics [1999-01-03..2012-10-20] to /tmp/dilbert
    $ dilbert-get --start=1999-01-03 --end=2012-10-20 --output-dir=/tmp/dilbert
