forked from [matthewdean/roblox-web-apis](https://github.com/matthewdean/roblox-web-apis)<br />

## Table of Contents
* [Roblox API Subdomains](#roblox-api-subdomains)
* [oAuth2 APIs](#oauth2-apis)
* [Roblox Web APIs](#web-apis)
  * [Universe APIs](#universe-apis)
  * [Place APIs](#place-apis)
  * [User APIs](#user-apis)

## Roblox API Subdomains
*click a link to be directed to the public documentation, for a complete documentation of all APIs in one webpage, visit [here](https://api.roblox.com/docs?useConsolidatedPage=true)*
| Site | Description |
| -: | :- |
| [abtesting.roblox.com](https://abtesting.roblox.com/docs) \[ [v1](https://abtesting.roblox.com/docs#!/v1) \] | Endpoints for the A/B Testing framework |
| [accountinformation.roblox.com](https://accountinformation.roblox.com/docs) \[ [v1](https://accountinformation.roblox.com/docs#!/v1) \] | All endpoints for accessing/modifying account information |
| [accountsettings.roblox.com](https://accountsettings.roblox.com/docs) \[ [v1](https://accountsettings.roblox.com/docs#!/v1) \] | All endpoints for account/user settings. |
| [adconfiguration.roblox.com](https://adconfiguration.roblox.com/docs) \[ [v2](https://adconfiguration.roblox.com/docs#!/v2) \| [v1](https://adconfiguration.roblox.com/docs#!/v1) \] | Roblox Ad Configuration related endpoints. |
| [ads.roblox.com](https://ads.roblox.com/docs) \[ [v1](https://ads.roblox.com/docs#!/v1) \] | Ads configuration endpoints. |
| [api.roblox.com](https://api.roblox.com/docs) \[ [v1](https://api.roblox.com/docs#!/v1) \] | Roblox Legacy Api Endpoints |
| [assetdelivery.roblox.com](https://assetdelivery.roblox.com/docs) \[ [v1](https://assetdelivery.roblox.com/docs#!/v1) \] | Serves asset content. |
| [auth.roblox.com](https://auth.roblox.com/docs) \[ [v3](https://auth.roblox.com/docs#!/v3) \| [v2](https://auth.roblox.com/docs#!/v2) \| [v1](https://auth.roblox.com/docs#!/v1) \] | All endpoints that tamper with authentication sessions. |
| [avatar.roblox.com](https://avatar.roblox.com/docs) \[ [v1](https://avatar.roblox.com/docs#!/v1) \] | Endpoints relating to the customization of player avatars. |
| [badges.roblox.com](https://badges.roblox.com/docs) \[ [v2](https://badges.roblox.com/docs#!/v2) \| [v1](https://badges.roblox.com/docs#!/v1) \] | Endpoints for badges and badge awards management. |
| [billing.roblox.com](https://billing.roblox.com/docs) \[ [v1](https://billing.roblox.com/docs#!/v1) \] | Real money transactions and interaction. |
| [captcha.roblox.com](https://captcha.roblox.com/docs) \[ [v1](https://captcha.roblox.com/docs#!/v1) \] | Captcha Api Site |
| [catalog.roblox.com](https://catalog.roblox.com/docs) \[ [v2](https://catalog.roblox.com/docs#!/v2) \| [v1](https://catalog.roblox.com/docs#!/v1) \] | Catalog items browsing and searching. Content and user based catalog items recommendations. |
| [cdnproviders.roblox.com](https://cdnproviders.roblox.com/docs) \[ [v1](https://cdnproviders.roblox.com/docs#!/v1) \] | Purpose of Api here. |
| [chat.roblox.com](https://chat.roblox.com/docs) \[ [v2](https://chat.roblox.com/docs#!/v2) \| [v1.0](https://chat.roblox.com/docs#!/v1.0) \] | All chat and party related endpoints. |
| [clientsettings.roblox.com](https://clientsettings.roblox.com/docs) \[ [v2](https://clientsettings.roblox.com/docs#!/v2) \| [v1](https://clientsettings.roblox.com/docs#!/v1) \] | Used by various Roblox clients to retrieve configuration information. |
| [clientsettingscdn.roblox.com](https://clientsettingscdn.roblox.com/docs) \[ [v2](https://clientsettingscdn.roblox.com/docs#!/v2) \| [v1](https://clientsettingscdn.roblox.com/docs#!/v1) \] | Used by various Roblox clients to retrieve configuration information. |
| [contacts.roblox.com](https://contacts.roblox.com/docs) \[ [v1](https://contacts.roblox.com/docs#!/v1) \] | Contacts and userTag management. |
| [contentstore.roblox.com](https://contentstore.roblox.com/docs) \[ [v1](https://contentstore.roblox.com/docs#!/v1) \] | ApiSite to front the TemporaryStore for files before uploading to S3 |
| [develop.roblox.com](https://develop.roblox.com/docs) \[ [v2](https://develop.roblox.com/docs#!/v2) \| [v1](https://develop.roblox.com/docs#!/v1) \] | Game development configuration endpoints. |
| [economy.roblox.com](https://economy.roblox.com/docs) \[ [v2](https://economy.roblox.com/docs#!/v2) \| [v1](https://economy.roblox.com/docs#!/v1) \] | Endpoints related to transactions and currency. |
| [economycreatorstats.roblox.com](https://economycreatorstats.roblox.com/docs) \[ [v1](https://economycreatorstats.roblox.com/docs#!/v1) \] | Roblox.EconomyCreatorStats.Api endpoints. |
| [engagementpayouts.roblox.com](https://engagementpayouts.roblox.com/docs) \[ [v1](https://engagementpayouts.roblox.com/docs#!/v1) \] | For engagement-based payout information |
| [followings.roblox.com](https://followings.roblox.com/docs) \[ [v2](https://followings.roblox.com/docs#!/v2) \| [v1](https://followings.roblox.com/docs#!/v1) \] | Establishes follow relationship between subscriber entities (users, groups, etc) and source entities (games, groups, assets, etc.) |
| [friends.roblox.com](https://friends.roblox.com/docs) \[ [v1](https://friends.roblox.com/docs#!/v1) \] | Friends, followers, and contacts management. |
| [gameinternationalization.roblox.com](https://gameinternationalization.roblox.com/docs) \[ [v2](https://gameinternationalization.roblox.com/docs#!/v2) \| [v1](https://gameinternationalization.roblox.com/docs#!/v1) \] | Manages internationalization of games such as translating in game content. |
| [gamejoin.roblox.com](https://gamejoin.roblox.com/docs) \[ [v1](https://gamejoin.roblox.com/docs#!/v1) \] | All endpoints around launching a game. |
| [gamepersistence.roblox.com](https://gamepersistence.roblox.com/docs) \[ [v2](https://gamepersistence.roblox.com/docs#!/v2) \| [v1](https://gamepersistence.roblox.com/docs#!/v1) \| [v0](https://gamepersistence.roblox.com/docs#!/v0) \] | Endpoints for the in-game datastore system for storing data for games. |
| [games.roblox.com](https://games.roblox.com/docs) \[ [v2](https://games.roblox.com/docs#!/v2) \| [v1](https://games.roblox.com/docs#!/v1) \] | All endpoints for game discovery, and details. |
| [groups.roblox.com](https://groups.roblox.com/docs) \[ [v2](https://groups.roblox.com/docs#!/v2) \| [v1](https://groups.roblox.com/docs#!/v1) \| [v0](https://groups.roblox.com/docs#!/v0) \] | Groups management. |
| [inventory.roblox.com](https://inventory.roblox.com/docs) \[ [v2](https://inventory.roblox.com/docs#!/v2) \| [v1](https://inventory.roblox.com/docs#!/v1) \] | All endpoints for viewing (but not granting) ownership of items. |
| [itemconfiguration.roblox.com](https://itemconfiguration.roblox.com/docs) \[ [v1](https://itemconfiguration.roblox.com/docs#!/v1) \] | Configure Items (bundles and avatar assets). |
| [locale.roblox.com](https://locale.roblox.com/docs) \[ [v1](https://locale.roblox.com/docs#!/v1) \] | User locale management. |
| [localizationtables.roblox.com](https://localizationtables.roblox.com/docs) \[ [v1](https://localizationtables.roblox.com/docs#!/v1) \] | Handles managing of localization tables. |
| [metrics.roblox.com](https://metrics.roblox.com/docs) \[ [v1](https://metrics.roblox.com/docs#!/v1) \] | Record metrics across Roblox. |
| [midas.roblox.com](https://midas.roblox.com/docs) \[ [v1](https://midas.roblox.com/docs#!/v1) \] | Handle requests around making purchases using Midas |
| [notifications.roblox.com](https://notifications.roblox.com/docs) \[ [v2](https://notifications.roblox.com/docs#!/v2) \] | All notification stream endpoints. |
| [points.roblox.com](https://points.roblox.com/docs) \[ [v1](https://points.roblox.com/docs#!/v1) \] | The web Api for the in-game PointsService. |
| [premiumfeatures.roblox.com](https://premiumfeatures.roblox.com/docs) \[ [v1](https://premiumfeatures.roblox.com/docs#!/v1) \] | This API is for premium features and anything pertaining to account add ons |
| [presence.roblox.com](https://presence.roblox.com/docs) \[ [v1](https://presence.roblox.com/docs#!/v1) \] | All endpoints for managing presence. |
| [privatemessages.roblox.com](https://privatemessages.roblox.com/docs) \[ [v1](https://privatemessages.roblox.com/docs#!/v1) \] | All messages page endpoints. |
| [publish.roblox.com](https://publish.roblox.com/docs) \[ [v1](https://publish.roblox.com/docs#!/v1) \] | All endpoints handling file uploads. |
| [share.roblox.com](https://share.roblox.com/docs) \[ [v1](https://share.roblox.com/docs#!/v1) \] | Purpose of Api here. |
| [textfilter.roblox.com](https://textfilter.roblox.com/docs) \[ [v2](https://textfilter.roblox.com/docs#!/v2) \] | High volume text filtering. |
| [thumbnails.roblox.com](https://thumbnails.roblox.com/docs) \[ [v1](https://thumbnails.roblox.com/docs#!/v1) \] | Endpoints for requesting thumbnails. |
| [thumbnailsresizer.roblox.com](https://thumbnailsresizer.roblox.com/docs) \[ [v1](https://thumbnailsresizer.roblox.com/docs#!/v1) \] | Validate and resize thumbnails to requested dimensions |
| [trades.roblox.com](https://trades.roblox.com/docs) \[ [v1](https://trades.roblox.com/docs#!/v1) \] | Endpoints for trading collectible items. |
| [translationroles.roblox.com](https://translationroles.roblox.com/docs) \[ [v1](https://translationroles.roblox.com/docs#!/v1) \] | Manages translation roles of developers in game localization. |
| [translations.roblox.com](https://translations.roblox.com/docs) \[ [v1](https://translations.roblox.com/docs#!/v1) \] | Endpoints for requesting translations. |
| [twostepverification.roblox.com](https://twostepverification.roblox.com/docs) \[ [v1](https://twostepverification.roblox.com/docs#!/v1) \] | Platform interface for the two step verification system. |
| [users.roblox.com](https://users.roblox.com/docs) \[ [v1](https://users.roblox.com/docs#!/v1) \] | For direct Roblox user information. |
| [voice.roblox.com](https://voice.roblox.com/docs) \[ [v1](https://voice.roblox.com/docs#!/v1) \] | APIs for Voice calls. |

<!-- TODO:
Complete (duh..)
Add proper responses and requests (wish GithHub's Markdown allowed showing the content of files in the repo)
Make this relevant
-->
## oAuth2 APIs
*Earlier in 2020, Roblox implemented oAuth2 into the Creator Dashboard, and now has been used on **2 applications**. It's unsure if Roblox developers will be able to take advantage of it in the future.*
* oAuth2 Configuration
  * https://apis.roblox.com/application-authorization/.well-known/openid-configuration
* Authorization
  * https://apis.roblox.com/application-authorization/v1/authorize?client_id=CLIENT_ID&scope=SCOPE&response_type=RESPONSE_TYPE&redirect_uri=URI
* Visual Authorization
  * https://www.roblox.com/permission-request?client_id=CLIENT_ID&scope=SCOPE&response_type=RESPONSE_TYPE&redirect_uri=URI
* Known Client IDs
  * **e3a58e71-5993-4070-a0e1-9c757f6b8748** Creator Dashboard
  * **b03b1542-931c-4f68-a5c3-3311eeba9ac2** BevyLabs
* Examples
  * [Visual (Creator Dashboard)](https://www.roblox.com/permission-request?client_id=e3a58e71-5993-4070-a0e1-9c757f6b8748&scope=openId%20profile&response_type=code&redirect_uri=https://create.roblox.com/home)
  * [Visual (BevyLabs)](https://www.roblox.com/permission-request?client_id=b03b1542-931c-4f68-a5c3-3311eeba9ac2&scope=openId%20profile&response_type=code&redirect_uri=https://events.rbx.com/accounts/oidc/callback/)
  * [Direct (Creator Dashboard)](https://apis.roblox.com/application-authorization/v1/authorize?client_id=e3a58e71-5993-4070-a0e1-9c757f6b8748&scope=openId%20profile&response_type=code&redirect_uri=https://create.roblox.com/home)
  * [Direct (BevyLabs)](https://apis.roblox.com/application-authorization/v1/authorize?client_id=b03b1542-931c-4f68-a5c3-3311eeba9ac2&scope=openId%20profile&response_type=code&redirect_uri=https://events.rbx.com/accounts/oidc/callback/)
* Other Information
  * Roblox's oAuth2 codes are around 1604 characters long
  

## Web APIs
*Endpoints on the www subdomain are most likely deprecated, and could be removed by Roblox at any time.*

### Universe APIs
<details><summary>Get the private server instances of a universe that the authenticated user can access</summary>
 
* https://www.roblox.com/private-server/instance-list-json?universeId=130580&page=1
</details>

<details><summary>Get start informatioin about a universe</summary>
 
* https://api.roblox.com/v1.1/game-start-info?universeId=13058
</details>

<details><summary>Get information about a universe</summary>

* api
  * https://api.roblox.com/universes/get-info?universeId=13058
* develop
  * https://develop.roblox.com/v1/universes/multiget?ids=13058
    * [Example request](https://develop.roblox.com/docs#!/Universes/get_v1_universes_multiget)
  * https://develop.roblox.com/v1/universes/13058
    * [Example request](https://develop.roblox.com/docs#!/Universes/get_v1_universes_universeId)
* games
  * https://games.roblox.com/v1/games?universeIds=13058
    * [Example request](https://games.roblox.com/docs#!/Games/get_v1_games)
     
</details>

<details><summary>Get gamepasses of a universe</summary>
 
* https://games.roblox.com/v1/games/13058/game-passes
  * [Example request](https://games.roblox.com/docs#!/GamePasses/get_v1_games_universeId_game_passes)
</details>

<details><summary>Get places of a universe</summary>
 
* api
  * https://api.roblox.com/universes/get-universe-places?universeId=13058&page=1
* develop
  * https://develop.roblox.com/v1/universes/13058/places
    * [Example request](https://develop.roblox.com/docs#!/Universes/get_v1_universes_universeId_places)
</details>

<details><summary>Get aliases of a universe</summary>
 
* https://api.roblox.com/universes/get-aliases?universeId=13058&page=1
</details>

<details><summary>Get symbolic links of a universe</summary>

* https://develop.roblox.com/v1/universes/13058/symbolic-links
</details>

<details><summary>Get badges of a universe</summary>
 
* https://badges.roblox.com/v1/universes/13058/badges
</details>

<details><summary>Get developer products of a universe</summary>
 
* https://api.roblox.com/developerproducts/list?universeId=13058&page=1
</details>

### Place APIs
<details><summary>Get information about a place</summary>

* www 
  * https://www.roblox.com/places/api-get-details?assetId=1818
* games
  * https://games.roblox.com/v1/games/multiget-place-details?placeIds=1818
    * [Example request](https://games.roblox.com/docs#!/Games/get_v1_games_multiget_place_details)
</details>

<details><summary>Get configuration of a place</summary>

* www
  * https://www.roblox.com/places/1818/settings
* develop
  * https://develop.roblox.com/v2/places/1818
    * [Example request](https://develop.roblox.com/docs#!/Places/get_v2_places_placeId)
</details>

<details><summary>Get server instances of a place</summary>

* www
  * https://www.roblox.com/games/getgameinstancesjson?placeId=1818&startindex=0
  * https://www.roblox.com/games/getfriendsgameinstances?placeId=1818&startindex=0
* games
  * https://games.roblox.com/v1/games/1818/servers/Public
    * [Example request](https://games.roblox.com/docs#!/Games/get_v1_games_placeId_servers_serverType)
  * https://games.roblox.com/v1/games/1818/servers/Friend
    * [Example request](https://games.roblox.com/docs#!/Games/get_v1_games_placeId_servers_serverType)
  * https://games.roblox.com/v1/games/1818/servers/VIP
    * [Example request](https://games.roblox.com/docs#!/Games/get_v1_games_placeId_servers_serverType)
</details>

<details><summary>Get information about a user's avatar in a place</summary>

* https://api.roblox.com/v1.1/avatar-fetch?placeId=1818&userId=306209
</details>

<details><summary>Get the universe that a place is assigned to</summary>

* https://api.roblox.com/universes/get-universe-containing-place?placeId=13058
</details>

<details><summary>Get developer products of a place</summary>
 
* https://api.roblox.com/developerproducts/list?placeId=1818&page=1
</details>

### User APIs
<details><summary>Get information and settings about the authenticated user</summary>
 
* www
  * https://www.roblox.com/my/account/json
  * https://www.roblox.com/my/settings/json
  * https://www.roblox.com/mobileapi/userinfo
* api
  * https://api.roblox.com/users/account-info
  * https://api.roblox.com/reference/deviceinfo
</details>

<details><summary>Get the balance of the authenticated user</summary>
 
* api
  * https://api.roblox.com/my/balance
  * https://api.roblox.com/my/platform-currency-budget
    * last used on the Xbox platform
  * http://api.roblox.com/currency/balance
* economy
  * https://economy.roblox.com/v1/users/306209/currency
    * [Example request](https://economy.roblox.com/docs#!/Currency/get_v1_users_userId_currency)
* billing
  * https://billing.roblox.com/v1/credit
</details>

<details><summary>Get restrictions and other settings of the authenticated user</summary>

* www
  * https://www.roblox.com/account/settings/private-message-privacy
  * https://www.roblox.com/account/settings/game-chat-privacy
  * https://www.roblox.com/account/settings/app-chat-privacy
  * https://www.roblox.com/account/settings/follow-me-privacy
  * https://www.roblox.com/account/settings/private-server-invite-privacy
  * https://www.roblox.com/account/settings/account-restrictions
  * https://www.roblox.com/account/settings/account-country
  * https://www.roblox.com/account/settings/settings-groups
* accountsettings
  * https://accountsettings.roblox.com/v1/content-restriction
    * [Example request](https://accountsettings.roblox.com/docs#!/ContentRestriction/get_v1_content_restriction)
  * https://accountsettings.roblox.com/v1/privacy
    * [Example request](https://accountsettings.roblox.com/docs#!/PrivacySettings/get_v1_privacy)
  * https://accountsettings.roblox.com/v1/privacy/info
    * [Example request](https://accountsettings.roblox.com/docs#!/PrivacySettings/get_v1_privacy_info)
  * https://accountsettings.roblox.com/v1/inventory-privacy
    * [Example request](https://accountsettings.roblox.com/docs#!/PrivacySettings/get_v1_inventory_privacy)
  * https://accountsettings.roblox.com/v1/trade-privacy
    * [Example request](https://accountsettings.roblox.com/docs#!/TradeSettings/get_v1_trade_privacy)
  * https://accountsettings.roblox.com/v1/trade-value
    * [Example request](https://accountsettings.roblox.com/docs#!/TradeSettings/get_v1_trade_value)
  * https://accountsettings.roblox.com/v1/themes/user
    * [Example request](https://accountsettings.roblox.com/docs#!/ThemeConfiguration/get_v1_themes_consumerType_consumerId)
* accountinformation
  * https://accountinformation.roblox.com/v1/gender
    * [Example request](https://accountinformation.roblox.com/docs#!/AccountInformation/get_v1_gender)
  * https://accountinformation.roblox.com/v1/phone
    * [Example request](https://accountinformation.roblox.com/docs#!/PhoneInformation/get_v1_phone)
  * https://accountinformation.roblox.com/v1/promotion-channels
    * [Example request](https://accountinformation.roblox.com/docs#!/PromotionChannel/get_v1_promotion_channels)
  * https://accountinformation.roblox.com/v1/birthdate
    * [Example request](https://accountinformation.roblox.com/docs#!/AccountInformation/get_v1_birthdate)
  * https://accountinformation.roblox.com/v1/description
    * [Example request](https://accountinformation.roblox.com/docs#!/AccountInformation/get_v1_description)
* notifications
  * http://notifications.roblox.com/v2/notifications/get-settings
    * [Example request](http://notifications.roblox.com/docs#!/Notifications/get_v2_notifications_get_settings)
</details>

<details><summary>Get information about a user's page</summary>

* https://www.roblox.com/users/profile/profileheader-json?userId=306209
</details>

<details><summary>Get information about a user</summary>
 
* https://users.roblox.com/v1/users/306209
  * [Example request](https://users.roblox.com/docs#!/Users/get_v1_users_userId)
</details>

<details><summary>Get a user's presence</summary>

* http://api.roblox.com/users/306209/onlinestatus
</details>

<details><summary>Get game badges that a user has obtained</summary>
 
* www
  * https://www.roblox.com/users/profile/playerassets-json?assetTypeId=21&userId=306209
* badges
  * https://badges.roblox.com/v1/users/306209/badges
    * [Example request](https://badges.roblox.com/docs#!/Badges/get_v1_users_userId_badges)
  * https://badges.roblox.com/v1/users/306209/badges
    * [Example request](https://badges.roblox.com/docs#!/BadgeAwards/get_v1_users_userId_badges_awarded_dates)
</details>

<details><summary>Get when a user obtained a game badger</summary>

* https://badges.roblox.com/v1/users/306209/badges/awarded-dates?badgeIds=31717745
  * [Example request](https://badges.roblox.com/docs#!/BadgeAwards/get_v1_users_userId_badges_awarded_dates)
</details>

<details><summary>Get roblox badges that a user has obtained</summary>
 
* https://accountinformation.roblox.com/v1/users/306209/roblox-badges
  * [Example request](https://accountinformation.roblox.com/docs#!/RobloxBadges/get_v1_users_userId_roblox_badges)
</details>

<details><summary>Get the collections of a user</summary>

* https://www.roblox.com/users/profile/robloxcollections-json?userId=306209
</details>

<details><summary>Get the inventory of a user</summary>

* www
  * https://www.roblox.com/users/inventory/list-json?assetTypeId=8&userId=306209
* inventory
  * https://inventory.roblox.com/v2/users/306209/inventory?assetTypes=8
    * [Example request](https://inventory.roblox.com/docs#!/Inventory/get_v2_users_userId_inventory)
</details>

# before
<details>
 <summary>pre-rewrite</summary>
 
Deprecated APIs
===============
* [Thumbnail APIs](#thumbnail-apis)
* [Group APIs](#group-apis)
* [Friend APIs](#friend-apis)
* [User APIs](#user-apis)

Search APIs
-----------
#### Search for an audio asset with the search term "pendulum fasten"
https://search.roblox.com/catalog/json?Category=9&Keyword=pendulum%20fasten

Place APIs
----------
#### Get a place's game instances
startIndex must be a multiple of 10
* https://www.roblox.com/games/getgameinstancesjson?placeId=1818&startindex=0
* https://www.roblox.com/games/getfriendsgameinstances?placeId=1818&startindex=0

Thumbnail APIs
--------------

#### Asset Thumbnails
* https://www.roblox.com/Thumbs/RawAsset.ashx?assetId=1818&imageFormat=png&width=60&height=62
  * Returns either `PENDING` or the URL. Also accepts `assetVersionId` in place of `assetId`

* https://www.roblox.com/headshot-thumbnail/json?userId=1&width=180&height=180
  * Returns `{"Url":"https://tr.rbxcdn.com/c3ee609e91804ee2f15c6375355a381a/180/180/AvatarHeadshot/Png","Final":true}`

* https://www.roblox.com/Thumbs/Asset.ashx?width=110&height=110&assetId=1818
  * Redirects to the URL. Also accepts `userAssetId`

* https://assetgame.roblox.com/Thumbs/Asset.asmx/RequestThumbnail_v2?assetId=1818&assetVersionId=0&width=null&height=null&imageFormat=%22Png%22&thumbnailFormatId=296
  * Returns `{"d":{"final":true,"url":"https://t3.rbxcdn.com/5d84cad6c2dda6a98ec94341bd418076"}}`
  
* https://www.roblox.com/Game/Tools/ThumbnailAsset.ashx?aid=1818&fmt=png&wd=420&ht=420
* https://assetgame.roblox.com/Game/Tools/ThumbnailAsset.ashx?assetVersionId=1&fmt=png&wd=420&ht=420
  * Redirects to the URL
  
* http://www.roblox.com/bust-thumbnail/json?userId=2025110&height=180&width=180
  * Returns `{"Url":"https://tr.rbxcdn.com/6402a6d488e255d00967c2c021d29fb0/180/180/AvatarBust/Png","Final":true}`

* https://www.roblox.com/headshot-thumbnail/json?userId=1390724&width=420&height=420
  * Returns `{"Url":"https://tr.rbxcdn.com/cc62e75ca1f869e91fcc2ec1821a3b6e/420/420/AvatarHeadshot/Png","Final":true}`

* https://www.roblox.com/item-thumbnails?params=[{assetId:1818}]
```json
[{
  "id":1818,
  "name": "Classic: Crossroads",
  "url": "https://www.roblox.com/games/1818/Classic-Crossroads",
  "thumbnailFinal": true,
  "thumbnailUrl": "https://t6.rbxcdn.com/eefde6937efa9c8f9f4334266bf4397c",
  "bcOverlayUrl": null,
  "limitedOverlayUrl": null,
  "deadlineOverlayUrl": null,
  "limitedAltText": null,
  "newOverlayUrl": null,
  "imageSize": "large",
  "saleOverlayUrl": null,
  "iosOverlayUrl": null,
  "transparentBackground": false
}]
```

  You can specify the small image size (110x110) with params=[{assetId:1818,imageSize:small}]. Otherwise it will default to `large` (420x420)

  Both of these APIs support JSONP, so this code can be embedded in any web page:
  ```javascript
  $.getJSON('https://www.roblox.com/item-thumbnails?params=[{assetId:1818}]&jsoncallback=?', function(json) {
      alert(json[0].name);
  });
  ```

* https://www.roblox.com/asset-thumbnail/json?assetId=1818&width=160&height=100&format=jpeg
  * Returns `{"Url":"https://t3.rbxcdn.com/c51dd4f8a509b20061a065117450e4c5","Final":true,"SubstitutionType":0}`

#### Avatar Thumbnails
* https://www.roblox.com/Thumbs/Avatar.ashx?username=Shedletsky
  * Redirects to the URL. Also accepts `userId` in place of `username`, and all other parameters can be omitted. If `userId` and `username` are both omitted, will return a ?

* https://www.roblox.com/avatar-thumbnails?params=[{userId:261}]
  * Returns JSON
  ```json
  [{
    "id": 261,
    "name": "Shedletsky",
    "url": "https://www.roblox.com/users/261/profile",
    "thumbnailFinal": true,
    "thumbnailUrl":"https://tr.rbxcdn.com/9ef254566449262ef5dc314724e6f648/60/60/AvatarHeadshot/Png",
    "bcOverlayUrl": null,
    "substitutionType": 0
  }]
  ```

#### Valid Thumbnail Sizes
|                                 | 48x48 | 60x62 | 75x75 | 100x100 | 110x110 | 160x100 | 250x250 | 352x352 | 420x230 | 420x420 |
| ------------------------------- | :---: | :---: | :---: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| /Game/Tools/ThumbnailAsset.ashx |       |       | x     |         | x       |         | x       |         |         | x       |
| /Asset-Thumbnail/Json           | x     | x     | x     | x       | x       | x       | x       | x       | x       | x       |
| /Thumbs/Asset.ashx              | x     | x     | x     | x       | x       | x       | x       | x       | x       | x       |
| /Thumbs/Avatar.ashx             | x     | x     | x     | x       | x       | x       | x       | x       | x       | x       |
| /Thumbs/RawAsset.ashx           | x     | x     | x     | x       | x       | x       | x       | x       | x       | x       |

Group APIs
----

#### Get a thumbnail for a group
 * https://www.roblox.com/group-thumbnails?params=[{groupId:1}]


Product APIs
----

#### Get information about a developer product
 * https://api.roblox.com/Marketplace/ProductDetails?productId=18026036

    ```json
    {
      "TargetId": 2,
      "ProductType": "Developer Product",
      "AssetId": 0,
      "ProductId": 18026036,
      "Name": "85 Candies Pack",
      "Description": null,
      "AssetTypeId": 0,
      "Creator": {
        "Id": 0,
        "Name": null,
        "CreatorType": null,
        "CreatorTargetId": 0
       },
      "IconImageAssetId": 0,
      "Created": "2013-10-16T00:37:38.517Z", 
      "Updated": "2013-10-16T00:37:38.517Z",
      "PriceInRobux": 50,
      "PremiumPriceInRobux": null,
      "PriceInTickets": null,
      "IsNew": false,
      "IsForSale": true,
      "IsPublicDomain": false,
      "IsLimited": false,
      "IsLimitedUnique": false,
      "Remaining": null,
      "MinimumMembershipLevel": 0
    }
    ```

User APIs
----
#### Get a list of places created by a user
* https://www.roblox.com/users/profile/playergames-json?userId=261

    ```json
    {
      "Title": "Games",
      "Games": [
        {
          "CreatorID": 0,
          "CreatorName": "Shedletsky",
          "CreatorAbsoluteUrl": "https://www.roblox.com/users/261/profile",
          "Plays": 0,
          "Price": 0,
          "ProductID":0, 
          "IsOwned": false,
          "IsVotingEnabled": true,
          "TotalUpVotes": 0,
          "TotalDownVotes": 0,
          "TotalBought": 0,
          "UniverseID": 51584661,
          "HasErrorOcurred": false,
          "Favorites": 335,
          "Description": null,
          "GameDetailReferralUrl": "https://www.roblox.com/games/refer?PlaceId=119445489&Position=1&PageType=Profile",
          "Thumbnail": { 
            "Final": true,
            "Url": "https://t7.rbxcdn.com/ebfb8e2733d4e06b32db6c33b2f17ba3",
            "RetryUrl":null,
            "UserId":0,
            "EndpointType":"Avatar"
          },
          "UseDataSrc":  false,
          "IsAsyncThumbnailEnabled": false,
          "GamePageResources": null,
          "Name": "Bloxburg: Global Offensive",
          "PlaceID": 119445489,
          "PlayerCount": 0,
          "ImageId": 0
        }
      ]
    }
    ```

Asset APIs
----------

#### Get an asset's assetVersionId
* http://www.roblox.com/studio/plugins/info?assetId=1818

##### Download various versions of an asset
* https://assetdelivery.roblox.com/v1/asset?id=1818
* https://assetdelivery.roblox.com/v1/asset?id=1818&version=1
* https://assetdelivery.roblox.com/v1/asset?assetVersionId=1
* https://assetdelivery.roblox.com/v1/asset?hash=b3c6b23ff18f48557b823ef5b72a0508

#### User APIs
 * [/Game/GetCurrentUser.ashx](https://assetgame.roblox.com/Game/GetCurrentUser.ashx)
 * [/MobileAPI/UserInfo](https://www.roblox.com/mobileapi/userinfo)

### Roblox Clients
#### Windows
* [Roblox Studio](http://setup.roblox.com/RobloxStudioLauncherBeta.exe)
  * [Roblox Studio - qq](https://setup.rbxcdn.qq.com/RobloxStudioLauncherBetaCJV.exe)
  * [Roblox Studio - sitetest1](http://setup.sitetest1.robloxlabs.com/RobloxStudioLauncherBeta.exe)
  * [Roblox Studio - sitetest2](http://setup.sitetest2.robloxlabs.com/RobloxStudioLauncherBeta.exe)
  * [Roblox Studio - sitetest3](http://setup.sitetest3.robloxlabs.com/RobloxStudioLauncherBeta.exe)
  * [Roblox Studio - gametest1](http://setup.gametest1.robloxlabs.com/RobloxStudioLauncherBeta.exe)
  * [Roblox Studio - gametest2](http://setup.gametest2.robloxlabs.com/RobloxStudioLauncherBeta.exe)
* [Roblox](http://setup.roblox.com/Roblox.exe)
  * [Roblox - sitetest1](http://setup.sitetest1.robloxlabs.com/Roblox.exe)
  * [Roblox - sitetest2](http://setup.sitetest2.robloxlabs.com/Roblox.exe)
  * [Roblox - sitetest3](http://setup.sitetest3.robloxlabs.com/Roblox.exe)
  * [Roblox - gametest1](http://setup.gametest1.robloxlabs.com/Roblox.exe)
  * [Roblox - gametest2](http://setup.gametest2.robloxlabs.com/Roblox.exe)
#### macOS
* [Roblox Studio](http://setup.roblox.com/mac/RobloxStudio.dmg)
* [Roblox](http://setup.roblox.com/mac/Roblox.dmg)
</details>
