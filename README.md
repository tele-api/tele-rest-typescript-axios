## Typescript API client for tele_rest@9.0.0

This TypeScript/JavaScript client uses [axios](https://github.com/axios/axios) and is compatible with the following environments:

Environment
* Node.js
* Webpack
* Browserify

Language level
* ES5 - you must have a Promises/A+ library installed
* ES6

Module system
* CommonJS
* ES6 module system

It can be used in both TypeScript and JavaScript. In TypeScript, the definition will be automatically resolved via `package.json`. ([Reference](https://www.typescriptlang.org/docs/handbook/declaration-files/consumption.html))

### Building

To build and compile the typescript sources to javascript use:
```
npm install
npm run build
```

### Publishing

First build the package then run `npm publish`

### Consuming

navigate to the folder of your consuming project and run one of the following commands.

_published:_

```
npm install tele_rest@9.0.0 --save
```

_unPublished (not recommended):_

```
npm install PATH_TO_GENERATED_PACKAGE --save
```

### Documentation for API Endpoints

All URIs are relative to *https://api.telegram.org/bot123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**postAddStickerToSet**](docs/DefaultApi.md#postaddstickertoset) | **POST** /addStickerToSet | addStickerToSet
*DefaultApi* | [**postAnswerCallbackQuery**](docs/DefaultApi.md#postanswercallbackquery) | **POST** /answerCallbackQuery | answerCallbackQuery
*DefaultApi* | [**postAnswerInlineQuery**](docs/DefaultApi.md#postanswerinlinequery) | **POST** /answerInlineQuery | answerInlineQuery
*DefaultApi* | [**postAnswerPreCheckoutQuery**](docs/DefaultApi.md#postanswerprecheckoutquery) | **POST** /answerPreCheckoutQuery | answerPreCheckoutQuery
*DefaultApi* | [**postAnswerShippingQuery**](docs/DefaultApi.md#postanswershippingquery) | **POST** /answerShippingQuery | answerShippingQuery
*DefaultApi* | [**postAnswerWebAppQuery**](docs/DefaultApi.md#postanswerwebappquery) | **POST** /answerWebAppQuery | answerWebAppQuery
*DefaultApi* | [**postApproveChatJoinRequest**](docs/DefaultApi.md#postapprovechatjoinrequest) | **POST** /approveChatJoinRequest | approveChatJoinRequest
*DefaultApi* | [**postBanChatMember**](docs/DefaultApi.md#postbanchatmember) | **POST** /banChatMember | banChatMember
*DefaultApi* | [**postBanChatSenderChat**](docs/DefaultApi.md#postbanchatsenderchat) | **POST** /banChatSenderChat | banChatSenderChat
*DefaultApi* | [**postClose**](docs/DefaultApi.md#postclose) | **POST** /close | close
*DefaultApi* | [**postCloseForumTopic**](docs/DefaultApi.md#postcloseforumtopic) | **POST** /closeForumTopic | closeForumTopic
*DefaultApi* | [**postCloseGeneralForumTopic**](docs/DefaultApi.md#postclosegeneralforumtopic) | **POST** /closeGeneralForumTopic | closeGeneralForumTopic
*DefaultApi* | [**postConvertGiftToStars**](docs/DefaultApi.md#postconvertgifttostars) | **POST** /convertGiftToStars | convertGiftToStars
*DefaultApi* | [**postCopyMessage**](docs/DefaultApi.md#postcopymessage) | **POST** /copyMessage | copyMessage
*DefaultApi* | [**postCopyMessages**](docs/DefaultApi.md#postcopymessages) | **POST** /copyMessages | copyMessages
*DefaultApi* | [**postCreateChatInviteLink**](docs/DefaultApi.md#postcreatechatinvitelink) | **POST** /createChatInviteLink | createChatInviteLink
*DefaultApi* | [**postCreateChatSubscriptionInviteLink**](docs/DefaultApi.md#postcreatechatsubscriptioninvitelink) | **POST** /createChatSubscriptionInviteLink | createChatSubscriptionInviteLink
*DefaultApi* | [**postCreateForumTopic**](docs/DefaultApi.md#postcreateforumtopic) | **POST** /createForumTopic | createForumTopic
*DefaultApi* | [**postCreateInvoiceLink**](docs/DefaultApi.md#postcreateinvoicelink) | **POST** /createInvoiceLink | createInvoiceLink
*DefaultApi* | [**postCreateNewStickerSet**](docs/DefaultApi.md#postcreatenewstickerset) | **POST** /createNewStickerSet | createNewStickerSet
*DefaultApi* | [**postDeclineChatJoinRequest**](docs/DefaultApi.md#postdeclinechatjoinrequest) | **POST** /declineChatJoinRequest | declineChatJoinRequest
*DefaultApi* | [**postDeleteBusinessMessages**](docs/DefaultApi.md#postdeletebusinessmessages) | **POST** /deleteBusinessMessages | deleteBusinessMessages
*DefaultApi* | [**postDeleteChatPhoto**](docs/DefaultApi.md#postdeletechatphoto) | **POST** /deleteChatPhoto | deleteChatPhoto
*DefaultApi* | [**postDeleteChatStickerSet**](docs/DefaultApi.md#postdeletechatstickerset) | **POST** /deleteChatStickerSet | deleteChatStickerSet
*DefaultApi* | [**postDeleteForumTopic**](docs/DefaultApi.md#postdeleteforumtopic) | **POST** /deleteForumTopic | deleteForumTopic
*DefaultApi* | [**postDeleteMessage**](docs/DefaultApi.md#postdeletemessage) | **POST** /deleteMessage | deleteMessage
*DefaultApi* | [**postDeleteMessages**](docs/DefaultApi.md#postdeletemessages) | **POST** /deleteMessages | deleteMessages
*DefaultApi* | [**postDeleteMyCommands**](docs/DefaultApi.md#postdeletemycommands) | **POST** /deleteMyCommands | deleteMyCommands
*DefaultApi* | [**postDeleteStickerFromSet**](docs/DefaultApi.md#postdeletestickerfromset) | **POST** /deleteStickerFromSet | deleteStickerFromSet
*DefaultApi* | [**postDeleteStickerSet**](docs/DefaultApi.md#postdeletestickerset) | **POST** /deleteStickerSet | deleteStickerSet
*DefaultApi* | [**postDeleteStory**](docs/DefaultApi.md#postdeletestory) | **POST** /deleteStory | deleteStory
*DefaultApi* | [**postDeleteWebhook**](docs/DefaultApi.md#postdeletewebhook) | **POST** /deleteWebhook | deleteWebhook
*DefaultApi* | [**postEditChatInviteLink**](docs/DefaultApi.md#posteditchatinvitelink) | **POST** /editChatInviteLink | editChatInviteLink
*DefaultApi* | [**postEditChatSubscriptionInviteLink**](docs/DefaultApi.md#posteditchatsubscriptioninvitelink) | **POST** /editChatSubscriptionInviteLink | editChatSubscriptionInviteLink
*DefaultApi* | [**postEditForumTopic**](docs/DefaultApi.md#posteditforumtopic) | **POST** /editForumTopic | editForumTopic
*DefaultApi* | [**postEditGeneralForumTopic**](docs/DefaultApi.md#posteditgeneralforumtopic) | **POST** /editGeneralForumTopic | editGeneralForumTopic
*DefaultApi* | [**postEditMessageCaption**](docs/DefaultApi.md#posteditmessagecaption) | **POST** /editMessageCaption | editMessageCaption
*DefaultApi* | [**postEditMessageLiveLocation**](docs/DefaultApi.md#posteditmessagelivelocation) | **POST** /editMessageLiveLocation | editMessageLiveLocation
*DefaultApi* | [**postEditMessageMedia**](docs/DefaultApi.md#posteditmessagemedia) | **POST** /editMessageMedia | editMessageMedia
*DefaultApi* | [**postEditMessageReplyMarkup**](docs/DefaultApi.md#posteditmessagereplymarkup) | **POST** /editMessageReplyMarkup | editMessageReplyMarkup
*DefaultApi* | [**postEditMessageText**](docs/DefaultApi.md#posteditmessagetext) | **POST** /editMessageText | editMessageText
*DefaultApi* | [**postEditStory**](docs/DefaultApi.md#posteditstory) | **POST** /editStory | editStory
*DefaultApi* | [**postEditUserStarSubscription**](docs/DefaultApi.md#postedituserstarsubscription) | **POST** /editUserStarSubscription | editUserStarSubscription
*DefaultApi* | [**postExportChatInviteLink**](docs/DefaultApi.md#postexportchatinvitelink) | **POST** /exportChatInviteLink | exportChatInviteLink
*DefaultApi* | [**postForwardMessage**](docs/DefaultApi.md#postforwardmessage) | **POST** /forwardMessage | forwardMessage
*DefaultApi* | [**postForwardMessages**](docs/DefaultApi.md#postforwardmessages) | **POST** /forwardMessages | forwardMessages
*DefaultApi* | [**postGetAvailableGifts**](docs/DefaultApi.md#postgetavailablegifts) | **POST** /getAvailableGifts | getAvailableGifts
*DefaultApi* | [**postGetBusinessAccountGifts**](docs/DefaultApi.md#postgetbusinessaccountgifts) | **POST** /getBusinessAccountGifts | getBusinessAccountGifts
*DefaultApi* | [**postGetBusinessAccountStarBalance**](docs/DefaultApi.md#postgetbusinessaccountstarbalance) | **POST** /getBusinessAccountStarBalance | getBusinessAccountStarBalance
*DefaultApi* | [**postGetBusinessConnection**](docs/DefaultApi.md#postgetbusinessconnection) | **POST** /getBusinessConnection | getBusinessConnection
*DefaultApi* | [**postGetChat**](docs/DefaultApi.md#postgetchat) | **POST** /getChat | getChat
*DefaultApi* | [**postGetChatAdministrators**](docs/DefaultApi.md#postgetchatadministrators) | **POST** /getChatAdministrators | getChatAdministrators
*DefaultApi* | [**postGetChatMember**](docs/DefaultApi.md#postgetchatmember) | **POST** /getChatMember | getChatMember
*DefaultApi* | [**postGetChatMemberCount**](docs/DefaultApi.md#postgetchatmembercount) | **POST** /getChatMemberCount | getChatMemberCount
*DefaultApi* | [**postGetChatMenuButton**](docs/DefaultApi.md#postgetchatmenubutton) | **POST** /getChatMenuButton | getChatMenuButton
*DefaultApi* | [**postGetCustomEmojiStickers**](docs/DefaultApi.md#postgetcustomemojistickers) | **POST** /getCustomEmojiStickers | getCustomEmojiStickers
*DefaultApi* | [**postGetFile**](docs/DefaultApi.md#postgetfile) | **POST** /getFile | getFile
*DefaultApi* | [**postGetForumTopicIconStickers**](docs/DefaultApi.md#postgetforumtopiciconstickers) | **POST** /getForumTopicIconStickers | getForumTopicIconStickers
*DefaultApi* | [**postGetGameHighScores**](docs/DefaultApi.md#postgetgamehighscores) | **POST** /getGameHighScores | getGameHighScores
*DefaultApi* | [**postGetMe**](docs/DefaultApi.md#postgetme) | **POST** /getMe | getMe
*DefaultApi* | [**postGetMyCommands**](docs/DefaultApi.md#postgetmycommands) | **POST** /getMyCommands | getMyCommands
*DefaultApi* | [**postGetMyDefaultAdministratorRights**](docs/DefaultApi.md#postgetmydefaultadministratorrights) | **POST** /getMyDefaultAdministratorRights | getMyDefaultAdministratorRights
*DefaultApi* | [**postGetMyDescription**](docs/DefaultApi.md#postgetmydescription) | **POST** /getMyDescription | getMyDescription
*DefaultApi* | [**postGetMyName**](docs/DefaultApi.md#postgetmyname) | **POST** /getMyName | getMyName
*DefaultApi* | [**postGetMyShortDescription**](docs/DefaultApi.md#postgetmyshortdescription) | **POST** /getMyShortDescription | getMyShortDescription
*DefaultApi* | [**postGetStarTransactions**](docs/DefaultApi.md#postgetstartransactions) | **POST** /getStarTransactions | getStarTransactions
*DefaultApi* | [**postGetStickerSet**](docs/DefaultApi.md#postgetstickerset) | **POST** /getStickerSet | getStickerSet
*DefaultApi* | [**postGetUpdates**](docs/DefaultApi.md#postgetupdates) | **POST** /getUpdates | getUpdates
*DefaultApi* | [**postGetUserChatBoosts**](docs/DefaultApi.md#postgetuserchatboosts) | **POST** /getUserChatBoosts | getUserChatBoosts
*DefaultApi* | [**postGetUserProfilePhotos**](docs/DefaultApi.md#postgetuserprofilephotos) | **POST** /getUserProfilePhotos | getUserProfilePhotos
*DefaultApi* | [**postGetWebhookInfo**](docs/DefaultApi.md#postgetwebhookinfo) | **POST** /getWebhookInfo | getWebhookInfo
*DefaultApi* | [**postGiftPremiumSubscription**](docs/DefaultApi.md#postgiftpremiumsubscription) | **POST** /giftPremiumSubscription | giftPremiumSubscription
*DefaultApi* | [**postHideGeneralForumTopic**](docs/DefaultApi.md#posthidegeneralforumtopic) | **POST** /hideGeneralForumTopic | hideGeneralForumTopic
*DefaultApi* | [**postLeaveChat**](docs/DefaultApi.md#postleavechat) | **POST** /leaveChat | leaveChat
*DefaultApi* | [**postLogOut**](docs/DefaultApi.md#postlogout) | **POST** /logOut | logOut
*DefaultApi* | [**postPinChatMessage**](docs/DefaultApi.md#postpinchatmessage) | **POST** /pinChatMessage | pinChatMessage
*DefaultApi* | [**postPostStory**](docs/DefaultApi.md#postpoststory) | **POST** /postStory | postStory
*DefaultApi* | [**postPromoteChatMember**](docs/DefaultApi.md#postpromotechatmember) | **POST** /promoteChatMember | promoteChatMember
*DefaultApi* | [**postReadBusinessMessage**](docs/DefaultApi.md#postreadbusinessmessage) | **POST** /readBusinessMessage | readBusinessMessage
*DefaultApi* | [**postRefundStarPayment**](docs/DefaultApi.md#postrefundstarpayment) | **POST** /refundStarPayment | refundStarPayment
*DefaultApi* | [**postRemoveBusinessAccountProfilePhoto**](docs/DefaultApi.md#postremovebusinessaccountprofilephoto) | **POST** /removeBusinessAccountProfilePhoto | removeBusinessAccountProfilePhoto
*DefaultApi* | [**postRemoveChatVerification**](docs/DefaultApi.md#postremovechatverification) | **POST** /removeChatVerification | removeChatVerification
*DefaultApi* | [**postRemoveUserVerification**](docs/DefaultApi.md#postremoveuserverification) | **POST** /removeUserVerification | removeUserVerification
*DefaultApi* | [**postReopenForumTopic**](docs/DefaultApi.md#postreopenforumtopic) | **POST** /reopenForumTopic | reopenForumTopic
*DefaultApi* | [**postReopenGeneralForumTopic**](docs/DefaultApi.md#postreopengeneralforumtopic) | **POST** /reopenGeneralForumTopic | reopenGeneralForumTopic
*DefaultApi* | [**postReplaceStickerInSet**](docs/DefaultApi.md#postreplacestickerinset) | **POST** /replaceStickerInSet | replaceStickerInSet
*DefaultApi* | [**postRestrictChatMember**](docs/DefaultApi.md#postrestrictchatmember) | **POST** /restrictChatMember | restrictChatMember
*DefaultApi* | [**postRevokeChatInviteLink**](docs/DefaultApi.md#postrevokechatinvitelink) | **POST** /revokeChatInviteLink | revokeChatInviteLink
*DefaultApi* | [**postSavePreparedInlineMessage**](docs/DefaultApi.md#postsavepreparedinlinemessage) | **POST** /savePreparedInlineMessage | savePreparedInlineMessage
*DefaultApi* | [**postSendAnimation**](docs/DefaultApi.md#postsendanimation) | **POST** /sendAnimation | sendAnimation
*DefaultApi* | [**postSendAudio**](docs/DefaultApi.md#postsendaudio) | **POST** /sendAudio | sendAudio
*DefaultApi* | [**postSendChatAction**](docs/DefaultApi.md#postsendchataction) | **POST** /sendChatAction | sendChatAction
*DefaultApi* | [**postSendContact**](docs/DefaultApi.md#postsendcontact) | **POST** /sendContact | sendContact
*DefaultApi* | [**postSendDice**](docs/DefaultApi.md#postsenddice) | **POST** /sendDice | sendDice
*DefaultApi* | [**postSendDocument**](docs/DefaultApi.md#postsenddocument) | **POST** /sendDocument | sendDocument
*DefaultApi* | [**postSendGame**](docs/DefaultApi.md#postsendgame) | **POST** /sendGame | sendGame
*DefaultApi* | [**postSendGift**](docs/DefaultApi.md#postsendgift) | **POST** /sendGift | sendGift
*DefaultApi* | [**postSendInvoice**](docs/DefaultApi.md#postsendinvoice) | **POST** /sendInvoice | sendInvoice
*DefaultApi* | [**postSendLocation**](docs/DefaultApi.md#postsendlocation) | **POST** /sendLocation | sendLocation
*DefaultApi* | [**postSendMediaGroup**](docs/DefaultApi.md#postsendmediagroup) | **POST** /sendMediaGroup | sendMediaGroup
*DefaultApi* | [**postSendMessage**](docs/DefaultApi.md#postsendmessage) | **POST** /sendMessage | sendMessage
*DefaultApi* | [**postSendPaidMedia**](docs/DefaultApi.md#postsendpaidmedia) | **POST** /sendPaidMedia | sendPaidMedia
*DefaultApi* | [**postSendPhoto**](docs/DefaultApi.md#postsendphoto) | **POST** /sendPhoto | sendPhoto
*DefaultApi* | [**postSendPoll**](docs/DefaultApi.md#postsendpoll) | **POST** /sendPoll | sendPoll
*DefaultApi* | [**postSendSticker**](docs/DefaultApi.md#postsendsticker) | **POST** /sendSticker | sendSticker
*DefaultApi* | [**postSendVenue**](docs/DefaultApi.md#postsendvenue) | **POST** /sendVenue | sendVenue
*DefaultApi* | [**postSendVideo**](docs/DefaultApi.md#postsendvideo) | **POST** /sendVideo | sendVideo
*DefaultApi* | [**postSendVideoNote**](docs/DefaultApi.md#postsendvideonote) | **POST** /sendVideoNote | sendVideoNote
*DefaultApi* | [**postSendVoice**](docs/DefaultApi.md#postsendvoice) | **POST** /sendVoice | sendVoice
*DefaultApi* | [**postSetBusinessAccountBio**](docs/DefaultApi.md#postsetbusinessaccountbio) | **POST** /setBusinessAccountBio | setBusinessAccountBio
*DefaultApi* | [**postSetBusinessAccountGiftSettings**](docs/DefaultApi.md#postsetbusinessaccountgiftsettings) | **POST** /setBusinessAccountGiftSettings | setBusinessAccountGiftSettings
*DefaultApi* | [**postSetBusinessAccountName**](docs/DefaultApi.md#postsetbusinessaccountname) | **POST** /setBusinessAccountName | setBusinessAccountName
*DefaultApi* | [**postSetBusinessAccountProfilePhoto**](docs/DefaultApi.md#postsetbusinessaccountprofilephoto) | **POST** /setBusinessAccountProfilePhoto | setBusinessAccountProfilePhoto
*DefaultApi* | [**postSetBusinessAccountUsername**](docs/DefaultApi.md#postsetbusinessaccountusername) | **POST** /setBusinessAccountUsername | setBusinessAccountUsername
*DefaultApi* | [**postSetChatAdministratorCustomTitle**](docs/DefaultApi.md#postsetchatadministratorcustomtitle) | **POST** /setChatAdministratorCustomTitle | setChatAdministratorCustomTitle
*DefaultApi* | [**postSetChatDescription**](docs/DefaultApi.md#postsetchatdescription) | **POST** /setChatDescription | setChatDescription
*DefaultApi* | [**postSetChatMenuButton**](docs/DefaultApi.md#postsetchatmenubutton) | **POST** /setChatMenuButton | setChatMenuButton
*DefaultApi* | [**postSetChatPermissions**](docs/DefaultApi.md#postsetchatpermissions) | **POST** /setChatPermissions | setChatPermissions
*DefaultApi* | [**postSetChatPhoto**](docs/DefaultApi.md#postsetchatphoto) | **POST** /setChatPhoto | setChatPhoto
*DefaultApi* | [**postSetChatStickerSet**](docs/DefaultApi.md#postsetchatstickerset) | **POST** /setChatStickerSet | setChatStickerSet
*DefaultApi* | [**postSetChatTitle**](docs/DefaultApi.md#postsetchattitle) | **POST** /setChatTitle | setChatTitle
*DefaultApi* | [**postSetCustomEmojiStickerSetThumbnail**](docs/DefaultApi.md#postsetcustomemojistickersetthumbnail) | **POST** /setCustomEmojiStickerSetThumbnail | setCustomEmojiStickerSetThumbnail
*DefaultApi* | [**postSetGameScore**](docs/DefaultApi.md#postsetgamescore) | **POST** /setGameScore | setGameScore
*DefaultApi* | [**postSetMessageReaction**](docs/DefaultApi.md#postsetmessagereaction) | **POST** /setMessageReaction | setMessageReaction
*DefaultApi* | [**postSetMyCommands**](docs/DefaultApi.md#postsetmycommands) | **POST** /setMyCommands | setMyCommands
*DefaultApi* | [**postSetMyDefaultAdministratorRights**](docs/DefaultApi.md#postsetmydefaultadministratorrights) | **POST** /setMyDefaultAdministratorRights | setMyDefaultAdministratorRights
*DefaultApi* | [**postSetMyDescription**](docs/DefaultApi.md#postsetmydescription) | **POST** /setMyDescription | setMyDescription
*DefaultApi* | [**postSetMyName**](docs/DefaultApi.md#postsetmyname) | **POST** /setMyName | setMyName
*DefaultApi* | [**postSetMyShortDescription**](docs/DefaultApi.md#postsetmyshortdescription) | **POST** /setMyShortDescription | setMyShortDescription
*DefaultApi* | [**postSetPassportDataErrors**](docs/DefaultApi.md#postsetpassportdataerrors) | **POST** /setPassportDataErrors | setPassportDataErrors
*DefaultApi* | [**postSetStickerEmojiList**](docs/DefaultApi.md#postsetstickeremojilist) | **POST** /setStickerEmojiList | setStickerEmojiList
*DefaultApi* | [**postSetStickerKeywords**](docs/DefaultApi.md#postsetstickerkeywords) | **POST** /setStickerKeywords | setStickerKeywords
*DefaultApi* | [**postSetStickerMaskPosition**](docs/DefaultApi.md#postsetstickermaskposition) | **POST** /setStickerMaskPosition | setStickerMaskPosition
*DefaultApi* | [**postSetStickerPositionInSet**](docs/DefaultApi.md#postsetstickerpositioninset) | **POST** /setStickerPositionInSet | setStickerPositionInSet
*DefaultApi* | [**postSetStickerSetThumbnail**](docs/DefaultApi.md#postsetstickersetthumbnail) | **POST** /setStickerSetThumbnail | setStickerSetThumbnail
*DefaultApi* | [**postSetStickerSetTitle**](docs/DefaultApi.md#postsetstickersettitle) | **POST** /setStickerSetTitle | setStickerSetTitle
*DefaultApi* | [**postSetUserEmojiStatus**](docs/DefaultApi.md#postsetuseremojistatus) | **POST** /setUserEmojiStatus | setUserEmojiStatus
*DefaultApi* | [**postSetWebhook**](docs/DefaultApi.md#postsetwebhook) | **POST** /setWebhook | setWebhook
*DefaultApi* | [**postStopMessageLiveLocation**](docs/DefaultApi.md#poststopmessagelivelocation) | **POST** /stopMessageLiveLocation | stopMessageLiveLocation
*DefaultApi* | [**postStopPoll**](docs/DefaultApi.md#poststoppoll) | **POST** /stopPoll | stopPoll
*DefaultApi* | [**postTransferBusinessAccountStars**](docs/DefaultApi.md#posttransferbusinessaccountstars) | **POST** /transferBusinessAccountStars | transferBusinessAccountStars
*DefaultApi* | [**postTransferGift**](docs/DefaultApi.md#posttransfergift) | **POST** /transferGift | transferGift
*DefaultApi* | [**postUnbanChatMember**](docs/DefaultApi.md#postunbanchatmember) | **POST** /unbanChatMember | unbanChatMember
*DefaultApi* | [**postUnbanChatSenderChat**](docs/DefaultApi.md#postunbanchatsenderchat) | **POST** /unbanChatSenderChat | unbanChatSenderChat
*DefaultApi* | [**postUnhideGeneralForumTopic**](docs/DefaultApi.md#postunhidegeneralforumtopic) | **POST** /unhideGeneralForumTopic | unhideGeneralForumTopic
*DefaultApi* | [**postUnpinAllChatMessages**](docs/DefaultApi.md#postunpinallchatmessages) | **POST** /unpinAllChatMessages | unpinAllChatMessages
*DefaultApi* | [**postUnpinAllForumTopicMessages**](docs/DefaultApi.md#postunpinallforumtopicmessages) | **POST** /unpinAllForumTopicMessages | unpinAllForumTopicMessages
*DefaultApi* | [**postUnpinAllGeneralForumTopicMessages**](docs/DefaultApi.md#postunpinallgeneralforumtopicmessages) | **POST** /unpinAllGeneralForumTopicMessages | unpinAllGeneralForumTopicMessages
*DefaultApi* | [**postUnpinChatMessage**](docs/DefaultApi.md#postunpinchatmessage) | **POST** /unpinChatMessage | unpinChatMessage
*DefaultApi* | [**postUpgradeGift**](docs/DefaultApi.md#postupgradegift) | **POST** /upgradeGift | upgradeGift
*DefaultApi* | [**postUploadStickerFile**](docs/DefaultApi.md#postuploadstickerfile) | **POST** /uploadStickerFile | uploadStickerFile
*DefaultApi* | [**postVerifyChat**](docs/DefaultApi.md#postverifychat) | **POST** /verifyChat | verifyChat
*DefaultApi* | [**postVerifyUser**](docs/DefaultApi.md#postverifyuser) | **POST** /verifyUser | verifyUser


### Documentation For Models

 - [AcceptedGiftTypes](docs/AcceptedGiftTypes.md)
 - [AffiliateInfo](docs/AffiliateInfo.md)
 - [Animation](docs/Animation.md)
 - [Audio](docs/Audio.md)
 - [BackgroundFill](docs/BackgroundFill.md)
 - [BackgroundFillFreeformGradient](docs/BackgroundFillFreeformGradient.md)
 - [BackgroundFillGradient](docs/BackgroundFillGradient.md)
 - [BackgroundFillSolid](docs/BackgroundFillSolid.md)
 - [BackgroundType](docs/BackgroundType.md)
 - [BackgroundTypeChatTheme](docs/BackgroundTypeChatTheme.md)
 - [BackgroundTypeFill](docs/BackgroundTypeFill.md)
 - [BackgroundTypePattern](docs/BackgroundTypePattern.md)
 - [BackgroundTypeWallpaper](docs/BackgroundTypeWallpaper.md)
 - [Birthdate](docs/Birthdate.md)
 - [BotCommand](docs/BotCommand.md)
 - [BotCommandScope](docs/BotCommandScope.md)
 - [BotCommandScopeAllChatAdministrators](docs/BotCommandScopeAllChatAdministrators.md)
 - [BotCommandScopeAllGroupChats](docs/BotCommandScopeAllGroupChats.md)
 - [BotCommandScopeAllPrivateChats](docs/BotCommandScopeAllPrivateChats.md)
 - [BotCommandScopeChat](docs/BotCommandScopeChat.md)
 - [BotCommandScopeChatAdministrators](docs/BotCommandScopeChatAdministrators.md)
 - [BotCommandScopeChatMember](docs/BotCommandScopeChatMember.md)
 - [BotCommandScopeDefault](docs/BotCommandScopeDefault.md)
 - [BotDescription](docs/BotDescription.md)
 - [BotName](docs/BotName.md)
 - [BotShortDescription](docs/BotShortDescription.md)
 - [BusinessBotRights](docs/BusinessBotRights.md)
 - [BusinessConnection](docs/BusinessConnection.md)
 - [BusinessIntro](docs/BusinessIntro.md)
 - [BusinessLocation](docs/BusinessLocation.md)
 - [BusinessMessagesDeleted](docs/BusinessMessagesDeleted.md)
 - [BusinessOpeningHours](docs/BusinessOpeningHours.md)
 - [BusinessOpeningHoursInterval](docs/BusinessOpeningHoursInterval.md)
 - [CallbackQuery](docs/CallbackQuery.md)
 - [Chat](docs/Chat.md)
 - [ChatAdministratorRights](docs/ChatAdministratorRights.md)
 - [ChatBackground](docs/ChatBackground.md)
 - [ChatBoost](docs/ChatBoost.md)
 - [ChatBoostAdded](docs/ChatBoostAdded.md)
 - [ChatBoostRemoved](docs/ChatBoostRemoved.md)
 - [ChatBoostSource](docs/ChatBoostSource.md)
 - [ChatBoostSourceGiftCode](docs/ChatBoostSourceGiftCode.md)
 - [ChatBoostSourceGiveaway](docs/ChatBoostSourceGiveaway.md)
 - [ChatBoostSourcePremium](docs/ChatBoostSourcePremium.md)
 - [ChatBoostUpdated](docs/ChatBoostUpdated.md)
 - [ChatFullInfo](docs/ChatFullInfo.md)
 - [ChatInviteLink](docs/ChatInviteLink.md)
 - [ChatJoinRequest](docs/ChatJoinRequest.md)
 - [ChatLocation](docs/ChatLocation.md)
 - [ChatMember](docs/ChatMember.md)
 - [ChatMemberAdministrator](docs/ChatMemberAdministrator.md)
 - [ChatMemberBanned](docs/ChatMemberBanned.md)
 - [ChatMemberLeft](docs/ChatMemberLeft.md)
 - [ChatMemberMember](docs/ChatMemberMember.md)
 - [ChatMemberOwner](docs/ChatMemberOwner.md)
 - [ChatMemberRestricted](docs/ChatMemberRestricted.md)
 - [ChatMemberUpdated](docs/ChatMemberUpdated.md)
 - [ChatPermissions](docs/ChatPermissions.md)
 - [ChatPhoto](docs/ChatPhoto.md)
 - [ChatShared](docs/ChatShared.md)
 - [ChosenInlineResult](docs/ChosenInlineResult.md)
 - [Contact](docs/Contact.md)
 - [CopyTextButton](docs/CopyTextButton.md)
 - [Dice](docs/Dice.md)
 - [Document](docs/Document.md)
 - [EncryptedCredentials](docs/EncryptedCredentials.md)
 - [EncryptedPassportElement](docs/EncryptedPassportElement.md)
 - [ExternalReplyInfo](docs/ExternalReplyInfo.md)
 - [ForceReply](docs/ForceReply.md)
 - [ForumTopic](docs/ForumTopic.md)
 - [ForumTopicCreated](docs/ForumTopicCreated.md)
 - [ForumTopicEdited](docs/ForumTopicEdited.md)
 - [Game](docs/Game.md)
 - [GameHighScore](docs/GameHighScore.md)
 - [Gift](docs/Gift.md)
 - [GiftInfo](docs/GiftInfo.md)
 - [Gifts](docs/Gifts.md)
 - [Giveaway](docs/Giveaway.md)
 - [GiveawayCompleted](docs/GiveawayCompleted.md)
 - [GiveawayCreated](docs/GiveawayCreated.md)
 - [GiveawayWinners](docs/GiveawayWinners.md)
 - [InaccessibleMessage](docs/InaccessibleMessage.md)
 - [InlineKeyboardButton](docs/InlineKeyboardButton.md)
 - [InlineKeyboardMarkup](docs/InlineKeyboardMarkup.md)
 - [InlineQuery](docs/InlineQuery.md)
 - [InlineQueryResult](docs/InlineQueryResult.md)
 - [InlineQueryResultArticle](docs/InlineQueryResultArticle.md)
 - [InlineQueryResultAudio](docs/InlineQueryResultAudio.md)
 - [InlineQueryResultCachedAudio](docs/InlineQueryResultCachedAudio.md)
 - [InlineQueryResultCachedDocument](docs/InlineQueryResultCachedDocument.md)
 - [InlineQueryResultCachedGif](docs/InlineQueryResultCachedGif.md)
 - [InlineQueryResultCachedMpeg4Gif](docs/InlineQueryResultCachedMpeg4Gif.md)
 - [InlineQueryResultCachedPhoto](docs/InlineQueryResultCachedPhoto.md)
 - [InlineQueryResultCachedSticker](docs/InlineQueryResultCachedSticker.md)
 - [InlineQueryResultCachedVideo](docs/InlineQueryResultCachedVideo.md)
 - [InlineQueryResultCachedVoice](docs/InlineQueryResultCachedVoice.md)
 - [InlineQueryResultContact](docs/InlineQueryResultContact.md)
 - [InlineQueryResultDocument](docs/InlineQueryResultDocument.md)
 - [InlineQueryResultGame](docs/InlineQueryResultGame.md)
 - [InlineQueryResultGif](docs/InlineQueryResultGif.md)
 - [InlineQueryResultLocation](docs/InlineQueryResultLocation.md)
 - [InlineQueryResultMpeg4Gif](docs/InlineQueryResultMpeg4Gif.md)
 - [InlineQueryResultPhoto](docs/InlineQueryResultPhoto.md)
 - [InlineQueryResultVenue](docs/InlineQueryResultVenue.md)
 - [InlineQueryResultVideo](docs/InlineQueryResultVideo.md)
 - [InlineQueryResultVoice](docs/InlineQueryResultVoice.md)
 - [InlineQueryResultsButton](docs/InlineQueryResultsButton.md)
 - [InputContactMessageContent](docs/InputContactMessageContent.md)
 - [InputInvoiceMessageContent](docs/InputInvoiceMessageContent.md)
 - [InputLocationMessageContent](docs/InputLocationMessageContent.md)
 - [InputMedia](docs/InputMedia.md)
 - [InputMediaAnimation](docs/InputMediaAnimation.md)
 - [InputMediaAudio](docs/InputMediaAudio.md)
 - [InputMediaDocument](docs/InputMediaDocument.md)
 - [InputMediaPhoto](docs/InputMediaPhoto.md)
 - [InputMediaVideo](docs/InputMediaVideo.md)
 - [InputMessageContent](docs/InputMessageContent.md)
 - [InputPaidMedia](docs/InputPaidMedia.md)
 - [InputPaidMediaPhoto](docs/InputPaidMediaPhoto.md)
 - [InputPaidMediaVideo](docs/InputPaidMediaVideo.md)
 - [InputPollOption](docs/InputPollOption.md)
 - [InputProfilePhoto](docs/InputProfilePhoto.md)
 - [InputProfilePhotoAnimated](docs/InputProfilePhotoAnimated.md)
 - [InputProfilePhotoStatic](docs/InputProfilePhotoStatic.md)
 - [InputSticker](docs/InputSticker.md)
 - [InputStoryContent](docs/InputStoryContent.md)
 - [InputStoryContentPhoto](docs/InputStoryContentPhoto.md)
 - [InputStoryContentVideo](docs/InputStoryContentVideo.md)
 - [InputTextMessageContent](docs/InputTextMessageContent.md)
 - [InputVenueMessageContent](docs/InputVenueMessageContent.md)
 - [Invoice](docs/Invoice.md)
 - [KeyboardButton](docs/KeyboardButton.md)
 - [KeyboardButtonPollType](docs/KeyboardButtonPollType.md)
 - [KeyboardButtonRequestChat](docs/KeyboardButtonRequestChat.md)
 - [KeyboardButtonRequestUsers](docs/KeyboardButtonRequestUsers.md)
 - [LabeledPrice](docs/LabeledPrice.md)
 - [LinkPreviewOptions](docs/LinkPreviewOptions.md)
 - [Location](docs/Location.md)
 - [LocationAddress](docs/LocationAddress.md)
 - [LoginUrl](docs/LoginUrl.md)
 - [MaskPosition](docs/MaskPosition.md)
 - [MaybeInaccessibleMessage](docs/MaybeInaccessibleMessage.md)
 - [MenuButton](docs/MenuButton.md)
 - [MenuButtonCommands](docs/MenuButtonCommands.md)
 - [MenuButtonDefault](docs/MenuButtonDefault.md)
 - [MenuButtonWebApp](docs/MenuButtonWebApp.md)
 - [Message](docs/Message.md)
 - [MessageAutoDeleteTimerChanged](docs/MessageAutoDeleteTimerChanged.md)
 - [MessageEntity](docs/MessageEntity.md)
 - [MessageId](docs/MessageId.md)
 - [MessageOrigin](docs/MessageOrigin.md)
 - [MessageOriginChannel](docs/MessageOriginChannel.md)
 - [MessageOriginChat](docs/MessageOriginChat.md)
 - [MessageOriginHiddenUser](docs/MessageOriginHiddenUser.md)
 - [MessageOriginUser](docs/MessageOriginUser.md)
 - [MessageReactionCountUpdated](docs/MessageReactionCountUpdated.md)
 - [MessageReactionUpdated](docs/MessageReactionUpdated.md)
 - [ModelError](docs/ModelError.md)
 - [ModelFile](docs/ModelFile.md)
 - [OrderInfo](docs/OrderInfo.md)
 - [OwnedGift](docs/OwnedGift.md)
 - [OwnedGiftRegular](docs/OwnedGiftRegular.md)
 - [OwnedGiftUnique](docs/OwnedGiftUnique.md)
 - [OwnedGifts](docs/OwnedGifts.md)
 - [PaidMedia](docs/PaidMedia.md)
 - [PaidMediaInfo](docs/PaidMediaInfo.md)
 - [PaidMediaPhoto](docs/PaidMediaPhoto.md)
 - [PaidMediaPreview](docs/PaidMediaPreview.md)
 - [PaidMediaPurchased](docs/PaidMediaPurchased.md)
 - [PaidMediaVideo](docs/PaidMediaVideo.md)
 - [PaidMessagePriceChanged](docs/PaidMessagePriceChanged.md)
 - [PassportData](docs/PassportData.md)
 - [PassportElementError](docs/PassportElementError.md)
 - [PassportElementErrorDataField](docs/PassportElementErrorDataField.md)
 - [PassportElementErrorFile](docs/PassportElementErrorFile.md)
 - [PassportElementErrorFiles](docs/PassportElementErrorFiles.md)
 - [PassportElementErrorFrontSide](docs/PassportElementErrorFrontSide.md)
 - [PassportElementErrorReverseSide](docs/PassportElementErrorReverseSide.md)
 - [PassportElementErrorSelfie](docs/PassportElementErrorSelfie.md)
 - [PassportElementErrorTranslationFile](docs/PassportElementErrorTranslationFile.md)
 - [PassportElementErrorTranslationFiles](docs/PassportElementErrorTranslationFiles.md)
 - [PassportElementErrorUnspecified](docs/PassportElementErrorUnspecified.md)
 - [PassportFile](docs/PassportFile.md)
 - [PhotoSize](docs/PhotoSize.md)
 - [Poll](docs/Poll.md)
 - [PollAnswer](docs/PollAnswer.md)
 - [PollOption](docs/PollOption.md)
 - [PostAnswerCallbackQueryRequest](docs/PostAnswerCallbackQueryRequest.md)
 - [PostAnswerInlineQueryRequest](docs/PostAnswerInlineQueryRequest.md)
 - [PostAnswerPreCheckoutQueryRequest](docs/PostAnswerPreCheckoutQueryRequest.md)
 - [PostAnswerShippingQueryRequest](docs/PostAnswerShippingQueryRequest.md)
 - [PostAnswerWebAppQuery200Response](docs/PostAnswerWebAppQuery200Response.md)
 - [PostAnswerWebAppQueryRequest](docs/PostAnswerWebAppQueryRequest.md)
 - [PostApproveChatJoinRequestRequest](docs/PostApproveChatJoinRequestRequest.md)
 - [PostBanChatMemberRequest](docs/PostBanChatMemberRequest.md)
 - [PostBanChatMemberRequestChatId](docs/PostBanChatMemberRequestChatId.md)
 - [PostBanChatSenderChatRequest](docs/PostBanChatSenderChatRequest.md)
 - [PostCloseForumTopicRequest](docs/PostCloseForumTopicRequest.md)
 - [PostConvertGiftToStarsRequest](docs/PostConvertGiftToStarsRequest.md)
 - [PostCopyMessage200Response](docs/PostCopyMessage200Response.md)
 - [PostCopyMessageRequest](docs/PostCopyMessageRequest.md)
 - [PostCopyMessagesRequest](docs/PostCopyMessagesRequest.md)
 - [PostCreateChatInviteLink200Response](docs/PostCreateChatInviteLink200Response.md)
 - [PostCreateChatInviteLinkRequest](docs/PostCreateChatInviteLinkRequest.md)
 - [PostCreateChatSubscriptionInviteLinkRequest](docs/PostCreateChatSubscriptionInviteLinkRequest.md)
 - [PostCreateChatSubscriptionInviteLinkRequestChatId](docs/PostCreateChatSubscriptionInviteLinkRequestChatId.md)
 - [PostCreateForumTopic200Response](docs/PostCreateForumTopic200Response.md)
 - [PostCreateForumTopicRequest](docs/PostCreateForumTopicRequest.md)
 - [PostCreateInvoiceLinkRequest](docs/PostCreateInvoiceLinkRequest.md)
 - [PostDeleteBusinessMessagesRequest](docs/PostDeleteBusinessMessagesRequest.md)
 - [PostDeleteChatStickerSetRequest](docs/PostDeleteChatStickerSetRequest.md)
 - [PostDeleteMessageRequest](docs/PostDeleteMessageRequest.md)
 - [PostDeleteMessagesRequest](docs/PostDeleteMessagesRequest.md)
 - [PostDeleteMyCommandsRequest](docs/PostDeleteMyCommandsRequest.md)
 - [PostDeleteStickerFromSetRequest](docs/PostDeleteStickerFromSetRequest.md)
 - [PostDeleteStickerSetRequest](docs/PostDeleteStickerSetRequest.md)
 - [PostDeleteStoryRequest](docs/PostDeleteStoryRequest.md)
 - [PostDeleteWebhookRequest](docs/PostDeleteWebhookRequest.md)
 - [PostEditChatInviteLinkRequest](docs/PostEditChatInviteLinkRequest.md)
 - [PostEditChatSubscriptionInviteLinkRequest](docs/PostEditChatSubscriptionInviteLinkRequest.md)
 - [PostEditForumTopicRequest](docs/PostEditForumTopicRequest.md)
 - [PostEditGeneralForumTopicRequest](docs/PostEditGeneralForumTopicRequest.md)
 - [PostEditMessageCaptionRequest](docs/PostEditMessageCaptionRequest.md)
 - [PostEditMessageLiveLocationRequest](docs/PostEditMessageLiveLocationRequest.md)
 - [PostEditMessageReplyMarkupRequest](docs/PostEditMessageReplyMarkupRequest.md)
 - [PostEditMessageText200Response](docs/PostEditMessageText200Response.md)
 - [PostEditMessageText200ResponseResult](docs/PostEditMessageText200ResponseResult.md)
 - [PostEditMessageTextRequest](docs/PostEditMessageTextRequest.md)
 - [PostEditMessageTextRequestChatId](docs/PostEditMessageTextRequestChatId.md)
 - [PostEditUserStarSubscriptionRequest](docs/PostEditUserStarSubscriptionRequest.md)
 - [PostExportChatInviteLink200Response](docs/PostExportChatInviteLink200Response.md)
 - [PostExportChatInviteLinkRequest](docs/PostExportChatInviteLinkRequest.md)
 - [PostForwardMessageRequest](docs/PostForwardMessageRequest.md)
 - [PostForwardMessageRequestFromChatId](docs/PostForwardMessageRequestFromChatId.md)
 - [PostForwardMessages200Response](docs/PostForwardMessages200Response.md)
 - [PostForwardMessagesRequest](docs/PostForwardMessagesRequest.md)
 - [PostForwardMessagesRequestFromChatId](docs/PostForwardMessagesRequestFromChatId.md)
 - [PostGetAvailableGifts200Response](docs/PostGetAvailableGifts200Response.md)
 - [PostGetBusinessAccountGifts200Response](docs/PostGetBusinessAccountGifts200Response.md)
 - [PostGetBusinessAccountGiftsRequest](docs/PostGetBusinessAccountGiftsRequest.md)
 - [PostGetBusinessAccountStarBalance200Response](docs/PostGetBusinessAccountStarBalance200Response.md)
 - [PostGetBusinessConnection200Response](docs/PostGetBusinessConnection200Response.md)
 - [PostGetBusinessConnectionRequest](docs/PostGetBusinessConnectionRequest.md)
 - [PostGetChat200Response](docs/PostGetChat200Response.md)
 - [PostGetChatAdministrators200Response](docs/PostGetChatAdministrators200Response.md)
 - [PostGetChatMember200Response](docs/PostGetChatMember200Response.md)
 - [PostGetChatMemberCount200Response](docs/PostGetChatMemberCount200Response.md)
 - [PostGetChatMemberRequest](docs/PostGetChatMemberRequest.md)
 - [PostGetChatMenuButton200Response](docs/PostGetChatMenuButton200Response.md)
 - [PostGetChatMenuButtonRequest](docs/PostGetChatMenuButtonRequest.md)
 - [PostGetCustomEmojiStickersRequest](docs/PostGetCustomEmojiStickersRequest.md)
 - [PostGetFile200Response](docs/PostGetFile200Response.md)
 - [PostGetFileRequest](docs/PostGetFileRequest.md)
 - [PostGetForumTopicIconStickers200Response](docs/PostGetForumTopicIconStickers200Response.md)
 - [PostGetGameHighScores200Response](docs/PostGetGameHighScores200Response.md)
 - [PostGetGameHighScoresRequest](docs/PostGetGameHighScoresRequest.md)
 - [PostGetMe200Response](docs/PostGetMe200Response.md)
 - [PostGetMyCommands200Response](docs/PostGetMyCommands200Response.md)
 - [PostGetMyCommandsRequest](docs/PostGetMyCommandsRequest.md)
 - [PostGetMyDefaultAdministratorRights200Response](docs/PostGetMyDefaultAdministratorRights200Response.md)
 - [PostGetMyDefaultAdministratorRightsRequest](docs/PostGetMyDefaultAdministratorRightsRequest.md)
 - [PostGetMyDescription200Response](docs/PostGetMyDescription200Response.md)
 - [PostGetMyName200Response](docs/PostGetMyName200Response.md)
 - [PostGetMyNameRequest](docs/PostGetMyNameRequest.md)
 - [PostGetMyShortDescription200Response](docs/PostGetMyShortDescription200Response.md)
 - [PostGetStarTransactions200Response](docs/PostGetStarTransactions200Response.md)
 - [PostGetStarTransactionsRequest](docs/PostGetStarTransactionsRequest.md)
 - [PostGetStickerSet200Response](docs/PostGetStickerSet200Response.md)
 - [PostGetStickerSetRequest](docs/PostGetStickerSetRequest.md)
 - [PostGetUpdates200Response](docs/PostGetUpdates200Response.md)
 - [PostGetUpdatesRequest](docs/PostGetUpdatesRequest.md)
 - [PostGetUserChatBoosts200Response](docs/PostGetUserChatBoosts200Response.md)
 - [PostGetUserChatBoostsRequest](docs/PostGetUserChatBoostsRequest.md)
 - [PostGetUserChatBoostsRequestChatId](docs/PostGetUserChatBoostsRequestChatId.md)
 - [PostGetUserProfilePhotos200Response](docs/PostGetUserProfilePhotos200Response.md)
 - [PostGetUserProfilePhotosRequest](docs/PostGetUserProfilePhotosRequest.md)
 - [PostGetWebhookInfo200Response](docs/PostGetWebhookInfo200Response.md)
 - [PostGiftPremiumSubscriptionRequest](docs/PostGiftPremiumSubscriptionRequest.md)
 - [PostLeaveChatRequest](docs/PostLeaveChatRequest.md)
 - [PostLeaveChatRequestChatId](docs/PostLeaveChatRequestChatId.md)
 - [PostPinChatMessageRequest](docs/PostPinChatMessageRequest.md)
 - [PostPostStory200Response](docs/PostPostStory200Response.md)
 - [PostPromoteChatMemberRequest](docs/PostPromoteChatMemberRequest.md)
 - [PostReadBusinessMessageRequest](docs/PostReadBusinessMessageRequest.md)
 - [PostRefundStarPaymentRequest](docs/PostRefundStarPaymentRequest.md)
 - [PostRemoveBusinessAccountProfilePhotoRequest](docs/PostRemoveBusinessAccountProfilePhotoRequest.md)
 - [PostRemoveUserVerificationRequest](docs/PostRemoveUserVerificationRequest.md)
 - [PostRestrictChatMemberRequest](docs/PostRestrictChatMemberRequest.md)
 - [PostRestrictChatMemberRequestChatId](docs/PostRestrictChatMemberRequestChatId.md)
 - [PostRevokeChatInviteLinkRequest](docs/PostRevokeChatInviteLinkRequest.md)
 - [PostRevokeChatInviteLinkRequestChatId](docs/PostRevokeChatInviteLinkRequestChatId.md)
 - [PostSavePreparedInlineMessage200Response](docs/PostSavePreparedInlineMessage200Response.md)
 - [PostSavePreparedInlineMessageRequest](docs/PostSavePreparedInlineMessageRequest.md)
 - [PostSendAnimationRequestAnimation](docs/PostSendAnimationRequestAnimation.md)
 - [PostSendAudioRequestAudio](docs/PostSendAudioRequestAudio.md)
 - [PostSendAudioRequestThumbnail](docs/PostSendAudioRequestThumbnail.md)
 - [PostSendChatActionRequest](docs/PostSendChatActionRequest.md)
 - [PostSendContactRequest](docs/PostSendContactRequest.md)
 - [PostSendDiceRequest](docs/PostSendDiceRequest.md)
 - [PostSendDocumentRequestDocument](docs/PostSendDocumentRequestDocument.md)
 - [PostSendGameRequest](docs/PostSendGameRequest.md)
 - [PostSendGiftRequest](docs/PostSendGiftRequest.md)
 - [PostSendGiftRequestChatId](docs/PostSendGiftRequestChatId.md)
 - [PostSendInvoiceRequest](docs/PostSendInvoiceRequest.md)
 - [PostSendLocationRequest](docs/PostSendLocationRequest.md)
 - [PostSendMediaGroup200Response](docs/PostSendMediaGroup200Response.md)
 - [PostSendMediaGroupRequestMediaInner](docs/PostSendMediaGroupRequestMediaInner.md)
 - [PostSendMessage200Response](docs/PostSendMessage200Response.md)
 - [PostSendMessageRequest](docs/PostSendMessageRequest.md)
 - [PostSendMessageRequestChatId](docs/PostSendMessageRequestChatId.md)
 - [PostSendMessageRequestReplyMarkup](docs/PostSendMessageRequestReplyMarkup.md)
 - [PostSendPaidMediaRequestChatId](docs/PostSendPaidMediaRequestChatId.md)
 - [PostSendPhotoRequestPhoto](docs/PostSendPhotoRequestPhoto.md)
 - [PostSendPollRequest](docs/PostSendPollRequest.md)
 - [PostSendStickerRequestSticker](docs/PostSendStickerRequestSticker.md)
 - [PostSendVenueRequest](docs/PostSendVenueRequest.md)
 - [PostSendVideoNoteRequestVideoNote](docs/PostSendVideoNoteRequestVideoNote.md)
 - [PostSendVideoRequestCover](docs/PostSendVideoRequestCover.md)
 - [PostSendVideoRequestVideo](docs/PostSendVideoRequestVideo.md)
 - [PostSendVoiceRequestVoice](docs/PostSendVoiceRequestVoice.md)
 - [PostSetBusinessAccountBioRequest](docs/PostSetBusinessAccountBioRequest.md)
 - [PostSetBusinessAccountGiftSettingsRequest](docs/PostSetBusinessAccountGiftSettingsRequest.md)
 - [PostSetBusinessAccountNameRequest](docs/PostSetBusinessAccountNameRequest.md)
 - [PostSetBusinessAccountUsernameRequest](docs/PostSetBusinessAccountUsernameRequest.md)
 - [PostSetChatAdministratorCustomTitleRequest](docs/PostSetChatAdministratorCustomTitleRequest.md)
 - [PostSetChatDescriptionRequest](docs/PostSetChatDescriptionRequest.md)
 - [PostSetChatMenuButtonRequest](docs/PostSetChatMenuButtonRequest.md)
 - [PostSetChatPermissionsRequest](docs/PostSetChatPermissionsRequest.md)
 - [PostSetChatStickerSetRequest](docs/PostSetChatStickerSetRequest.md)
 - [PostSetChatTitleRequest](docs/PostSetChatTitleRequest.md)
 - [PostSetCustomEmojiStickerSetThumbnailRequest](docs/PostSetCustomEmojiStickerSetThumbnailRequest.md)
 - [PostSetGameScoreRequest](docs/PostSetGameScoreRequest.md)
 - [PostSetMessageReactionRequest](docs/PostSetMessageReactionRequest.md)
 - [PostSetMyCommandsRequest](docs/PostSetMyCommandsRequest.md)
 - [PostSetMyDefaultAdministratorRightsRequest](docs/PostSetMyDefaultAdministratorRightsRequest.md)
 - [PostSetMyDescriptionRequest](docs/PostSetMyDescriptionRequest.md)
 - [PostSetMyNameRequest](docs/PostSetMyNameRequest.md)
 - [PostSetMyShortDescriptionRequest](docs/PostSetMyShortDescriptionRequest.md)
 - [PostSetPassportDataErrorsRequest](docs/PostSetPassportDataErrorsRequest.md)
 - [PostSetStickerEmojiListRequest](docs/PostSetStickerEmojiListRequest.md)
 - [PostSetStickerKeywordsRequest](docs/PostSetStickerKeywordsRequest.md)
 - [PostSetStickerMaskPositionRequest](docs/PostSetStickerMaskPositionRequest.md)
 - [PostSetStickerPositionInSetRequest](docs/PostSetStickerPositionInSetRequest.md)
 - [PostSetStickerSetThumbnailRequestThumbnail](docs/PostSetStickerSetThumbnailRequestThumbnail.md)
 - [PostSetStickerSetTitleRequest](docs/PostSetStickerSetTitleRequest.md)
 - [PostSetUserEmojiStatusRequest](docs/PostSetUserEmojiStatusRequest.md)
 - [PostSetWebhook200Response](docs/PostSetWebhook200Response.md)
 - [PostStopMessageLiveLocationRequest](docs/PostStopMessageLiveLocationRequest.md)
 - [PostStopPoll200Response](docs/PostStopPoll200Response.md)
 - [PostStopPollRequest](docs/PostStopPollRequest.md)
 - [PostTransferBusinessAccountStarsRequest](docs/PostTransferBusinessAccountStarsRequest.md)
 - [PostTransferGiftRequest](docs/PostTransferGiftRequest.md)
 - [PostUnbanChatMemberRequest](docs/PostUnbanChatMemberRequest.md)
 - [PostUnpinChatMessageRequest](docs/PostUnpinChatMessageRequest.md)
 - [PostUpgradeGiftRequest](docs/PostUpgradeGiftRequest.md)
 - [PostVerifyChatRequest](docs/PostVerifyChatRequest.md)
 - [PostVerifyUserRequest](docs/PostVerifyUserRequest.md)
 - [PreCheckoutQuery](docs/PreCheckoutQuery.md)
 - [PreparedInlineMessage](docs/PreparedInlineMessage.md)
 - [ProximityAlertTriggered](docs/ProximityAlertTriggered.md)
 - [ReactionCount](docs/ReactionCount.md)
 - [ReactionType](docs/ReactionType.md)
 - [ReactionTypeCustomEmoji](docs/ReactionTypeCustomEmoji.md)
 - [ReactionTypeEmoji](docs/ReactionTypeEmoji.md)
 - [ReactionTypePaid](docs/ReactionTypePaid.md)
 - [RefundedPayment](docs/RefundedPayment.md)
 - [ReplyKeyboardMarkup](docs/ReplyKeyboardMarkup.md)
 - [ReplyKeyboardRemove](docs/ReplyKeyboardRemove.md)
 - [ReplyParameters](docs/ReplyParameters.md)
 - [ReplyParametersChatId](docs/ReplyParametersChatId.md)
 - [ResponseParameters](docs/ResponseParameters.md)
 - [RevenueWithdrawalState](docs/RevenueWithdrawalState.md)
 - [RevenueWithdrawalStateFailed](docs/RevenueWithdrawalStateFailed.md)
 - [RevenueWithdrawalStatePending](docs/RevenueWithdrawalStatePending.md)
 - [RevenueWithdrawalStateSucceeded](docs/RevenueWithdrawalStateSucceeded.md)
 - [SentWebAppMessage](docs/SentWebAppMessage.md)
 - [SharedUser](docs/SharedUser.md)
 - [ShippingAddress](docs/ShippingAddress.md)
 - [ShippingOption](docs/ShippingOption.md)
 - [ShippingQuery](docs/ShippingQuery.md)
 - [StarAmount](docs/StarAmount.md)
 - [StarTransaction](docs/StarTransaction.md)
 - [StarTransactions](docs/StarTransactions.md)
 - [Sticker](docs/Sticker.md)
 - [StickerSet](docs/StickerSet.md)
 - [Story](docs/Story.md)
 - [StoryArea](docs/StoryArea.md)
 - [StoryAreaPosition](docs/StoryAreaPosition.md)
 - [StoryAreaType](docs/StoryAreaType.md)
 - [StoryAreaTypeLink](docs/StoryAreaTypeLink.md)
 - [StoryAreaTypeLocation](docs/StoryAreaTypeLocation.md)
 - [StoryAreaTypeSuggestedReaction](docs/StoryAreaTypeSuggestedReaction.md)
 - [StoryAreaTypeUniqueGift](docs/StoryAreaTypeUniqueGift.md)
 - [StoryAreaTypeWeather](docs/StoryAreaTypeWeather.md)
 - [SuccessfulPayment](docs/SuccessfulPayment.md)
 - [SwitchInlineQueryChosenChat](docs/SwitchInlineQueryChosenChat.md)
 - [TextQuote](docs/TextQuote.md)
 - [TransactionPartner](docs/TransactionPartner.md)
 - [TransactionPartnerAffiliateProgram](docs/TransactionPartnerAffiliateProgram.md)
 - [TransactionPartnerChat](docs/TransactionPartnerChat.md)
 - [TransactionPartnerFragment](docs/TransactionPartnerFragment.md)
 - [TransactionPartnerOther](docs/TransactionPartnerOther.md)
 - [TransactionPartnerTelegramAds](docs/TransactionPartnerTelegramAds.md)
 - [TransactionPartnerTelegramApi](docs/TransactionPartnerTelegramApi.md)
 - [TransactionPartnerUser](docs/TransactionPartnerUser.md)
 - [UniqueGift](docs/UniqueGift.md)
 - [UniqueGiftBackdrop](docs/UniqueGiftBackdrop.md)
 - [UniqueGiftBackdropColors](docs/UniqueGiftBackdropColors.md)
 - [UniqueGiftInfo](docs/UniqueGiftInfo.md)
 - [UniqueGiftModel](docs/UniqueGiftModel.md)
 - [UniqueGiftSymbol](docs/UniqueGiftSymbol.md)
 - [Update](docs/Update.md)
 - [User](docs/User.md)
 - [UserChatBoosts](docs/UserChatBoosts.md)
 - [UserProfilePhotos](docs/UserProfilePhotos.md)
 - [UsersShared](docs/UsersShared.md)
 - [Venue](docs/Venue.md)
 - [Video](docs/Video.md)
 - [VideoChatEnded](docs/VideoChatEnded.md)
 - [VideoChatParticipantsInvited](docs/VideoChatParticipantsInvited.md)
 - [VideoChatScheduled](docs/VideoChatScheduled.md)
 - [VideoNote](docs/VideoNote.md)
 - [Voice](docs/Voice.md)
 - [WebAppData](docs/WebAppData.md)
 - [WebAppInfo](docs/WebAppInfo.md)
 - [WebhookInfo](docs/WebhookInfo.md)
 - [WriteAccessAllowed](docs/WriteAccessAllowed.md)


<a id="documentation-for-authorization"></a>
## Documentation For Authorization

Endpoints do not require authorization.

