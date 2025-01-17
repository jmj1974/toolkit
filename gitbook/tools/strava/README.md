---
description: Social media fitness app with exercise map based on users' GPS data.
---

# Strava

## URL

[https://www.strava.com](https://www.strava.com)

## Description

Strava is a fitness app that allows users to publish various exercise activities on a map using GPS data. Activities are automatically mapped and key metrics are recorded. Strava also acts as a social network for fitness and outdor enthusiasts with each user having their own profile on the platform and possibilities to interact with each other. Researchers may use Strava to track a users' activities, gather location data, and understand patterns of movement.

1. **Profile Analysis:**
   * Username and Bio: Analyze users' profile information. Look for any clues or personal details that could be useful in identifying the individual.
   * Activity History: Review the user's activity history to understand their routines, frequented locations, and types of activities they engage in.
2. **Activity Details:**
   * Date and Time: Note the timestamps of activities to establish patterns of behavior or routine.
   * Location: Use the map feature to pinpoint specific locations where activities have taken place. Users may upload public photos or videos on their routes. This can include routes, starting points, and endpoints. [Note](https://support.strava.com/hc/en-us/articles/115000173384-Edit-Map-Visibility) that users may hide their start and end points up to one mile. [Strava](https://support.strava.com/hc/en-us/articles/115000173384-Edit-Map-Visibility) will hide the first and last 200 meters of activity maps by default after the first time a user logs an activity. Users may also [hide](https://stories.strava.com/articles/new-hide-your-start-time-on-any-activity) their activity start time.
   * Activity Type: Determine the types of activities the user engages in, which can provide insights into their interests and habits.
3. **Heat Maps:**
   * View a weekly and yearly [heat map](https://www.strava.com/maps/global-heatmap) of users' activities in any location around the world. Search a location on the heat map, use filters such as activity type and length of route, and add map overlays like popular segments. The [yearly](https://support.strava.com/hc/en-us/articles/216918877-Strava-Metro-and-the-Global-Heatmap) heat map is updated every month, and the [weekly](https://support.strava.com/hc/en-us/articles/26887067613197-The-Weekly-Heatmap) heat map is updated every 24 hours.
4. **Segments and Leaderboards:**
   * Explore segments where the user has recorded activities. [Segments](https://support.strava.com/hc/en-us/articles/216918167-Strava-Segments) designate specific portions of roads or trails created by users and allow users to compare times. Researchers may also click on segments to discover new profiles who have logged particular segments in a loction. Segment data includes a leaderboard that shows the date that a particular user has participated in an activity on that segment. Click on the user to view their profile and activities.
5. **Connections and Networks:**
   * Followers: Identify who the user follows and who follows them. This can reveal connections, affiliations, or relationships that might be relevant to the investigation.
   * Interactions: View which profiles give "kudos" to other users' workouts (similar to a "like") or comment on other users' activities.
   * Clubs and Groups: Join relevant clubs or groups the user is part of to gather more information about a users' social circles or interests. Users can filter their search of groups and clubs by location and sport type.
6. **Map Overlays and Data Export:**
   * Use map types and layers (standard, satellite, and hybrid) to visualize activity routes and identify potential points of interest.

## Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

Strava has an unpaid and paid subscription. The unpaid subscription is sufficient for an OSINT investigation because it still allows users to view Strava's heat maps, view groups and clubs, and discover or add other Strava users. However, some features like community photos are only available to paying users.

The paid version is geared towards maximizing a users’ personal workouts and goals. In the United States, subscribers [pay](https://www.strava.com/pricing) $11.99 per month or $79.99 per year. Subscribers on a Family Plan pay $139.99 per year.

## Level of Difficulty

<table><thead><tr><th data-type="rating" data-max="5"></th></tr></thead><tbody><tr><td>2</td></tr></tbody></table>

## Requirements

Users must create a Strava account using an email address to find other users and log activities. Users may use Strava on desktop or download the Strava app.&#x20;

The global heat map is available to the public, but only registered Strava users may view the weekly heat map or zoom in to street-level details of activity on the global heatmap.

## Limitations

Using Strava for OSINT research has several limitations:

1. **Privacy Settings**: Many users have their profiles set to private, limiting the visibility of their activities and personal information to non-connections.&#x20;
2. **Accuracy of Data**: While Strava provides detailed activity data, the [accuracy](https://support.strava.com/hc/en-us/articles/216917917-Why-is-GPS-data-sometimes-inaccurate) of this data can vary depending on factors such as GPS signal strength and signal obstruction. The [timestamps](https://support.strava.com/hc/en-us/articles/216515918-My-Activity-Has-the-Wrong-Date-or-Start-Time) on activities may also not always be reliable based on a users' GPS settings or timezone.
3. **Incomplete Data**: Not all users record all of their activities on Strava. Some may only use it sporadically or for specific types of activities, which can lead to incomplete or skewed data.
4. **False or Misleading Information**: Users can manipulate their profiles or activity data, either intentionally or unintentionally, leading to false or misleading information for OSINT purposes.
5. **Different Data on Desktop vs Smartphone:** Researchers may find more detailed heat map data using desktop rather than for a smartphone. The weekly heat map is only available on desktop.

## Ethical Considerations

Strava displays user-generated content, which may include location data and personal information knowingly or unknowingly shared by individuals.&#x20;

Users may opt out of the aggregate data usage in their privacy settings. Activities with the privacy setting "Only You" or “Followers” are excluded from the heat map automatically. Strava may also exclude all portions of activities based on a users' map visibility settings. However, the default setting for new users is to have their profile and activities (workouts, races or events) visible to everyone. Some users might not be aware of those default settings.

## Guides and Articles

Toler, Aric: How to Use and Interpret Data from Strava's Activity Map, [https://www.bellingcat.com/resources/how-tos/2018/01/29/strava-interpretation-guide/](https://www.bellingcat.com/resources/how-tos/2018/01/29/strava-interpretation-guide/)

Tobitt, Charlotte: Telegraph in IPSO breach with article claiming cyclists were doing 52mph and ‘putting lives at risk’[https://pressgazette.co.uk/the-wire/newspaper-corrections-media-mistakes-errors-legal/telegraph-cyclists-ipso/](https://pressgazette.co.uk/the-wire/newspaper-corrections-media-mistakes-errors-legal/telegraph-cyclists-ipso/)

## Tool provider

Strava Inc., USA

## Advertising Trackers

* [x] This tool has not been checked for advertising trackers yet.
* [ ] This tool uses tracking cookies. Use with caution.
* [ ] This tool does not appear to use tracking cookies.

| Page maintainer           |
| ------------------------- |
| Bellingcat Volunteer Team |
|                           |
