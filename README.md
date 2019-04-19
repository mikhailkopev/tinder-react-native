
<h3 align="center">
	Tinder Clone - React Native
</h3>

## Overview

**Perfect to start an Tinder Clone app.** 4 screens are availables : Explore, Matches, Messages and Profile. You'll find some components like Card Component to pass props and variant. No frameworks UI like Bootstrap or Material UI are used.

More features will be added to the project in the future.

### Running the project

Clone this repository :

```
git clone https://github.com/stevenpersia/tinder-react-native.git
cd tinder-react-native
```

Install packages :

```
npm install
```

When installation is complete, run with version of your choice :

```bash
react-native run-ios
# or
react-native run-android
```


## Props

### CardItem

| Name | Type | Required | Description | Example |
| -- | -- | -- | -- | -- |
| `image` | string | Yes | Picture of member. | `image="https://..."`|
| `name` | string | Yes | Name of member. | `name="John Doe"`|
| `description` | string | Yes | Description of member. | `description="Full-time Traveller. Globe Trotter."`|
| `matches` | string | Yes | Match percentage. | `matches="95"`|
| `actions` | boolean | No | Display actions buttons (Like, Dislike, ...). | `actions`|
| `onPressLeft` | function | No | Swipe card to left. | `onPressLeft={() => this.swiper.swipeLeft()}`|
| `onPressRight` | function | No | Swipe card to right. | `onPressRight={() => this.swiper.swipeRight()}`|
| `status` | string | No | Display online or offline badge (`Online` and `Offline`). | `status="Online"`|
| `variant` | boolean | No | Display another style of card (used for Matches screen). | `variant`|

### Message

| Name | Type | Required | Description | Example |
| -- | -- | -- | -- | -- |
| `image` | string | Yes | Picture of member. | `image="https://..."`|
| `name` | string | Yes | Name of member. | `name="John Doe"`|
| `lastMessage` | string | Yes | Last message of member. | `lastMessage="You want order in Gotham. Batman must take off his mask and turn himself in."`|


### ProfileItem

| Name | Type | Required | Description | Example |
| -- | -- | -- | -- | -- |
| `name` | string | Yes | Name of member. | `name="John Doe"`|
| `matches` | string | Yes | Match percentage. | `matches="95"`|
| `age` | string | No | Age of member. | `age="25"`|
| `location` | string | No | Location of member. | `location="Paris, France"`|
| `info1` | string | No | More information of member. | `info1="Straight, Single"`|
| `info2` | string | No | More information of member. | `info2="Tea Totaller & Loves Photography"`|
| `info3` | string | No | More information of member. | `info3="Beaches, Mountain & Coffee"`|
| `info4` | string | No | More information of member. | `info4="Last seen: 23h ago"`|

