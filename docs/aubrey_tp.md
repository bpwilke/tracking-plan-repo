Marketing Sources



### Account Created

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**account_create_date** | `string` |...|Required/Optional|
|**account_id** | `string` |...|Required/Optional|
|**account_name** | `string` |...|Required/Optional|
|**account_prop** | `string` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("Account Created" {
"account_create_date": "<<string>>"
"account_id": "<<string>>"
"account_name": "<<string>>"
"account_prop": "<<string>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Account Deleted

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**account_id** | `string` |...|Required/Optional|
|**account_name** | `string` |...|Required/Optional|
|**reason** | `string` |...|Required/Optional|
|**reason_number** | `string` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("Account Deleted" {
"account_id": "<<string>>"
"account_name": "<<string>>"
"reason": "<<string>>"
"reason_number": "<<string>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Aubrey Event

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**birthday** | `string` |...|Required/Optional|
|**company** | `string` |...|Required/Optional|
|**name** | `string` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("Aubrey Event" {
"birthday": "<<string>>"
"company": "<<string>>"
"name": "<<string>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Button Clicked

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**milo_is_a_bot** | `string` |...|Required/Optional|
|**milo_still_a_bot** | `string` |...|Required/Optional|
|**prop** | `string` |...|Required/Optional|
|**prop_10** | `string` |...|Required/Optional|
|**prop_3** | `string` |...|Required/Optional|
|**prop_6** | `string` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("Button Clicked" {
"milo_is_a_bot": "<<string>>"
"milo_still_a_bot": "<<string>>"
"prop": "<<string>>"
"prop_10": "<<string>>"
"prop_3": "<<string>>"
"prop_6": "<<string>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Earnin Conversion

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**account_id** | `string` |...|Required/Optional|
|**amount** | `string` |...|Required/Optional|
|**number** | `string` |...|Required/Optional|
|**turnover** | `string` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("Earnin Conversion" {
"account_id": "<<string>>"
"amount": "<<string>>"
"number": "<<string>>"
"turnover": "<<string>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Earnin Event

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
#### **JS**

```javascript
analytics.track("Earnin Event" {
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Email Marked as Spam

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
#### **JS**

```javascript
analytics.track("Email Marked as Spam" {
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Email Opened

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
#### **JS**

```javascript
analytics.track("Email Opened" {
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Kal

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
#### **JS**

```javascript
analytics.track("Kal" {
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### New Event A

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**property_a** | `string` |...|Required/Optional|
|**property_b** | `string` |...|Required/Optional|
|**property_c** | `integer` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("New Event A" {
"property_a": "<<string>>"
"property_b": "<<string>>"
"property_c": "<<integer>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Preferences Changed

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**prop** | `string` |...|Required/Optional|
|**prop_3** | `string` |...|Required/Optional|
|**prop_4** | `string` |...|Required/Optional|
|**reason** | `string` |...|Required/Optional|
|**sku** | `string` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("Preferences Changed" {
"prop": "<<string>>"
"prop_3": "<<string>>"
"prop_4": "<<string>>"
"reason": "<<string>>"
"sku": "<<string>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Product List Filtered

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**favorite_color** | `string` |...|Required/Optional|
|**first_name** | `string` |...|Required/Optional|
|**last_name** | `string` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("Product List Filtered" {
"favorite_color": "<<string>>"
"first_name": "<<string>>"
"last_name": "<<string>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Product List Viewed

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**account_type** | `string` |...|Required/Optional|
|**birthday** | `string` |...|Required/Optional|
|**campaign_name** | `string` |...|Required/Optional|
|**email** | `string` |...|Required/Optional|
|**email_subject** | `string` |...|Required/Optional|
|**favorite_color** | `string` |...|Required/Optional|
|**first_name** | `string` |...|Required/Optional|
|**trial_start_date** | `string` |...|Required/Optional|
|**user_id** | `integer` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("Product List Viewed" {
"account_type": "<<string>>"
"birthday": "<<string>>"
"campaign_name": "<<string>>"
"email": "<<string>>"
"email_subject": "<<string>>"
"favorite_color": "<<string>>"
"first_name": "<<string>>"
"trial_start_date": "<<string>>"
"user_id": "<<integer>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Products Searched

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**account_type** | `string` |...|Required/Optional|
|**birthday** | `string` |...|Required/Optional|
|**button_color** | `string` |...|Required/Optional|
|**button_text** | `string` |...|Required/Optional|
|**button_type** | `string` |...|Required/Optional|
|**user_id** | `integer` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("Products Searched" {
"account_type": "<<string>>"
"birthday": "<<string>>"
"button_color": "<<string>>"
"button_text": "<<string>>"
"button_type": "<<string>>"
"user_id": "<<integer>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Upside Event

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**property_a** | `integer` |...|Required/Optional|
|**property_b** | `string` |...|Required/Optional|
|**property_c** | `string` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("Upside Event" {
"property_a": "<<integer>>"
"property_b": "<<string>>"
"property_c": "<<string>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Video Playback Buffer Started

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
#### **JS**

```javascript
analytics.track("Video Playback Buffer Started" {
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Video Playback Interrupted

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
#### **JS**

```javascript
analytics.track("Video Playback Interrupted" {
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Video Playback Paused

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
|**video_name** | `string` |...|Required/Optional|
#### **JS**

```javascript
analytics.track("Video Playback Paused" {
"video_name": "<<string>>"
});
``` 

<!-- tabs:end -->

<!-- panels:end -->



### Video Playback Started

<!-- tabs:start -->
#### **Basics**

Fires when...
#### **Properties**

|**Name** | `Type` | Description | Required?|
| :--- | :--- | :--- | :---|
#### **JS**

```javascript
analytics.track("Video Playback Started" {
});
``` 

<!-- tabs:end -->

<!-- panels:end -->
