dcdc-2014-summaries-csv
=======================

CSV/JSON Data Files for easy access to currently published Delta Conservation Demonstration Center project and field data for 2014 and prior.

The raw data is published in Excel files in a human reader oriented manner. The original author of this repository wished to display this data with interactive charting and desired them in more data oriented formats, specifically oriented for use with libraries such as [D3 [2]](https://github.com/mbostock/d3) and [Crossfilter [3]](https://github.com/square/crossfilter).

About the Project
------

Conservation in the Delta has to be different because one practice does not fit everyone, one program will not work for everybody.  __The DCDC is a 638-acre working farm that demonstrates sound management practices that save water and keep the soil on the field for Delta farmers.__  The DCDC shows alternative cropping and tillage systems with limited tillage and crop rotations.  The DCDC’s purpose is to demonstrate the benefits of field buffers:  grassed waterways, field borders, and filter strips.  Also, the Center shows various applicable water conservation and water quality practices.  There are plant material utilization demonstrations, along with wildlife and pollinator habitat demonstrations.  _They are very tour-friendly, and they invite you to visit the farm [[DCDC Overview] [1]](http://www.dcdcfarm.org/fielddata2.htm)!_



Sources
======

1. [DCDC Project Overview](http://www.dcdcfarm.org/fielddata2.htm)
2. [D3 (Data Driven Documents)](https://github.com/mbostock/d3)
3. [Crossfilter](https://github.com/square/crossfilter)
1. Raw Data
  1. 2014
    1. [Field and Rain Data](http://www.dcdcfarm.org/2014data/2014FieldandRainData.xls)
    2. [Rain Events](http://www.dcdcfarm.org/2014rain/RainEvents.xls)
  3. [2013 (Combined)](http://www.dcdcfarm.org/zips/2013FieldData.zip)
  4. [2012 (Combined)](http://www.dcdcfarm.org/zips/2012%20FIELD%20DATA.zip)
  5. [2011 (Combined)](http://www.dcdcfarm.org/zips/FIELD%20DATA%202011.zip)
  6. [2010 (Combined)](http://www.dcdcfarm.org/zips/2010%20Field%20Data.zip)
  7. [2009 (Combined)](http://www.dcdcfarm.org/zips/FIELD%20DATA%202009.zip)
  8. [2008 (Combined)](http://www.dcdcfarm.org/zips/FIELD%20DATA%20%202008.zip)
  9. [2007 (Combined)](http://www.dcdcfarm.org/zips/FIELD%20DATA%202007.zip)
  10. [2006 (Combined)](http://www.dcdcfarm.org/zips/FIELD%20DATA%202006.zip)
  11. [2005 (Combined)](http://www.dcdcfarm.org/zips/DCDC%20Field%20Data%202005.zip)


Interesting Other Similary Related Data Sources
======

1. Planting Guides
  2. These are primarily verbal and pictoral, so some manual conversion would be neat.
  3. [Mississippi Planting Guide](http://www.nrcs.usda.gov/Internet/FSE_DOCUMENTS/nrcs142p2_017068.pdf)
  4. [NCRS Plant Materials Program](http://www.nrcs.usda.gov/Internet/FSE_DOCUMENTS/nrcs142p2_016955.pdf)
  3. Metric Brainstorm
    4. Category
    4. Variety
    6. Description
      7. Text blurb
      1. Potential data points
        2. Origin country
          2. Not always present, but would be nice. Could provide null for missing entries and manually filled in later?
    1. Uses
      2. Text based. Categorical?
    1. Soil adaptation
      2. Text based.
      3. Potential data points
      4.  MS zone of adapation classification/location data is sometimes provided
    1. Varieties
      2. Text based. Categorical/assocation-ripe.
    1. Method of establishment
      2. Text based. Categorical/assocation-ripe.
    1. Seedbed preparation: Requires a clean, firm seedbed. Prepare seedbed by disking and
    harrowing.
    1. Planting rate
      2. lbs/acre
      3. Seed cover depth (inches)
    1. Planting time
      1. Date ranges
      2. Text blob. Some different ordinal/categorical notes could be mined
    1. Fertility requirements
      1. Text blob. Some data could be mined.
    5. pH requirements
      6. Numerical! Plug in your field's numbers and look at what's left! :)
    5. Companion Plants
      6. Ripe for network/association/cluster diagrams
    7. Management
      8. Text blob. Some different ordinal/categorical notes could be mined, like `Ideal Grazing Time` could have like `Until good sod established` and `Do not graze below 3 inches` as entries in its domain.
      9. 
    4. Seed Production
      5. Usually contains numerical ranges
    5. Environmental Concerns
      6. Text blurbs.. metrics could be useful for filtering and then perusing this data in a table.

