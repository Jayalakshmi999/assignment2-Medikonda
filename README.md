# assignment2-Medikonda
# Jaya Lakshmi Medikonda
###### Turkish and Islamic Arts Museum
The Turkish and Islamic Arts Museum (Turkish: Türk ve İslam Eserleri Müzesi) **is a museum located in Sultanahmet Square in Fatih district of Istanbul, Turkey.** Constructed in 1524, **the building was formerly the palace of Pargalı Ibrahim Pasha,** who was the second grand vizier to Suleiman the Magnificent, and was once thought to have been the husband of the Sultan's sister, Hatice Sultan.
_ _ _
# Airport close to Museum and the Surroundings
Istanbul Airport
1. Head toward Sultan Ahmet Park
2. Continue on to Hasdal-OkmeydabiBaglantisi
3. Continue Towards D020
4. Use the right 2 lanes to turn slightly right
5. Continue straight
6. keep left
7. Turkish and Islamic Arts Museum (destination)
- Topkapi Palace
- Hagia Irene
- Galata Tower Museum
- Istanbul Archaeological Museums
- The Great Palace Mosaics Museum
- Turbes Museum
- Rumeli Hisari Fortress Museum

**[about me link](AboutMe.md)**
_ _ _
# Tables
It describes the cities, location and time to spend in particular location
| City | Location | Time |
| --- | --- | ---|
| Newyork | Central Park | 2hours |
| Newjersy | Coastline | 1hour|
| Connecticut | Mystic | 3 hours |
| Texas | The alamo | 4 hours |
_ _ _
#  Pithy Quotes
> The Journey of a thousand miles begins with one step.

*Lao Tzu*

> Get busy living or get busy dying. 

*Stephen King*
_ _ _
# Code Fencing
> What does that mixin mean?
[stackoverflow](https://stackoverflow.com/questions/54974250/what-does-this-mixin-mean)
```
/// Gives a card depth effect.
/// @param {Number} $depth - depth level (between 1 and 5)
/// @link http://www.google.com/design/spec/layout/layout-principles.html#layout-principles-dimensionality Google Design
/// @requires {function} top-shadow
/// @requires {function} bottom-shadow
@mixin card($depth) {
  @if $depth < 1 {
    box-shadow: none;
  } @else if $depth > 5 {
    @warn "Invalid $depth `#{$depth}` for mixin `card`.";
  } @else {
    box-shadow: bottom-shadow($depth), top-shadow($depth);  
  }
}
```
[Snippet Source](https://css-tricks.com/snippets/sass/material-shadows-mixin/)
