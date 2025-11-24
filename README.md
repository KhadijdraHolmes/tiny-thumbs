# tiny-thumbs
App for toddlers to rate sitters and share their experience. 



The Toddler Sitter Rating App is a mobile Android application built in Java that allows toddlers to rate their babysitters using simple emoji buttons. Parents can log in to view sitter profiles, past ratings, and average scores. Although the Java code and database are not complete, the project outline has been updated to reflect planned progress. The outline includes the app’s main features, technical plan, planned file structure, and version changelog.

The main features of the app include an emoji-based rating system for toddlers, parent account login, sitter profiles with photo and rating history, local database storage for ratings and sitter information, and display of average ratings for each sitter. The technical plan identifies planned Java classes and activities, including MainActivity.java for the app entry point, RatingActivity.java for toddler ratings, SitterProfileActivity.java for sitter profiles, and DatabaseHelper.java for managing database operations. A Models folder will contain Sitter.java and Rating.java classes.

The planned file structure is as follows:

/app ├─ /java │ └─ com.example.toddlerapp │ ├─ MainActivity.java │ ├─ RatingActivity.java │ ├─ RatingActivity.java │ ├─ SitterProfileActivity.java │ ├─ DatabaseHelper.java │ └─ Models/ │ ├─ Sitter.java │ └─ Rating.java └─ /res ├─ layout/ ├─ drawable/ ├─ values/

Version Changelog: v1.0 (Week 2): Original project idea and general concept

v1.1 (Week 3): Planned parent dashboard and sitter profiles

v1.2 (Week 4, current): Outline created, file structure, planned database models, and planned Java classes

v1.3 (Week 5, planned): Begin coding Java activities, connect database, create UI

v2.0 (Week 7 final): Complete app with functional database, UI, and updated README
