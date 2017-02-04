# PokemonGoBiomes
Collection of OpenStreetMap queries for determining natural habitat for each Pokemon in Pokemon Go

# Usage
1. Open [overpassturbo](overpassturbo) file
2. Copy and paste the file contents to [http://overpass-turbo.eu/](http://overpass-turbo.eu/)
3. Move the overpass-turbo map to the area where you want
  * You can also click the small circle to center to your current location.
4. Click **Run** on the top left corner.

**Note**: You can move the map to next area and click Run again to fetch the data again. The overpassturbo file will evolve over time so you should come here and copy updated version every once in a while.

# How do I read this map
I have made an assumption that each *type* of common Pokemon can spawn within some area. These areas are colored with the same colors that this [chart](https://rankedboost.com/pokemon-go/type-chart/) shows. There is also a label in the middle of the bounding box of the area showing the type of Pokemon for that area.

Exceptions to the color chart:
* Black color represents areas that do not match any query.
* White color represents area for "natural"="wood" which seems to contain Grass, Bug, Poison and Flying types. This color does not have a label.

In addition to spawn areas I have assumed that rare Pokemon can spawn at specific spots. You can see a small image of the Pokemon that might spawn at that specific spot.

# Problems
* There are areas within an area and when multiple colors mix you might not see correct colors. Labels help a bit but not always.
* Labels are centered to center of bounding box. So for example if you have L shaped area the label appears outside of the area.
