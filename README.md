# ![LOGO](logo.png) Stats **flow**ground Connector

## Description

A generated **flow**ground connector for the Stats API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/haloapi.com/stats/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:42:15+03:00

## API Description

API that provides statistical data about Players and Matches.

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Halo 5 - Match Result - Arena

> <p>Retrieves detailed statistics for a Match with the Arena Game Mode.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 12, 2018:</strong></p><br/>
>     <ul><br/>
>         <li>Updated the documentation for "PlayerScore".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Game Mode clarifications to the Endpoint description.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Post-Game Carnage Report: Arena" to "Halo 5 - Match Result - Arena".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>         <li>Updated the documentation for "GameVariantResourceId" and "MapVariantResourceId" to reference the UGC API.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>May 16, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Documented HTTP 503 Response Code.</li><br/>
>         <li>Added documentation for the "MatchSpeedWinAmount", "ObjectivesCompletedAmount", and "BoostData" fields.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>April 20, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added documentation for the "GameVariantResourceId", "MapVariantResourceId", and "PlayerScore" fields.</li><br/>
>         <li>Updated the documentation for the "MapVariantId" and "GameVariantId" fields with the recommendation of using the "MapVariantResourceId" and "GameVariantResourceId" fields, respectively.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `matchId` - _required_ - An ID that uniquely identifies a Match. Match IDs can be retrieved from the "Halo 5 - Player Match History" Endpoint.

### Halo 5 - Match Result - Campaign

> <p>Retrieves detailed statistics for a Match with the Campaign Game Mode.</p><br/>
> <p>Every time a player plays a portion of a Campaign Mission, a Match will be generated whether the player finishes the Mission or not. If the "Match" ends because the Mission was completed, this will be indicated in the response.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Game Mode clarifications to the Endpoint description.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Post-Game Carnage Report: Campaign" to "Halo 5 - Match Result - Campaign".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>May 16, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Documented HTTP 503 Response Code.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>April 20, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added documentation for the "GameVariantResourceId", "MapVariantResourceId", and "PlayerScore" fields.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `matchId` - _required_ - An ID that uniquely identifies a Match. Match IDs can be retrieved from the "Halo 5 - Player Match History" Endpoint.

### Halo 5 - Company

> <p>Retrieves information about the Company. The response will contain the Company's name, status, and members.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>July 14, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `companyId` - _required_ - The ID for the Company. The Company ID for a player can be retrieved from the Profile APIs via the "Halo 5 - Player Apperance" Endpoint.

### Halo 5 - Company Commendations

> <p>Retrieves the commendation state for a Company.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>July 14, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `companyId` - _required_ - The ID for the Company. The Company ID for a player can be retrieved from the Profile APIs via the "Halo 5 - Player Apperance" Endpoint.

### Halo 5 - Match Result - Custom

> <p>Retrieves detailed statistics for a Match with the Custom Game Mode. Games with the Custom Game Mode are played on Xbox Live Servers. For games played on Local Servers, use the "Halo 5 - Match Result - Custom Local" Endpoint.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 12, 2018:</strong></p><br/>
>     <ul><br/>
>         <li>Updated the documentation for "PlayerScore".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Game Mode clarifications to the Endpoint description.</li><br/>
>         <li>Added documentation for "PresentInMatch".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Post-Game Carnage Report: Custom" to "Halo 5 - Match Result - Custom".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>         <li>Updated the documentation for "GameVariantResourceId" and "MapVariantResourceId" to reference the UGC API.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>May 16, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Documented HTTP 503 Response Code.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>April 20, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added documentation for the "GameVariantResourceId", "MapVariantResourceId", and "PlayerScore" fields.</li><br/>
>         <li>Updated the documentation for the "MapVariantId" and "GameVariantId" fields with the recommendation of using the "MapVariantResourceId" and "GameVariantResourceId" fields, respectively.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `matchId` - _required_ - An ID that uniquely identifies a Match. Match IDs can be retrieved from the "Halo 5 - Player Match History" Endpoint.

### Halo 5 - Match Result - Custom Local

> <p>Retrieves detailed statistics for a Match with the Custom Local Game Mode. Games with the Custom Local Game Mode are played on Local Servers. For games played on Xbox Live Servers, use the "Halo 5 - Match Result - Custom" Endpoint.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 12, 2018:</strong></p><br/>
>     <ul><br/>
>         <li>Updated the documentation for "PlayerScore".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `matchId` - _required_ - An ID that uniquely identifies a Match. Match IDs can be retrieved from the "Halo 5 - Player Match History" Endpoint.

### Halo 5 - Match Events

> <p>Retrieves a set of Events related to the Match specified. Events are only available once the Match has completed.</p><br/>
> <p>The set of Events may grow over time as data becomes available.</p><br/>
> <p>This Endpoint does not have the accuracy guarantees of other Endpoints have, so please use with caution. This endpoint may not return Matches before December 1, 2015.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Events for Match" to "Halo 5 - Match Events".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>May 20, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>The Endpoint now correctly reports the "Content-Type" Response Header as "application/json".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>May 16, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Documented HTTP 503 Response Code.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>April 20, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added new types of events to the Endpoint: Impulses, Medals, Player Spawns, Round Stats, Round Ends, Weapon Drops, Weapon Pickups, and Weapon Pickup Pads.</li><br/>
>         <li>Fixed an issue that caused the API to consistently return HTTP 500's for matches where a player left and rejoined the match.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `matchId` - _required_ - An ID that uniquely identifies a Match. Match IDs can be retrieved from the "Halo 5 - Player Match History" Endpoint.

### Halo 5 - Leaderboard - Player CSR

> <p>Retrieves the Leaderboard for Player CSRs. The Leaderboard consists of the top Players with a CSR of 1800 or above for a given Playlist in a Season.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>March 6, 2018:</strong></p><br/>
>     <ul><br/>
>         <li>Fixed documentation typos for the names of the "Player" and "Gamertag" properties.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>July 31, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Clarified documentation for which players are included in the leaderboard.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Player Leaderboard" to "Halo 5 - Leaderboard Player CSR".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>April 20, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `seasonId` - _required_ - The ID for the Season.
* `playlistId` - _required_ - The ID for the Playlist.
* `count` - _optional_ - When specified, this indicates the maximum quantity of items the client would like returned in the response.

When omitted, 200 is assumed.

When the value contains a non-digit or is exactly "0", HTTP 400 ("Bad Request") is returned.

When the value is greater than the allowed range [1,250], the maximum allowed value is used instead.

The "Count" field in the response will confirm the actual value that was used.

### Halo 5 - Player Commendations

> <p>Retrieves the commendation state for a Player.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>July 14, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `player` - _required_ - The Player's Gamertag.

### Halo 5 - Player Match History

> <p>Retrieves a list of Matches that the Player has participated in and which have completed processing. If the Player is currently in a match, it is not returned in this API.</p><br/>
> <p>This endpoint will include games played on Local Servers with the Custom Local Game Mode for games that occurred or after December 22, 2017.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 1, 2019:</strong></p><br/>
>     <ul><br/>
>         <li>Enabled support for viewing the time component of the "MatchCompletedDate" via the "{include-times}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added support for the Custom Local Game mode.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Matches for Player" to "Halo 5 - Player Match History".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>April 20, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Clarified documentation for the "MapVariant" and "GameVariant" fields.</li><br/>
>         <li>Corrected "OwnerType" values for the "MapVariant" and "GameVariant" fields.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `player` - _required_ - The Player's Gamertag.
* `modes` - _optional_ - Indicates what Game Mode(s) the client is interested in getting Matches for (arena, campaign, custom, customlocal, or warzone).

When the parameter is omitted or empty, Matches from all modes are returned. When a client would like to receive Matches spanning multiple Modes, separate the Modes with a comma (e.g. "arena,custom"). There is no significance to the order the Modes are specified in this parameter.

When an invalid Mode is specified, HTTP 400 ("Bad Request") is returned.

When a valid Mode is specified more than once, HTTP 400 ("Bad Request") is returned.
* `start` - _optional_ - When specified, this indicates the starting index (0-based) for which the batch of results will begin at. For example, "start=0" indicates that the first qualifying result will be returned, no items are 'skipped'. Passing "start=10" indicates that the result will begin with the 11th item, the first 10 will be 'skipped'.

When omitted, zero is assumed.

When the value contains a non-digit, HTTP 400 ("Bad Request") is returned.
* `count` - _optional_ - When specified, this indicates the maximum quantity of items the client would like returned in the response.

When omitted, 25 is assumed.

When the value contains a non-digit or is exactly "0", HTTP 400 ("Bad Request") is returned.

When the value is greater than the allowed range [1,25], the maximum allowed value is used instead. The "Count" field in the response will confirm the actual value that was used.
* `include-times` - _optional_ - When set to "true", this indicates that the time component of the "MatchCompletedDate" field should be populated.

Otherwise, when set to "false" or when omitted, the time component will be set to "00:00:00".

When the value contains a non-boolean, HTTP 400 ("Bad Request") is returned.

### Halo 5 - Player Service Records - Arena

> <p>Retrieves Service Records for the Arena Game Mode for one or more players. A Service Record contains a player's lifetime statistics in the Game Mode.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>June 29, 2018:</strong></p><br/>
>     <ul><br/>
>         <li>Added support for Social (Unranked) Playlists.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Game Mode clarifications to the Endpoint description.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Service Record: Arena" to "Halo 5 - Player Service Records - Arena".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>April 20, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added documentation for the "CsrPercentile" field.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `players` - _required_ - A comma-separated list of Gamertags. Up to 32 Gamertags may be specified.
* `seasonId` - _optional_ - When specified, this indicates the Season to request the Arena Playlist Stats for. If this is not specified, the default is the current Season. Seasons are available via the Metadata API. Social (Unranked) Arena Playlist Stats can be retrieved by specifying "NonSeasonal".

### Halo 5 - Player Service Records - Campaign

> <p>Retrieves Service Records for the Campaign Game Mode for one or more players. A Service Record contains a player's lifetime statistics in the Game Mode.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Game Mode clarifications to the Endpoint description.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Service Record: Campaign" to "Halo 5 - Player Service Records - Campaign".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `players` - _required_ - A comma-separated list of Gamertags. Up to 32 Gamertags may be specified.

### Halo 5 - Player Service Records - Custom

> <p>Retrieves Service Records for the Custom Game Mode for one or more players. A Service Record contains a player's lifetime statistics in the Game Mode. Games with the Custom Game Mode are played on Xbox Live Servers. For games played on Local Servers, use the "Halo 5 - Player Service Records - Custom Local" Endpoint.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Game Mode clarifications to the Endpoint description.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Service Record: Custom" to "Halo 5 - Player Service Records - Custom".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `players` - _required_ - A comma-separated list of Gamertags. Up to 32 Gamertags may be specified.

### Halo 5 - Player Service Records - Custom Local

> <p>Retrieves Service Records for the Custom Local Game Mode for one or more players. A Service Record contains a player's lifetime statistics in the Game Mode. Games with the Custom Local Game Mode are played on Local Servers. For games played on Xbox Live Servers, use the "Halo 5 - Player Service Records - Custom" Endpoint. A player's Custom Local Service Record summarizes games played on or after December 22, 2017.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `players` - _required_ - A comma-separated list of Gamertags. Up to 32 Gamertags may be specified.

### Halo 5 - Player Service Records - Warzone

> <p>Retrieves Service Records for the Warzone Game Mode for one or more players. A Service Record contains a player's lifetime statistics in the Game Mode.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Game Mode clarifications to the Endpoint description.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Service Record: Warzone" to "Halo 5 - Player Service Records - Warzone".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `players` - _required_ - A comma-separated list of Gamertags. Up to 32 Gamertags may be specified.

### Halo 5 - Match Result - Warzone

> <p>Retrieves detailed statistics for a Match with the Warzone Game Mode.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Game Mode clarifications to the Endpoint description.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Post-Game Carnage Report: Warzone" to "Halo 5 - Match Result - Warzone".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>         <li>Updated the documentation for "GameVariantResourceId" and "MapVariantResourceId" to reference the UGC API.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>May 16, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Documented HTTP 503 Response Code.</li><br/>
>         <li>Added documentation for the "MatchSpeedWinAmount", "ObjectivesCompletedAmount", and "BoostData" fields.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>April 20, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added documentation for the "GameVariantResourceId", "MapVariantResourceId", and "PlayerScore" fields.</li><br/>
>         <li>Updated the documentation for the "MapVariantId" and "GameVariantId" fields with the recommendation of using the "MapVariantResourceId" and "GameVariantResourceId" fields, respectively.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `matchId` - _required_ - An ID that uniquely identifies a Match. Match IDs can be retrieved from the "Halo 5 - Player Match History" Endpoint.

### Halo 5 PC - Match Result - Custom

> <p>Retrieves detailed statistics for a Match with the Custom Game Mode. Games with the Custom Game Mode are played on Xbox Live Servers. For games played on Local Servers, use the "Halo 5 - Match Result - Custom Local" Endpoint.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 12, 2018:</strong></p><br/>
>     <ul><br/>
>         <li>Updated the documentation for "PlayerScore".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Game Mode clarifications to the Endpoint description.</li><br/>
>         <li>Added documentation for "PresentInMatch".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Post-Game Carnage Report: Custom" to "Halo 5 - Match Result - Custom".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>         <li>Updated the documentation for "GameVariantResourceId" and "MapVariantResourceId" to reference the UGC API.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>May 16, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Documented HTTP 503 Response Code.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>April 20, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added documentation for the "GameVariantResourceId", "MapVariantResourceId", and "PlayerScore" fields.</li><br/>
>         <li>Updated the documentation for the "MapVariantId" and "GameVariantId" fields with the recommendation of using the "MapVariantResourceId" and "GameVariantResourceId" fields, respectively.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `matchId` - _required_ - An ID that uniquely identifies a Match. Match IDs can be retrieved from the "Halo 5 PC - Player Match History" Endpoint.

### Halo 5 PC - Player Match History

> <p>Retrieves a list of Matches that the Player has participated in and which have completed processing. If the Player is currently in a match, it is not returned in this API.</p><br/>
> <p>This endpoint will include games played on Local Servers with the Custom Local Game Mode for games that occurred or after December 22, 2017.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 1, 2019:</strong></p><br/>
>     <ul><br/>
>         <li>Enabled support for viewing the time component of the "MatchCompletedDate" via the "{include-times}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added support for the Custom Local Game mode.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Matches for Player" to "Halo 5 - Player Match History".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>April 20, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Clarified documentation for the "MapVariant" and "GameVariant" fields.</li><br/>
>         <li>Corrected "OwnerType" values for the "MapVariant" and "GameVariant" fields.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `player` - _required_ - The Player's Gamertag.
* `modes` - _optional_ - Indicates what Game Mode(s) the client is interested in getting Matches for (arena, campaign, custom, or warzone).

When the parameter is omitted or empty, Matches from all modes are returned. When a client would like to receive Matches spanning multiple Modes, separate the Modes with a comma (e.g. "arena,custom"). There is no significance to the order the Modes are specified in this parameter.

When an invalid Mode is specified, HTTP 400 ("Bad Request") is returned.

When a valid Mode is specified more than once, HTTP 400 ("Bad Request") is returned.
* `start` - _optional_ - When specified, this indicates the starting index (0-based) for which the batch of results will begin at. For example, "start=0" indicates that the first qualifying result will be returned, no items are 'skipped'. Passing "start=10" indicates that the result will begin with the 11th item, the first 10 will be 'skipped'.

When omitted, zero is assumed.

When the value contains a non-digit, HTTP 400 ("Bad Request") is returned.
* `count` - _optional_ - When specified, this indicates the maximum quantity of items the client would like returned in the response.

When omitted, 25 is assumed.

When the value contains a non-digit or is exactly "0", HTTP 400 ("Bad Request") is returned.

When the value is greater than the allowed range [1,25], the maximum allowed value is used instead. The "Count" field in the response will confirm the actual value that was used.
* `include-times` - _optional_ - When set to "true", this indicates that the time component of the "MatchCompletedDate" field should be populated.

Otherwise, when set to "false" or when omitted, the time component will be set to "00:00:00".

When the value contains a non-boolean, HTTP 400 ("Bad Request") is returned.

### Halo 5 PC - Player Service Records - Custom

> <p>Retrieves Service Records for the Custom Game Mode for one or more players. A Service Record contains a player's lifetime statistics in the Game Mode. Games with the Custom Game Mode are played on Xbox Live Servers. For games played on Local Servers, use the "Halo 5 - Player Service Records - Custom Local" Endpoint.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>December 22, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Game Mode clarifications to the Endpoint description.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Service Record: Custom" to "Halo 5 - Player Service Records - Custom".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `players` - _required_ - A comma-separated list of Gamertags. Up to 32 Gamertags may be specified.

### Halo Wars 2 - Match Result

> <p>Retrieves detailed statistics for a Match. Matches can be retrieved before they are completed; however, the data for in-progress Matches is only updated every few minutes.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>September 5, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Documented new game mode "Terminus Firefight".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `matchId` - _required_ - An ID that uniquely identifies a Match. Match IDs can be retrieved from the "Halo Wars 2 - Player Match History" Endpoint.

### Halo Wars 2 - Match Events

> <p>Retrieves a set of Events related to the Match specified. Events are only available once the Match has completed. Events are not available for Matches played with the Custom Match Type.</p><br/>
> <p>The set of Events may grow over time as data becomes available.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>September 5, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Documented new game mode "Terminus Firefight".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `matchId` - _required_ - An ID that uniquely identifies a Match. Match IDs can be retrieved from the "Halo Wars 2 - Player Match History" Endpoint.

### Halo Wars 2 - Leaderboard - Player CSR

> <p>Retrieves the Leaderboard for Player CSRs. The Leaderboard consists of the top Players with a CSR of 1800 or above for a given Playlist in a Season.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>March 6, 2018:</strong></p><br/>
>     <ul><br/>
>         <li>Fixed documentation typos for the names of the "Player" and "Gamertag" properties.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>July 31, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Clarified documentation for which players are included in the leaderboard.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>July 14, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `seasonId` - _required_ - The ID for the Season.
* `playlistId` - _required_ - The ID for the Playlist.
* `count` - _optional_ - When specified, this indicates the maximum quantity of items the client would like returned in the response.

When omitted, 200 is assumed.

When the value contains a non-digit or is exactly "0", HTTP 400 ("Bad Request") is returned.

When the value is greater than the allowed range [1,250], the maximum allowed value is used instead.

The "Count" field in the response will confirm the actual value that was used.

### Halo Wars 2 - Player Campaign Progress

> <p>Retrieves the Campaign Progress state for a Player.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `player` - _required_ - The Player's Gamertag.

### Halo Wars 2 - Player Match History

> <p>Retrieves a list of Matches that the Player has participated in. If the Player is currently in a Match, it is not returned in this API.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>September 5, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Documented new game mode "Terminus Firefight".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `player` - _required_ - The Player's Gamertag.
* `matchType` - _optional_ - Indicates what Match Type the client is interested in getting Matches for ("custom" or "matchmaking").

When the parameter is omitted or empty, Matches from all Match Types are returned.

When an invalid Mode is specified, HTTP 400 ("Bad Request") is returned.
* `start` - _optional_ - When specified, this indicates the starting index (0-based) for which the batch of results will begin at. For example, "start=0" indicates that the first qualifying result will be returned, no items are 'skipped'. Passing "start=10" indicates that the result will begin with the 11th item, the first 10 will be 'skipped'.

When omitted, zero is assumed.

When the value contains a non-digit, HTTP 400 ("Bad Request") is returned.
* `count` - _optional_ - When specified, this indicates the maximum quantity of items the client would like returned in the response.

When omitted, 25 is assumed.

When the value contains a non-digit or is exactly "0", HTTP 400 ("Bad Request") is returned.

When the value is greater than the allowed range [1,25], the maximum allowed value is used instead. The "Count" field in the response will confirm the actual value that was used.

### Halo Wars 2 - Player Stats Summary

> <p>Retrieves high-level aggregations across the lifetime of a Player.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>September 5, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added additional fields: "GameMode" and "HighestObjectiveScoreByTeamSize".</li><br/>
>         <li>Documented new game mode "Terminus Firefight".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `player` - _required_ - The Player's Gamertag.

### Halo Wars 2 - Player Season Stats Summary

> <p>Retrieves high-level aggregations across a Season for a Player.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>September 5, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added additional pivots of data: "CustomModeStats", "SinglePlayerModeStats", "MultiplayerModeStats", "SocialModeStats", and "RankedModeStats".</li><br/>
>         <li>Added additional fields to the "Summary" contract: "GameMode" and "HighestObjectiveScoreByTeamSize".</li><br/>
>         <li>Documented new game mode "Terminus Firefight".</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `player` - _required_ - The Player's Gamertag.
* `seasonId` - _required_ - A Season ID or "current" for the current Season. Seasons are available via the Metadata API.

### Halo Wars 2 - Player Playlist Ratings

> <p>Retrieves Playlist Ratings in the current season for one or more Players.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `playlistId` - _required_ - The ID of the Playlist to get Ratings for.
* `players` - _required_ - A comma-separated list of Gamertags. Up to 6 Gamertags may be specified.

### Halo Wars 2 - Player XPs

> <p>Retrieves XP and Rank information for one or more players.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `players` - _required_ - A comma-separated list of Gamertags. Up to 6 Gamertags may be specified.

## License

**flow**ground :- Telekom iPaaS / haloapi-com-stats-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
