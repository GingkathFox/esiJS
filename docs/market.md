<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

## groupInfo

Get information on an item group.

### Parameters

-   `groupID` **[number][1]** 

Returns **[object][2]** 

## groups

Get a list of item groups.

Returns **\[[number][1]]** 

## history

Return a list of historical market statistics for the specified type in a region.

### Parameters

-   `regionID` **[number][1]** 
-   `typeID` **[number][1]** 

Returns **[object][2]** 

## orders

Return a list of orders in a region.

### Parameters

-   `regionID` **[number][1]** 
-   `typeID` **[number][1]** 
-   `bOs` **[string][3]**  (optional, default `'all'`)
-   `pageNumber` **[number][1]**  (optional, default `1`)

## prices

Return a list of prices.

Returns **[object][2]** 

## types

Return a list of type IDs that have active orders in the region, for efficient market indexing.

### Parameters

-   `regionID` **[number][1]** 
-   `pageNumber` **[number][1]**  (optional, default `1`)

Returns **[object][2]** 

## getSettings

Gets the settings for esiJS.

Returns **[JSON][4]** A JSON object with the settings.

## setSettings

Sets the settings for esiJS.

### Parameters

-   `$0` **[Object][2]** 
    -   `$0.route`  
    -   `$0.authToken`  
    -   `$0.language`  
    -   `$0.programName`  
-   `route` **[string][3]** Any of the valid routes through ESI.
-   `authToken` **[string][3]** A valid auth token.
-   `language` **[string][3]** A valid language code.
-   `programName` **[string][3]** The name of your project, used by esiJS to pass in as a header.

Returns **[Boolean][5]** True if it was able to sucessfully write. Otherwise, a error.

## sleep

Pause execution of code for a specified amount of time.

### Parameters

-   `millis` **[number][1]** The time to delay (in milliseconds)

Returns **[Promise][6]&lt;[function][7]>** 

[1]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number

[2]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object

[3]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String

[4]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/JSON

[5]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Boolean

[6]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise

[7]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Statements/function