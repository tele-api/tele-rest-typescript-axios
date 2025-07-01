# StoryAreaType

Describes the type of a clickable area on a story. Currently, it can be one of  * [StoryAreaTypeLocation](https://core.telegram.org/bots/api/#storyareatypelocation) * [StoryAreaTypeSuggestedReaction](https://core.telegram.org/bots/api/#storyareatypesuggestedreaction) * [StoryAreaTypeLink](https://core.telegram.org/bots/api/#storyareatypelink) * [StoryAreaTypeWeather](https://core.telegram.org/bots/api/#storyareatypeweather) * [StoryAreaTypeUniqueGift](https://core.telegram.org/bots/api/#storyareatypeuniquegift)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the area, always “unique\\_gift” | [default to 'unique_gift']
**latitude** | **number** | Location latitude in degrees | [default to undefined]
**longitude** | **number** | Location longitude in degrees | [default to undefined]
**reaction_type** | [**ReactionType**](ReactionType.md) |  | [default to undefined]
**url** | **string** | HTTP or tg:// URL to be opened when the area is clicked | [default to undefined]
**temperature** | **number** | Temperature, in degree Celsius | [default to undefined]
**emoji** | **string** | Emoji representing the weather | [default to undefined]
**background_color** | **number** | A color of the area background in the ARGB format | [default to undefined]
**name** | **string** | Unique name of the gift | [default to undefined]
**address** | [**LocationAddress**](LocationAddress.md) |  | [optional] [default to undefined]
**is_dark** | **boolean** | *Optional*. Pass *True* if the reaction area has a dark background | [optional] [default to undefined]
**is_flipped** | **boolean** | *Optional*. Pass *True* if reaction area corner is flipped | [optional] [default to undefined]

## Example

```typescript
import { StoryAreaType } from 'tele_rest';

const instance: StoryAreaType = {
    type,
    latitude,
    longitude,
    reaction_type,
    url,
    temperature,
    emoji,
    background_color,
    name,
    address,
    is_dark,
    is_flipped,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
