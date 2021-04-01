# Starbucks Locations

Starbucks locations scraped from the Starbucks website by Chris Meller. From
the original README:


    Contains a single commit for each day that batches up all changes to the
    Starbucks dataset as a CSV file.

    Deletes will obviously be stores that seem to have closed and adds are new
    stores that have opened.

    This is a work in progress. There is additional data that needs to be
    included in this dataset and it needs to get properly automated so we hav e
    a regular commit daily at a particular time.

This dataset release re-geocodes all of the addresses, for the ``us_starbucks``
dataset. The original datafile has lat and lon values truncated to 2 decimal
places, about 1km in North America. The re-geocoded addressss are much more
precise.
