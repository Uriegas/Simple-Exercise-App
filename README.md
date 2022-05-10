# Simple-Exercise-App

## Requirements:
* The app consist of `routines`, each routine consist of cards, a card is an `exercise`.
* An `exercise` is composed of name, time_duration, image_url.
* Each `exercise` is editable.
* Before starting another exercise there is a customizable time delay which satisfies `t >= 0`
* The user can create a `routine` which is defined as an ordered list of exercises, time of the routing should be displayed
    - routine_time = `SELECT SUM(time_duration) FROM exercises WHERE user = target_user`.
* The user can add an `exercise` to the app either creating it himself or selecting it from a predefined set of `exercises`.

## Future requirements:
* The user has the option to set a `schedule` to make his routines and the user should be notified `x` time before.
* Add multilenguage support in the settings menu.
    - The user has an option to enable the speaking mode in a `routine`, this option makes each exercise to be spoken aloud in addition to it being displayed.
* A user can connect the app to the web and copy others people routines.
