## What is location
- A particular place or position
- A site or position; situation. the act or process or the state of being located

[[Location]] is a type that contains latitude, longitude and address. It may be accessed as an object with 3 keys in it. These keys are:

-   The `latitude` of the location. This may be null, if the object has been recently uploaded. This _must_ be decimal degrees, for example: `41.8657007325722`
-   The `longitude` of the location. This may be null, if the object has been recently uploaded. This _must_ be in decimal degrees, for example: `-87.76110202195098`
-   The `human_address`, which is a JSON object containing the U.S. address of the location. This may be null. The object has the following keys:
    -   `address` – The street address of the location.
    -   `city` – The city this address is in
    -   `state` – The state this address is in
    -   `zip` – The zip code for this address