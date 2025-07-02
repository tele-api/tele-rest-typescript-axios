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
 - [AddStickerToSetRequest](docs/AddStickerToSetRequest.md)
 - [AddStickerToSetResponse](docs/AddStickerToSetResponse.md)
 - [AffiliateInfo](docs/AffiliateInfo.md)
 - [Animation](docs/Animation.md)
 - [AnswerCallbackQueryRequest](docs/AnswerCallbackQueryRequest.md)
 - [AnswerCallbackQueryResponse](docs/AnswerCallbackQueryResponse.md)
 - [AnswerInlineQueryRequest](docs/AnswerInlineQueryRequest.md)
 - [AnswerInlineQueryResponse](docs/AnswerInlineQueryResponse.md)
 - [AnswerPreCheckoutQueryRequest](docs/AnswerPreCheckoutQueryRequest.md)
 - [AnswerPreCheckoutQueryResponse](docs/AnswerPreCheckoutQueryResponse.md)
 - [AnswerShippingQueryRequest](docs/AnswerShippingQueryRequest.md)
 - [AnswerShippingQueryResponse](docs/AnswerShippingQueryResponse.md)
 - [AnswerWebAppQueryRequest](docs/AnswerWebAppQueryRequest.md)
 - [AnswerWebAppQueryResponse](docs/AnswerWebAppQueryResponse.md)
 - [ApproveChatJoinRequestRequest](docs/ApproveChatJoinRequestRequest.md)
 - [ApproveChatJoinRequestResponse](docs/ApproveChatJoinRequestResponse.md)
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
 - [BanChatMemberRequest](docs/BanChatMemberRequest.md)
 - [BanChatMemberRequestChatId](docs/BanChatMemberRequestChatId.md)
 - [BanChatMemberResponse](docs/BanChatMemberResponse.md)
 - [BanChatSenderChatRequest](docs/BanChatSenderChatRequest.md)
 - [BanChatSenderChatResponse](docs/BanChatSenderChatResponse.md)
 - [Birthdate](docs/Birthdate.md)
 - [BotCommand](docs/BotCommand.md)
 - [BotCommandScope](docs/BotCommandScope.md)
 - [BotCommandScopeAllChatAdministrators](docs/BotCommandScopeAllChatAdministrators.md)
 - [BotCommandScopeAllGroupChats](docs/BotCommandScopeAllGroupChats.md)
 - [BotCommandScopeAllPrivateChats](docs/BotCommandScopeAllPrivateChats.md)
 - [BotCommandScopeChat](docs/BotCommandScopeChat.md)
 - [BotCommandScopeChatAdministrators](docs/BotCommandScopeChatAdministrators.md)
 - [BotCommandScopeChatChatId](docs/BotCommandScopeChatChatId.md)
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
 - [CloseForumTopicRequest](docs/CloseForumTopicRequest.md)
 - [CloseForumTopicResponse](docs/CloseForumTopicResponse.md)
 - [CloseGeneralForumTopicRequest](docs/CloseGeneralForumTopicRequest.md)
 - [CloseGeneralForumTopicResponse](docs/CloseGeneralForumTopicResponse.md)
 - [CloseResponse](docs/CloseResponse.md)
 - [Contact](docs/Contact.md)
 - [ConvertGiftToStarsRequest](docs/ConvertGiftToStarsRequest.md)
 - [ConvertGiftToStarsResponse](docs/ConvertGiftToStarsResponse.md)
 - [CopyMessageRequest](docs/CopyMessageRequest.md)
 - [CopyMessageResponse](docs/CopyMessageResponse.md)
 - [CopyMessagesRequest](docs/CopyMessagesRequest.md)
 - [CopyMessagesResponse](docs/CopyMessagesResponse.md)
 - [CopyTextButton](docs/CopyTextButton.md)
 - [CreateChatInviteLinkRequest](docs/CreateChatInviteLinkRequest.md)
 - [CreateChatInviteLinkResponse](docs/CreateChatInviteLinkResponse.md)
 - [CreateChatSubscriptionInviteLinkRequest](docs/CreateChatSubscriptionInviteLinkRequest.md)
 - [CreateChatSubscriptionInviteLinkRequestChatId](docs/CreateChatSubscriptionInviteLinkRequestChatId.md)
 - [CreateChatSubscriptionInviteLinkResponse](docs/CreateChatSubscriptionInviteLinkResponse.md)
 - [CreateForumTopicRequest](docs/CreateForumTopicRequest.md)
 - [CreateForumTopicResponse](docs/CreateForumTopicResponse.md)
 - [CreateInvoiceLinkRequest](docs/CreateInvoiceLinkRequest.md)
 - [CreateInvoiceLinkResponse](docs/CreateInvoiceLinkResponse.md)
 - [CreateNewStickerSetRequest](docs/CreateNewStickerSetRequest.md)
 - [CreateNewStickerSetResponse](docs/CreateNewStickerSetResponse.md)
 - [DeclineChatJoinRequestRequest](docs/DeclineChatJoinRequestRequest.md)
 - [DeclineChatJoinRequestResponse](docs/DeclineChatJoinRequestResponse.md)
 - [DeleteBusinessMessagesRequest](docs/DeleteBusinessMessagesRequest.md)
 - [DeleteBusinessMessagesResponse](docs/DeleteBusinessMessagesResponse.md)
 - [DeleteChatPhotoRequest](docs/DeleteChatPhotoRequest.md)
 - [DeleteChatPhotoResponse](docs/DeleteChatPhotoResponse.md)
 - [DeleteChatStickerSetRequest](docs/DeleteChatStickerSetRequest.md)
 - [DeleteChatStickerSetResponse](docs/DeleteChatStickerSetResponse.md)
 - [DeleteForumTopicRequest](docs/DeleteForumTopicRequest.md)
 - [DeleteForumTopicResponse](docs/DeleteForumTopicResponse.md)
 - [DeleteMessageRequest](docs/DeleteMessageRequest.md)
 - [DeleteMessageResponse](docs/DeleteMessageResponse.md)
 - [DeleteMessagesRequest](docs/DeleteMessagesRequest.md)
 - [DeleteMessagesResponse](docs/DeleteMessagesResponse.md)
 - [DeleteMyCommandsRequest](docs/DeleteMyCommandsRequest.md)
 - [DeleteMyCommandsResponse](docs/DeleteMyCommandsResponse.md)
 - [DeleteStickerFromSetRequest](docs/DeleteStickerFromSetRequest.md)
 - [DeleteStickerFromSetResponse](docs/DeleteStickerFromSetResponse.md)
 - [DeleteStickerSetRequest](docs/DeleteStickerSetRequest.md)
 - [DeleteStickerSetResponse](docs/DeleteStickerSetResponse.md)
 - [DeleteStoryRequest](docs/DeleteStoryRequest.md)
 - [DeleteStoryResponse](docs/DeleteStoryResponse.md)
 - [DeleteWebhookRequest](docs/DeleteWebhookRequest.md)
 - [DeleteWebhookResponse](docs/DeleteWebhookResponse.md)
 - [Dice](docs/Dice.md)
 - [Document](docs/Document.md)
 - [EditChatInviteLinkRequest](docs/EditChatInviteLinkRequest.md)
 - [EditChatInviteLinkResponse](docs/EditChatInviteLinkResponse.md)
 - [EditChatSubscriptionInviteLinkRequest](docs/EditChatSubscriptionInviteLinkRequest.md)
 - [EditChatSubscriptionInviteLinkResponse](docs/EditChatSubscriptionInviteLinkResponse.md)
 - [EditForumTopicRequest](docs/EditForumTopicRequest.md)
 - [EditForumTopicResponse](docs/EditForumTopicResponse.md)
 - [EditGeneralForumTopicRequest](docs/EditGeneralForumTopicRequest.md)
 - [EditGeneralForumTopicResponse](docs/EditGeneralForumTopicResponse.md)
 - [EditMessageCaptionRequest](docs/EditMessageCaptionRequest.md)
 - [EditMessageCaptionResponse](docs/EditMessageCaptionResponse.md)
 - [EditMessageLiveLocationRequest](docs/EditMessageLiveLocationRequest.md)
 - [EditMessageLiveLocationResponse](docs/EditMessageLiveLocationResponse.md)
 - [EditMessageMediaRequest](docs/EditMessageMediaRequest.md)
 - [EditMessageMediaResponse](docs/EditMessageMediaResponse.md)
 - [EditMessageReplyMarkupRequest](docs/EditMessageReplyMarkupRequest.md)
 - [EditMessageReplyMarkupResponse](docs/EditMessageReplyMarkupResponse.md)
 - [EditMessageTextRequest](docs/EditMessageTextRequest.md)
 - [EditMessageTextRequestChatId](docs/EditMessageTextRequestChatId.md)
 - [EditMessageTextResponse](docs/EditMessageTextResponse.md)
 - [EditMessageTextResponseResult](docs/EditMessageTextResponseResult.md)
 - [EditStoryRequest](docs/EditStoryRequest.md)
 - [EditStoryResponse](docs/EditStoryResponse.md)
 - [EditUserStarSubscriptionRequest](docs/EditUserStarSubscriptionRequest.md)
 - [EditUserStarSubscriptionResponse](docs/EditUserStarSubscriptionResponse.md)
 - [EncryptedCredentials](docs/EncryptedCredentials.md)
 - [EncryptedPassportElement](docs/EncryptedPassportElement.md)
 - [ExportChatInviteLinkRequest](docs/ExportChatInviteLinkRequest.md)
 - [ExportChatInviteLinkResponse](docs/ExportChatInviteLinkResponse.md)
 - [ExternalReplyInfo](docs/ExternalReplyInfo.md)
 - [ForceReply](docs/ForceReply.md)
 - [ForumTopic](docs/ForumTopic.md)
 - [ForumTopicCreated](docs/ForumTopicCreated.md)
 - [ForumTopicEdited](docs/ForumTopicEdited.md)
 - [ForwardMessageRequest](docs/ForwardMessageRequest.md)
 - [ForwardMessageRequestFromChatId](docs/ForwardMessageRequestFromChatId.md)
 - [ForwardMessageResponse](docs/ForwardMessageResponse.md)
 - [ForwardMessagesRequest](docs/ForwardMessagesRequest.md)
 - [ForwardMessagesRequestFromChatId](docs/ForwardMessagesRequestFromChatId.md)
 - [ForwardMessagesResponse](docs/ForwardMessagesResponse.md)
 - [Game](docs/Game.md)
 - [GameHighScore](docs/GameHighScore.md)
 - [GetAvailableGiftsResponse](docs/GetAvailableGiftsResponse.md)
 - [GetBusinessAccountGiftsRequest](docs/GetBusinessAccountGiftsRequest.md)
 - [GetBusinessAccountGiftsResponse](docs/GetBusinessAccountGiftsResponse.md)
 - [GetBusinessAccountStarBalanceRequest](docs/GetBusinessAccountStarBalanceRequest.md)
 - [GetBusinessAccountStarBalanceResponse](docs/GetBusinessAccountStarBalanceResponse.md)
 - [GetBusinessConnectionRequest](docs/GetBusinessConnectionRequest.md)
 - [GetBusinessConnectionResponse](docs/GetBusinessConnectionResponse.md)
 - [GetChatAdministratorsRequest](docs/GetChatAdministratorsRequest.md)
 - [GetChatAdministratorsResponse](docs/GetChatAdministratorsResponse.md)
 - [GetChatMemberCountRequest](docs/GetChatMemberCountRequest.md)
 - [GetChatMemberCountResponse](docs/GetChatMemberCountResponse.md)
 - [GetChatMemberRequest](docs/GetChatMemberRequest.md)
 - [GetChatMemberResponse](docs/GetChatMemberResponse.md)
 - [GetChatMenuButtonRequest](docs/GetChatMenuButtonRequest.md)
 - [GetChatMenuButtonResponse](docs/GetChatMenuButtonResponse.md)
 - [GetChatRequest](docs/GetChatRequest.md)
 - [GetChatResponse](docs/GetChatResponse.md)
 - [GetCustomEmojiStickersRequest](docs/GetCustomEmojiStickersRequest.md)
 - [GetCustomEmojiStickersResponse](docs/GetCustomEmojiStickersResponse.md)
 - [GetFileRequest](docs/GetFileRequest.md)
 - [GetFileResponse](docs/GetFileResponse.md)
 - [GetForumTopicIconStickersResponse](docs/GetForumTopicIconStickersResponse.md)
 - [GetGameHighScoresRequest](docs/GetGameHighScoresRequest.md)
 - [GetGameHighScoresResponse](docs/GetGameHighScoresResponse.md)
 - [GetMeResponse](docs/GetMeResponse.md)
 - [GetMyCommandsRequest](docs/GetMyCommandsRequest.md)
 - [GetMyCommandsResponse](docs/GetMyCommandsResponse.md)
 - [GetMyDefaultAdministratorRightsRequest](docs/GetMyDefaultAdministratorRightsRequest.md)
 - [GetMyDefaultAdministratorRightsResponse](docs/GetMyDefaultAdministratorRightsResponse.md)
 - [GetMyDescriptionRequest](docs/GetMyDescriptionRequest.md)
 - [GetMyDescriptionResponse](docs/GetMyDescriptionResponse.md)
 - [GetMyNameRequest](docs/GetMyNameRequest.md)
 - [GetMyNameResponse](docs/GetMyNameResponse.md)
 - [GetMyShortDescriptionRequest](docs/GetMyShortDescriptionRequest.md)
 - [GetMyShortDescriptionResponse](docs/GetMyShortDescriptionResponse.md)
 - [GetStarTransactionsRequest](docs/GetStarTransactionsRequest.md)
 - [GetStarTransactionsResponse](docs/GetStarTransactionsResponse.md)
 - [GetStickerSetRequest](docs/GetStickerSetRequest.md)
 - [GetStickerSetResponse](docs/GetStickerSetResponse.md)
 - [GetUpdatesRequest](docs/GetUpdatesRequest.md)
 - [GetUpdatesResponse](docs/GetUpdatesResponse.md)
 - [GetUserChatBoostsRequest](docs/GetUserChatBoostsRequest.md)
 - [GetUserChatBoostsRequestChatId](docs/GetUserChatBoostsRequestChatId.md)
 - [GetUserChatBoostsResponse](docs/GetUserChatBoostsResponse.md)
 - [GetUserProfilePhotosRequest](docs/GetUserProfilePhotosRequest.md)
 - [GetUserProfilePhotosResponse](docs/GetUserProfilePhotosResponse.md)
 - [GetWebhookInfoResponse](docs/GetWebhookInfoResponse.md)
 - [Gift](docs/Gift.md)
 - [GiftInfo](docs/GiftInfo.md)
 - [GiftPremiumSubscriptionRequest](docs/GiftPremiumSubscriptionRequest.md)
 - [GiftPremiumSubscriptionResponse](docs/GiftPremiumSubscriptionResponse.md)
 - [Gifts](docs/Gifts.md)
 - [Giveaway](docs/Giveaway.md)
 - [GiveawayCompleted](docs/GiveawayCompleted.md)
 - [GiveawayCreated](docs/GiveawayCreated.md)
 - [GiveawayWinners](docs/GiveawayWinners.md)
 - [HideGeneralForumTopicRequest](docs/HideGeneralForumTopicRequest.md)
 - [HideGeneralForumTopicResponse](docs/HideGeneralForumTopicResponse.md)
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
 - [LeaveChatRequest](docs/LeaveChatRequest.md)
 - [LeaveChatRequestChatId](docs/LeaveChatRequestChatId.md)
 - [LeaveChatResponse](docs/LeaveChatResponse.md)
 - [LinkPreviewOptions](docs/LinkPreviewOptions.md)
 - [Location](docs/Location.md)
 - [LocationAddress](docs/LocationAddress.md)
 - [LogOutResponse](docs/LogOutResponse.md)
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
 - [PinChatMessageRequest](docs/PinChatMessageRequest.md)
 - [PinChatMessageResponse](docs/PinChatMessageResponse.md)
 - [Poll](docs/Poll.md)
 - [PollAnswer](docs/PollAnswer.md)
 - [PollOption](docs/PollOption.md)
 - [PostStoryRequest](docs/PostStoryRequest.md)
 - [PostStoryResponse](docs/PostStoryResponse.md)
 - [PreCheckoutQuery](docs/PreCheckoutQuery.md)
 - [PreparedInlineMessage](docs/PreparedInlineMessage.md)
 - [PromoteChatMemberRequest](docs/PromoteChatMemberRequest.md)
 - [PromoteChatMemberResponse](docs/PromoteChatMemberResponse.md)
 - [ProximityAlertTriggered](docs/ProximityAlertTriggered.md)
 - [ReactionCount](docs/ReactionCount.md)
 - [ReactionType](docs/ReactionType.md)
 - [ReactionTypeCustomEmoji](docs/ReactionTypeCustomEmoji.md)
 - [ReactionTypeEmoji](docs/ReactionTypeEmoji.md)
 - [ReactionTypePaid](docs/ReactionTypePaid.md)
 - [ReadBusinessMessageRequest](docs/ReadBusinessMessageRequest.md)
 - [ReadBusinessMessageResponse](docs/ReadBusinessMessageResponse.md)
 - [RefundStarPaymentRequest](docs/RefundStarPaymentRequest.md)
 - [RefundStarPaymentResponse](docs/RefundStarPaymentResponse.md)
 - [RefundedPayment](docs/RefundedPayment.md)
 - [RemoveBusinessAccountProfilePhotoRequest](docs/RemoveBusinessAccountProfilePhotoRequest.md)
 - [RemoveBusinessAccountProfilePhotoResponse](docs/RemoveBusinessAccountProfilePhotoResponse.md)
 - [RemoveChatVerificationRequest](docs/RemoveChatVerificationRequest.md)
 - [RemoveChatVerificationResponse](docs/RemoveChatVerificationResponse.md)
 - [RemoveUserVerificationRequest](docs/RemoveUserVerificationRequest.md)
 - [RemoveUserVerificationResponse](docs/RemoveUserVerificationResponse.md)
 - [ReopenForumTopicRequest](docs/ReopenForumTopicRequest.md)
 - [ReopenForumTopicResponse](docs/ReopenForumTopicResponse.md)
 - [ReopenGeneralForumTopicRequest](docs/ReopenGeneralForumTopicRequest.md)
 - [ReopenGeneralForumTopicResponse](docs/ReopenGeneralForumTopicResponse.md)
 - [ReplaceStickerInSetRequest](docs/ReplaceStickerInSetRequest.md)
 - [ReplaceStickerInSetResponse](docs/ReplaceStickerInSetResponse.md)
 - [ReplyKeyboardMarkup](docs/ReplyKeyboardMarkup.md)
 - [ReplyKeyboardRemove](docs/ReplyKeyboardRemove.md)
 - [ReplyParameters](docs/ReplyParameters.md)
 - [ReplyParametersChatId](docs/ReplyParametersChatId.md)
 - [ResponseParameters](docs/ResponseParameters.md)
 - [RestrictChatMemberRequest](docs/RestrictChatMemberRequest.md)
 - [RestrictChatMemberResponse](docs/RestrictChatMemberResponse.md)
 - [RevenueWithdrawalState](docs/RevenueWithdrawalState.md)
 - [RevenueWithdrawalStateFailed](docs/RevenueWithdrawalStateFailed.md)
 - [RevenueWithdrawalStatePending](docs/RevenueWithdrawalStatePending.md)
 - [RevenueWithdrawalStateSucceeded](docs/RevenueWithdrawalStateSucceeded.md)
 - [RevokeChatInviteLinkRequest](docs/RevokeChatInviteLinkRequest.md)
 - [RevokeChatInviteLinkRequestChatId](docs/RevokeChatInviteLinkRequestChatId.md)
 - [RevokeChatInviteLinkResponse](docs/RevokeChatInviteLinkResponse.md)
 - [SavePreparedInlineMessageRequest](docs/SavePreparedInlineMessageRequest.md)
 - [SavePreparedInlineMessageResponse](docs/SavePreparedInlineMessageResponse.md)
 - [SendAnimationRequest](docs/SendAnimationRequest.md)
 - [SendAnimationResponse](docs/SendAnimationResponse.md)
 - [SendAudioRequest](docs/SendAudioRequest.md)
 - [SendAudioResponse](docs/SendAudioResponse.md)
 - [SendChatActionRequest](docs/SendChatActionRequest.md)
 - [SendChatActionResponse](docs/SendChatActionResponse.md)
 - [SendContactRequest](docs/SendContactRequest.md)
 - [SendContactResponse](docs/SendContactResponse.md)
 - [SendDiceRequest](docs/SendDiceRequest.md)
 - [SendDiceResponse](docs/SendDiceResponse.md)
 - [SendDocumentRequest](docs/SendDocumentRequest.md)
 - [SendDocumentResponse](docs/SendDocumentResponse.md)
 - [SendGameRequest](docs/SendGameRequest.md)
 - [SendGameResponse](docs/SendGameResponse.md)
 - [SendGiftRequest](docs/SendGiftRequest.md)
 - [SendGiftRequestChatId](docs/SendGiftRequestChatId.md)
 - [SendGiftResponse](docs/SendGiftResponse.md)
 - [SendInvoiceRequest](docs/SendInvoiceRequest.md)
 - [SendInvoiceResponse](docs/SendInvoiceResponse.md)
 - [SendLocationRequest](docs/SendLocationRequest.md)
 - [SendLocationResponse](docs/SendLocationResponse.md)
 - [SendMediaGroupRequest](docs/SendMediaGroupRequest.md)
 - [SendMediaGroupRequestMediaInner](docs/SendMediaGroupRequestMediaInner.md)
 - [SendMediaGroupResponse](docs/SendMediaGroupResponse.md)
 - [SendMessageRequest](docs/SendMessageRequest.md)
 - [SendMessageRequestChatId](docs/SendMessageRequestChatId.md)
 - [SendMessageRequestReplyMarkup](docs/SendMessageRequestReplyMarkup.md)
 - [SendMessageResponse](docs/SendMessageResponse.md)
 - [SendPaidMediaRequest](docs/SendPaidMediaRequest.md)
 - [SendPaidMediaRequestChatId](docs/SendPaidMediaRequestChatId.md)
 - [SendPaidMediaResponse](docs/SendPaidMediaResponse.md)
 - [SendPhotoRequest](docs/SendPhotoRequest.md)
 - [SendPhotoResponse](docs/SendPhotoResponse.md)
 - [SendPollRequest](docs/SendPollRequest.md)
 - [SendPollResponse](docs/SendPollResponse.md)
 - [SendStickerRequest](docs/SendStickerRequest.md)
 - [SendStickerResponse](docs/SendStickerResponse.md)
 - [SendVenueRequest](docs/SendVenueRequest.md)
 - [SendVenueResponse](docs/SendVenueResponse.md)
 - [SendVideoNoteRequest](docs/SendVideoNoteRequest.md)
 - [SendVideoNoteResponse](docs/SendVideoNoteResponse.md)
 - [SendVideoRequest](docs/SendVideoRequest.md)
 - [SendVideoResponse](docs/SendVideoResponse.md)
 - [SendVoiceRequest](docs/SendVoiceRequest.md)
 - [SendVoiceResponse](docs/SendVoiceResponse.md)
 - [SentWebAppMessage](docs/SentWebAppMessage.md)
 - [SetBusinessAccountBioRequest](docs/SetBusinessAccountBioRequest.md)
 - [SetBusinessAccountBioResponse](docs/SetBusinessAccountBioResponse.md)
 - [SetBusinessAccountGiftSettingsRequest](docs/SetBusinessAccountGiftSettingsRequest.md)
 - [SetBusinessAccountGiftSettingsResponse](docs/SetBusinessAccountGiftSettingsResponse.md)
 - [SetBusinessAccountNameRequest](docs/SetBusinessAccountNameRequest.md)
 - [SetBusinessAccountNameResponse](docs/SetBusinessAccountNameResponse.md)
 - [SetBusinessAccountProfilePhotoRequest](docs/SetBusinessAccountProfilePhotoRequest.md)
 - [SetBusinessAccountProfilePhotoResponse](docs/SetBusinessAccountProfilePhotoResponse.md)
 - [SetBusinessAccountUsernameRequest](docs/SetBusinessAccountUsernameRequest.md)
 - [SetBusinessAccountUsernameResponse](docs/SetBusinessAccountUsernameResponse.md)
 - [SetChatAdministratorCustomTitleRequest](docs/SetChatAdministratorCustomTitleRequest.md)
 - [SetChatAdministratorCustomTitleResponse](docs/SetChatAdministratorCustomTitleResponse.md)
 - [SetChatDescriptionRequest](docs/SetChatDescriptionRequest.md)
 - [SetChatDescriptionResponse](docs/SetChatDescriptionResponse.md)
 - [SetChatMenuButtonRequest](docs/SetChatMenuButtonRequest.md)
 - [SetChatMenuButtonResponse](docs/SetChatMenuButtonResponse.md)
 - [SetChatPermissionsRequest](docs/SetChatPermissionsRequest.md)
 - [SetChatPermissionsResponse](docs/SetChatPermissionsResponse.md)
 - [SetChatPhotoRequest](docs/SetChatPhotoRequest.md)
 - [SetChatPhotoResponse](docs/SetChatPhotoResponse.md)
 - [SetChatStickerSetRequest](docs/SetChatStickerSetRequest.md)
 - [SetChatStickerSetResponse](docs/SetChatStickerSetResponse.md)
 - [SetChatTitleRequest](docs/SetChatTitleRequest.md)
 - [SetChatTitleResponse](docs/SetChatTitleResponse.md)
 - [SetCustomEmojiStickerSetThumbnailRequest](docs/SetCustomEmojiStickerSetThumbnailRequest.md)
 - [SetCustomEmojiStickerSetThumbnailResponse](docs/SetCustomEmojiStickerSetThumbnailResponse.md)
 - [SetGameScoreRequest](docs/SetGameScoreRequest.md)
 - [SetGameScoreResponse](docs/SetGameScoreResponse.md)
 - [SetMessageReactionRequest](docs/SetMessageReactionRequest.md)
 - [SetMessageReactionResponse](docs/SetMessageReactionResponse.md)
 - [SetMyCommandsRequest](docs/SetMyCommandsRequest.md)
 - [SetMyCommandsResponse](docs/SetMyCommandsResponse.md)
 - [SetMyDefaultAdministratorRightsRequest](docs/SetMyDefaultAdministratorRightsRequest.md)
 - [SetMyDefaultAdministratorRightsResponse](docs/SetMyDefaultAdministratorRightsResponse.md)
 - [SetMyDescriptionRequest](docs/SetMyDescriptionRequest.md)
 - [SetMyDescriptionResponse](docs/SetMyDescriptionResponse.md)
 - [SetMyNameRequest](docs/SetMyNameRequest.md)
 - [SetMyNameResponse](docs/SetMyNameResponse.md)
 - [SetMyShortDescriptionRequest](docs/SetMyShortDescriptionRequest.md)
 - [SetMyShortDescriptionResponse](docs/SetMyShortDescriptionResponse.md)
 - [SetPassportDataErrorsRequest](docs/SetPassportDataErrorsRequest.md)
 - [SetPassportDataErrorsResponse](docs/SetPassportDataErrorsResponse.md)
 - [SetStickerEmojiListRequest](docs/SetStickerEmojiListRequest.md)
 - [SetStickerEmojiListResponse](docs/SetStickerEmojiListResponse.md)
 - [SetStickerKeywordsRequest](docs/SetStickerKeywordsRequest.md)
 - [SetStickerKeywordsResponse](docs/SetStickerKeywordsResponse.md)
 - [SetStickerMaskPositionRequest](docs/SetStickerMaskPositionRequest.md)
 - [SetStickerMaskPositionResponse](docs/SetStickerMaskPositionResponse.md)
 - [SetStickerPositionInSetRequest](docs/SetStickerPositionInSetRequest.md)
 - [SetStickerPositionInSetResponse](docs/SetStickerPositionInSetResponse.md)
 - [SetStickerSetThumbnailRequest](docs/SetStickerSetThumbnailRequest.md)
 - [SetStickerSetThumbnailResponse](docs/SetStickerSetThumbnailResponse.md)
 - [SetStickerSetTitleRequest](docs/SetStickerSetTitleRequest.md)
 - [SetStickerSetTitleResponse](docs/SetStickerSetTitleResponse.md)
 - [SetUserEmojiStatusRequest](docs/SetUserEmojiStatusRequest.md)
 - [SetUserEmojiStatusResponse](docs/SetUserEmojiStatusResponse.md)
 - [SetWebhookRequest](docs/SetWebhookRequest.md)
 - [SetWebhookResponse](docs/SetWebhookResponse.md)
 - [SharedUser](docs/SharedUser.md)
 - [ShippingAddress](docs/ShippingAddress.md)
 - [ShippingOption](docs/ShippingOption.md)
 - [ShippingQuery](docs/ShippingQuery.md)
 - [StarAmount](docs/StarAmount.md)
 - [StarTransaction](docs/StarTransaction.md)
 - [StarTransactions](docs/StarTransactions.md)
 - [Sticker](docs/Sticker.md)
 - [StickerSet](docs/StickerSet.md)
 - [StopMessageLiveLocationRequest](docs/StopMessageLiveLocationRequest.md)
 - [StopMessageLiveLocationResponse](docs/StopMessageLiveLocationResponse.md)
 - [StopPollRequest](docs/StopPollRequest.md)
 - [StopPollResponse](docs/StopPollResponse.md)
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
 - [TransferBusinessAccountStarsRequest](docs/TransferBusinessAccountStarsRequest.md)
 - [TransferBusinessAccountStarsResponse](docs/TransferBusinessAccountStarsResponse.md)
 - [TransferGiftRequest](docs/TransferGiftRequest.md)
 - [TransferGiftResponse](docs/TransferGiftResponse.md)
 - [UnbanChatMemberRequest](docs/UnbanChatMemberRequest.md)
 - [UnbanChatMemberResponse](docs/UnbanChatMemberResponse.md)
 - [UnbanChatSenderChatRequest](docs/UnbanChatSenderChatRequest.md)
 - [UnbanChatSenderChatResponse](docs/UnbanChatSenderChatResponse.md)
 - [UnhideGeneralForumTopicRequest](docs/UnhideGeneralForumTopicRequest.md)
 - [UnhideGeneralForumTopicResponse](docs/UnhideGeneralForumTopicResponse.md)
 - [UniqueGift](docs/UniqueGift.md)
 - [UniqueGiftBackdrop](docs/UniqueGiftBackdrop.md)
 - [UniqueGiftBackdropColors](docs/UniqueGiftBackdropColors.md)
 - [UniqueGiftInfo](docs/UniqueGiftInfo.md)
 - [UniqueGiftModel](docs/UniqueGiftModel.md)
 - [UniqueGiftSymbol](docs/UniqueGiftSymbol.md)
 - [UnpinAllChatMessagesRequest](docs/UnpinAllChatMessagesRequest.md)
 - [UnpinAllChatMessagesResponse](docs/UnpinAllChatMessagesResponse.md)
 - [UnpinAllForumTopicMessagesRequest](docs/UnpinAllForumTopicMessagesRequest.md)
 - [UnpinAllForumTopicMessagesResponse](docs/UnpinAllForumTopicMessagesResponse.md)
 - [UnpinAllGeneralForumTopicMessagesRequest](docs/UnpinAllGeneralForumTopicMessagesRequest.md)
 - [UnpinAllGeneralForumTopicMessagesResponse](docs/UnpinAllGeneralForumTopicMessagesResponse.md)
 - [UnpinChatMessageRequest](docs/UnpinChatMessageRequest.md)
 - [UnpinChatMessageResponse](docs/UnpinChatMessageResponse.md)
 - [Update](docs/Update.md)
 - [UpgradeGiftRequest](docs/UpgradeGiftRequest.md)
 - [UpgradeGiftResponse](docs/UpgradeGiftResponse.md)
 - [UploadStickerFileRequest](docs/UploadStickerFileRequest.md)
 - [UploadStickerFileResponse](docs/UploadStickerFileResponse.md)
 - [User](docs/User.md)
 - [UserChatBoosts](docs/UserChatBoosts.md)
 - [UserProfilePhotos](docs/UserProfilePhotos.md)
 - [UsersShared](docs/UsersShared.md)
 - [Venue](docs/Venue.md)
 - [VerifyChatRequest](docs/VerifyChatRequest.md)
 - [VerifyChatResponse](docs/VerifyChatResponse.md)
 - [VerifyUserRequest](docs/VerifyUserRequest.md)
 - [VerifyUserResponse](docs/VerifyUserResponse.md)
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

