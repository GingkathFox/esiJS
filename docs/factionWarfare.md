<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

## characters

Top 100 leaderboard of pilots for kills and victory points separated by total, last week and yesterday

Returns **[object][1]** Character leaderboard of kills and victory points within faction warfare.

## corps

Returns **[object][1]** Corporation leaderboard of kills and victory points within faction warfare.

## leaderboard

Top 4 leaderboard of factions for kills and victory points separated by total, last week and yesterday.

Returns **[object][1]** All-time leaderboard of kills and victory points within faction warfare.

## stats

Statistical overviews of factions involved in faction warfare

Returns **[object][1]** Per faction breakdown of faction warfare statistics.

## systems

An overview of the current ownership of faction warfare solar systems.

Returns **[object][1]** 

## wars

Data about which NPC factions are at war.

Returns **[object][1]** 

## getSettings

Gets the settings for esiJS.

Returns **[JSON][2]** A JSON object with the settings.

## setSettings

Sets the settings for esiJS.

### Parameters

-   `$0` **[Object][1]** 
    -   `$0.route`  
    -   `$0.authToken`  
    -   `$0.language`  
    -   `$0.programName`  
-   `route` **[string][3]** Any of the valid routes through ESI.
-   `authToken` **[string][3]** A valid auth token.
-   `language` **[string][3]** A valid language code.
-   `programName` **[string][3]** The name of your project, used by esiJS to pass in as a header.

Returns **[Boolean][4]** True if it was able to sucessfully write. Otherwise, a error.

## sleep

Pause execution of code for a specified amount of time.

### Parameters

-   `millis` **[number][5]** The time to delay (in milliseconds)

Returns **[Promise][6]&lt;[function][7]>** 

[1]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object

[2]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/JSON

[3]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String

[4]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Boolean

[5]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number

[6]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise

[7]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Statements/function