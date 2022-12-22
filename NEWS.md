# stocksmart 0.4.1

* Data pull Dec 21,2022

## Time series added

* American plaice - Gulf of Maine / Georges Bank	(172877):		2022
* Atlantic cod - Eastern Georges Bank	(164712):	2022
* Atlantic halibut - Northwestern Atlantic Coast	(172933):		2022
* Atlantic salmon - Gulf of Maine	(161996):	2021
* Atlantic wolffish - Gulf of Maine / Georges Bank	(171341):		2022
* Barndoor skate - Georges Bank / Southern New England	(564139):	2022
* Clearnose skate - Southern New England / Mid-Atlantic	(160855):	2022
* Goosefish - Gulf of Maine / Northern Georges Bank	(164499):		2022
* Goosefish - Southern Georges Bank / Mid-Atlantic	(164499):	2022
* Little skate - Georges Bank / Southern New England	(564130):		2022
* Ocean pout - Northwestern Atlantic Coast	(630979):	2022
* Rosette skate - Southern New England / Mid-Atlantic	(564136):		2022
* Smooth skate - Gulf of Maine	(564151):		2022
* Thorny skate - Gulf of Maine	(564149):	2022
* White hake - Gulf of Maine / Georges Bank	(164732):	2022
* Winter flounder - Gulf of Maine	(172905):	2022
* Winter skate - Georges Bank / Southern New England	(564145): 2022
* Witch flounder - Northwestern Atlantic Coast	(172873):		2022
* Yellowtail flounder - Georges Bank	(172909):		2022
* Yellowtail flounder - Southern New England / Mid-Atlantic	(172909):	2022

## Summaries added

* Atlantic salmon - Gulf of Maine	(161996):	2021
* American plaice - Gulf of Maine / Georges Bank	(172877):	2022
* Atlantic cod - Eastern Georges Bank	(164712):	2022
* Atlantic halibut - Northwestern Atlantic Coast	(172933):	2022
* Atlantic wolffish - Gulf of Maine / Georges Bank	(171341):	2022
* Haddock - Eastern Georges Bank	(164744):	2022
* Haddock - Georges Bank	(164744):	2022
* Haddock - Gulf of Maine	(164744):	2022
* Ocean pout - Northwestern Atlantic Coast	(630979):	2022
* Pollock - Gulf of Maine / Georges Bank	(164727):	2022
* White hake - Gulf of Maine / Georges Bank	(164732):	2022
* Winter flounder - Georges Bank	(172905):	2022
* Winter flounder - Gulf of Maine	(172905):	2022
* Witch flounder - Northwestern Atlantic Coast	(172873):	2022
* Yellowtail flounder - Cape Cod / Gulf of Maine	(172909):	2022
* Yellowtail flounder - Georges Bank	(172909):	2022
* Yellowtail flounder - Southern New England / Mid-Atlantic	(172909):	2022
* Barndoor skate - Georges Bank / Southern New England	(564139):	2022
* Clearnose skate - Southern New England / Mid-Atlantic	(160855):	2022
* Little skate - Georges Bank / Southern New England	(564130):	2022
* Rosette skate - Southern New England / Mid-Atlantic	(564136):	2022
* Smooth skate - Gulf of Maine	(564151):	2022
* Thorny skate - Gulf of Maine	(564149):	2022
* Winter skate - Georges Bank / Southern New England	(564145):	2022
* Goosefish - Gulf of Maine / Northern Georges Bank	(164499):	2022
* Goosefish - Southern Georges Bank / Mid-Atlantic	(164499):	2022


# stocksmart 0.4.0

## New Feature

* `get_species_itis` - filters summary data to identify stock itis
* `get_available_ts` -  filters time series data to get an idea of how much data is available in each assessment.

## Minor fixes

* `query_stocksmart_api - url of API changed
* `process_stocksmart_api.r` - included argument to be able to run locally without creating changes files required for commits

# stocksmart 0.3.7

* Data pull Dec 9, 2022
* Fixes Summary data missing entries

# stocksmart 0.3.6

* Data pull Dec 08, 2022

# stocksmart 0.3.5

* Data pull Dec 01, 2022
* Bug in release. Entries duplicated

# stocksmart 0.3.4

## Minor Bugs

* Fixed bug in filtering of data in `get_latest_metrics` function

# stocksmart 0.3.3

* Data pull Feb 23, 2022

## New Feature

* Added `get_latest_metrics` function to filter lazydata and return the most recent assessment containing time series data for any subset of Abundance, Catch, Fmort, and Recruitment

## Time series added

* Pacific grenadier - Pacific Coast   (165334)
* Pacific sanddab - Pacific Coast     (172716)
* Rock sole - Gulf of Alaska          (172917)
* Bank rockfish - California          (166761)
* Squarespot rockfish - Pacific Coast (166753)
* Stripetail rockfish - Pacific Coast (166741)
* Vermilion rockfish - Oregon         (166729)
* Vermilion rockfish - Washington     (166729)
* Blue rockfish - Southern California (166730)

## Time series removed

* Gopher rockfish - Northern California (166767)

# stocksmart 0.3.2

## Minor Bugs

* Added missing output variables to documentation
* Data pull Oct 26, 2021

# stocksmart 0.3.1

* Package name change from `assessmentdata` to `stocksmart`
* Data pull Oct 26, 2021

# assessmentdata 0.2.1

* Added `get_latest_full_assessment` function to filter lazydata and return the most recent assessment containing time series data for Abundance, Catch, Fmort, and Recruitment
* Data pull July 19, 2021

# assessmentdata 0.1.1

* Data pull May 28, 2021

## Time series added

* Bering Sea / Aleutian Islands Blackspotted and Rougheye Rockfish Complex
* Yelloweye rockfish - Gulf of Alaska
* Yelloweye rockfish - Pacific Coast
* Yellowfin goatfish - Main Hawaiian Islands
* Yellowfin sole - Bering Sea / Aleutian Islands
* Yellowfin tuna - Atlantic
* Yellowstripe goatfish - Main Hawaiian Islands
* Yellowtail flounder - Cape Cod / Gulf of Maine
* Yellowtail flounder - Georges Bank                
* Yellowtail flounder - Southern New England / Mid-Atlantic

## Time series removed

* Atlantic sharpnose shark - Gulf of Mexico

## Summaries added

* Red grouper - Gulf of Mexico
* Black sea bass - Mid-Atlantic Coast
* Scup - Atlantic Coast
* Atlantic cod - Georges Bank
* Coho salmon - Puget Sound: Hood Canal

## Summaries removed

* Gulf of Alaska Blackspotted and Rougheye Rockfish Complex
* Coho salmon - Oregon Production Index Area: Central California Coast
* Coho salmon - Oregon Production Index Area: Columbia River Early Hatchery
* Coho salmon - Oregon Production Index Area: Columbia River Late Hatchery

# assessmentdata 0.1.0

* Initial data pull on April 7, 2021