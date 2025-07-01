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
*DefaultApi* | [**addStickerToSetPost**](docs/DefaultApi.md#addstickertosetpost) | **POST** /addStickerToSet | 
*DefaultApi* | [**answerCallbackQueryPost**](docs/DefaultApi.md#answercallbackquerypost) | **POST** /answerCallbackQuery | 
*DefaultApi* | [**answerInlineQueryPost**](docs/DefaultApi.md#answerinlinequerypost) | **POST** /answerInlineQuery | 
*DefaultApi* | [**answerPreCheckoutQueryPost**](docs/DefaultApi.md#answerprecheckoutquerypost) | **POST** /answerPreCheckoutQuery | 
*DefaultApi* | [**answerShippingQueryPost**](docs/DefaultApi.md#answershippingquerypost) | **POST** /answerShippingQuery | 
*DefaultApi* | [**answerWebAppQueryPost**](docs/DefaultApi.md#answerwebappquerypost) | **POST** /answerWebAppQuery | 
*DefaultApi* | [**approveChatJoinRequestPost**](docs/DefaultApi.md#approvechatjoinrequestpost) | **POST** /approveChatJoinRequest | 
*DefaultApi* | [**banChatMemberPost**](docs/DefaultApi.md#banchatmemberpost) | **POST** /banChatMember | 
*DefaultApi* | [**banChatSenderChatPost**](docs/DefaultApi.md#banchatsenderchatpost) | **POST** /banChatSenderChat | 
*DefaultApi* | [**closeForumTopicPost**](docs/DefaultApi.md#closeforumtopicpost) | **POST** /closeForumTopic | 
*DefaultApi* | [**closeGeneralForumTopicPost**](docs/DefaultApi.md#closegeneralforumtopicpost) | **POST** /closeGeneralForumTopic | 
*DefaultApi* | [**closePost**](docs/DefaultApi.md#closepost) | **POST** /close | 
*DefaultApi* | [**convertGiftToStarsPost**](docs/DefaultApi.md#convertgifttostarspost) | **POST** /convertGiftToStars | 
*DefaultApi* | [**copyMessagePost**](docs/DefaultApi.md#copymessagepost) | **POST** /copyMessage | 
*DefaultApi* | [**copyMessagesPost**](docs/DefaultApi.md#copymessagespost) | **POST** /copyMessages | 
*DefaultApi* | [**createChatInviteLinkPost**](docs/DefaultApi.md#createchatinvitelinkpost) | **POST** /createChatInviteLink | 
*DefaultApi* | [**createChatSubscriptionInviteLinkPost**](docs/DefaultApi.md#createchatsubscriptioninvitelinkpost) | **POST** /createChatSubscriptionInviteLink | 
*DefaultApi* | [**createForumTopicPost**](docs/DefaultApi.md#createforumtopicpost) | **POST** /createForumTopic | 
*DefaultApi* | [**createInvoiceLinkPost**](docs/DefaultApi.md#createinvoicelinkpost) | **POST** /createInvoiceLink | 
*DefaultApi* | [**createNewStickerSetPost**](docs/DefaultApi.md#createnewstickersetpost) | **POST** /createNewStickerSet | 
*DefaultApi* | [**declineChatJoinRequestPost**](docs/DefaultApi.md#declinechatjoinrequestpost) | **POST** /declineChatJoinRequest | 
*DefaultApi* | [**deleteBusinessMessagesPost**](docs/DefaultApi.md#deletebusinessmessagespost) | **POST** /deleteBusinessMessages | 
*DefaultApi* | [**deleteChatPhotoPost**](docs/DefaultApi.md#deletechatphotopost) | **POST** /deleteChatPhoto | 
*DefaultApi* | [**deleteChatStickerSetPost**](docs/DefaultApi.md#deletechatstickersetpost) | **POST** /deleteChatStickerSet | 
*DefaultApi* | [**deleteForumTopicPost**](docs/DefaultApi.md#deleteforumtopicpost) | **POST** /deleteForumTopic | 
*DefaultApi* | [**deleteMessagePost**](docs/DefaultApi.md#deletemessagepost) | **POST** /deleteMessage | 
*DefaultApi* | [**deleteMessagesPost**](docs/DefaultApi.md#deletemessagespost) | **POST** /deleteMessages | 
*DefaultApi* | [**deleteMyCommandsPost**](docs/DefaultApi.md#deletemycommandspost) | **POST** /deleteMyCommands | 
*DefaultApi* | [**deleteStickerFromSetPost**](docs/DefaultApi.md#deletestickerfromsetpost) | **POST** /deleteStickerFromSet | 
*DefaultApi* | [**deleteStickerSetPost**](docs/DefaultApi.md#deletestickersetpost) | **POST** /deleteStickerSet | 
*DefaultApi* | [**deleteStoryPost**](docs/DefaultApi.md#deletestorypost) | **POST** /deleteStory | 
*DefaultApi* | [**deleteWebhookPost**](docs/DefaultApi.md#deletewebhookpost) | **POST** /deleteWebhook | 
*DefaultApi* | [**editChatInviteLinkPost**](docs/DefaultApi.md#editchatinvitelinkpost) | **POST** /editChatInviteLink | 
*DefaultApi* | [**editChatSubscriptionInviteLinkPost**](docs/DefaultApi.md#editchatsubscriptioninvitelinkpost) | **POST** /editChatSubscriptionInviteLink | 
*DefaultApi* | [**editForumTopicPost**](docs/DefaultApi.md#editforumtopicpost) | **POST** /editForumTopic | 
*DefaultApi* | [**editGeneralForumTopicPost**](docs/DefaultApi.md#editgeneralforumtopicpost) | **POST** /editGeneralForumTopic | 
*DefaultApi* | [**editMessageCaptionPost**](docs/DefaultApi.md#editmessagecaptionpost) | **POST** /editMessageCaption | 
*DefaultApi* | [**editMessageLiveLocationPost**](docs/DefaultApi.md#editmessagelivelocationpost) | **POST** /editMessageLiveLocation | 
*DefaultApi* | [**editMessageMediaPost**](docs/DefaultApi.md#editmessagemediapost) | **POST** /editMessageMedia | 
*DefaultApi* | [**editMessageReplyMarkupPost**](docs/DefaultApi.md#editmessagereplymarkuppost) | **POST** /editMessageReplyMarkup | 
*DefaultApi* | [**editMessageTextPost**](docs/DefaultApi.md#editmessagetextpost) | **POST** /editMessageText | 
*DefaultApi* | [**editStoryPost**](docs/DefaultApi.md#editstorypost) | **POST** /editStory | 
*DefaultApi* | [**editUserStarSubscriptionPost**](docs/DefaultApi.md#edituserstarsubscriptionpost) | **POST** /editUserStarSubscription | 
*DefaultApi* | [**exportChatInviteLinkPost**](docs/DefaultApi.md#exportchatinvitelinkpost) | **POST** /exportChatInviteLink | 
*DefaultApi* | [**forwardMessagePost**](docs/DefaultApi.md#forwardmessagepost) | **POST** /forwardMessage | 
*DefaultApi* | [**forwardMessagesPost**](docs/DefaultApi.md#forwardmessagespost) | **POST** /forwardMessages | 
*DefaultApi* | [**getAvailableGiftsPost**](docs/DefaultApi.md#getavailablegiftspost) | **POST** /getAvailableGifts | 
*DefaultApi* | [**getBusinessAccountGiftsPost**](docs/DefaultApi.md#getbusinessaccountgiftspost) | **POST** /getBusinessAccountGifts | 
*DefaultApi* | [**getBusinessAccountStarBalancePost**](docs/DefaultApi.md#getbusinessaccountstarbalancepost) | **POST** /getBusinessAccountStarBalance | 
*DefaultApi* | [**getBusinessConnectionPost**](docs/DefaultApi.md#getbusinessconnectionpost) | **POST** /getBusinessConnection | 
*DefaultApi* | [**getChatAdministratorsPost**](docs/DefaultApi.md#getchatadministratorspost) | **POST** /getChatAdministrators | 
*DefaultApi* | [**getChatMemberCountPost**](docs/DefaultApi.md#getchatmembercountpost) | **POST** /getChatMemberCount | 
*DefaultApi* | [**getChatMemberPost**](docs/DefaultApi.md#getchatmemberpost) | **POST** /getChatMember | 
*DefaultApi* | [**getChatMenuButtonPost**](docs/DefaultApi.md#getchatmenubuttonpost) | **POST** /getChatMenuButton | 
*DefaultApi* | [**getChatPost**](docs/DefaultApi.md#getchatpost) | **POST** /getChat | 
*DefaultApi* | [**getCustomEmojiStickersPost**](docs/DefaultApi.md#getcustomemojistickerspost) | **POST** /getCustomEmojiStickers | 
*DefaultApi* | [**getFilePost**](docs/DefaultApi.md#getfilepost) | **POST** /getFile | 
*DefaultApi* | [**getForumTopicIconStickersPost**](docs/DefaultApi.md#getforumtopiciconstickerspost) | **POST** /getForumTopicIconStickers | 
*DefaultApi* | [**getGameHighScoresPost**](docs/DefaultApi.md#getgamehighscorespost) | **POST** /getGameHighScores | 
*DefaultApi* | [**getMePost**](docs/DefaultApi.md#getmepost) | **POST** /getMe | 
*DefaultApi* | [**getMyCommandsPost**](docs/DefaultApi.md#getmycommandspost) | **POST** /getMyCommands | 
*DefaultApi* | [**getMyDefaultAdministratorRightsPost**](docs/DefaultApi.md#getmydefaultadministratorrightspost) | **POST** /getMyDefaultAdministratorRights | 
*DefaultApi* | [**getMyDescriptionPost**](docs/DefaultApi.md#getmydescriptionpost) | **POST** /getMyDescription | 
*DefaultApi* | [**getMyNamePost**](docs/DefaultApi.md#getmynamepost) | **POST** /getMyName | 
*DefaultApi* | [**getMyShortDescriptionPost**](docs/DefaultApi.md#getmyshortdescriptionpost) | **POST** /getMyShortDescription | 
*DefaultApi* | [**getStarTransactionsPost**](docs/DefaultApi.md#getstartransactionspost) | **POST** /getStarTransactions | 
*DefaultApi* | [**getStickerSetPost**](docs/DefaultApi.md#getstickersetpost) | **POST** /getStickerSet | 
*DefaultApi* | [**getUpdatesPost**](docs/DefaultApi.md#getupdatespost) | **POST** /getUpdates | 
*DefaultApi* | [**getUserChatBoostsPost**](docs/DefaultApi.md#getuserchatboostspost) | **POST** /getUserChatBoosts | 
*DefaultApi* | [**getUserProfilePhotosPost**](docs/DefaultApi.md#getuserprofilephotospost) | **POST** /getUserProfilePhotos | 
*DefaultApi* | [**getWebhookInfoPost**](docs/DefaultApi.md#getwebhookinfopost) | **POST** /getWebhookInfo | 
*DefaultApi* | [**giftPremiumSubscriptionPost**](docs/DefaultApi.md#giftpremiumsubscriptionpost) | **POST** /giftPremiumSubscription | 
*DefaultApi* | [**hideGeneralForumTopicPost**](docs/DefaultApi.md#hidegeneralforumtopicpost) | **POST** /hideGeneralForumTopic | 
*DefaultApi* | [**leaveChatPost**](docs/DefaultApi.md#leavechatpost) | **POST** /leaveChat | 
*DefaultApi* | [**logOutPost**](docs/DefaultApi.md#logoutpost) | **POST** /logOut | 
*DefaultApi* | [**pinChatMessagePost**](docs/DefaultApi.md#pinchatmessagepost) | **POST** /pinChatMessage | 
*DefaultApi* | [**postStoryPost**](docs/DefaultApi.md#poststorypost) | **POST** /postStory | 
*DefaultApi* | [**promoteChatMemberPost**](docs/DefaultApi.md#promotechatmemberpost) | **POST** /promoteChatMember | 
*DefaultApi* | [**readBusinessMessagePost**](docs/DefaultApi.md#readbusinessmessagepost) | **POST** /readBusinessMessage | 
*DefaultApi* | [**refundStarPaymentPost**](docs/DefaultApi.md#refundstarpaymentpost) | **POST** /refundStarPayment | 
*DefaultApi* | [**removeBusinessAccountProfilePhotoPost**](docs/DefaultApi.md#removebusinessaccountprofilephotopost) | **POST** /removeBusinessAccountProfilePhoto | 
*DefaultApi* | [**removeChatVerificationPost**](docs/DefaultApi.md#removechatverificationpost) | **POST** /removeChatVerification | 
*DefaultApi* | [**removeUserVerificationPost**](docs/DefaultApi.md#removeuserverificationpost) | **POST** /removeUserVerification | 
*DefaultApi* | [**reopenForumTopicPost**](docs/DefaultApi.md#reopenforumtopicpost) | **POST** /reopenForumTopic | 
*DefaultApi* | [**reopenGeneralForumTopicPost**](docs/DefaultApi.md#reopengeneralforumtopicpost) | **POST** /reopenGeneralForumTopic | 
*DefaultApi* | [**replaceStickerInSetPost**](docs/DefaultApi.md#replacestickerinsetpost) | **POST** /replaceStickerInSet | 
*DefaultApi* | [**restrictChatMemberPost**](docs/DefaultApi.md#restrictchatmemberpost) | **POST** /restrictChatMember | 
*DefaultApi* | [**revokeChatInviteLinkPost**](docs/DefaultApi.md#revokechatinvitelinkpost) | **POST** /revokeChatInviteLink | 
*DefaultApi* | [**savePreparedInlineMessagePost**](docs/DefaultApi.md#savepreparedinlinemessagepost) | **POST** /savePreparedInlineMessage | 
*DefaultApi* | [**sendAnimationPost**](docs/DefaultApi.md#sendanimationpost) | **POST** /sendAnimation | 
*DefaultApi* | [**sendAudioPost**](docs/DefaultApi.md#sendaudiopost) | **POST** /sendAudio | 
*DefaultApi* | [**sendChatActionPost**](docs/DefaultApi.md#sendchatactionpost) | **POST** /sendChatAction | 
*DefaultApi* | [**sendContactPost**](docs/DefaultApi.md#sendcontactpost) | **POST** /sendContact | 
*DefaultApi* | [**sendDicePost**](docs/DefaultApi.md#senddicepost) | **POST** /sendDice | 
*DefaultApi* | [**sendDocumentPost**](docs/DefaultApi.md#senddocumentpost) | **POST** /sendDocument | 
*DefaultApi* | [**sendGamePost**](docs/DefaultApi.md#sendgamepost) | **POST** /sendGame | 
*DefaultApi* | [**sendGiftPost**](docs/DefaultApi.md#sendgiftpost) | **POST** /sendGift | 
*DefaultApi* | [**sendInvoicePost**](docs/DefaultApi.md#sendinvoicepost) | **POST** /sendInvoice | 
*DefaultApi* | [**sendLocationPost**](docs/DefaultApi.md#sendlocationpost) | **POST** /sendLocation | 
*DefaultApi* | [**sendMediaGroupPost**](docs/DefaultApi.md#sendmediagrouppost) | **POST** /sendMediaGroup | 
*DefaultApi* | [**sendMessagePost**](docs/DefaultApi.md#sendmessagepost) | **POST** /sendMessage | 
*DefaultApi* | [**sendPaidMediaPost**](docs/DefaultApi.md#sendpaidmediapost) | **POST** /sendPaidMedia | 
*DefaultApi* | [**sendPhotoPost**](docs/DefaultApi.md#sendphotopost) | **POST** /sendPhoto | 
*DefaultApi* | [**sendPollPost**](docs/DefaultApi.md#sendpollpost) | **POST** /sendPoll | 
*DefaultApi* | [**sendStickerPost**](docs/DefaultApi.md#sendstickerpost) | **POST** /sendSticker | 
*DefaultApi* | [**sendVenuePost**](docs/DefaultApi.md#sendvenuepost) | **POST** /sendVenue | 
*DefaultApi* | [**sendVideoNotePost**](docs/DefaultApi.md#sendvideonotepost) | **POST** /sendVideoNote | 
*DefaultApi* | [**sendVideoPost**](docs/DefaultApi.md#sendvideopost) | **POST** /sendVideo | 
*DefaultApi* | [**sendVoicePost**](docs/DefaultApi.md#sendvoicepost) | **POST** /sendVoice | 
*DefaultApi* | [**setBusinessAccountBioPost**](docs/DefaultApi.md#setbusinessaccountbiopost) | **POST** /setBusinessAccountBio | 
*DefaultApi* | [**setBusinessAccountGiftSettingsPost**](docs/DefaultApi.md#setbusinessaccountgiftsettingspost) | **POST** /setBusinessAccountGiftSettings | 
*DefaultApi* | [**setBusinessAccountNamePost**](docs/DefaultApi.md#setbusinessaccountnamepost) | **POST** /setBusinessAccountName | 
*DefaultApi* | [**setBusinessAccountProfilePhotoPost**](docs/DefaultApi.md#setbusinessaccountprofilephotopost) | **POST** /setBusinessAccountProfilePhoto | 
*DefaultApi* | [**setBusinessAccountUsernamePost**](docs/DefaultApi.md#setbusinessaccountusernamepost) | **POST** /setBusinessAccountUsername | 
*DefaultApi* | [**setChatAdministratorCustomTitlePost**](docs/DefaultApi.md#setchatadministratorcustomtitlepost) | **POST** /setChatAdministratorCustomTitle | 
*DefaultApi* | [**setChatDescriptionPost**](docs/DefaultApi.md#setchatdescriptionpost) | **POST** /setChatDescription | 
*DefaultApi* | [**setChatMenuButtonPost**](docs/DefaultApi.md#setchatmenubuttonpost) | **POST** /setChatMenuButton | 
*DefaultApi* | [**setChatPermissionsPost**](docs/DefaultApi.md#setchatpermissionspost) | **POST** /setChatPermissions | 
*DefaultApi* | [**setChatPhotoPost**](docs/DefaultApi.md#setchatphotopost) | **POST** /setChatPhoto | 
*DefaultApi* | [**setChatStickerSetPost**](docs/DefaultApi.md#setchatstickersetpost) | **POST** /setChatStickerSet | 
*DefaultApi* | [**setChatTitlePost**](docs/DefaultApi.md#setchattitlepost) | **POST** /setChatTitle | 
*DefaultApi* | [**setCustomEmojiStickerSetThumbnailPost**](docs/DefaultApi.md#setcustomemojistickersetthumbnailpost) | **POST** /setCustomEmojiStickerSetThumbnail | 
*DefaultApi* | [**setGameScorePost**](docs/DefaultApi.md#setgamescorepost) | **POST** /setGameScore | 
*DefaultApi* | [**setMessageReactionPost**](docs/DefaultApi.md#setmessagereactionpost) | **POST** /setMessageReaction | 
*DefaultApi* | [**setMyCommandsPost**](docs/DefaultApi.md#setmycommandspost) | **POST** /setMyCommands | 
*DefaultApi* | [**setMyDefaultAdministratorRightsPost**](docs/DefaultApi.md#setmydefaultadministratorrightspost) | **POST** /setMyDefaultAdministratorRights | 
*DefaultApi* | [**setMyDescriptionPost**](docs/DefaultApi.md#setmydescriptionpost) | **POST** /setMyDescription | 
*DefaultApi* | [**setMyNamePost**](docs/DefaultApi.md#setmynamepost) | **POST** /setMyName | 
*DefaultApi* | [**setMyShortDescriptionPost**](docs/DefaultApi.md#setmyshortdescriptionpost) | **POST** /setMyShortDescription | 
*DefaultApi* | [**setPassportDataErrorsPost**](docs/DefaultApi.md#setpassportdataerrorspost) | **POST** /setPassportDataErrors | 
*DefaultApi* | [**setStickerEmojiListPost**](docs/DefaultApi.md#setstickeremojilistpost) | **POST** /setStickerEmojiList | 
*DefaultApi* | [**setStickerKeywordsPost**](docs/DefaultApi.md#setstickerkeywordspost) | **POST** /setStickerKeywords | 
*DefaultApi* | [**setStickerMaskPositionPost**](docs/DefaultApi.md#setstickermaskpositionpost) | **POST** /setStickerMaskPosition | 
*DefaultApi* | [**setStickerPositionInSetPost**](docs/DefaultApi.md#setstickerpositioninsetpost) | **POST** /setStickerPositionInSet | 
*DefaultApi* | [**setStickerSetThumbnailPost**](docs/DefaultApi.md#setstickersetthumbnailpost) | **POST** /setStickerSetThumbnail | 
*DefaultApi* | [**setStickerSetTitlePost**](docs/DefaultApi.md#setstickersettitlepost) | **POST** /setStickerSetTitle | 
*DefaultApi* | [**setUserEmojiStatusPost**](docs/DefaultApi.md#setuseremojistatuspost) | **POST** /setUserEmojiStatus | 
*DefaultApi* | [**setWebhookPost**](docs/DefaultApi.md#setwebhookpost) | **POST** /setWebhook | 
*DefaultApi* | [**stopMessageLiveLocationPost**](docs/DefaultApi.md#stopmessagelivelocationpost) | **POST** /stopMessageLiveLocation | 
*DefaultApi* | [**stopPollPost**](docs/DefaultApi.md#stoppollpost) | **POST** /stopPoll | 
*DefaultApi* | [**transferBusinessAccountStarsPost**](docs/DefaultApi.md#transferbusinessaccountstarspost) | **POST** /transferBusinessAccountStars | 
*DefaultApi* | [**transferGiftPost**](docs/DefaultApi.md#transfergiftpost) | **POST** /transferGift | 
*DefaultApi* | [**unbanChatMemberPost**](docs/DefaultApi.md#unbanchatmemberpost) | **POST** /unbanChatMember | 
*DefaultApi* | [**unbanChatSenderChatPost**](docs/DefaultApi.md#unbanchatsenderchatpost) | **POST** /unbanChatSenderChat | 
*DefaultApi* | [**unhideGeneralForumTopicPost**](docs/DefaultApi.md#unhidegeneralforumtopicpost) | **POST** /unhideGeneralForumTopic | 
*DefaultApi* | [**unpinAllChatMessagesPost**](docs/DefaultApi.md#unpinallchatmessagespost) | **POST** /unpinAllChatMessages | 
*DefaultApi* | [**unpinAllForumTopicMessagesPost**](docs/DefaultApi.md#unpinallforumtopicmessagespost) | **POST** /unpinAllForumTopicMessages | 
*DefaultApi* | [**unpinAllGeneralForumTopicMessagesPost**](docs/DefaultApi.md#unpinallgeneralforumtopicmessagespost) | **POST** /unpinAllGeneralForumTopicMessages | 
*DefaultApi* | [**unpinChatMessagePost**](docs/DefaultApi.md#unpinchatmessagepost) | **POST** /unpinChatMessage | 
*DefaultApi* | [**upgradeGiftPost**](docs/DefaultApi.md#upgradegiftpost) | **POST** /upgradeGift | 
*DefaultApi* | [**uploadStickerFilePost**](docs/DefaultApi.md#uploadstickerfilepost) | **POST** /uploadStickerFile | 
*DefaultApi* | [**verifyChatPost**](docs/DefaultApi.md#verifychatpost) | **POST** /verifyChat | 
*DefaultApi* | [**verifyUserPost**](docs/DefaultApi.md#verifyuserpost) | **POST** /verifyUser | 


### Documentation For Models

 - [AcceptedGiftTypes](docs/AcceptedGiftTypes.md)
 - [AffiliateInfo](docs/AffiliateInfo.md)
 - [Animation](docs/Animation.md)
 - [AnswerCallbackQueryPostRequest](docs/AnswerCallbackQueryPostRequest.md)
 - [AnswerInlineQueryPostRequest](docs/AnswerInlineQueryPostRequest.md)
 - [AnswerPreCheckoutQueryPostRequest](docs/AnswerPreCheckoutQueryPostRequest.md)
 - [AnswerShippingQueryPostRequest](docs/AnswerShippingQueryPostRequest.md)
 - [AnswerWebAppQueryPost200Response](docs/AnswerWebAppQueryPost200Response.md)
 - [AnswerWebAppQueryPostRequest](docs/AnswerWebAppQueryPostRequest.md)
 - [ApproveChatJoinRequestPostRequest](docs/ApproveChatJoinRequestPostRequest.md)
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
 - [BanChatMemberPostRequest](docs/BanChatMemberPostRequest.md)
 - [BanChatMemberPostRequestChatId](docs/BanChatMemberPostRequestChatId.md)
 - [BanChatSenderChatPostRequest](docs/BanChatSenderChatPostRequest.md)
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
 - [CloseForumTopicPostRequest](docs/CloseForumTopicPostRequest.md)
 - [Contact](docs/Contact.md)
 - [ConvertGiftToStarsPostRequest](docs/ConvertGiftToStarsPostRequest.md)
 - [CopyMessagePost200Response](docs/CopyMessagePost200Response.md)
 - [CopyMessagePostRequest](docs/CopyMessagePostRequest.md)
 - [CopyMessagesPostRequest](docs/CopyMessagesPostRequest.md)
 - [CopyTextButton](docs/CopyTextButton.md)
 - [CreateChatInviteLinkPost200Response](docs/CreateChatInviteLinkPost200Response.md)
 - [CreateChatInviteLinkPostRequest](docs/CreateChatInviteLinkPostRequest.md)
 - [CreateChatSubscriptionInviteLinkPostRequest](docs/CreateChatSubscriptionInviteLinkPostRequest.md)
 - [CreateChatSubscriptionInviteLinkPostRequestChatId](docs/CreateChatSubscriptionInviteLinkPostRequestChatId.md)
 - [CreateForumTopicPost200Response](docs/CreateForumTopicPost200Response.md)
 - [CreateForumTopicPostRequest](docs/CreateForumTopicPostRequest.md)
 - [CreateInvoiceLinkPostRequest](docs/CreateInvoiceLinkPostRequest.md)
 - [DeleteBusinessMessagesPostRequest](docs/DeleteBusinessMessagesPostRequest.md)
 - [DeleteChatStickerSetPostRequest](docs/DeleteChatStickerSetPostRequest.md)
 - [DeleteMessagePostRequest](docs/DeleteMessagePostRequest.md)
 - [DeleteMessagesPostRequest](docs/DeleteMessagesPostRequest.md)
 - [DeleteMyCommandsPostRequest](docs/DeleteMyCommandsPostRequest.md)
 - [DeleteStickerFromSetPostRequest](docs/DeleteStickerFromSetPostRequest.md)
 - [DeleteStickerSetPostRequest](docs/DeleteStickerSetPostRequest.md)
 - [DeleteStoryPostRequest](docs/DeleteStoryPostRequest.md)
 - [DeleteWebhookPostRequest](docs/DeleteWebhookPostRequest.md)
 - [Dice](docs/Dice.md)
 - [Document](docs/Document.md)
 - [EditChatInviteLinkPostRequest](docs/EditChatInviteLinkPostRequest.md)
 - [EditChatSubscriptionInviteLinkPostRequest](docs/EditChatSubscriptionInviteLinkPostRequest.md)
 - [EditForumTopicPostRequest](docs/EditForumTopicPostRequest.md)
 - [EditGeneralForumTopicPostRequest](docs/EditGeneralForumTopicPostRequest.md)
 - [EditMessageCaptionPostRequest](docs/EditMessageCaptionPostRequest.md)
 - [EditMessageLiveLocationPostRequest](docs/EditMessageLiveLocationPostRequest.md)
 - [EditMessageReplyMarkupPostRequest](docs/EditMessageReplyMarkupPostRequest.md)
 - [EditMessageTextPost200Response](docs/EditMessageTextPost200Response.md)
 - [EditMessageTextPost200ResponseResult](docs/EditMessageTextPost200ResponseResult.md)
 - [EditMessageTextPostRequest](docs/EditMessageTextPostRequest.md)
 - [EditMessageTextPostRequestChatId](docs/EditMessageTextPostRequestChatId.md)
 - [EditUserStarSubscriptionPostRequest](docs/EditUserStarSubscriptionPostRequest.md)
 - [EncryptedCredentials](docs/EncryptedCredentials.md)
 - [EncryptedPassportElement](docs/EncryptedPassportElement.md)
 - [ExportChatInviteLinkPost200Response](docs/ExportChatInviteLinkPost200Response.md)
 - [ExportChatInviteLinkPostRequest](docs/ExportChatInviteLinkPostRequest.md)
 - [ExternalReplyInfo](docs/ExternalReplyInfo.md)
 - [ForceReply](docs/ForceReply.md)
 - [ForumTopic](docs/ForumTopic.md)
 - [ForumTopicCreated](docs/ForumTopicCreated.md)
 - [ForumTopicEdited](docs/ForumTopicEdited.md)
 - [ForwardMessagePostRequest](docs/ForwardMessagePostRequest.md)
 - [ForwardMessagePostRequestFromChatId](docs/ForwardMessagePostRequestFromChatId.md)
 - [ForwardMessagesPost200Response](docs/ForwardMessagesPost200Response.md)
 - [ForwardMessagesPostRequest](docs/ForwardMessagesPostRequest.md)
 - [ForwardMessagesPostRequestFromChatId](docs/ForwardMessagesPostRequestFromChatId.md)
 - [Game](docs/Game.md)
 - [GameHighScore](docs/GameHighScore.md)
 - [GetAvailableGiftsPost200Response](docs/GetAvailableGiftsPost200Response.md)
 - [GetBusinessAccountGiftsPost200Response](docs/GetBusinessAccountGiftsPost200Response.md)
 - [GetBusinessAccountGiftsPostRequest](docs/GetBusinessAccountGiftsPostRequest.md)
 - [GetBusinessAccountStarBalancePost200Response](docs/GetBusinessAccountStarBalancePost200Response.md)
 - [GetBusinessConnectionPost200Response](docs/GetBusinessConnectionPost200Response.md)
 - [GetBusinessConnectionPostRequest](docs/GetBusinessConnectionPostRequest.md)
 - [GetChatAdministratorsPost200Response](docs/GetChatAdministratorsPost200Response.md)
 - [GetChatMemberCountPost200Response](docs/GetChatMemberCountPost200Response.md)
 - [GetChatMemberPost200Response](docs/GetChatMemberPost200Response.md)
 - [GetChatMemberPostRequest](docs/GetChatMemberPostRequest.md)
 - [GetChatMenuButtonPost200Response](docs/GetChatMenuButtonPost200Response.md)
 - [GetChatMenuButtonPostRequest](docs/GetChatMenuButtonPostRequest.md)
 - [GetChatPost200Response](docs/GetChatPost200Response.md)
 - [GetCustomEmojiStickersPostRequest](docs/GetCustomEmojiStickersPostRequest.md)
 - [GetFilePost200Response](docs/GetFilePost200Response.md)
 - [GetFilePostRequest](docs/GetFilePostRequest.md)
 - [GetForumTopicIconStickersPost200Response](docs/GetForumTopicIconStickersPost200Response.md)
 - [GetGameHighScoresPost200Response](docs/GetGameHighScoresPost200Response.md)
 - [GetGameHighScoresPostRequest](docs/GetGameHighScoresPostRequest.md)
 - [GetMePost200Response](docs/GetMePost200Response.md)
 - [GetMyCommandsPost200Response](docs/GetMyCommandsPost200Response.md)
 - [GetMyCommandsPostRequest](docs/GetMyCommandsPostRequest.md)
 - [GetMyDefaultAdministratorRightsPost200Response](docs/GetMyDefaultAdministratorRightsPost200Response.md)
 - [GetMyDefaultAdministratorRightsPostRequest](docs/GetMyDefaultAdministratorRightsPostRequest.md)
 - [GetMyDescriptionPost200Response](docs/GetMyDescriptionPost200Response.md)
 - [GetMyNamePost200Response](docs/GetMyNamePost200Response.md)
 - [GetMyNamePostRequest](docs/GetMyNamePostRequest.md)
 - [GetMyShortDescriptionPost200Response](docs/GetMyShortDescriptionPost200Response.md)
 - [GetStarTransactionsPost200Response](docs/GetStarTransactionsPost200Response.md)
 - [GetStarTransactionsPostRequest](docs/GetStarTransactionsPostRequest.md)
 - [GetStickerSetPost200Response](docs/GetStickerSetPost200Response.md)
 - [GetStickerSetPostRequest](docs/GetStickerSetPostRequest.md)
 - [GetUpdatesPost200Response](docs/GetUpdatesPost200Response.md)
 - [GetUpdatesPostRequest](docs/GetUpdatesPostRequest.md)
 - [GetUserChatBoostsPost200Response](docs/GetUserChatBoostsPost200Response.md)
 - [GetUserChatBoostsPostRequest](docs/GetUserChatBoostsPostRequest.md)
 - [GetUserChatBoostsPostRequestChatId](docs/GetUserChatBoostsPostRequestChatId.md)
 - [GetUserProfilePhotosPost200Response](docs/GetUserProfilePhotosPost200Response.md)
 - [GetUserProfilePhotosPostRequest](docs/GetUserProfilePhotosPostRequest.md)
 - [GetWebhookInfoPost200Response](docs/GetWebhookInfoPost200Response.md)
 - [Gift](docs/Gift.md)
 - [GiftInfo](docs/GiftInfo.md)
 - [GiftPremiumSubscriptionPostRequest](docs/GiftPremiumSubscriptionPostRequest.md)
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
 - [LeaveChatPostRequest](docs/LeaveChatPostRequest.md)
 - [LeaveChatPostRequestChatId](docs/LeaveChatPostRequestChatId.md)
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
 - [PinChatMessagePostRequest](docs/PinChatMessagePostRequest.md)
 - [Poll](docs/Poll.md)
 - [PollAnswer](docs/PollAnswer.md)
 - [PollOption](docs/PollOption.md)
 - [PostStoryPost200Response](docs/PostStoryPost200Response.md)
 - [PreCheckoutQuery](docs/PreCheckoutQuery.md)
 - [PreparedInlineMessage](docs/PreparedInlineMessage.md)
 - [PromoteChatMemberPostRequest](docs/PromoteChatMemberPostRequest.md)
 - [ProximityAlertTriggered](docs/ProximityAlertTriggered.md)
 - [ReactionCount](docs/ReactionCount.md)
 - [ReactionType](docs/ReactionType.md)
 - [ReactionTypeCustomEmoji](docs/ReactionTypeCustomEmoji.md)
 - [ReactionTypeEmoji](docs/ReactionTypeEmoji.md)
 - [ReactionTypePaid](docs/ReactionTypePaid.md)
 - [ReadBusinessMessagePostRequest](docs/ReadBusinessMessagePostRequest.md)
 - [RefundStarPaymentPostRequest](docs/RefundStarPaymentPostRequest.md)
 - [RefundedPayment](docs/RefundedPayment.md)
 - [RemoveBusinessAccountProfilePhotoPostRequest](docs/RemoveBusinessAccountProfilePhotoPostRequest.md)
 - [RemoveUserVerificationPostRequest](docs/RemoveUserVerificationPostRequest.md)
 - [ReplyKeyboardMarkup](docs/ReplyKeyboardMarkup.md)
 - [ReplyKeyboardRemove](docs/ReplyKeyboardRemove.md)
 - [ReplyParameters](docs/ReplyParameters.md)
 - [ReplyParametersChatId](docs/ReplyParametersChatId.md)
 - [ResponseParameters](docs/ResponseParameters.md)
 - [RestrictChatMemberPostRequest](docs/RestrictChatMemberPostRequest.md)
 - [RestrictChatMemberPostRequestChatId](docs/RestrictChatMemberPostRequestChatId.md)
 - [RevenueWithdrawalState](docs/RevenueWithdrawalState.md)
 - [RevenueWithdrawalStateFailed](docs/RevenueWithdrawalStateFailed.md)
 - [RevenueWithdrawalStatePending](docs/RevenueWithdrawalStatePending.md)
 - [RevenueWithdrawalStateSucceeded](docs/RevenueWithdrawalStateSucceeded.md)
 - [RevokeChatInviteLinkPostRequest](docs/RevokeChatInviteLinkPostRequest.md)
 - [RevokeChatInviteLinkPostRequestChatId](docs/RevokeChatInviteLinkPostRequestChatId.md)
 - [SavePreparedInlineMessagePost200Response](docs/SavePreparedInlineMessagePost200Response.md)
 - [SavePreparedInlineMessagePostRequest](docs/SavePreparedInlineMessagePostRequest.md)
 - [SendAnimationPostRequestAnimation](docs/SendAnimationPostRequestAnimation.md)
 - [SendAudioPostRequestAudio](docs/SendAudioPostRequestAudio.md)
 - [SendAudioPostRequestThumbnail](docs/SendAudioPostRequestThumbnail.md)
 - [SendChatActionPostRequest](docs/SendChatActionPostRequest.md)
 - [SendContactPostRequest](docs/SendContactPostRequest.md)
 - [SendDicePostRequest](docs/SendDicePostRequest.md)
 - [SendDocumentPostRequestDocument](docs/SendDocumentPostRequestDocument.md)
 - [SendGamePostRequest](docs/SendGamePostRequest.md)
 - [SendGiftPostRequest](docs/SendGiftPostRequest.md)
 - [SendGiftPostRequestChatId](docs/SendGiftPostRequestChatId.md)
 - [SendInvoicePostRequest](docs/SendInvoicePostRequest.md)
 - [SendLocationPostRequest](docs/SendLocationPostRequest.md)
 - [SendMediaGroupPost200Response](docs/SendMediaGroupPost200Response.md)
 - [SendMediaGroupPostRequestMediaInner](docs/SendMediaGroupPostRequestMediaInner.md)
 - [SendMessagePost200Response](docs/SendMessagePost200Response.md)
 - [SendMessagePostRequest](docs/SendMessagePostRequest.md)
 - [SendMessagePostRequestChatId](docs/SendMessagePostRequestChatId.md)
 - [SendMessagePostRequestReplyMarkup](docs/SendMessagePostRequestReplyMarkup.md)
 - [SendPaidMediaPostRequestChatId](docs/SendPaidMediaPostRequestChatId.md)
 - [SendPhotoPostRequestPhoto](docs/SendPhotoPostRequestPhoto.md)
 - [SendPollPostRequest](docs/SendPollPostRequest.md)
 - [SendStickerPostRequestSticker](docs/SendStickerPostRequestSticker.md)
 - [SendVenuePostRequest](docs/SendVenuePostRequest.md)
 - [SendVideoNotePostRequestVideoNote](docs/SendVideoNotePostRequestVideoNote.md)
 - [SendVideoPostRequestCover](docs/SendVideoPostRequestCover.md)
 - [SendVideoPostRequestVideo](docs/SendVideoPostRequestVideo.md)
 - [SendVoicePostRequestVoice](docs/SendVoicePostRequestVoice.md)
 - [SentWebAppMessage](docs/SentWebAppMessage.md)
 - [SetBusinessAccountBioPostRequest](docs/SetBusinessAccountBioPostRequest.md)
 - [SetBusinessAccountGiftSettingsPostRequest](docs/SetBusinessAccountGiftSettingsPostRequest.md)
 - [SetBusinessAccountNamePostRequest](docs/SetBusinessAccountNamePostRequest.md)
 - [SetBusinessAccountUsernamePostRequest](docs/SetBusinessAccountUsernamePostRequest.md)
 - [SetChatAdministratorCustomTitlePostRequest](docs/SetChatAdministratorCustomTitlePostRequest.md)
 - [SetChatDescriptionPostRequest](docs/SetChatDescriptionPostRequest.md)
 - [SetChatMenuButtonPostRequest](docs/SetChatMenuButtonPostRequest.md)
 - [SetChatPermissionsPostRequest](docs/SetChatPermissionsPostRequest.md)
 - [SetChatStickerSetPostRequest](docs/SetChatStickerSetPostRequest.md)
 - [SetChatTitlePostRequest](docs/SetChatTitlePostRequest.md)
 - [SetCustomEmojiStickerSetThumbnailPostRequest](docs/SetCustomEmojiStickerSetThumbnailPostRequest.md)
 - [SetGameScorePostRequest](docs/SetGameScorePostRequest.md)
 - [SetMessageReactionPostRequest](docs/SetMessageReactionPostRequest.md)
 - [SetMyCommandsPostRequest](docs/SetMyCommandsPostRequest.md)
 - [SetMyDefaultAdministratorRightsPostRequest](docs/SetMyDefaultAdministratorRightsPostRequest.md)
 - [SetMyDescriptionPostRequest](docs/SetMyDescriptionPostRequest.md)
 - [SetMyNamePostRequest](docs/SetMyNamePostRequest.md)
 - [SetMyShortDescriptionPostRequest](docs/SetMyShortDescriptionPostRequest.md)
 - [SetPassportDataErrorsPostRequest](docs/SetPassportDataErrorsPostRequest.md)
 - [SetStickerEmojiListPostRequest](docs/SetStickerEmojiListPostRequest.md)
 - [SetStickerKeywordsPostRequest](docs/SetStickerKeywordsPostRequest.md)
 - [SetStickerMaskPositionPostRequest](docs/SetStickerMaskPositionPostRequest.md)
 - [SetStickerPositionInSetPostRequest](docs/SetStickerPositionInSetPostRequest.md)
 - [SetStickerSetThumbnailPostRequestThumbnail](docs/SetStickerSetThumbnailPostRequestThumbnail.md)
 - [SetStickerSetTitlePostRequest](docs/SetStickerSetTitlePostRequest.md)
 - [SetUserEmojiStatusPostRequest](docs/SetUserEmojiStatusPostRequest.md)
 - [SetWebhookPost200Response](docs/SetWebhookPost200Response.md)
 - [SharedUser](docs/SharedUser.md)
 - [ShippingAddress](docs/ShippingAddress.md)
 - [ShippingOption](docs/ShippingOption.md)
 - [ShippingQuery](docs/ShippingQuery.md)
 - [StarAmount](docs/StarAmount.md)
 - [StarTransaction](docs/StarTransaction.md)
 - [StarTransactions](docs/StarTransactions.md)
 - [Sticker](docs/Sticker.md)
 - [StickerSet](docs/StickerSet.md)
 - [StopMessageLiveLocationPostRequest](docs/StopMessageLiveLocationPostRequest.md)
 - [StopPollPost200Response](docs/StopPollPost200Response.md)
 - [StopPollPostRequest](docs/StopPollPostRequest.md)
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
 - [TransferBusinessAccountStarsPostRequest](docs/TransferBusinessAccountStarsPostRequest.md)
 - [TransferGiftPostRequest](docs/TransferGiftPostRequest.md)
 - [UnbanChatMemberPostRequest](docs/UnbanChatMemberPostRequest.md)
 - [UniqueGift](docs/UniqueGift.md)
 - [UniqueGiftBackdrop](docs/UniqueGiftBackdrop.md)
 - [UniqueGiftBackdropColors](docs/UniqueGiftBackdropColors.md)
 - [UniqueGiftInfo](docs/UniqueGiftInfo.md)
 - [UniqueGiftModel](docs/UniqueGiftModel.md)
 - [UniqueGiftSymbol](docs/UniqueGiftSymbol.md)
 - [UnpinChatMessagePostRequest](docs/UnpinChatMessagePostRequest.md)
 - [Update](docs/Update.md)
 - [UpgradeGiftPostRequest](docs/UpgradeGiftPostRequest.md)
 - [User](docs/User.md)
 - [UserChatBoosts](docs/UserChatBoosts.md)
 - [UserProfilePhotos](docs/UserProfilePhotos.md)
 - [UsersShared](docs/UsersShared.md)
 - [Venue](docs/Venue.md)
 - [VerifyChatPostRequest](docs/VerifyChatPostRequest.md)
 - [VerifyUserPostRequest](docs/VerifyUserPostRequest.md)
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

