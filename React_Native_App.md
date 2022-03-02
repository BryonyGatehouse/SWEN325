# Assignment 2 : React Native

This assignment was to create the [decribed app](App_Description.md) using the React Native framework. The app is presented to a tutor (one-to-one).

A report is written on the app to show the understanding of the architecture, the framework, and your application. This included:
- A description of the overall architecture
  - Used the suggested architecture which seperated the components into a presentation layer, business layer, and data access layer. 
- Utilisation of a Major Existing External Component
  - OpenWeatherMap
    - I used OpenWeatherMap which allowed the user to quickly check their schedule and the weather in one app.
    - Noting the problem of IOS refusing to call unsecure links which was (unfortunately) solved by downloading the required images.
  - SQLite Storage
    - I used SQLite Storage to store information onto the user's device.
    - Doesn't require an internet connection but does use up space on the user's device.
- Reflection on React Native as a Framework
  - Renders to the native platform UI.
  - Compared to Ionic:
    - It's more popular but still fairly new so less components avaliable.
    - Doesn't work with the local storage (hence the need for SQLite) and would take a few refreshes to recieve new information from SQLite.
- UX Decisions made in your App
  - Calendar display
    - Combine view of events (homework, class, social).
    - Use an Agenda View to show upcoming events organised by day rather than a Day View which only shows today's events inhibiting the user from preparing for the future.
- Appendix
  - A quick description and explaination for each page of the app.
